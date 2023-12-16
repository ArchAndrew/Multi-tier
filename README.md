# Creating Three Tier Architecture

<img src= "https://github.com/ArchAndrew/Multi-tier/blob/main/ThreeTier.png" style="width:700px;">





## Prerequisites

- An AWS account with access keys assigned to corresponding user.
- Basic understanding of the [AWS console](https://aws.amazon.com/console/)
- Visual Studio Code [VSC](https://code.visualstudio.com/) (Windows)

## Step 1: Go to Route 53 
1. Enter Route 53 in search bar within AWS console.
2. Select registered domains.


<img src= "https://github.com/ArchAndrew/Multi-tier/blob/main/RTE53Domain.png" alt="image description" style="width:200px;">


3. Click on register domains.
   
<img src= "https://github.com/ArchAndrew/Multi-tier/blob/main/Register%20Domain.png" alt="image description" style="width:500px;">

4. Search for desired domain for availability and purchase it.

<img src= "https://github.com/ArchAndrew/Multi-tier/blob/main/SearchDomain.png" alt="image description" style="width:500px;">

## Step 2: Go to AWS Certificate Manager

1. Click on request certificate.

<img src= "https://github.com/ArchAndrew/Multi-tier/blob/main/RequestCert.png" alt="image description" style="width:500px;">

2. Now enter your domain name from step 1.
3. And choose certificate validatation via. Email (Though DNS validation is recommended I choose the email option being that it is faster).

Note: Validation can take up to an hour.

<img src= "https://github.com/ArchAndrew/Multi-tier/blob/main/DomainName.png" style="width:500px;">

4. Go to "list certificates" to confirm validation.

<img src= "https://github.com/ArchAndrew/Multi-tier/blob/main/ListCert.png" style="width:500px;">




