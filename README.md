# NessusPro V7 - Nessus IO - Report Exporter Tool (Powershell)

## Notes

**ScriptName:** NessusPro_v7_Report_Exporter_Tool.ps1  
**PSVersion:**  5.1  
**Purpose:**    Powershell script that use REST methods to obtain report automation tasks.  
**Author:**     Paperclips.  
**Email:**      Pwd9000@hotmail.co.uk  
**Created:**    Sept 2018  

## Description

A PowerShell script which will allow the user to connect to any Nessus Server (IO) Or (ProV7) URL + Port and interact with the Nessus API to obtain information on scan reports.  
The user will be able to Export reports in a format of their choice e.g. nessus, CSV, PDF, HTML.  
Reports will be stored on the local system under the path of C:\Temp\  

## Usage

The user will be prompted for the following input criteria when the script is run:  

- Enter a full Nessus Scanner URL incl port (e.g. https://NessusServerFQDN:8834 ).  
- Enter a valid Username that has access to the nessus scanner URL provided.  
- Enter a valid Password to the corresponding Uername provided.  

## Comments

- Script must be run with an ACL that has proxy access or internet access if external facing Nessus.io servers are targeted.  
- Ensure that the correct execution policy is set when executing the script.