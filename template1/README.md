# Multi-NIC Virtual Machine Creation using Two Subnets
This template creates a new VM with two NICs which connect to two different subnets within the same VNet.

[![Deploy To Azure](https://raw.githubusercontent.com/icebrian/azure-mbcp-ss-template/master/deploytoazure.svg?token=AACPXX7ARO4BQ5TQCZJACLS7LDT7U)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ficebrian%2Fazure-mbcp-ss-template%2Fmaster%2Ftemplate1%2Fazuredeploy.json%3Ftoken%3DAACPXX2GYPZIT7NGMWCIO227LDUEM)
[![Visualize](https://raw.githubusercontent.com/icebrian/azure-mbcp-ss-template/master/visualizebutton.svg?token=AACPXXYEALH2BIU2GYEPV4K7LDUA4)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Ficebrian%2Fazure-mbcp-ss-template%2Fmaster%2Ftemplate1%2Fazuredeploy.json%3Ftoken%3DAACPXX2GYPZIT7NGMWCIO227LDUEM)


## Tips

1. If running under PowerShell you may update the **azuredeploy.parameters** file with the **allowedValues** for the subnet name of the Primary NIC and Secondary NIC for a nice dropdown list.
2. Customize parameters in **azuredeploy.parameters** as you see appropriate, at the very least the **adminPassword**.

Feel free to post questions and enjoy!