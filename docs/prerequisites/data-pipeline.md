## Data Pipeline

Please confirm which of the following your plant uses to manage operational data: 

* [Distributed Control System (DCS)](#distributed-control-system-(DCS)) only
* [Supervisory Control And Data Acquisition (SCADA)](#Supervisory-Control-And-Data-Acquisition-(SCADA)) system on top of a DCS

### Distributed Control System (DCS)

If your plant solely operates on a DCS, implementing a SCADA application that can collect, store, and share data over the Internet will be necessary to integrate with Delta Zero.

Refer to [SCADA](https://docs.google.com/document/d/1QJO5gixlL42dbc0yzW5z_vm_f1FVinaeIDwZi-1RnLA/edit#heading=h.g1gc7da9g9pc) for a list of supported solutions.

### Supervisory Control And Data Acquisition (SCADA)

Ideally, your plant manages data through a SCADA system along with a DCS. These platforms typically have a pre-built Application Programming Interface (API) that facilitates data exchange through a secure HTTP connection.

Carbon Re supports the following solutions: 

* [Cogent Datahub](https://cogentdatahub.com/products/cogent-datahub/) (Cogent)
* [Ignition](https://inductiveautomation.com/scada-software/) (Inductive Automation)
* [KEPServerEx](https://www.ptc.com/en/products/kepware/kepserverex) (PTC Inc.)
* [OSI PI System](https://www.osisoft.com/pi-system) (OSIsoft)

If your plant uses an alternative solution, please contact us at {{ support }} to discuss options.


## Plant data requirements

During the discovery phase, you will be asked to fill out a General Plant Questionnaire to assess the data needed to get set up with Delta Zero.

In addition to the questionnaire, you will be asked to provide the following information: 

- [ ] Full list of available data tags, such as: 
    * Plant parameters & metrics (i.e. sensor data, such as temperature, pressure, air flow, etc)
    * Fuel chemistry analyses
    * Other chemistry data (e.g. kiln feed, hot meal, clinker chemistry, etc)

- [ ] Kiln cooler & preheater specifications.
- [ ] Standard kiln and lab operation practices & processes.
- [ ] Comprehensive logs on plant maintenance & changes (e.g. maintenance schedules, operational issues, history of sensor failures, etc).
- [ ] History of downtime periods, including unplanned & planned downtimes, and shutdowns.
- [ ] List of common issues experienced by the plant.
- [ ] Plant process and instrumentation diagrams.

If the plant is running on an expert optimiser (EO), please also provide:

- [ ] Historical data on EO setpoints & settings.
- [ ] Diagrams of the control loops and mechanisms used to run the EO.
- [ ] List of plant parameters controlled by the EO & EO actuators.

If you require additional data tags, these can be supported provided the following information: 

- [ ] Name & location of the recorded equipment
- [ ] Unit of measurement (e.g. kcal/kg, percentage, Celsius)
- [ ] Range of stability (minimum & maximum values)

These requirements will be communicated to your technical point of contact and amended based on continuous feedback during the discovery phase with Carbon Re representatives. 
