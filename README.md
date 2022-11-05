# CMPG-323-Overview---30586453

## The following repositories will be created for other projects:

#### Project number: 2
  Repository name: API Development 

#### Project number: 3
  Repository name: Patterns & Standards 

#### Project number: 4
  Repository name: Testing & RPA

#### Project number: 5
  Repository name: Reporting & Monitoring

#### Project number: 6
  Repository name: Exam(POE)
  
  
## Projects and Repositories
### ![image](https://user-images.githubusercontent.com/84228144/185400506-a197a3ac-f955-41ea-be2b-23b5c18a66cb.png)

I am going to create a repository for each project.

## Branching Strategy
The branching strategy that will be employed in each project is that I am gonna be working on the main branch on every project. If a bug arises, I will then create a development branch to fix it.

## .gitignore Usage
In each project, the .gitignore will be used to hide some sensitive files from the public, even though the repositories themselves will  be public.

## Security
Credentials and sensitive information will be stored in files that will be ignored from being published to the public.


## Charts
### Status Chart
![Screenshot (20)](https://user-images.githubusercontent.com/84228144/187913426-219950a7-b658-42dc-8f38-770b76b8d11f.png)

### Burndown Chart
![Screenshot (21)](https://user-images.githubusercontent.com/84228144/187913474-93e7753e-c987-419d-9c3e-da5e94b33990.png)

### Label Chart
![Screenshot (22)](https://user-images.githubusercontent.com/84228144/187913526-b11baaf9-e4c4-4297-8d69-63aa5af5e66f.png)

### Sprint Chart
![Screenshot (23)](https://user-images.githubusercontent.com/84228144/187913568-e54166b8-744b-4637-b3ab-6f2c34e478e7.png)


# Project 2

![image](https://user-images.githubusercontent.com/84228144/189093836-f1497d5e-fa67-467e-a191-c0aa78a92ead.png)

Project 2 is done and added to github.
This is a Web API project that works together with a database called ConnectedOffice. This datase is a SQL Server database that is hosted on Azure. The database has three tables, namely; Categories, Devices, and Zone.

This API is fundamentally an IoT Device Management System keeps track of the whereabouts of all IoT devices deployed by the organisation. Depending on the type of organisation, different categories of devices are used. Each IoT device is initially categorised and registered. Then, IoT devices are deployed throughout the organisation's buildings in predefined zones. Administrators can view all IoT devices, update their properties, add new devices and move them to other zones.


# Overview
In this day and age, there are millions of applications that have been created and are widely used. 
A developer’s ability to read and understand code is even more important than their ability to write 
code. As such, I was given a an existing ASP.NET Core MVC Application and I enhanced and improved it.

I enhanced and improved the application by applying architectural patterns to it, while also keeping 
to the SOLID principles as best as I could.

# Using the Application:
## The Home page 

![home page not logged in](https://user-images.githubusercontent.com/84228144/192527981-639eba0b-2ed7-411a-8173-338dc23e82cc.png)

When accessed, the landing page will look like this, and a new user will have to create an account.
The next step is to click on the Register button.

## Registering an account

![register page](https://user-images.githubusercontent.com/84228144/192528448-01728638-09c8-4857-bc40-dc6902cfef75.png)

The user will have to fill in all of the fields and then click the register button. After that they
will be redirected to the home page where the user now has to login.

## Logging in

![home page not logged in](https://user-images.githubusercontent.com/84228144/192527981-639eba0b-2ed7-411a-8173-338dc23e82cc.png)

The user must click on the Login button, and they will be redirected to the following page:

![login page](https://user-images.githubusercontent.com/84228144/192529348-477b9e1f-dcb3-4dd8-a33e-19cfaf752ce0.png)

The user now has to enter their login credentials and click on the Login button. Thereafter, they
will land on the following page:

![Homepage after logging in](https://user-images.githubusercontent.com/84228144/192529811-47193e72-f4f0-4a7d-aaa4-caf16b40738e.png)

## The set of instructions can be followed with either Categories, Zones, and Devices. Zone will be used
to explain how to work with the database tables

### Landing page after clicking on Zones button from the Home page:

![Zone landing page](https://user-images.githubusercontent.com/84228144/192530775-deba2a30-954a-40c8-a087-5ccb80d40b7d.png)

### Adding a new Zone:
The user must click on the plus symbol enclosed in circle beside the text "Zone" (+). Then
the following page will appear

![Create zone](https://user-images.githubusercontent.com/84228144/192531349-c1c2b083-a787-436e-bbdf-40f0d8979cfd.png)

The user can now add the Zone, and click on the Create button. They will be reedirected to the
landing page of Zones where they can now see the newly created zone.

### Editing a Zone:
The user must locate a specific zone that they want to edit and then click on the pencil icon
towards the end of the row. Thereafter they will be redirected to the following page:

![edit zone](https://user-images.githubusercontent.com/84228144/192532527-bdf67457-ac1e-46db-85af-efd242c36e32.png)

The user can now edit the Zone details by changing whatever is written in the fields that appear 
there. After that the user must click on the Save button, they will be reedirected to the
landing page of Zones where they can now see the newly created zone.

### Viewing the Zone Details:

The user must click on the eye icon that appears at the end of the row of the Zone of interest.
After that they will be redirected to the following page:

![zone details](https://user-images.githubusercontent.com/84228144/192533450-74ab9631-ea22-4f71-bd5f-5083376e9d19.png)

The user can either click on "Edit" or "Back to List" links after checking out the details of the
Zone of interest.

### Deleting a Zone:
The user must click on the Trash-can icon that appears at the end of the zone of interest.
They will then be redirected to the following page:

![delete zone](https://user-images.githubusercontent.com/84228144/192534007-27309454-b380-4a1f-bf4a-83ab61e619e9.png)

The user will have to click the Delete button in red. Thereafter they will be redirected to the 
Zones landing page.

![Zone landing page](https://user-images.githubusercontent.com/84228144/192534393-8b5d6ad4-9825-49b3-abc9-5b80326f8d3d.png)

# CMPG323--Project--4--30586453

## Background
Robotic Process Automation (RPA) refers to the use of technology to mimic human tasks in the 
same way that a person would execute a process. This usually refers to, what we would call, 
‘front-end’ or UI (User Interface) automation. RPA is often used to automate time-consuming and 
highly repetitive tasks to allow people the availed capacity to work on more intuitive tasks.

![rpa](https://user-images.githubusercontent.com/84228144/198193168-e28da3d3-fb61-48e3-b8ce-284cccf8729f.svg)

## About the Project
This project automates the populating, reading, updating, and reading of data in the 
https://connectedoffice-devicemanagement.azurewebsites.net/ web application. 

## How Stakeholders should use the solution
Since this application was created using UIPath community studio in conjuction with the Firefox
browser, the stakeholder should have these two applications on their machine. The automation solution
comes with the login credentials (username: L.wizard.h@gmail.com, password: Lehlohonolo@21), and the user
should not worry about needing to insert the login credentials because the automation solution has them
already. All that the stakeholder needs to do is to run the automation inside of UIPath studio community.
The automation solution will run, taking input from the excel and populating the database tables with it.
The tables will then be updated and deleted automatically.


# Connected Office Device Monitoring
## Upon opening the project, the user can click on the first page titled
"High-Level Metrics". The following should appear:

![1](https://user-images.githubusercontent.com/84228144/200129813-de948b52-d29e-40cb-b8a7-3f8d5799eb35.png)

### High-Level Metrics
The user can see the number of Devices, Zones, and Categories in the report.

### Device Monitoring

![2](https://user-images.githubusercontent.com/84228144/200130115-5af617f7-fe20-4f84-9652-0d0c4ed73b25.png)

The user can see reports on devices.

### Device Registration

![3](https://user-images.githubusercontent.com/84228144/200130276-7d7d3fed-aa08-44ac-97d1-754e79dfaff2.png)

The user must click on "Device Registration" page to see the report above.

### Filtering

![4](https://user-images.githubusercontent.com/84228144/200130405-094e5bde-10bf-4e81-9319-940c676fd1a1.png)

The user must click on the "Filtering" page in order to see the above view. They can select to filter the 
data according to the filters on this page. After clicking the filter, they can navigate to the other pages
where the data will now be filtered.
