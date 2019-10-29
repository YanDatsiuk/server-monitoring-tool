# Server Monitoring tool

Main purpose of the project - allow servers owners / administrators to monitor its work / status.

## Status of this project

Date of creation: 29 Oct 2019  
Status: actively developing.

## Developer's guide for this project

Directory `tools` - consist of tools, written preferably but not obligatory in Golang.

Directory `tools-config` - contains .json files with configurations about execution frequency & parameters of each tool. *(this directory is added to .gitignore)*

Directory `execution-log` - contains information about start and end execution time of each tool. *(this directory is added to .gitignore)*


## Roadmap

- tools
  - create simple server ping tool.
  - create tool for getting webpage and measure time of response.
- create admin dashboard for managing tools-configurations.
  - user should have a possibility to add tool and set its configuration.
  - user should have a possibility to view/edit/remove already existed tools and their configurations.
- create admin dashboard for watching execution logs.
- create and integrate system with different notification channel providers. (email, sms, slack...)
