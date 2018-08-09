# Python3-Access-Azure-Blob
This articel shows how to use Microsoft Azure Python packages to access Azure Storage Account Blob, including: create container, assign security to container, upload a local file to blob and download blob file to local.

A good tutorial is located at https://docs.microsoft.com/en-us/python/api/overview/azure/storage?view=azure-python

We assume that
1. An Azure Storage Account has been created

2. Python 3 kernel has been installed with Anaconda or others

Then we install the folloiwng Microsoft Azure SDK packages locally:

pip install azure-storage-blob

pip install azure-mgmt-storage

We add a configuration file in ~/Documents. The Python 3 code will read the blob account anme and key from the file and run the folloiwngs:

1. Create the BlockBlockService that is used to call the Blob service for the storage account

2. Create a container called 'jacktestcontainer'.

3. Set the permission so the blobs are public.

4. Create a file in Documents to test the upload and download.

5. Clean up resources. This includes the container and the temp files
