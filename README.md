# Leave Management System RESTful API

The Leave Management System (LMS) RESTful API is a backend solution that enables the digitalization, automation, and cloud-based management of leave requests within an organization. This API provides a comprehensive set of CRUD (Create, Retrieve, Update, Delete) operations for managing employees and leave requests.

## Description
The LMS RESTful API allows access to two roles: EMPLOYEE and MANAGER. The API manages two entities: employees and leave requests. The functionalities available for each role are as follows:


## MANAGER Role
- Create Employee: Create new employee profiles with necessary details like name, contact information, and role.
- Retrieve Employee Information: Retrieve employee information, including personal details, leave balance, and leave history.
- Update Employee Information: Update employee profiles, enabling changes to personal information or job-related details.
- Delete Employee: Remove employee profiles from the system.
- Create Leave: Submit leave requests on behalf of employees, specifying the type of leave, start date, end date, and any additional notes.
- Retrieve Leave Information: Access information about leave requests, including the status (pending, approved, rejected), dates, and relevant employee details.
- Update Leave Information: Modify leave request information, allowing changes to the leave type, dates, or additional notes.
- Delete Leave: Delete leave requests from the system.

## EMPLOYEE Role
- Retrieve Employee Information: Access own employee information, including personal details, leave balance, and leave history.
- Create Leave: Submit leave requests, specifying the type of leave, start date, end date, and any additional notes.
- Retrieve Leave Information: Access information about own leave requests, including the status (pending, approved, rejected), dates, and any relevant updates.
- Update Leave Information: Modify own leave request information, allowing changes to the leave type, dates, or additional notes.

## Getting Started
1. Install the necessary dependencies.
2. Set up the database and configure the connection.
3. Start the server.
4. Use appropriate HTTP methods and endpoints to interact with the API.

## Contributing

Contributions to the Leave Management System RESTful API are welcome! If you find any bugs or have suggestions for enhancements, please submit an issue or a pull request.

## License

[MIT](https://choosealicense.com/licenses/mit/)
