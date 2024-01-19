# REST_API_Project_Two
#### How to Run this project
  - Clone this project
  - Open with Postman/Command Shell
  - Run this Command

To deploy this project run

```bash
newman run Project_two.postman_collection.json -e Project_two.postman_environment.json
```
To generate report run this command
```bash
newman run Project_two.postman_collection.json -e Project_two.postman_environment.json -r cli,htmlextra
```
#### Technology Used
 - Postman
 - Newman 
 #### Prerequisite:
 - Jdk
 - Node Js
 - Newman 
 - Html report libary
 #### Newman and Report Installation Process:
 - Newman Install Command:
 ```bash
npm install -g newman-reporter-htmlextra
 ```
 - Newman Html Report Install Command:
  ```bash
npm install -g newman-reporter-htmlextra
   ```
#### API Documentation
```bash
https://documenter.getpostman.com/view/32179388/2s9YsT5Tdc
   ```
### Test Case List
#### Create a Booking 
- Create Data Sets Using the Dynamic Random Variables.
#### Verify created booking details through method get
#### validate the following field values::
- First name
- Lastname
- Total price
- Depositpaid
- Check-in
- Check-out 
- Additional needs
#### Get the created booking
- Validate if created information is correct
#### Create a Token for Update & Delete
- username & password to get a token
#### Update the values
- Use token in the header section to update the values
#### Automate the whole process by setting the Variables in the environment and use them in the body. To random generate huge number of data use pre-request script and postman predifined Variables. 
