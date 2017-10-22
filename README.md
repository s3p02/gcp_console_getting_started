## Getting started once you've created a free GCP account



# The First thing you see upon logging into the console of you GCP account is the Dashboard:




<kbd>
  <img src="/0_after_creating_instance.png">
</kbd>




## Step 1: Select App Engine >> VM instances


<kbd>
  <img src="/1_vm_instance.png">
</kbd>



## Step 2: Select Create under VM Instances

<kbd>
  <img src="/2_create_instance.png">
</kbd>

## Step 3: Customize your VM

# Name your instance, pick region us-west1-b as they have GPU's and click customize.


<kbd>
  <img src="/3_name_customize.png">
</kbd>!


## Step 4: Select No. of Cores, Ram, GPU

# Click GPU's


<kbd>
  <img src="/4_gpu.png">
</kbd>

# Select 1 NVIDIA Tesla K80


<kbd>
  <img src="/4_1_gpu.png">
</kbd>


## Step 5: Change Operating System & Storage

# Select Ubuntu 14.04 and 100GB Standard Persistant Disk

<kbd>
  <img src="/6_os_100_gb.png">
</kbd>


## Step 6: Firewall & SSH KEY

# Under Firewall, check for HTTP & HTTPS traffic

<kbd>
  <img src="/7_firewall_ssh_key.png">
</kbd>

# Enter the SSH Key Generated

# Click Create to create an instance

You are most likely going to encounter an error after clicking create. This is primarily because, GPU's are not allotted directly with a free account. A Quota request is required for GPU.

