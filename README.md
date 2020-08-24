# Installation
## 1. virtualenv 
Simply create virtual environment for your own project, where projectname is the name of your project:

  ```
  $ mkvirtualenv --clear projectname
  ```

## 2. Download
Now, you need the KNN-Based-Attendance-System-for-Employees project files in your workspace:
```
$ cd /path/to/your/workspace
$ git clone git://https://github.com/alsulke/KNN-Based-Attendance-System-for-Employees.git projectname && cd projectname
```
## 3. Requirements
Right there, you will find the requirements.txt file that has all the great debugging tools, django helpers and some other cool stuff. To install them, simply type:
```
$ pip install -r requirements.txt
```

## Ready? Go!
```
./manage.py runserver
```


# System Architecture
![alt text](https://github.com/alsulke/KNN-Based-Attendance-System-for-Employees/blob/master/Image/arc.png)
