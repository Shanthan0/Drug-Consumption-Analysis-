# Drug-Consumption-Analysis

Project demo - https://youtu.be/sf6Y1eu_B98

The main objective is to determine the risk of drug consumption of individual. Drug consumption effects the health of a person. A person’s personality profile can be used to determine whether he can be a drug user on not. Personality measurements are Neuroticism, Extraversion, Openness to Experience, Agreeableness and Conscientiousness

Personality measurements are as follows:

1. Neuroticism: It is a tendency to express negative emotions such as anxiety and tension.
2. Extraversion: They enjoy human interaction such as talkative and taking words of other people in a positive manner.
3. Openness to Experience: It is like appreciating some others art.
4. Agreeableness: It is a measure of interpersonal conduct such as trust and kindness.
5. Conscientiousness: It is also a tendency to be organized and strong willed.

The data set that I used consists of 1885 respondents and for each individual, I have collected scores based on their personality measurements. The individual levels of consumption of some drugs like Coke, Heroin, Amphet, Benzos are taken. I have classified individual consumption levels as Never Used, Used over a decade ago, Used in the last decade, Used in last year, Used in last month, Used in last week, Used in last day. In order to determine the consumption levels, I have used two classification algorithms namely Random Forest and Support Vector Machine (SVM)

 CL0 represents that an individual never used particular drug.
 CL1 represents that the individual used it over a decade ago.
 CL2 represents that the individual used it in the last decade.
 CL3 represents that the individual used a year ago.
 CL4 represents that the individual used in the last year.
 CL5 represents that the individual used in the last week.
 CL6 represents that the individual used last day.

So in order to determine the consumption level of an individual based on their personality scores we have used four machine learning classification techniques.

I used Azure notebooks to execute my project with following steps.

Notebook Link - https://ml.azure.com/fileexplorerAzNB?wsid=/subscriptions/6166b34b-f2a6-45f0-a8a4-411c20cdc8ab/resourcegroups/RGdrugconsumption/workspaces/WSdrugconsumption&tid=d4963ce2-af94-4122-95a9-644e8b01624d&activeFilePath=Users/kuthurusree.shanthan2019/drug_consumption_prediction.ipynb

Dataset Link - https://ml.azure.com/fileexplorerAzNB?wsid=/subscriptions/6166b34b-f2a6-45f0-a8a4-411c20cdc8ab/resourcegroups/RGdrugconsumption/workspaces/WSdrugconsumption&tid=d4963ce2-af94-4122-95a9-644e8b01624d&activeFilePath=Users/kuthurusree.shanthan2019/drug_consumption(1).csv

1. Create a resource group in AI + Machine Learning category with product as Machine Learning

![image](https://user-images.githubusercontent.com/68529782/151414113-2ef3ef15-12ef-4dd0-b67a-1a3977055a0b.png)

2. After the deployment go to workspace and open Machine Learning Studio

![image](https://user-images.githubusercontent.com/68529782/151414588-04c21c38-3eb9-49f0-8db7-5a92a2b3c0a7.png)

3. From the left catalog choose notebooks and upload the notebook

![image](https://user-images.githubusercontent.com/68529782/151414806-790d42d7-4591-437c-b2c6-e74cbf360ef6.png)

4. Now upload the dataset file

![image](https://user-images.githubusercontent.com/68529782/151414866-5021cefd-689d-4159-a022-dc5bf9f178fc.png)

5. Create a compute instance by choosing the required virtual machine

![image](https://user-images.githubusercontent.com/68529782/151414906-bee1ca15-1e72-44e3-a794-aa0fbd2dcb1f.png)

6. Now the code is ready to run.

![image](https://user-images.githubusercontent.com/68529782/151414964-9907403f-e11e-4852-8c10-07a127c715dc.png)

SCREENSHOTS

![image](https://user-images.githubusercontent.com/68529782/151419846-2d43af4b-8f1e-46cb-9e51-bf6b065d9eae.png)


![image](https://user-images.githubusercontent.com/68529782/151419799-e3bf38bd-e929-4896-9a44-8f1e16116d1c.png)

![image](https://user-images.githubusercontent.com/68529782/151419943-6463f027-00cc-4b07-bafa-5c2de78e2721.png)

