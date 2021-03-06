# MalbehavD-V1 (API calls Dataset)
MalBehvaD-V1 is a new dynamic dataset of API calls sequences extracted from benign and malware portable executables (PE) program/files in Windows using the dynamic analysis approach. Each file was executed in an isolated environment powered by the Cuckoo sandbox.  Malware samples were collected from VirusTotal while benign samples were collected from CNET site (https://download.cnet.com/). Only malware samples submitted in the second quarter of 2021 were used and each benign file was submitted to VirusTotal Online Engine (https://www.virustotal.com/gui/home/upload) to check if it does not possess any malicious characteristics or behaviour.
#### Dataset Composition
The dataset composition consists of 1285 bening files and 1285 malicicious files, creating a total of 2570 files in the whole dataset.
#### Categories of Malware in the dataset
The MalbehavD-V1 has the behavioural characteristics of current emerging malware such as ransomware, worms, Viruses,
Spyware, backdoor, adware, keyloggers, Trojans, and rootkits. The dataset has been processed to remove all inconsistencies/noise, making it ready to be used for evaluating the performance of machine learning and deep
learning models without further pre-processing steps. In addition, the dataset is labeled and the hash value for each file
has been included to avoid duplication of files while extending
the dataset in the future, which makes it easier to include behavioural characteristics of new malware variants in the dataset
or combine it with any of the existing datasets of API calls extracted from Windows PE files.
#### Dynamic analysis Environment
The analysis environment has  five main components and the network architecture is presented in Figure Below.  
- windows main host machine
- Linux Ubuntu host machine
- Windows virtual machines
- Cukcoo sandbox
- Oracle VirtualBox (virtualization software)



![Dynamic Analysis Environment1](https://user-images.githubusercontent.com/18678162/174477553-998fefd0-c129-43c6-aebd-9f6d78fa0d84.png)

Figure 1: Analysis Environment used to generate MalbehavD-V1

#### Citing the dataset
Please use the BIB format provided below to cite MalbehavD-V1 when you use it in your work.

BIB: 
