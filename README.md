# ENLP_GED


## Add other models

<p>

## T5 model - JFLEG

Build with [happyTransformer](https://huggingface.co/vennify/t5-base-grammar-correction)

<p> Files are located in the folder "t5_jfleg"

### Training the model

<p> use "t5_traning.ipynb" file

- In order to setup your environment first install the below requirements.

```shell
!pip install happytransformer

!pip install transformers
```


- While running the program, if you run into errors, try running the below commands and restarting your environment

```shell
!pip uninstall -y transformers accelerate

!pip install transformers accelerate
```

<p>

-At the end, remember to connect to google drive or you can locally save the model that will be generated after it has been trained over the JFLEG data. If you decided to save the model to your google drive, remember to insert the path you want to save the model to.

<p>
<p>

### Using the pre-trained model 

<p> use "t5_saved_model.ipynb" file


- In order to setup your environment first install the below requirements.

```shell
!pip install happytransformer
```

- Have the path of your saved model and test dataset handy, so that you can insert it into the code, where we have added prompts for the user in the ipynb to enter the respective paths

- You can tune the model by changing the below parameters, but remember to understand the advantages and disadvantages of making changes which are mentioned in the report.
```shell
    min_length
    max_length
    number_of_beams
```
    

<p> Below are some snippets of sample input given to the model which shouws how the grammar errors are corrected. We have used this feature for our GED task while performing evaluations on our multiGed test set.
    
<p>

    <img width="998" alt="image" src="https://github.com/nicole-mathias/ENLP_GED/assets/47077945/81e16d0a-e7d7-46c2-8235-24ce9a2262a5">
    
    
    <img width="998" alt="image" src="https://github.com/nicole-mathias/ENLP_GED/assets/47077945/fd78bf0b-6518-4d16-bbc1-058b8f218d50">








