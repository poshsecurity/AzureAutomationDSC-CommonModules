# Azure Automation DSC - Common PowerShell DSC Modules

[![Deploy to Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fposhsecurity%2FAzureAutomationDSC-CommonModules%2Fmaster%2Fazuredeploy.json)

[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fposhsecurity%2FAzureAutomationDSC-CommonModules%2Fmaster%2Fazuredeploy.json)

This template deploys common PowerShell DSC modules to an existing Azure Automation account.

Authored by Kieran Jacobsen.

`Tags: PowerShell, DSC, AzureAutomation`

## Solution overview and deployed resources

This solution accelerates the use and development of Azure Automation DSC. The solution will deploy approximately 30 commonly used PowerShell DSC modules to Azure Automation.


## Modules Deployed

This table lists the modules that will be deployed, along with the author and description (from the PowerShell Gallery). As ARM templates are fixed to a specific version, the version being deployed is listed.

| Module Name | Author | Description | Version |
| --- | --- | --- | --- | --- |
| ActiveDirectoryCSDsc | Microsoft Corporation | This DSC Resource module can be used to install or uninstall Certificate Services components in Windows Server. | 3.0.0.0 |
| AuditPolicyDsc | Microsoft Corporation | The AuditPolicyDsc module allows you to configure and manage the advanced audit policy on all currently supported versions of Windows. | 1.3.0.0 |
| cChoco | Chocolatey Software Lawrence Gripper Javy de Koning | Chocolatey DSC Resources for use with internal packages and the community package repository. Learn more at http://chocolatey.org/ | 2.4.0.0 |
| CertificateDsc | Microsoft Corporation | This module includes DSC resources that simplify administration of certificates on a Windows Server | 4.2.0.0 |
| ComputerManagementDsc | Microsoft Corporation | The ComputerManagementDsc module is originally part of the Windows PowerShell Desired State Configuration (DSC) Resource Kit. This version has been modified for use in Azure. This module contains the xComputer and xDisk resources. These DSC Resources allow you to perform computer management tasks, like joining a domain or initializing disks. | 6.0.0.0 |
| cSpeculationControlFixes | Kieran Jacobsen | PowerShell DSC for enabling Speculation Control fixes on Windows Server | 0.4 |
| DFSDsc | Microsoft Corporation | DSC resources for configuring Distributed File System Replication and Namespaces. | 4.2.0.0 |
| GPRegistryPolicy | Microsoft Corporation | Module with cmdlets to work with GP Registry Policy .pol files | 0.3 |
| GPRegistryPolicyParser | Microsoft Corporation | Module with parser cmdlets to work with GP Registry Policy .pol files | 0.2 |
| HybridRunbookWorkerDsc | Ben Gelens | This DSC Resource Module contains DSC resources to deal with Automation Hybrid Runbook Workers. | 1.0.0.2 |
| NetworkingDsc | Microsoft Corporation | Module with DSC Resources for Networking area | 6.2.0.0 |
| PackageManagementProviderResource | Microsoft Corporation | Module with DSC resources for the package management. | 1.0.3 |
| PSDscResources | Microsoft Corporation | This module contains the standard DSC resources. Because PSDscResources overwrites in-box resources, it is only available for WMF 5.1. Many of the resource updates provided here are also included in the xPSDesiredStateConfiguration module which is still compatible with WMF 4 and WMF 5 (though that module is not supported and may be removed in the future). | 2.9.0.0 |
| SecurityPolicyDsc | Microsoft Corporation | This module is a wrapper around secedit.exe which provides the ability to configure user rights assignments | 2.6.0.0 |
| SqlServerDsc | Microsoft Corporation | Module with DSC Resources for deployment and configuration of Microsoft SQL Server. | 12.1.0.0 |
| StorageDsc | Microsoft Corporation | This module contains all resources related to the PowerShell Storage module, or pertaining to disk management. | 4.3.0.0 |
| UpdateServicesDsc | Michael Greene | Module with DSC Resources for deployment and configuration of Windows Server Update Services. | 1.0.75.0 |
| WindowsDefender | Microsoft Corporation | Windows Defender module allows you to configure Windows Defender settings. | 1.0.0.4 |
| xActiveDirectory | Microsoft Corporation | The xActiveDirectory module is originally part of the Windows PowerShell Desired State Configuration (DSC) Resource Kit. This version has been modified for use in Azure. This module contains the xADDomain, xADDomainController, xADUser, and xWaitForDomain resources. These DSC Resources allow you to configure and manage Active Directory. | 2.22.0.0 |
| xDhcpServer | Microsoft Corporation | Module with DSC Resources for DHCP Server area | 2.0.0.0 |
| xDismFeature | Microsoft Corporation | Module with DSC Resources for Deployment Image Servicing and Management features. | 1.3.0.0 |
| xDnsServer | Microsoft Corporation | Module with DSC Resources for DNS Server area | 1.11.0.0 |
| xFailOverCluster | Microsoft Corporation | Module containing DSC resources used to configure FailOver Clusters. | 1.11.0.0 |
| xInternetExplorerHomePage | Microsoft Corporation | This DSC Resources can easily set an URL for the home page of Internet Explorer | 1.0.0 |
| xPendingReboot | Microsoft Corporation | This module identifies pending reboots in Windows Server and acts on them. | 0.4.0.0 |
| xPSDesiredStateConfiguration | Microsoft Corporation | The xPSDesiredStateConfiguration module is a part of the Windows PowerShell Desired State Configuration (DSC) Resource Kit, which is a collection of DSC Resources produced by the PowerShell Team. This module contains the xDscWebService, xWindowsProcess, xService, xPackage, xArchive, xRemoteFile, xPSEndpoint and xWindowsOptionalFeature resources. | 8.4.0.0 |
| xRemoteDesktopAdmin | Microsoft Corporation | Module with DSC Resources for enabling administrative Remote Desktop Connections | 1.1.0.0 |
| xSmbShare | Microsoft Corporation | Module with DSC Resources for SmbShare area | 2.1.0.0 |
| xSystemSecurity | Arun Chandrasekhar | Handles Windows related security settings like UAC and IE ESC. xUAC enables or disables the User Account Control prompt, while xIEEsc enables or disables IE Enhanced Security Configuration. | 1.4.0.0 |
| xTimeZone | Microsoft Corporation | This DSC Resources can easily set the System Time Zone. | 1.8.0.0 |
| xWebAdministration | Microsoft Corporation | Module with DSC Resources for Web Administration | 2.3.0.0 |
| xWindowsEventForwarding | Microsoft Corporation | This module can be used to manage configuration of a Windows Event Forwarding server in a Collector role. | 1.0.0.0 |
| xWindowsUpdate | Microsoft Corporation | Module with DSC Resources for Windows Update | 2.7.0.0 |
| xWinEventLog | Microsoft Corporation | Configure Windows Event Logs | 1.2.0.0 |

## Prerequisites

You must already have an Azure Automation account to use this solution.

## Deployment steps

You can click the "deploy to Azure" button at the beginning of this document or follow the standard command line process for the deployment of ARM templates.

## Contributing

Interested in contributing? Read how you can [Contribute](contributing.md).

This project maintains a [Code of Conduct](code-of-conduct.md) that establishes how the project is governed and how everyone involved is expected to behave. You can report unacceptable behavior to [code@poshsecurity.com](mailto:code@poshsecurity.com).

## Release History

A detailed release history is contained in the [Change Log](CHANGELOG.md).

## License

This is provided under the [MIT license](LICENSE.md).
