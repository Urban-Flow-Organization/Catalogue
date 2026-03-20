# Catalogue
URBAN FLOW develops a set of software tools that implement the Local Digital Twin foundation, data and KPI management, interoperability with data spaces, online collaboration, and impact assessment capabilities described in the Grant Agreement.

These tools will be progressively released as separate repositories under this organisation:
​

### Online collaboration platform for URBAN FLOW (Decidim)
Decidim is a participatory democracy framework, written in Ruby on Rails, originally developed for the Barcelona City government online and offline participation website. Installing these libraries will provide you a generator and gems to help you develop web applications like the ones found on example applications or like our demo application.

[Repository](https://github.com/Urban-Flow-Organization/decidim)

#### Decidim Modules Extensions:

[decidim-module-apiauth](https://github.com/Urban-Flow-Organization/decidim-module-apiauth)

[decidim-module-idra](https://github.com/Urban-Flow-Organization/decidim-module-idra)

[decidim-module-iframe](https://github.com/Urban-Flow-Organization/decidim-module-iframe)

[decidim-module-keycloak](https://github.com/Urban-Flow-Organization/decidim-module-keycloak)

[decidim-module-nbs_stories](https://github.com/Urban-Flow-Organization/decidim-module-nbs_stories)

[decidim-module-urbreath-ui](https://github.com/Urban-Flow-Organization/decidim-module-urbreath-ui)

[decidim-module-whiteboard](https://github.com/Urban-Flow-Organization/decidim-module-whiteboard)

### Idra - Open Data Federation Platform
Idra is a web application able to federate existing Open Data Management Systems (ODMS) based on different technologies providing a unique access point to search and discover open datasets coming from heterogeneous sources. Idra uniforms representation of collected open datasets, thanks to the adoption of international standards (DCAT-AP) and provides a set of RESTful APIs to be used by third party applications.

Idra supports natively ODMS based on CKAN, DKAN, Socrata, Orion Context Broker (NGSI v2, NGSI-LD) and many other technologies: Idra provides also a set of APIs to federate ODMS not natively supported. In addition, it is possible to federate generic open data portals, that don't expose API, using the web scraping functionality or providing a dump file of the datasets in DCAT-AP format. Furthermore, Idra provides a SPARQL endpoint in order to perform queries on 5 stars RDF linked open data collected from federated ODMS and allows to easily create charts based on federated open datasets (through DatalEt-Ecosystem Provider DEEP )

Idra is an open source software developed by Engineering Ingegneria Informatica SpA inside the EU founded project "FESTIVAL". This project is part of FIWARE. For more information check the FIWARE Catalogue entry for Data Publication. 

[Repository](https://github.com/Urban-Flow-Organization/Idra)​

### KPI Manager
The KPI Manager (part of the Digital Enabler platform) is designed to track, analyze, and manage key performance indicators effectively.
Its primary purpose is to provide insights into the performance of various aspects of an organization, a project, a solution, enabling informed decision-making and strategic planning.
It acts as a central hub for aggregating data from various sources. By consolidating data from disparate systems and databases, the KPI Manager provides a unified view of performance metrics.
Through intuitive visualization tools such as dashboards, charts, and graphs, KPI Manager presents KPIs in a clear and accessible manner. This allows stakeholders to quickly see trends, patterns, and outliers within the data, facilitating informed decision-making.

[Repository](https://github.com/Urban-Flow-Organization/KPI-Manager)​

### GeoCacher
GeoCacher is a backend service designed to support a graphical dashboard for visualizing geospatial data. Its primary purpose is to interface with a FIWARE ORION Context Broker to extract and temporarily store (cache) data.

Key features include:

Data Extraction: Retrieves filters and geospatial data from the ORION Context Broker.
Search Management: Supports CRUD (Create, Read, Update, Delete) operations to save and manage user searches on a supporting MongoDB database.
GeoJSON Upload: Allows users to upload and display custom GeoJSON files on the dashboard.

[Frontend](https://github.com/Urban-Flow-Organization/GeoCacher-frontend)

[Backend](https://github.com/Urban-Flow-Organization/GeoCacher-backend)

### Orion Context Broker (with Linked Data Extensions)
Orion-LD is a Context Broker and CEF building block for context data management, implementting both the NGSI-LD API and the NGSIv2 API. It is currently a fork of the original Orion Context Broker extending support to add NGSI-LD and linked data concepts. Orion-LD follows the ETSI specification for NGSI-LD and has been tested to be a stable and fast NGSI-LD broker with near compliance to the version 1.6.1 of the NGSI-LD API specification (and some features from newer releases).

[Repository](https://github.com/Urban-Flow-Organization/context.Orion-LD)​

### New component here
New component description here

[Repository](https://github.com/URBREATH/Idra)

