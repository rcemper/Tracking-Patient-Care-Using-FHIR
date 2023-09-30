[![objectscriptquality](https://github.com/rcemper/Tracking-Patient-Care-Using-FHIR/actions/workflows/objectscript-quality.yml/badge.svg)](https://github.com/rcemper/Tracking-Patient-Care-Using-FHIR/actions/workflows/objectscript-quality.yml)

# Tracking Patient Care Using FHIR

In this exercise, you will modify an existing InterSystems IRIS for Health™ system to monitor incoming HL7® FHIR® data from a smart device connected to a Bluetooth oximeter. You will see how InterSystems IRIS for Health acts as a decision support tool, sending HL7 V2 requests to other applications based on parameters that are tracked by the Bluetooth device.

See instructions for *[Tracking Patient Care Using FHIR](https://learning.intersystems.com/course/view.php?name=FHIROximeter)* exercise on the [InterSystems Learning site](https://learning.intersystems.com/).

This package has   
- support for IPM  
- quality tag  
  
### Prerequisites    
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.    
### Installation   
Clone/git pull the repo into any local directory  

````    
git https://github.com/rcemper/Samples-FHIR-Oximeter-Devices-AD.git
````    
   
Build the container with your project:     

````
docker compose --progress plain build
````

Run the container     

 ````
docker compose up -d
````
To follow the startup you may use     

````
docker compose logs -f 
````
[Article in Learning](https://learning.intersystems.com/course/view.php?name=FHIROximeter)

