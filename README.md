# Ex02 Django ORM Web Application
## Date: 26.11.2025
## 25003567

## AIM
To develop a Django Application to store and retrieve data from a E-Commerce Website Database for Amazon or Flipkart using Object Relational Mapping(ORM).


## ENTITY RELATIONSHIP DIAGRAM



## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
models.py
```
from django.db import models
from django.db import models 
from django.contrib import admin
class amazon_DB (models.Model):
     Product_name=models.CharField(max_length=20)
     S_no=models.IntegerField (primary_key=True)
     Product_type=models.CharField(max_length=20)
     Price=models.CharField(max_length=20)
     Year=models.IntegerField()
class amazon_DBAdmin(admin.ModelAdmin)
     list_display=["Product_name","S_no","Product_type","Price","Year"]
```
admin.py
```
from django.contrib import admin
from .models import amazon_DB,amazon_DBAdmin
admin.site.register(amazon_DB,amazon_DBAdmin)
```



## OUTPUT
<img width="1016" height="817" alt="Screenshot 2025-11-27 211010" src="https://github.com/user-attachments/assets/4793a44b-047f-410f-9b69-54a27d770990" />

<img width="1409" height="712" alt="Screenshot 2025-11-27 210806" src="https://github.com/user-attachments/assets/48118451-dc81-4451-a5c1-0e437100327d" />



## RESULT
Thus the program for creating E-commerce website database using ORM hass been executed successfully
