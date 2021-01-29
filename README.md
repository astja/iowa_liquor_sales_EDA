# iowa_liquor_sales_EDA

#### 1. Download and Install Anaconda

The quickest and easiest way to install Python and Jupyter Notebook is to use the Anaconda Distribution. You can follow the instructions <a href="https://docs.anaconda.com/anaconda/install/" target="_blank">here</a> to find the guide to installing Anaconda on your operating system. 

#### 2. Install Google Cloud Python SDK and authenticate

Follow Google’s <a href="https://cloud.google.com/sdk/docs/quickstarts" target="_blank">guide</a> to install Cloud SDK for your specific OS. After installing and initialize the SDK, you should setup application-default authentication by doing the following:

Open Terminal/Anaconda prompt/Command line and type in the following

```
gcloud auth application-default login</title>
```

#### 3. Install GCP python library and pandas_gbq

Install the following Python packages:

```
pip install --user --upgrade google-api-python-client
pip install --user pandas-gbq -U
```

#### 4. Clone this repo

```
git clone git@github.com:astja/iowa_liquor_sales_EDA.git
```

#### 5. Running Jupyter notebook

```
jupyter notebook
```

#### 6. Open downloaded notebook
