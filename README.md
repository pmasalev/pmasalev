# 👋 Hi, I'm Pavel
System Analyst | Turning Complex Systems into Clear Solutions 🦸‍♂️

## About Me
Hello! My name is Pavel, and I specialize in system analysis, process optimization, and technical documentation.  
I enjoy breaking down complex problems into manageable components and delivering efficient solutions.  

- 🔧 System Analysis & Design
- 📊 Data-Driven Decision Making
- 📝 Documentation & Process Optimization
- 💡 Exploring new technologies and tools

---

## Projects 🚀

### **MyMobile**
- **Description**: Mobile application for a regional mobile network operator with 1.5 million subscribers.  
  The project involved creating a detailed **Software Requirements Specification (SRS)** document to define the functional and non-functional requirements of the application, ensuring compliance with Russian Federal Law No. 152-FZ on Personal Data Protection.

  **Key Features**:
  - User authentication via SMS code.
  - Balance checking, including minutes, SMS, and data allowance.
  - Viewing current tariff plan details and switching between available plans.
  - Managing additional service options (activation/deactivation).

  **Platforms**: Android 12+, iOS 16.7.10+  
  **API Integration**: RESTful API for customer management, tariff plans, and service options.  
  **Future Enhancements**: In-app account top-up, multi-account management, support chat integration, and retail store locator.

  **Project**: [MyMobile](https://github.com/pmasalev/MyMobile)  
  **Documentation**: [SRS Document](https://github.com/pmasalev/MyMobile/blob/main/SRS%20MyMobile%20v.1.0.0.docx)
  
---

### **Neto-Courier. Courier Ordering System**
- **Description**: A cloud-based PostgreSQL database system designed for managing courier requests for document delivery to counterparties.  
  The project involved creating a scalable and secure database schema, implementing user roles, and developing procedures and functions for data management and reporting.

  **Key Features**:
  - **Cloud Database Setup**: Created a PostgreSQL database using [Supabase](https://supabase.com/).
  - **User Roles**: Configured a user (`netocourier`) with full access to the `public` schema and read-only access to `information_schema` and `pg_catalog`.
  - **Database Schema**:
    - `courier`: Stores courier request data, including source, destination, document name, and status.
    - `account`: Manages counterparty information.
    - `contact`: Stores contact details of counterparties.
    - `user`: Tracks employee information, including active and dismissed statuses.
  - **Data Generation**: Implemented a procedure `insert_test_data(value)` to generate random test data for all tables.
  - **Testing**: Developed a procedure `erase_test_data()` to clean up test data after testing.
  - **Functions and Procedures**:
    - `add_courier()`: Adds new courier requests to the database.
    - `get_courier()`: Retrieves courier request data with sorting by status and creation date.
    - `change_status()`: Updates the status of a courier request.
    - `get_users()`: Returns a list of active employees sorted by last name.
    - `get_accounts()`: Returns a list of counterparties sorted by name.
    - `get_contacts(account_id)`: Retrieves contacts for a specific counterparty or prompts the user to select one.
  - **Reporting**:
    - `courier_statistic`: A view that provides detailed statistics on courier requests, including order counts, completion rates, cancellations, and trends compared to the previous month.

  **Technologies**:
  - PostgreSQL
  - Supabase
  - UUID generation using `uuid-ossp`
  - Enum types for status management
  - Random data generation for testing
    
  **Project**: [Neto-Courier](https://github.com/pmasalev/neto-courier-tz)) 
  **Documentation**: [Technical Specification](https://github.com/pmasalev/neto-courier-tz/blob/main/technical_specification.md)

---

## Skills 🛠️

### **Business Analysis**
- Business Process Modeling (BPMN)
- Business Process Optimization
- Automation of Business Processes
- Description of Business Processes
- Requirements Gathering

### **System Analysis**
- Development of Technical Specifications
- Writing Technical Assignments (**according to GOST and SRS standards**)
- System Architecture Design
- Data Warehouse (DWH) Design
- **ER Diagrams (Entity-Relationship)**
- **ERD (Entity-Relationship Diagrams)**
- **Sequence Diagrams**

### **Tools & Technologies**
- **Databases**: [PostgreSQL](https://github.com/pmasalev/examples/blob/main/POSTGRESQL.sql), SAP ERP, 1C: Enterprise, JSON, XML
- **APIs**: JSON API, Swagger, Postman
- **Warehouse Management**: WMS (Warehouse Management Systems)
- **Data Formats**: JSON, XML, YML
- **Database Administration**: Database Management, DWH

### **Methodologies**
- Agile
- Scrum

---

## Examples of Thematic Assignments 📑

Here are some examples of thematic assignments that demonstrate my skills and expertise:

1. **Software Requirements Specification (SRS)**
   - Developed detailed SRS documents, ensuring compliance with [**GOST**](https://github.com/pmasalev/examples/blob/main/GOST.md) and [**SRS**](https://github.com/pmasalev/MyMobile/blob/main/SRS%20MyMobile%20v.1.0.0.docx) standards.
   - Defined functional and non-functional requirements, user stories, use cases, and wireframes.
   - Collaborated with stakeholders to gather requirements and translate them into technical specifications.

2. **System Architecture Design**
   - Designed scalable architectures for web and mobile applications.
   - Integrated RESTful APIs for customer management, billing systems, and service options.
   - Created [ER diagrams](https://github.com/pmasalev/examples/blob/main/ER.md) and [database schemas](https://github.com/pmasalev/examples/blob/main/DWH.md) for structured data storage.

3. **Business Process Optimization**
   - Analyzed and optimized business processes to reduce costs and improve efficiency.
   - Automated repetitive tasks such as balance checks, tariff changes, and service option management.
   - Implemented process improvements based on [**BPMN**](https://github.com/pmasalev/examples/blob/main/BPMN.md) modeling.

4. **Technical Documentation**
   - Wrote comprehensive technical documentation for developers, testers, and end-users.
   - Used tools like [**Swagger**](https://github.com/pmasalev/examples/blob/main/API.md) and **Postman** for API testing and documentation.
   - Created sequence diagrams, class diagrams, and API descriptions.

5. **Data Modeling**
   - Designed entity-relationship (ER) diagrams for customer, tariff, and balance data structures.
   - Developed database schemas for storing user data, service options, and transaction history.
   - Ensured data integrity and compliance with security standards.

6. **Use Cases and User Stories**
   - Developed detailed [**use cases**](https://github.com/pmasalev/examples/blob/main/UC%20%26%20UCD.md) for key functionalities such as user authentication, balance checking, and tariff management.
   - Included alternative flows and exception handling to ensure robustness.
   - Used BPMN and UML diagrams to visualize workflows and interactions.

7. **Use Case Diagrams**
   - Created [**Use Case Diagrams**](https://github.com/pmasalev/examples/blob/main/UC%20%26%20UCD.md) to visually represent interactions between users and the system.
   - Example: A diagram showing how an "Authorized User" interacts with the system to perform actions like "View Balance," "Change Tariff," and "Manage Options."

---

## Contact Me 📬

Feel free to reach out if you have any questions or want to collaborate:  
📧 [Email](mailto:pmasalev@yandex.ru)  
🌐 [VK](https://vk.com/false_e)  

---

> "The best way to predict the future is to create it." – Peter Drucker  
> Let's build something amazing together! 🚀
