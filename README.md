# selected-3_project_fcai
FCAI-HU Project


*******we add the documentation with pictures of the code running in document file ******


##Problem description

the idea: identify and classify documents by topic 

we will use dataset scrapped from Makeup site and make classification on it
This dataset contains makeup products from the Heruko App Makeup API,
It has different prices,descriptions,names,price_sign,currency,
product_types like(lip_liner,lipstick,foundation,eyeliner,eyeshadow andso on),
brands like(colourpop,boosh,deciem,zorah biocosmetiques and so on),
categories like(like lipsticks,liquids,powder,lip_gloss,pencil and so on),
and tags (like Gluten Free,Vegan,silicone free,oil free,alcohol free,cruelty free,water free and so on).

dataset link: https://github.com/aniass/Extracting-data-using-API



##Model design

01) Importing packages and loading data

02) Data Analysis
-Check missing values
-Data type changed to string
-making the data unique
-Grouping data with similar names 
After running we will have five group of classes:
(Eye makeup-
Lipstick-
Foundation-
Contour-
Nail polish
)
-Mapping data to numeric data for learning

03) Text Pre-processing
-remove punctuations
-remove stopwords
-Stemming
-COUNT VECTORIZER for ENCODING
-Extract TF-idf
 
04) Splitting Data

05) Build the models 
-we used (logistic Regression-SVM- Random Forest)


##Experimental results

***logistic Regression
ACCURACY : 0.8669527896995708 

***SVM
ACCURACY : 0.9227467811158798 

***Random Forest
ACCURACY : 0.9012875536480687 

##Model performance
the best model performance is SVM with ACCURACY 92% 

