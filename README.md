# relational-model-hotel-example-test

<img width="1240" alt="Screen Shot 2024-11-18 at 16 26 09" src="https://github.com/user-attachments/assets/03fefe0e-3c33-41d7-9493-c9e29dc3e8b9">



# Relational Model

## Hotel
- **Hotel_Id** 
- Hotel_name
- #Type_id

## Type
- **Type_Id** 
- Type_Name

## Room
- **Room_Id** 
- Floor
- #Hotel_Id 
- #Categorie_Id

## Category
- **Category_Id** 
- Category_Name
- Price
- Beds_numbers

## Employee
- **Employee_Id** 
- Employee_Name
- Employee_Speciality
- #Hotel_Id
- #Director_id
