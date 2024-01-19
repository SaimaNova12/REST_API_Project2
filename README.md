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
![1p](https://github.com/SaimaNova12/REST_API_Project2/assets/76209488/135c5808-4b85-420b-adf9-9ed4197b9c58)
![2p](https://github.com/SaimaNova12/REST_API_Project2/assets/76209488/9a11da6a-4a6d-4071-af8c-4d65729af1e7)
![3p](https://github.com/SaimaNova12/REST_API_Project2/assets/76209488/98340c0e-9929-4a00-853b-348c4815d836)
![4p](https://github.com/SaimaNova12/REST_API_Project2/assets/76209488/6e6313e7-9c1f-4e06-8e8d-7c4bf5b2fda7)

