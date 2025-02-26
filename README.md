# Resume
<h2>SUMMARY</h2>
Pursuing a Master’s in Computer Science at the University of Kansas, I am passionate about leveraging data insights and technology to solve real-world challenges.<br>

I bring hands-on experience from Cognizant Technology Solutions, where I worked as a Programmer Analyst specializing in automation testing, backend optimization, and microservices development. My expertise includes designing scalable backend systems with Spring Boot, optimizing database interactions using Hibernate, and integrating RESTful APIs for seamless communication. My internship as a QA Engineer focused on enhancing application efficiency and user testing in payment systems. Additionally, my recent projects include a healthcare data privacy framework and a Boolean Satisfiability Solver using the DPLL algorithm.<br>

I am continuously seeking to enhance my skills and stay updated with industry trends to bring fresh perspectives to every project.<br><br>

<h2>EDUCATION</h2><br>
University at Kansas, Lawrence, Kansas<br>
Master’s degree | 2023- 2025<br>


<h2>TECHNICAL SKILLS</h2><br>
**Programming/Scripting Languages:** Java, C ,Javascript.<br>
**Operating Systems:** Windows, Linux.<br>
**Skills and Tools:** SpringBoot ,Spring Framework ,Spring Security ,Hibernate/JPA ,GIT ,Git&Github ,Spring Cloud ,Maven ,RestAPI ,MySQL ,PostgreSQL , AzureDevOps , Amazon Web Services, Docker, Kubernetes. <br><br>

<h2>Work Experience</h2>
<h3>Programmer Analyst</h3>
<h3>Cognizant Technology Solutions</h3>                                                                         <h3>  (July 2021- July2023)</h3>
-> Designed and implemented scalable backend systems using Spring Boot, ensuring high availability for payment processing applications.<br>
-> Developed and optimized microservices architecture for seamless integration of CBPR+, ISO 20022 migration, SWIFT Release, and SEPA payments.<br>
-> Implemented Spring Security for authentication and authorization in banking transactions, ensuring compliance with financial regulations.<br>
-> Utilized Hibernate and Spring Data JPA to manage large transaction datasets, reducing query execution time and improving performance.<br>
-> Integrated RESTful APIs with third-party payment gateways and internal banking systems to support international payment processing.<br>
-> Ensured smooth deployment and integration of software solutions by collaborating with cross-functional teams, including payment operations and compliance teams.<br>
-> Followed Agile (Scrum) methodology, actively participating in sprint planning, estimation, daily stand-ups, sprint demos, and retrospectives.<br>
-> Managed and maintained Git and GitHub repositories, implementing access control strategies for secure versioning and collaboration.<br><br>


<h2>Internship</h2><br>
<h3>Cognizant Technology Solutions</h3>   <h3>(Feb 2021 - June 2021)</h3>
-> Analyzed and understood business requirements from Mapping Specification documents provided by Business Analysts (BAs) for payment processing and banking applications.<br>
-> Developed functional maps in IBM WTX/ITX and integrated them with Spring Boot services, reducing mapping complexity and improving data transformation efficiency.<br>
-> Implemented Hibernate and Spring Data JPA for database interaction, optimizing queries for large datasets related to banking transactions and financial records.<br>
-> Created and optimized JPA repositories and custom queries to support complex payment workflows such as CBPR+, ISO 20022, SWIFT, and SEPA payments.<br>
-> Actively participated in Agile development, attending sprint planning, daily stand-ups, sprint demos, and retrospectives to ensure smooth project execution.<br><br>


<h2>Projects</h2>
<h3>Real-time object detection using the ESP32-S3 microcontroller</h3>
<p>Our project focuses on real-time object detection using the ESP32-S3 microcontroller. The goal was to create a lightweight and efficient system that could detect objects within the ESP32-S3's resource constraints.</p>

<h4>Implementation</h4>
<h4>Dataset and Training:</h4>
<p>We used a dataset of approximately 2.2k images and labels, splitting it into training, testing, and validation subsets. The YOLOv5n model was trained with parameters like a 320x320 image size, 50 epochs, and a batch size of 16, achieving precise results.</p>

<h4>Optimization:</h4>
<p>We pruned 20% of the model weights to reduce size and fine-tuned it for optimal performance. The optimized model was converted to TensorFlow Lite format and further quantized to uint8 format to improve compatibility with the ESP32-S3.</p>

<h4>Deployment:</h4>
<p>The uint8 TFLite model was integrated into the ESP32-S3. We wrote source files for camera setup, inference handling, and bounding box visualization. The system streamed live detection results via Wi-Fi, with bounding box coordinates visible on a hosted web page and the serial monitor.</p>


 <h3>DIFFERENTIAL PRIVACY ON HEALTHCARE</h3><br>
->In this project, we presented a comprehensive framework that integrates state-of-the-art
privacy-preserving techniques, addressing the critical privacy concern in healthcare data.<br>
->The main goal of our project is to strengthen the confidentiality of individual records by
implementing differential privacy, a paradigm that is widely acknowledged. The Laplace
mechanism is utilized to incorporate precisely calibrated noise into numeric columns in the database, like
'Age,' 'Billing Amount,' and 'Room Number,' maintaining data integrity while augmenting
privacy.<br>
->Data masking is incorporated to anonymize columns, like 'Medical
Condition' and 'Name,' by restricting their representation to a specific maximum length.<br>
->Applying hashing to tokenization, specific columns such as 'Hospital,' 'Insurance Provider,' and
'Medication' are protected against security breaches.<br>
->To give users concrete control over the degree of privacy they desire to
preserve, the project presents the idea of a privacy budget (ε) as a parameter. <br>
-> This comprehensive method yields a refined healthcare dataset, establishing the groundwork for
responsible data handling and adding to the ongoing conversation about privacy in the
healthcare industry.<br>

