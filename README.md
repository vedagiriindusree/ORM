# Ex02 Django ORM Web Application
## Date: 12.04.2025

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).

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
```
from django.contrib import admin 
from expapp.models import Student admin.site.register(Student) 
from django.db import models

Create your models here.

class Student(models.Model): 
user=models.CharField(max_length=100)
password=models.CharField(max_length=100) 
email=models.EmailField()
phone=models.CharField(max_length=100)
profile=models.ImageField(upload_to='profile/') 
address=models.TextField()
```
## OUTPUT

![image](https://github.com/user-attachments/assets/f2406fa8-f514-4f7e-b30e-e5d59ac3b06b)


## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
