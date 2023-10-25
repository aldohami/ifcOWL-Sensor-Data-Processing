# ifcOWL-Sensor-Data-Processing
 Comprehensive guidance for sensor data processing and visualization using IfcOpenShell and the rdflib library

##  What is ifcOWL?
- ifcOWL provides a Web Ontology Language (OWL) representation of the Industry Foundation Classes (IFC) schema. IFC is the open standard for representing building and construction data (see BuildingSMART). The ifcOWL ontology has the same status as the EXPRESS and XSD schemas of IFC.

![](images/expressxsdowl-300x192-300x192.png)

https://technical.buildingsmart.org/standards/ifc/ifc-formats/ifcowl/


- What is it good for?
Using the ifcOWL ontology, one can represent building data using state of the art web technologies (semantic web and linked data technologies). IFC data thus becomes available in directed labelled graphs (RDF). This graph model and the underlying web technology stack allows building data to be easily linked to material data, GIS data, product manufacturer data, **sensor data**, classification schemas, social data, and so forth. The result is a web of linked building data that brings major opportunities for data management and exchange in the construction industry and beyond.

## Table of Contents

- **Step 1: Installing the rdflib Library**

  Begin by Installing the rdflib library.

  > Note: If using this code locally, ensure you have JupyterIFCRenderer installed, which can be achieved through conda. Alternatively, in a Jupyter Notebook environment, the library may be readily available.

- **Step 2: Loading and Visualizing IFC Models**

  Immerse yourself in the world of IFC models using the JupyterIFCRenderer, enabling you to load and interactively visualize these complex structures.

  

- **Step 3: Processing RDF Data for Sensor Information**

  Embark on a journey of discovery by selecting spaces interactively and importing RDF data from a file. Learn the art of extracting vital information about rooms and their associated sensors through the use of SPARQL queries. See how to display comprehensive information about selected rooms and their corresponding sensors.

This repository is your go-to resource for those interested in working with RDF data in IfcOpenShell, whether for educational purposes or as a reference for ifcOWL data processing tasks.
