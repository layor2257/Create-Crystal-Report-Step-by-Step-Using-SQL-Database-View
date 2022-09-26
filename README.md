# Create-Crystal-Report-Step-by-Step-Using-SQL-Database-View
This is step-by-step instructions for creating a Crystal Reports report using SQL database

## Step 1
Create a table in the database. Create an Employee table in the database.
### Command

![image](https://user-images.githubusercontent.com/49678841/192285778-24f84553-f39e-4ad9-93d4-3da6cded0724.png)

Now insert employee data into the Employee Table.

### Command
![image](https://user-images.githubusercontent.com/49678841/192286018-26d5c114-2092-4547-bdcb-5dc1774943f5.png)

Now Employee data has been inserted into the table.

Let's see it with a SQL Select Command Query in the SQL Database.

### Command
![image](https://user-images.githubusercontent.com/49678841/192286098-64ec4dfd-610e-4a30-968e-cd4636ec68db.png)


## Step 2

Create a VIEW in your database to display employee data information.

### Command
![image](https://user-images.githubusercontent.com/49678841/192286277-605a6c06-b3bb-454b-bbe9-15af170e782c.png)

Now, your Employee database view has been created.

## Step 3

Go to Visual Studio.

## Step 4

Go to the Solution Explorer and right-click on your project name and seelct Add -> New Item.  

![image](https://user-images.githubusercontent.com/49678841/192286396-6e94d5fe-a907-4c39-98ae-9197f98a29a9.png)

## Step 5

Add New Item-> Crystal Report.

![image](https://user-images.githubusercontent.com/49678841/192286484-038999b3-0951-45b4-9103-c86f6dec150a.png)

## Step 6

Click the Ok Button.

![image](https://user-images.githubusercontent.com/49678841/192286578-b8cd6d39-6382-4d08-bb2e-b8978816cd70.png)

## Step 7

Choose the data source as in the following:

![image](https://user-images.githubusercontent.com/49678841/192286809-11f74872-5889-4d54-a7c6-568602e74660.png)

Click the Next Button.

## Step 8

Select the data with OLEDB (ADO) as in the following:

![image](https://user-images.githubusercontent.com/49678841/192286906-f53cfce0-7f7e-44e0-b5aa-cae348128ac7.png)

Click the Next button to open a new dialog.

![image](https://user-images.githubusercontent.com/49678841/192286959-ab7cad87-ffa1-48c8-91ff-09546f7a5140.png)

Click the Finish button and open a new dialog box. In this, select your new view.

## Step 9

Select your view Employee view.

![image](https://user-images.githubusercontent.com/49678841/192287600-d897f48e-1d31-4126-8b29-e0c4ca0a6a3d.png)

## Step 10

Select the fields to display in the report area as in the following:

![image](https://user-images.githubusercontent.com/49678841/192287704-6c24f569-ce0f-4666-bf05-3460bb3dc50e.png)

And click the Finish button.

## Step 11

Select the report format as in the following:

![image](https://user-images.githubusercontent.com/49678841/192287878-b4f428cb-ae60-4a56-afa8-14e9176483e2.png)

Click the Finish Button after selecting the format of the report.

## Step 12

Now finally display your report in this format.

![image](https://user-images.githubusercontent.com/49678841/192287953-0886aa69-1d9b-48d1-9ca6-936c11cd15ba.png)

## Step 13

Now add a new .aspx page to display the report as in the following:

![image](https://user-images.githubusercontent.com/49678841/192288041-f8c5df46-5c40-42ea-8d38-470e7fce9b7b.png)

And provide the name EmployeeDataInfo.aspx.

## Step 14

Now add a Crystal Report Viewer to EmployeeDataInfo.aspx as shown in the following screeshot:

![image](https://user-images.githubusercontent.com/49678841/192288129-73aa16a6-27d1-4c90-8e25-9216c53d637f.png)

## Step 15

Go to the aspx page code side as shown below:

![image](https://user-images.githubusercontent.com/49678841/192288200-1cd0a28d-195f-4e52-ab7f-340ac57a85d9.png)

## Step 16

Write the report code in the .aspx.cs page as follows:

![image](https://user-images.githubusercontent.com/49678841/192288334-5f2cacf3-6a3d-408e-86f6-5b044db72430.png)

![image](https://user-images.githubusercontent.com/49678841/192288378-dc07d8b5-d35f-4d23-9bcf-8ab1b7c8d86e.png)

## Step 17

Finally run your report and display the Employee Information.

![image](https://user-images.githubusercontent.com/49678841/192288457-98f8de14-7285-4a44-b6ba-410085d68490.png)







