# MLRP Project for HackHouston 2017



# Online resume processing application using machine learning algorithms
------------------------------------------------------------------------
## Inspiration
As a team of undergrad computer scientists we will soon face the crazy world or resumes, interviews, work, etc... It stresses everyone out whether they will be able to get that dream job at Google or just to for the sake of competition.

## What it does
Our machine learning system uses unsupervised learning algorithms to cluster resumes of top software engineers in various companies and label their skills accordingly. Next, the user uploads their resume and it is tested against the predicted hypothesis by the ML algorithms which in hand return what tier(s) you belong to. As for tiers, we divided them into two parts. Top tier, such as Google, Facebook, Amazon, IBM, etc..., and bottom tier such as local Houston companies. Unfortunately, due to time constraints we cannot provide company specific statistics according to ones resume. (We plan to offer location based ranking and statistics in the future). Another factor we included was education and improvement. After viewing the results, users can follow recommended links provided to websites where they can practice on algorithms or take online certifications that can help them stand out even further!

## How we built it
We used scikit-learn module K Means Clustering Next we se tup the backend using Flask and published it on PythonAnyWhere. The frontend is built using HTML5/CSS3. 

## Challenges we ran into
Finding resumes! In order for our system to work accurately we must provide as much training data (resumes) as possible! And not only that but quality resumes! Such things are hard to come across. Luckily, we managed to come up with 1000 resumes. After some cleaning and preprocessing we shrink the number to 300. Right now, because resumes are personal data, We cannot put them as they are. Ergo, the data is preprocesed with stemming and cleaned from the stop words and stored in csv file.

## Accomplishments that we're proud of
We are really proud with the idea that we came up with because many students are worried about their future and would like to know what the future holds for them. Unfortunately, we are no fortune tellers but nevertheless we are skillful machine learning engineers who with some help of statistics, machine learning tools and Python can help anyone discover their real potential!

## What's next for MLRP
We would like to dive deeper into machine learning algorithms to provide more descriptive and personalized results to every single user for a full user friendly experience.

## How to run 

```
python3 flask_app.py
```



