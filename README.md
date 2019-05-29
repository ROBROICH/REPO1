# SAP and Azure IoT "Hello World" Demo 

Earlier this year [Microsoft and SAP announced an extended partnership to Internet of Things](https://azure.microsoft.com/en-us/blog/microsoft-and-sap-extend-partnership-to-internet-of-things/)

In parallel to this announcement basic integration scenarios between Azure IoT and SAP are already possible. 
The intention of this demo is to demonstrate the Lego-like integration between Azure IoT and SAP ECC based on SAP Gateway. 

The idea is to have a public repeatable setup of the demo based on :
-Public Azure Raspberry emulator

-Public SAP demo system 

-Azure IoT Hub and Logic App

Summarized this demo is a basic extension of an existing Azure IoT tutorial to demonstrate SAP connectivity

## Demo scenario and basic storyline 

-Imagine the Raspberry Emulator as a IoT device used in shipping of heat-sensitive vaccines

-If the temperature is measured above 30°, the vaccine is damaged and must be replaced  

-To replace the vaccine, a sales order is automatically created in SAP ECC in case the measured temperature is above 30° 

-For excel users the current sales order SAP ECC will be displayed in Excel 

image:: https://github.com/ROBROICH/REPO1/blob/master/images/DEMO_ARCHITECTURE.jpg
  :height: 1500px
  :width: 400 px
  :scale: 50 %
  


## Demo preparation: Raspberry PI emulator and IoT Hub

-Implement Raspberry PI emulator tutorial [Link](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-raspberry-pi-web-simulator-get-started)



-Implement IoT remote monitoring and notifications with Azure Logic Apps connecting your IoT hub and mailbox tutorial [Link](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-monitoring-notifications-with-azure-logic-apps)
Stop at the paragraph “Configure the logic app trigger”






These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
