# Developers
  * Connor DiLeo
  * Adam Wolfe


# Dataset Download Link
  * https://www.kaggle.com/sobhanmoosavi/us-accidents

# Setup Guide

  * Please download all the necessary files from the repository.
  * Make sure that the .pkl files are in the same location as the the main code life.
  * Upload each code to a Jupyter notebook and should be ran normally.
  
# Note
  * There may be extra steps for some people to allow Gmaps to run. Running "jupyter nbextension enable --py --sys-prefix widgetsnbextension" to make sure the widgets are enabled. Then "pip install gmaps". With a restart of your computer should fix this issue. More info can be found at https://jupyter-gmaps.readthedocs.io/en/latest/install.html
  * Due to the large dataset programs such as Google Colab could result in  a faster training time.
  * Google does not like us sharing our premium api_keys. If you do not have a premium key, the heatmap will still work but each box will have a "For development purposes only" covering it. If you do have a premium api_key please use it with the following command "gmaps.configure(api_key = "INSERT KEY HERE")" in the importing section.
  * If the countplot right before creating the X and y vectors produces an error, rerun the import statements at the beginning of the code and rerun the countplot, that should fix any errors.
