# Azure Recovery Services

Welcome! This repo has a bunch of content that will be getting covered in the Global Azure Bootcamp Auckland event for 2018. Here you can find the steps which we shall go through in the lab, the slide desk and some links to information hosted on technet, MVA and channel 9.

## Content

### What will you need for the lab?
1. A Microsoft Azure Account. You can sign up for a free trial [here](https://azure.microsoft.com/en-us/free/). - - If you dont have one already!
2. A computer running a Desktop OS such as WIndows, Mac or Linux with a browser such as Edge, Chrome or Firefox


### What you will learn

At the end of this session you should hopefully have a bit of insight into Azure Recovery Services and how you can leverage them for migration, DR and backup purposes. An area we shall pay specific attention to is Azure Site Recovery, you should be leaving with an understanding around the approach you should be taking when considering ASR as a DR or Migration solution and some of the considerations to keep in mind when planning, prepping and executing.

During the following lab, we shall deploy a small environment consisting of a virtual machine, Vnet, storage accounts and the components required for it to run followed by an Azure Recovery Services Vault. From here, we will enable replication of the VM to another region of Azure and run through some of the recovery plan options that you have available....


## Lab Steps

### Deploying Resources in Azure

First up, once you are logged in, lets create the resources we need for this lab.

1. Select 'Create a resource' and look for 'Windows Server 2016 VM'
![Create Cloud Shell Storage](images/createcloudshellstorage.png "Create Cloud Shell Storage")

a.
b.
c.
d.

2. Create Recovery Vault - Choose a location different to where your VM is.

3. Enabling DR on the VM
a.
b.

3. (Optional) Deploy a second VM to the same Vnet to simulate a multi-tier app


4. 






## Additional Content

- Channel 9 ASR Content - [Here](https://channel9.msdn.com/Series/Azure-Site-Recovery)
- Microsoft Tech ASR Content - [Here](https://docs.microsoft.com/en-us/azure/site-recovery/)
    - Replicating different workloads - [Here](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-active-directory)
- Azure Site Recovery Deep Dive - [Here](https://channel9.msdn.com//Series/Azure-Site-Recovery/Azure-Site-Recovery-Deep-Dive/)
