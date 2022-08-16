Under this Project, we will test , build Azure resources and services through IaC using ARM. 
Goal                                                                            To create azure resources/services through ARM and automate the process using Azure Devops.
In this we will also learn basics of Git and GitHub , How to clone, work on branches, pull requests , making readme.md files
Infrastrature Nomenclature.                                                   We will have naming standards for ARM files. For example Parameter file and template file should be separate. az resources/service should follow naming convention as - <resource/service>-<environment>-<Location>-<serialnumber> . example - sta-dev-eus-001 this means - storage acc for Dev environment in EastUS location and series as 001
Parameter File should be named as resource<serialnumber>.Parameter.json and Template file as resource.deploy,json , example - sta001.Parameter.json & sta001.deploy.json
                     