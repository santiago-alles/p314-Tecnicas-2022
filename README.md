P314 - Técnicas de Análisis Político e Internacional (2022-II)
=================================

Last update:
------------------
10-14-2022

</br >El presente repositorio contiene diferentes bases de datos utilizadas para realizar ejercicios (en clase y fuera de clase) en el curso <b>Técnicas de Análisis Político e Internacional</b>, del Departamento de Ciencias Sociales (Universidad de San Andrés), correspondiente al segundo semestre de 2022.

Todos los datos aquí reproducidos corresponden a bases de datos de acceso público, producidas por organismos públicos, organismos internacionales, artículos de investigación, textbooks, etc. Las fuentes de cada una de ellas aparece reproducido más abajo.

UK Districts data
------------------

El set de datos contiene tres variables: el nombre del distrito (name), el porcentaje de votos en favor de abandonar la UE (leave), y el procentaje de residentes con educación terciaria, universitaria o equivalente (high_education).
<pre><code>url <- 'https://raw.githubusercontent.com/santiago-alles/p314-Tecnicas-2022/master/'
file <- 'UK_districts.csv'</pre></code>
<b>Llaudet</b>, Elena, and Kosuke <b>Imai</b>. 2023. <i>Data Analysis for Social Science: A Friendly and Practical Introduction.</i> Princeton, NJ: Princeton University Press. Available at: <https://www.dropbox.com/sh/icpqf9bahqlf05h/AAA12Y1Q8DDtGkPSSOGTDcdMa>, accessed: 09-09-2022.

Titanic data
------------------

El set de datos contiene datos individuales de pasajeros del Titanic. El set de datos contiene información para 12 variables, entre ellas nombre (Name), sexo (Sex), y edad (Age) del pasajero, la categoría del pasaje (Pclass), su supervivencia al naugrafio (Survived), entre otros.
<pre><code>url <- 'https://raw.githubusercontent.com/datasciencedojo/datasets/master/'
file <- 'titanic.csv'</pre></code>

Publicado por <i>Data Science Dojo</i>. Disponible en: <https://github.com/datasciencedojo/datasets>, accedido: 09-14-2022.

Motor Trend data
------------------

The data was extracted from the 1974 <i>Motor Trend US</i> magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973–74 models).
<pre><code>datasets::mtcars</pre></code>

A data frame with 32 observations on 11 (numeric) variables.

mpg:	Miles/(US) gallon</br >
cyl:	Number of cylinders</br >
disp:	Displacement (cu.in.)</br >
hp:	Gross horsepower</br >
drat:	Rear axle ratio</br >
wt:	Weight (1000 lbs)</br >
qsec:	1/4 mile time</br >
vs:	Engine (0 = V-shaped, 1 = straight)</br >
am:	Transmission (0 = automatic, 1 = manual)</br >
gear:	Number of forward gears</br >
carb:	Number of carburetors</br >

<b>Henderson</b>, Harold V., and Paul F. <b>Velleman</b>. 1981. Building multiple regression models interactively. <i>Biometrics</i>, 37 (2): 391–411. Also available at: <https://gist.github.com/seankross>, accessed: 09-14-2022.

Fake data: Set #1
------------------

Cuatro sets de datos (falsos) para realizar ejercicios de clase.

<pre><code>url <- 'https://raw.githubusercontent.com/santiago-alles/p314-Tecnicas-2022/master/'

file <- 'econ_A62731.dta'
file <- 'econ_B79696.dta'

file <- 'educ_A74371.dta'
file <- 'educ_B63963.dta'</pre></code>

Los dos primeros sets de datos (econ_A62731, econ_B79696) contienen 112 observaciones cada uno, y simulan ser datos macroeconómicos y resultados electorales de países latinoamericanos. Contienen 6 variables: growth, inflation, unemploy, incumbent, ideology, y vote_pct.

Los otros dos sets de datos (educ_A74371, educ_B63963) contienen 120 observaciones cada uno, y simulan ser resultados de examenes escolares de niñxs de diferentes lugares. Contienen 5 variables: female, educ, expend, priv_school, y score.

Lung Capacity Data
------------------

El set de datos contiene información de 725 niños, en los cuales se indica su nivel escolar (School), edad (Age), estatura (Height), si fuman (Smoke), su género (Gender), si nació por cesárea (Caesarean), y su capacidad pulmonar (LungCap).

<pre><code>url <- 'https://raw.githubusercontent.com/santiago-alles/p314-Tecnicas-2022/master/'
file <- 'LungCapData.csv'</pre></code>

Disponible en: <https://statslectures.com/r-scripts-datasets>, accedido: 10-14-2022.
