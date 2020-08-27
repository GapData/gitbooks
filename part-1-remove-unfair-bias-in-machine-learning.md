# Part 1: Remove Unfair Bias in Machine Learning

AI can embed human and societal bias and be then deployed at scale. Many algorithms are now being reexamined due to illegal bias. So how do you remove bias & discrimination in the machine learning pipeline? In this workshop you will learn the debiasing techniques that can be implemented by using the open source toolkit [AI Fairness 360](https://aif360.mybluemix.net/).

AI Fairness 360 \([AIF360](https://github.com/Trusted-AI/AIF360)\) is an extensible, open source toolkit for measuring, understanding, and removing AI bias. It contains the most widely used bias metrics, bias mitigation algorithms, and metric explainers from the top AI fairness researchers across industry & academia.

You will learn:

* how to measure bias in your data sets & models
* how to apply the fairness algorithms to reduce bias
* how to apply a practical use case of bias measurement & mitigation

## IBM Cloud Pak for Data

{% hint style="danger" %}
If you have not done so yet, go to the [Introduction](https://margriet-groenendijk.gitbook.io/trusted-ai-workshop/introduction) and set up your free IBM Cloud account and follow the instructions to provision the services needed for this workshop.
{% endhint %}

![](.gitbook/assets/screenshot-2020-08-21-at-16.50.56.png)

## Jupyter notebooks in Watson Studio

Jupyter notebooks are running in an open-source web application that allows you to create and share documents containing live code, equations, visualisations and explanatory text. We will be using a number of notebooks in Watson Studio throughout this workshop. These notebooks are contained in a project that you will import into your Watson Studio instance.

Once you have opened Watson Studio, you will see the below:

\[WS welcome page\]

{% hint style="info" %}
You might have noticed the name Cloud Pak for Data at the top. This is the new name for this service and it includes \*\*\*. Through this renaming this is now consistent with all Cloud Paks that you can install and run on any cloud with OpenShift, both private and public.
{% endhint %}

### Create a project

1. Download the below project file \(do not unzip\).
2. Go to [Watson Studio](https://dataplatform.ibm.com) \(login if necessary\)
3. From the home page, click on the _**Create a Project**_ card     
4. Select the _**Create a project from a sample or file**_ option 
5. Browse for the project zip file you downloaded earlier and provide a name for the new project \(i.e. _trusted-ai-workshop_\)    
6. Once the import completes, click on the _**'View new project'**_ button.

### Open a notebook

1. Go to the assets tab
2. Click on the pencil next to the 



