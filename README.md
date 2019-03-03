# InstallEnsDemoLite

ENSDEMO port to IRIS without HL7 and DICOM examples

## Prerequisites

This project use large data files. Make sure that you have git-lfs installed.

```
See https://git-lfs.github.com/
```

As this port include HL7 and DICOM you need IRIS for Health.

### Installing

Clone this repository

```
git lfs clone https://github.com/grongierisc/InstallEnsDemoHealth.git
```

And run install.sh

```
sh install.sh <IRIS Instance> <IRIS SuperUser Password>
```

### Content of this project

The Samples database form Ensemble port on Iris.
This include data and code of :

* ComplexMap
* CustomSearchTable
* Dashboard
* DICOM
* FloodMonitor
* HL7
* HL7v3
* Loan
* RecordMap
* RecordMapBatch
* REST
* SAP
* Util
* Workflow
* X12

