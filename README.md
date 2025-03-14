
# CerealDB api 

A project made as part of [Specialisternes](https://dk.specialisterne.com/) academy course during week 3.

This project is designed to manage a ceral product database, including storing paths to images associated with each product.




## Features


- Connect to a MySQL database
- Fetch cereal product data
- Fetch cereal product data according to filters
- Fetch image related to cereal ID
- Post new cereal products to the database
- Edit existing cereal products' information.
- Delete cereal products from the database.

## Installation

1. Clone the repository:
```bash
    git clone https://github.com/Drejer1/SPAC-uge3.git
    cd SPAC-uge3/PythonCerealAPI
```
2. Create a virtual environment and activate it:
```bash
    python -m venv venv 
    source venv/bin/activate  # On Windows 
    use `venv\Scripts\activate`
```
3. Install the required dependencies:
```bash
    pip install -r requirements.txt
```
4. Make sure a local MySQL server is running and containing a database named "cereal_database"
5. Run the query located inside the Miscellaneous folder
6. Run ParseAndInsert.py
7. Run FillDatabaseWithPathsToImages.py

## Executing
Simply run PythonCerealAPI.py. 

Inside Miscellaneous folder there is a postman collection which can be used to test the functionality
