# Happiness Indicators
Through Tableau, I analyzed the reasons that make people happy

## What is the aim of this work?

The aim of this work is to determine which are the characteristics of people who consider themselves happier and less happy than the average.

## Which tool was used?

I used Tableau (https://www.tableau.com/)

## Where did I get the original data from?

The original dataset was obtained from Kaggle.com.
(https://www.kaggle.com/datasets/loveall/human-happiness-indicators)

## What is the dataset used?
The dataset used can be found in my repository under the name "Kag_happiness_indicators.csv"

## What was the process performed?
### Data preparation
1) Downloaded the dataset
2) Analyzed the data to identify the candidate columns to be relevant.
3) Performed the necessary transformations/cleaning before importing the data into Tableau.

### Data analysis
4) Compared the different fields with the corresponding number of happy people. In general I did not take absolute numbers because the sample was not uniform, and I used percentages within each sample category.
5) When analyzing each parameter, I determined if there were relevant differences within the groups that deserved to be discussed later.

### Presentation of results
6) Generated several Dashboards to show which were the characteristics of the happiest and unhappiest people.

## Cuáles son las principales conclusiones del trabajo?
### Caracteristicas irrelevantes
- La relación entre personas muy felices, algo felices, y no muy felices; se mantiene uniforme entre 1994 y 2006 para la muestra (probablemente de Estados Unidos) seleccionada.
- Estar divorciado no modifica el nivel de felicidad.
- Tener hijos adolescentes no modifica el nivel de felicidad.
- No existe diferencia de felicidad entre mujeres y no mujeres.

## What are the main conclusions of the work?
### Irrelevant characteristics
- The relationship between very happy, pretty happy, and not too happy remains uniform between 1994 and 2006 for the sample (probably from the United States) selected.
- Being divorced does not change the level of happiness.
- Having teenage children does not change the level of happiness.
- There is no difference in happiness between women and non-women.

### Relevant characteristics
- In general, for all segmentations, the group of "pretty happy" people is between 55% and 59%.

#### Ingresos
- Exsite una correlación positiva entre los ingresos y la felicidad.
  - Dentro de las personas menos felices, los de mayores ingresos son el grupo más reducido.
  - Las personas bastante felices ocupan la misma proporcion para cada grupo de ingresos.
  - La proporcion de personas muy felices es mayor en el grupo de mayores ingresos.
  
#### Income
- There is a positive correlation between income and happiness.
  - Among the not too happy people, those with the highest income are the smallest group.
  - Pretty happy people occupy the same proportion for each income group.
  - The proportion of very happy people is higher in the highest income group.

<p align="center">
<a><img src="https://github.com/DarianYane/HappinessIndicators/blob/main/Income%20and%20Guns.jpg" style="width: 836px; height: 400px;"/></a>
</p>

#### Guns
- There is a positive relationship between income and gun ownership, although it is not possible to determine which is the cause and which is the consequence. New data are yet to be collected.
- The proportion of very happy people is higher in the group that owns guns.

#### Employment Status and Education
- People with more years of education tend to be happier.
  - Comment: For the group of people with 4 years of study I observed a high proportion of very happy people, a very low proportion of pretty people, and a high proportion of not too happy people. This may be due to a problem with the sample (small sample size or biased sample). It is recommended that more data be obtained before drawing conclusions.
 - People who are retired, stay at home, or work full time tend to be happier.
 - The least happy groups are laid-off, unemployed, and temporarily unemployed workers.

#### Television Hours
- There is an inverse relation between happiness and hours of television consumed daily.
- However, the exception is the group that does not consume television. The happiest are those who consume between 1 and 2 hours per day.

#### Race and Gender
- Black people are less happy than non-black people.
- Black women are less happy than non-black women.

#### Hijos
Tener hijos hace más feliz a las personas, sobre todo cuando los niños tienen poca edad.
- Las personas con 3 o más hijos adolescentes tienden a ser muy felices, o no muy felices. Se observa una tendencia hacia los extremos.
- Dentro de las personas con bebés, los que tienen 2 o 3 hijos son muy felices en una proporcion mayor al resto.
- Los grupos menos felices son los que no tienen hijos.

#### Children
Having children makes people happier, especially when the children are young.
- People with 3 or more teenage children tend to be very happy, or not very happy. There is a trend toward extremes.
- Among people with babies, those with 2 or 3 children are very happy in a higher proportion than the rest.
- The least happy groups are those with no children.

## Where can I access the Tableau file? How can I view the complete job?

You can access the public Tableau archive at https://public.tableau.com/views/HappinessIndicators_16772570623250/Kids?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

You can also find it in this repository at https://github.com/DarianYane/HappinessIndicators/blob/main/Happiness%20Indicators.twbx

## Why did I do this job?
I did this work to demonstrate my skills as a data analyst and in the use of Tableau. It can be found on my Github and in my portfolio at https://www.darianyane.com/
