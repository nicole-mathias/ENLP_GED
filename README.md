# ENLP_GED


<!-- talk about how the model is saved and where it is saved and how you pick up the saved model for testing purpose -->

<!-- please remeber to restart runtime, or uninstall and re-install transformers (sometimes there are issues while running this program) -->


### Training the model

-In order to setup your environment first install the below requirements.

```shell
!pip install happytransformer

!pip install transformers
```


-While running the program, if you run into errors, try running the below commands and restarting your environment

```shell
!pip uninstall -y transformers accelerate

!pip install transformers accelerate
```

-At the end, remember to connect to google drive or you can locally save the model that will be generated after it has been trained over the JFLEG data. If you decided to save the model to your google drive, remember to insert the path you want to save the model to.


### Using the pre-trained model 

-In order to setup your environment first install the below requirements.

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




