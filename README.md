# unify-point-cloud-city
Code and documentation to unify the Enfield and Memphis point cloud datasets in NIST's Point Cloud City

This repository contains two notebooks, the first which can be used to unify the Point Cloud City dataset and the second which converts that dataset into the same format as Semantic KITTI.

https://www.nist.gov/ctl/pscr/funding-opportunities/past-funding-opportunities/psiap-point-cloud-city

https://www.semantic-kitti.org/


## Dataset Composition

### Enfield Project Overview:
The Enfield Project, part of the broader Point Cloud City initiative funded by the National Institute of Standards and Technology’s (NIST) Public Safety Innovation Accelerator Program, focuses on collecting and cataloging indoor point cloud and image data for various buildings in Enfield and Storrs, Connecticut. With a population of approximately 45,000, Enfield presents a diverse array of buildings, including schools, warehouses, and commercial and industrial facilities, making it an ideal setting for demonstrating the value of indoor 3D data in public safety contexts.

The project involved mapping the interiors of 11 buildings, including 6 schools, 1 office building, 1 industrial building, and 3 university buildings on the University of Connecticut Storrs campus. These buildings were selected to encompass a variety of architectural features, ensuring the robustness of the data collected. The primary goal was to create detailed 3D point clouds using LiDAR technology, which were then annotated to highlight features of interest to first responders, such as doors, windows, and walls.

The Enfield Fire Department (EFD) collaborated closely with researchers from the University of Connecticut (UCONN) to classify the point clouds and develop annotated floor plans. The EFD's expertise in public safety needs guided the classification process, while UCONN researchers, experienced in LiDAR field data collection and processing, ensured high-quality and accurate data. The resulting datasets, including 3D point clouds and 2D shapefiles, are crucial for advancing indoor navigation systems that can enhance the safety and effectiveness of first responders by providing accurate digital maps linked to real-world coordinates.

This project not only contributes to improving emergency response but also supports the development of indoor navigation technologies that will aid in guiding first responders through hazardous, low-visibility environments. The Enfield Project’s data and products are available upon request for researchers working on indoor mapping or navigation technology.



### Memphis Project Overview:
The Memphis Project, titled "Map 901: Building Rich Interior Hazard Maps for First Responders," is a key initiative within the broader Point Cloud City program, funded by the National Institute of Standards and Technology’s (NIST) Public Safety Innovation Accelerator Program. This project represents a collaboration between the City of Memphis and the University of Memphis, aiming to enhance the safety and effectiveness of first responders through the creation of detailed indoor hazard maps.

The project focuses on surveying 1.86 million square feet of indoor space across nine facilities in Memphis, including public and university buildings. Utilizing advanced technologies such as LiDAR-equipped backpacks, 360° cameras, and various environmental sensors, the team captures comprehensive 3D point cloud models of these indoor spaces. These models are then annotated with public safety objects, such as doors, windows, and potential hazards, to create information-rich maps that can be used during emergency operations.

The Memphis Project employs Velodyne’s Puck 3D LiDAR for both manned and automated data collection, supplemented by a range of sensors to gather time-synchronized images and environmental data. This multi-modal approach ensures that the resulting point clouds are not only spatially accurate but also enriched with contextual information critical for public safety. The data collected is geo-referenced using GPS, enabling precise mapping that is essential for indoor navigation systems.
The project’s technical innovations include real-time processing and visualization methods to enhance data collection efficiency, as well as the use of machine learning algorithms to identify and classify objects of interest within the point clouds. Additionally, the project incorporates robust data storage, compression, and security measures, including the use of hierarchical data naming and encryption, to ensure the integrity and accessibility of the data.

Led by the City of Memphis's Chief Information Officer, Michael Rodriguez, and Chief Data Officer, Todd Hollenbeck, along with University of Memphis professors Lan Wang and Eddie Jacobs, the project leverages extensive expertise in image sensing, named data networking, and multi-modal sensing systems. The collaboration also includes contributions from GreenValley International, which provided equipment and software for the project.

The Memphis Project not only aims to improve the safety and efficiency of first responders during emergencies but also facilitates broader research in indoor mapping, localization, and navigation. The datasets generated are shared with public safety agencies through the City’s open data platform, data.memphistn.gov, and will be available for future research, contributing to the ongoing development of indoor navigation and augmented reality applications.



### Hancock County Project Overview:
The Hancock County Project, part of the NIST Public Safety Innovation Accelerator Program’s Point Cloud City initiative, focused on generating a comprehensive catalog of annotated 3D indoor point clouds across various buildings in Hancock County, Mississippi. Known for its significant experience in disaster management and geospatial innovation, Hancock County partnered with local geospatial companies NVision Solutions Inc. and Teledyne Optech to conduct this project. The initiative aimed to advance indoor mapping, localization, and navigation technologies to enhance public safety.

Hancock County’s diverse architectural landscape, featuring both historical and modern buildings, provided a robust sampling for creating these datasets. The project employed advanced mobile mapping systems, including the Optech Maverick, to capture 3D point clouds and associated data. The project’s goal was to create detailed indoor maps that could be used by public safety agencies during emergency operations and by researchers in various geospatial fields.
However, the Hancock County dataset was not utilized in this round of our research due to a fundamental difference in their labeling practices. Unlike the datasets from Memphis and Enfield, which involved direct labeling of all points for each object within the point clouds, the Hancock County project employed a different method. They labeled only a single point or a set of four points to create a bounding box around objects, rather than labeling the entire point cloud directly. This difference in labeling methodology made it less compatible with our specific research objectives at this time.
Despite this, we recognize the value of the Hancock County dataset and plan to incorporate it into future research with different investigative goals. The dataset offers unique insights and will likely be valuable for exploring other aspects of indoor mapping and public safety applications in subsequent studies.
