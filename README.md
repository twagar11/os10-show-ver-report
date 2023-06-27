# os10-show-ver-report
The purpose of this Repo is to Use Ansible to issue various show commands to collect OS10 switch variables in preparation for switch software upgrades.  The playbook will collect switch hostname, model, service tag, OS version, S5200 PCIe ver, ONIE SW ver, firmware BIOS version.  Since show commands are unstructured the data will have to be parsed into simple variables.  Once all the variables are collected a single master csv report will be created for data mining via Excel.  Logic also exists to collect PCIe version information from only Dell S5200 model switches.
## Background
