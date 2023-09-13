[![Quality Gate Status](https://community.objectscriptquality.com/api/project_badges/measure?project=intersystems_iris_community%2FSamples-FHIR-Oximeter-Devices-AD&metric=alert_status)](https://community.objectscriptquality.com/dashboard?id=intersystems_iris_community%2FSamples-FHIR-Oximeter-Devices-AD)    

# Tracking Patient Care Using FHIR

In this exercise, you will modify an existing InterSystems IRIS for Health™ system to monitor incoming HL7® FHIR® data from a smart device connected to a Bluetooth oximeter. You will see how InterSystems IRIS for Health acts as a decision support tool, sending HL7 V2 requests to other applications based on parameters that are tracked by the Bluetooth device.

See instructions for *[Tracking Patient Care Using FHIR](https://learning.intersystems.com/course/view.php?name=FHIROximeter)* exercise on the [InterSystems Learning site](https://learning.intersystems.com/).

This package was adopted from the [orphaned predecessor](https://openexchange.intersystems.com/package/Samples-FHIR-Oximeter-Devices)    
- fixed dockerfile to be version independent   
- fixed pending mapping to SuperServer  
- fixed broken install script   
- adjusted code changes in HS  
- added support for IPM  
- added installation guide
- added quality tag  
- enhanced README

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

