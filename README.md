# GenericCredential

Get-GenericCredential

Description
Fetch the Generic Credential from Windows which is present in Control Panel -> User Account -> Credential Manager. So we can import this module and use for remote session without saving the password.

Import
To import the module including all source code you can just run in a PowerShell the following command:

Import-module .\GenericCredential.psm1

Support
. Provide functionality for automating windows session remotely by generic password. . Support Windows remote session

Example
. Get-GenericCredential -Name Jas

. Get-GenericCredential -Name domain\username
