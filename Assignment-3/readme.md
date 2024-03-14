Assignment-3:
IDEA: Creating a RESTful API using Express.js and integrate it with MongoDB to perform CRUD operations on a database.
Download the provided files and open the files in VSCODE
Run 'npm install' command in the terminal
In the terminal of VSCODE or in cmd type 'mongod'(with the file location)
![Screenshot 2024-03-14 185654](https://github.com/Sravani-PL/20JG1A4238-Pamarthi_Lakshmi_Sravani/assets/96241371/7c84adb6-44ff-4e73-8791-c295bd68b321)
After initializing mongod now run the command 'nodemon run start'
![Screenshot 2024-03-14 185646](https://github.com/Sravani-PL/20JG1A4238-Pamarthi_Lakshmi_Sravani/assets/96241371/48ad9d54-d9e2-446f-857c-69534f5429a5)

Now open Postman and entr the url as : http://localhost:9000/books

 Click on send and select HTTP request method as 'GET'
 This helps to retrieve the available data
 ![Screenshot 2024-03-14 184536](https://github.com/Sravani-PL/20JG1A4238-Pamarthi_Lakshmi_Sravani/assets/96241371/8c3d8ecf-97d6-42d4-a6bd-36854c2c1391)

 POST method: helps to add the data to books
 To add the data select 'Body' and use 'JSON' format data
 UPDATE method: helps to modify the data(PATCH)
 ![Screenshot 2024-03-14 185415](https://github.com/Sravani-PL/20JG1A4238-Pamarthi_Lakshmi_Sravani/assets/96241371/07ccc526-6553-4c92-818e-48e6cbf0f80b)

 DELETE method: deletes the data.
 Provide the id of the book to delete a particular data.
 ![Screenshot 2024-03-14 185257](https://github.com/Sravani-PL/20JG1A4238-Pamarthi_Lakshmi_Sravani/assets/96241371/f35f0597-dfca-4333-bad4-3c1ebdabcaf5)

 
