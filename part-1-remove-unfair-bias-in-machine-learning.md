# Part 1: Remove Unfair Bias in Machine Learning

AI can embed human and societal bias and be then deployed at scale. Many algorithms are now being reexamined due to illegal bias. So how do you remove bias & discrimination in the machine learning pipeline? In this part  you will learn about some of the debiasing techniques that can be implemented by using the open source toolkit [AI Fairness 360](https://aif360.mybluemix.net/).

AI Fairness 360 \([AIF360](https://github.com/Trusted-AI/AIF360)\) is a toolkit for measuring, understanding, and removing AI bias. It contains the most widely used bias metrics, bias mitigation algorithms, and metric explainers from the top AI fairness researchers across industry & academia.

You will learn:

* how to measure bias in your data sets & models
* how to apply the fairness algorithms to reduce bias
* how to apply a practical use case of bias measurement & mitigation

## IBM Cloud Pak for Data

{% hint style="danger" %}
If you have not done so yet, go to the [Introduction](https://margriet-groenendijk.gitbook.io/trusted-ai-workshop/introduction) and set up your free IBM Cloud account and follow the instructions to provision the services needed for this workshop.
{% endhint %}

After going through the cloud environment setup you should now see the below screen in a new browser tab:

![](.gitbook/assets/screenshot-2020-08-21-at-16.50.56%20%281%29.png)

{% hint style="info" %}
You might have noticed the name [_**IBM Cloud Pak for Data**_](https://www.ibm.com/uk-en/products/cloud-pak-for-data) at the top of the below screen instead of Watson Studio. This is the new name of the platform and includes Watson Studio, Watson Knowledge Catalog and Watson Machine Learning. This version runs in the IBM Cloud as-a-service \(aaS\) and now consistent with the Cloud Paks that you can install and run on any other cloud, both private and public, and is powered by [Openshift](https://www.openshift.com/).
{% endhint %}

## Jupyter notebooks in Watson Studio

Let's start by setting up a project where you can store data, notebooks and many other assets. 

Within the project we will use Jupyter notebooks that allow you to create and share documents containing live code, equations, visualisations and explanatory text. We will be using a number of notebooks in Watson Studio throughout this workshop. These notebooks are contained in a project that you will import into your Watson Studio instance.

### Create a project

Click on **Start working** to create a project that will contain all the assets for this workshop:

![](.gitbook/assets/screenshot-2020-08-21-at-16.50.56.png)

In the next screen click on **Create an empty project**. Then give your new project a name and click on Create in the bottom right:

![](.gitbook/assets/screenshot-2020-09-03-at-10.50.45.png)

1. 2. Download the below project file \(do not unzip\).
3. Go to Watson Studio \(login if necessary\)
4. From the home page, click on the _**Create a Project**_ card     
5. Select the _**Create a project from a sample or file**_ option 
6. Browse for the project zip file you downloaded earlier and provide a name for the new project \(i.e. _trusted-ai-workshop_\)    
7. Once the import completes, click on the _**'View new project'**_ button.

### Open a notebook

1. Go to the assets tab
2. Click on the pencil next to the 



