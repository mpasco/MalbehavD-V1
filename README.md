# MalbehavD-V1: A Dataset of API Calls Extracted from Malware and Benign Executable Files in Windows: 
MalBehvaD-V1 is a new dynamic dataset of API call sequences extracted from benign and malware executables files (EXE files) in Windows using the dynamic malware analysis approach. Each file was executed in an isolated environment powered by the Cuckoo sandbox.  Malware samples were collected from VirusTotal while benign samples were collected from the CNET site (https://download.cnet.com/). Only malware samples submitted in the second quarter of 2021 were used and each benign file was submitted to VirusTotal Online Engine (https://www.virustotal.com/gui/home/upload) to check if it does not possess any malicious characteristics or behaviours.
#### Dataset Composition
The dataset consists of 1285 benign files and 1285 malicious files, creating a total of 2570 files in the whole dataset.
#### Categories of Malware in the dataset
The MalbehavD-V1 has the behavioural characteristics of current emerging malware such as Ransomware, Worms, Viruses,
Spyware, Backdoor, Adware, Keyloggers, and Trojans. The dataset has been processed to remove all inconsistencies/noise, making it ready to be used for evaluating the performance of machine learning and deep
learning models. In addition, the dataset is labeled and the hash value for each file
has been included to avoid duplication of files while extending
the dataset in the future. This makes it easier to include behavioural characteristics of new malware variants in the dataset
or combine it with any of the existing datasets of API calls extracted from Windows EXE files.
#### Dynamic Analysis Environment
The analysis environment has five main components, and the network architecture is presented in Figure Below.  
- windows main host machine
- Linux Ubuntu host machine
- Windows virtual machines
- Cukcoo sandbox
- Oracle VirtualBox (virtualization software)

![Dynamic Analysis Environment1](https://user-images.githubusercontent.com/18678162/174477553-998fefd0-c129-43c6-aebd-9f6d78fa0d84.png)

Figure 1: Analysis Environment used to generate MalbehavD-V1

#### Software Downlaod
The above  software are opensource(except Windows) and can be download from: 

- Cukcoo sandbox: https://cuckoosandbox.org/
- Oracle VirtualBox: https://www.oracle.com/au/virtualization/technologies/vm/downloads/virtualbox-downloads.html
- Linux Ubuntu: https://ubuntu.com/download/desktop

### Cuckoo Installation: 
Please follow the following guide to setup the Cuckoo sandbox analysis environment.

https://utopianknight.com/malware/cuckoo-installation-on-ubuntu-20/

#### Citing the dataset
If you use MalbehavD-V1 dataset in your work, please cite it  as follows:

@article{maniriho2023api,

  title={API-MalDetect: Automated malware detection framework for windows based on API calls and deep learning techniques},
  
  author={Maniriho, Pascal and Mahmood, Abdun Naser and Chowdhury, Mohammad Jabed Morshed},
  
  journal={Journal of Network and Computer Applications},
  
  pages={103704},
  
  year={2023},
  
  publisher={Elsevier}
  
}
