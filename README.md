如果你是透過Azure Notebook直接開啟此專案，你只需要將 [configuration](configuration.ipynb) 執行完成，你就可以擁有免費CPU的ipython notebook使用。  
但建議你透過Azure Portal消費Azure subscription或是Azure Pass來開啟Azure Notebook，你可以開啟GPU的機器(直接透過Azure Notebook portal進入會無法使用GPU)，其中一種開啟方法 請參考 [link](https://docs.google.com/presentation/d/12CIhE3kJ0hyFNN6lLpUNp4lCB3WYZHF6vaco1HVjyS0/edit?usp=sharing) 


本次MNIST示範教學在 **tutorials** 資料夾。
in **how-to-use-azureml** folder.
 **Important:** You must select Python 3.6 as the kernel for your notebooks to use the SDK.
 
延伸參考文件:

 * [Azure/MachineLearningNotebooks GitHub site](https://github.com/Azure/MachineLearningNotebooks)
 * [Azure Machine Learning service documentation](https://docs.microsoft.com/en-us/azure/machine-learning/service)
 * The config.json file in this folder was created for you with details of your Azure Machine  Learning service workspace. Both these notebooks use this file to connect to your workspace. You can also copy this file into other places where you have code that needs this connection.