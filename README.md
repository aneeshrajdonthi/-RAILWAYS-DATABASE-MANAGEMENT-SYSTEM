# -RAILWAYS-DATABASE-MANAGEMENT-SYSTEM

Project Overview :

*This project involves designing, normalizing, and implementing a relational database system to efficiently manage and retrieve information about the Indian Railways. The database supports details such as:
*Train schedules and types.
*Station information.
*Passenger ticket details.
*Employees, counters, and stalls at stations.
*Real-time data related to train operations.
*The system was developed using an ER-to-Relational model conversion, normalization, and SQL for implementation and testing on Oracle 19c.

Features :

*Database Design: Based on a robust ER model, capturing entities such as trains, stations, employees, passengers, and their relationships.
*Normalization: Ensures database efficiency by adhering to BCNF.
*SQL Implementation: Includes schema creation, test data insertion, and testing with SQL queries.
*Functionality: Efficiently handles information about tickets, delays, employee assignments, and more.

Technical Details :

Entity-Relationship Model
The ER model describes entities like:
Train: Details include train number, name, and running days.
Station: Information about station codes, names, platforms, and locations.
Passenger: Ticket details such as PNR, seat number, and passenger details.
Schedule: Planned and actual schedules of trains.

Relational Model :

Key tables include:
Train: Attributes: Train_number, Train_name, Running_days, etc.
Train_Details: Attributes: Train_type, Goods_count, AC_count, etc.
Station: Attributes: Station_code, Station_name, Platform_count, etc.
PNR: Attributes: PNR_number, Date, Train_number, etc.
Employee: Attributes: Emp_id, Name, Designation, etc.
Schedule: Attributes: Train_number, Station_code, Arr_time, Dep_time, etc.

Normalization :
 
All tables were normalized to BCNF.
Transitive dependencies were removed, ensuring all relations follow lossless decomposition and dependency preservation properties.

Implementation :

Platform: Oracle 19c.
Languages: SQL for schema creation and testing.
Testing: Included queries to verify:
Train schedules.
Passenger details.
Employee assignments.
Cost calculations for tickets.

Challenges Faced :

Initial difficulties in constructing the ER model due to unfamiliarity with concepts.
Confusions while handling foreign keys during ER-to-Relational conversion.
Sole responsibility for implementation due to a teammate’s unavailability during minor exams.

Future Scope :

Integration with real-time train data for dynamic updates.
Optimization of queries for faster retrieval.
Web-based interface for easier access to database features.

Instructions for Use :

Clone the repository.
Load the SQL schema and data on Oracle 19c.
Run provided SQL queries for testing.

Thank you for exploring the Railways Database Management System!
