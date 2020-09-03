# Part 3: Build a machine learning model and monitor the performance, bias and drift

Watson OpenScale tracks and measures outcomes from your AI models, and helps ensure they remain fair, explainable and compliant wherever your models were built or are running. OpenScale is designed as an open platform that will operate with various model development environments and various open source tools, including TensorFlow, Keras, SparkML, Seldon, AWS SageMaker, AzureML and more.

Watson OpenScale provides a set of monitoring and management tools that help you build trust and implement control and governance structures around your AI investments.

* Providing production monitoring for compliance and safeguards \(auditing model decisions, detecting biases, etc\)
* Ensuring that models are resilient to changing situations
* Aligning model performance with business outcomes 

You have two options for this part of the workshop:

* Go directly to OpenScale to explore a demo 
* Configure OpenScale from a notebook \(optional\)

## Go directly to OpenScale

* Go to your IBM Cloud Resource list
* Click on OpenScale
* Click on Launch Application

When you open OpenScale for the first time a demo is automatically created. Click on the numbers in the tile on the Insights Dashboard to explore the different options:

![](.gitbook/assets/screenshot-2020-09-03-at-19.13.27.png)

For instance click on **88%** to see the below evaluations, where you can further explore through the menu on the left. 

![](.gitbook/assets/screenshot-2020-09-03-at-19.15.18.png)

## Configure OpenScale from a notebook 

Before you can run the last notebook, an API key and deployment space need to be set up. Follow the below instructions for this.

### IBM Cloud API key

To deploy a model to Watson Machine Learning and then monitor this model on Watson OpenScale an IBM Cloud API is needed. This key is associated with your identity and is used to access cloud platform and classic infrastructure APIs.

Go to the **Manage** menu at the top of the IBM Cloud page and click on **Access \(IAM\)**:

![](.gitbook/assets/screenshot-2020-09-03-at-16.45.43.png)

In the next page, click on **API keys** from the menu on the left. Now click on **Create an IBM Cloud API key**:

![](.gitbook/assets/screenshot-2020-09-03-at-14.14.16%20%281%29.png)

Give the API a name, e.g. _**trustedAI**_ and click **Create.** Now copy or download the key, as you will not be able to see it again. This key is needed in the last notebook of the workshop.

![](.gitbook/assets/screenshot-2020-09-03-at-14.14.38.png)

### Deployment Spaces

Next set up a deployment space where the model will be deployed. Go to [deployment spaces](https://dataplatform.cloud.ibm.com/ml-runtime/spaces?context=cpdaas) from the menu on the left:

![](.gitbook/assets/screenshot-2020-09-03-at-16.56.15.png)

Click on **New deployment space**:

![](.gitbook/assets/screenshot-2020-09-03-at-14.38.58.png)

Click on **Create an Empty Space**. 

In the below screen, give the space a name and select a storage service and machine learning service. Then click **Create**:

![](.gitbook/assets/screenshot-2020-09-03-at-14.39.30.png)

Click on the new space:

![](.gitbook/assets/screenshot-2020-09-03-at-17.15.29.png)

And go to the Settings:

![](.gitbook/assets/screenshot-2020-09-03-at-17.16.42.png)

Here you find the **Space ID**. Copy this ID, as it is also needed in the notebook to deploy the model. 

### Load and run the notebook

Now go back to your project in **Watson Studio**.

Go to the **Assets** tab and click on **Add to project** or **New Notebook**:

As before, in the next screen select **From URL**, give the notebook a name, paste the below link in the Notebook URL field and then click the Create button at the bottom right. You can leave the runtime as the default. 

`https://github.com/MargrietGroenendijk/gitbooks/blob/master/notebooks/3-xxx-xx.ipynb`

A kernel is being spun up and the notebook loaded. Run each cell in order by selecting it, and then clicking the ▶︎ Run button at the top or use **Shift-Enter**. 

### Explore OpenScale

After successfully running all cells in the above notebook you should now have a model deployed that is monitored in OpenScale. 

Go to [OpenScale](https://aiopenscale.cloud.ibm.com/) to explore the dashboards. 



