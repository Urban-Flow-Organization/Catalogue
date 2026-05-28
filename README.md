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

### Chimera
Chimera is a customizable software framework for data enrichment and harmonization. Chimera offers components to define schema and data transformation pipelines based on Semantic Web solutions. The tool will be enhanced to support harmonisation and fusion of data needed by URBAN-FLOW.

[Repository](https://github.com/Urban-Flow-Organization/chimera-urbanflow-route)

[Original Repository for Chimera](https://github.com/cefriel/chimera)

[Mapping Template Component](https://github.com/cefriel/mapping-template)

[convergo: GTFS/GTFS-RT to NeTEx/SIRI Converter](https://github.com/cefriel/convergo)

### U-NEED
U-NEED is an advanced data analytics tool to optimizing public transportation systems. The tool will consider the specific condition of disruptive climate events to adapt mobility in the city.

[Repository](https://github.com/jsuarez-etraid/U-Need)

[User Guide](https://github.com/jsuarez-etraid/U-Need/blob/main/UserGuide.md)

[Main Features](https://github.com/jsuarez-etraid/U-Need/blob/main/Functionalities.md)



### ELECTRA
ELECTRA allows the management and planning of the charging sessions of an electric bus fleet. The tool will consider the availability of V2G and the use of charging point for different types of EV.

[Repository](https://github.com/Urban-Flow-Organization)

### PARCAR
Tool to help the local authorities to dynamically manage curb-side parking at specific sites for various purposes, such as logistics (loading/unloading), school drop-off/pick-up, disabled access, and general use. The tool will support the dynamic use of public space as response to disruptive climate events. 

[Repository](https://github.com/Urban-Flow-Organization)

### INES CLOUD
INES Cloud is a modular platform for digitizing urban mobility and parking services. Certified in the national SaaS marketplace, it integrates multiple application modules, field devices, and external systems, offering a solution to regulate vehicle access and manage permits. The platform will be evolved with new API for data acquisition from new data sources, a data visualization tool and a recommendation and alerting tool to support policy makers.

[Repository](https://github.com/Urban-Flow-Organization)

### MUV CLOUD 
MUV Cloud is a cloud-native, interoperable platform to develop multimodal mobility services. It supports sustainable transport with a user app for trip planning and ticketing, and an operator interface for data integration, analytics, and service management. MUV Cloud will be evolved with vehicle tracking features to monitor vehicles journey within the LEZ area and to apply dynamic road pricing based on real mileage.

[Repository](https://github.com/Urban-Flow-Organization)

### THERMAL COMFORT 
Tool for the identification of optimal location of climate refugees and comfortable itineraries, based the thermal comfort criteria and specific accessibility needs. Industrialization of previous developments, inclusion of cycling, pedestrian mobility, public transport stops, school spaces.

[Repository](https://github.com/Urban-Flow-Organization)

### Digital Twin Solution 
The Digital Twin Solution allows you to view different elements of the city in layers such as buildings, green areas, roads and points of interest; and view its attributes. Progression from 2D and 3D to fully-immersive 3D (metaverse) interaction, adapted to different co-desing urban planning processes.

[Repository](https://github.com/Urban-Flow-Organization)

### SMART GEOSPATIAL CHAT 
Generative AI-based tools supporting the consultation and exploitation of information from the municipal GeoPortal. Extension of scenarios, considering heterogenous data and complex queries and interfaces. Industrialization of developments.

[Repository](https://github.com/Urban-Flow-Organization)

### ENERGY COMMUNITIES OPT 
A module that allows the solar energy generated by a building with photovoltaic panels to be distributed among other buildings in its surroundings. Improvement of optimization algorithms. Evolution of its UI and integration on DigitalTwin.

[Repository](https://github.com/Urban-Flow-Organization)

### TATEBE 
Tampere EV charging testbed for innovative charging technology experiments and assessment. V2X technology interoperability capabilities and user experience evaluation possibilities will be added.

[Repository](https://github.com/Urban-Flow-Organization)

### Remote Control Center
Remote supervising and controlling automated vehicles including facilities, HW, SW and connectivity. Support for on-demand and/or assisted services will be added.

[Repository](https://github.com/Urban-Flow-Organization)

### DataHub 
Aims at managing protocols and devices heterogeneity and provides access to data/actions of IoT devices. Creation of specific data bridges and data models to fit the project pilot needs for interoperability.

[Repository](https://github.com/Urban-Flow-Organization/kentyou-datahub)

### Kentyou Eye 
Urban hypervisor solution to visualize urban data, provide forecasts and decision support for municipal actors. Creation of dedicated data analytics and decision support solutions for the project pilots.

[Repository](https://github.com/Urban-Flow-Organization/kentyou-eye)

### EPISODE-CityChem 
Open-source urban air quality model that simulates city-level pollutant dispersion and chemical interactions, providing high-resolution exposure estimates for pollutants like NO2, O3, and PM2.5.

[Repository](https://github.com/Urban-Flow-Organization)

### BenMAP-CE 
BenMAP-CE quantifies health impacts of air pollutants on mortality and respiratory diseases, using exposure-response functions.

[Repository](https://github.com/Urban-Flow-Organization)



