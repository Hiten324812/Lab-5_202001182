# Lab-5_202001182

## Tool - python Mypy

### file link-1- https://github.com/Hiten324812/DBMS-PROJECT/blob/main/cyclist/cyclist/views.py

# ERROR 

![image](https://user-images.githubusercontent.com/107188205/225570720-a7362095-b988-45d4-b534-2bab09a54653.png)


- ### other dependent module like cycilst.model, cyclist.forms not found in code so that displaying error.
- ### mypy has its own search path for imports and does not resolve imports exactly as Python does and it isn't able to find the django.shortcuts, django.db module.

## Tool - python Mypy

### file link-2- https://github.com/Hiten324812/DBMS-PROJECT/blob/main/cyclist/cyclist/urls.py

# ERROR 

![image](https://user-images.githubusercontent.com/107188205/225573988-5ab8d087-b494-4791-8184-673848e65fde.png)


- ### The systemerror parent module not loaded cannot perform relative import error occurs when a module tries to import a relative module, but the parent module has not been imported or loaded yet

