# multiGWAS-vm
MultiGWAS ready-to-use VirtualBox virtual machine running Ubuntu linux 18.04.  

The virtual machine can be downloaded from the [corpoicaorg repository](https://corpoicaorg-my.sharepoint.com/:u:/g/personal/lgarreta_agrosavia_co/ERb_R-GatEpMnjHDg17PAdYB56osZ9RS_nK72qZlYJB_qg?e=cCwE4V)

# Usage instructions
- Import the virtual machine using the VirtualBox software
- Start the virtual machine
- Log in as "mg" user with password "mg"
- Open a linux terminal
- Change to the "examples" folder
- Execute multiGWAS with either "naive.config" of "full.config" configuration files
```
   multiGWAS full.config
```
- Open the file manager to browse the results:
  - The "multiGWAS-report.html" file contains a full report in html format of the GWAS analysis.
  - The "report" folder contains the original tables and graphics shown in the report.
  - The "out" folder contains the file outputs from MultiGWAS and from the four GWAS tools.
  - The "logs" folder contains log and output messages from the four GWAS tools.
