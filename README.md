# auto-center-business-process

## About Auto Center


 ![1](https://github.com/kamilczernuszka/auto-center-business-process/assets/139373087/e11d4300-13cf-4eff-9c0a-282ed51b0b7c)<br>
The Auto Center company is an organization where the process of repairing passenger cars takes place. Workplace
is headquartered at 5 Poziomkowa Street in Zielona Góra. Two people work in the company.

In terms of industry specifics, the company earns, among others, on checking and repairing car components
such as specialized electrical and electronic systems on board the vehicle.

## Glossary of Terms

- **Electrical/Electronic System**: A system composed of electrical and electronic components such as integrated circuits, resistors, capacitors, transformers, transistors, relays, etc. This term also includes complex components like engine controllers, ABS controllers, sensors, etc. An electrical system does not include microprocessor components.
- **Electrical Installation**: The wiring connections between electrical systems in a personal vehicle, allowing the transfer of signals in digital or analog form.
- **Electronic Device**: Devices found in a personal vehicle's equipment, such as radios, lights, diodes, GPS systems, audio systems, alarms, parktronic systems, etc.
- **Testing**: The process of verifying the correct operation of systems within a vehicle, including electronic devices, electrical installations, and electrical/electronic systems.
- **Diagnosis**: The process of assessing the technical condition of a vehicle by communicating with the onboard computer, which provides information about errors detected in specific electrical/electronic systems of the vehicle.

## Business Actors

### ID: AKT_KIEROWNIK
- Name: Company Manager
- Description: The company manager is responsible for financial management and handling formalities.

### ID: AKT_Elektryk
- Name: Electrician
- Description: The electrician is a workshop employee responsible for repairing personal vehicles. They typically handle repairs related to electrical systems in vehicles and also take customer orders.

## Business Objects

- **Zlecenie (Order)**: A document describing the problem for which a customer visits the car electrician workshop for repair. The document includes information about the estimated repair price (service cost).
- **Protokół naprawy (Repair Protocol)**: A document describing the identified source of the problem and the actions taken to repair it.
- **Faktura (Invoice)**: A document containing detailed information about the completed transaction for the vehicle repair service.
-   ## Business Rules
| ID  | Rule Definition                          
| Reg1| No permits, licenses, or authorizations are required to establish a car workshop. | **Type**: Fact | **Source**: Applicable regulations in CEIDG | <br>
| Reg2| In case of causing material damage, an application for compensation must be submitted to the company's insurer. | **Type** : Procedure | **Source**: Procedure for claiming liability insurance compensation | <br>
| Reg3| The service cost is calculated based on an hourly rate. | **Type**: Pricing | **Source**: Service price list with cost calculation and workshop margin |<br>
| Reg4| In case of canceling the service, a fee of 30% of the initial service cost will be charged. | **Type**: Limitation |  **Source**: Service execution regulations |<br>
| Reg5| Documents are archived in a specially designated archival cabinet, and repair protocols are stored in an electronic archive of the system. | **Type**: Fact | **Source**: Archiving regulations |

## Business process
The business process is editable in the auto-center-business-process.bpmn file.

# Running BPMN in Camunda Modeler

To run a auto-center-business-process.bpmn file in Camunda Modeler, follow these steps:

1. Download and install Camunda Modeler: Visit the official Camunda website (https://camunda.com/download/modeler/) to download the Camunda Modeler application compatible with your operating system.

2. Launch Camunda Modeler: After installing Camunda Modeler, open the application on your computer.

3. Open the BPMN file: In Camunda Modeler, go to "File" and select "Open File". Browse to the location where your BPMN file is stored and select it. The BPMN file will be loaded into the Camunda Modeler interface.

4. Execute the BPMN process in Camunda Engine: Camunda Modeler is primarily used for modeling and designing BPMN processes. To execute and monitor the BPMN process, you will need to deploy and run it in the Camunda Engine, which is a separate runtime environment provided by Camunda.

## License

This project is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute this project as needed.


