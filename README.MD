## Getting Started

### Prerequisites

* Install Python 3.x
* Install the Python SDKs<br>

pip3 install azure-mgmt-resource<br>
pip3 install azure-mgmt-media==3.0.0<br>
pip3 install azure-identity<br>
pip3 install azure-storage-blob<br>
pip3 install adal

### Set following environment variables so that this python program can use them to connect to your Azure Media Service Account

AADCLIENTID="00000000-0000-0000-0000-000000000000"<br>
AADSECRET="00000000-0000-0000-0000-000000000000"<br>
AADTENANTDOMAIN="microsoft.onmicrosoft.com"<br>
AADTENANTID="00000000-0000-0000-0000-000000000000"<br>
ACCOUNTNAME="amsaccount"<br>
LOCATION="West US 2"<br>
RESOURCEGROUP="amsResourceGroup"<br>
SUBSCRIPTIONID="00000000-0000-0000-0000-000000000000"<br>
ARMAADAUDIENCE="https://management.core.windows.net/"<br>
ARMENDPOINT="https://management.azure.com/"<br>

STORAGEACCOUNTNAME="XXXXX"<br>
STORAGEACCOUNTKEY="XXXXX"

### Execute

Go to project directory and run<br>

$python overlay-encoding.py<br>
Getting .env values<br>
Creating AMS client<br>
Creating input asset inputassetName8374<br>
Creating input asset inputlogoassetName8374<br>
Creating output asset outputassetName8374<br>
Uploading the file sample_beach.mp4<br>
Uploading the file cloud.png<br>
Creating transform MyOverlayTransform18374<br>
Creating  overlay job MyOvarlayJob8374<br>
First job check<br>
Processing<br>
Processing<br>
Processing<br>
Finished<br>

After it finishes, you should be able to see input image asset, input logo asset, and output Overlayed video assest that is ready to be streamed and thumbnail images. 
