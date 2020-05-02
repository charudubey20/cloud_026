# Executing CPP file using Linux Command Line
* Check whether you have g++ tool in your linux system or not by using
g++ --version
If not then enter this command- **sudo yum -y install gcc-c++**
![](image/1.png)

* To check whether g++ tool installed succesfully use this command- **g++ --version**
![](image/2.png)

## CREATE DIRECTORY
* To create directory use **mkdir directory_name**
Here directory name is **_sum_**
![](image/3.png)

* To check whether directory is created or not, enter **ls**,it will list all files and directory of current working directory

* Now change current path to **sum** by using following command
cd sum

## COMPILING CPP CODE
Create cpp file using vi tool by using **vi add.cpp**
![](image/4.png)

* Enter **_i_** for inserting
![](image/5.png)

* Now enter your code

* Once done press **esc** key and enter **:wq** to save your code into .cpp file and exit from current file
![](image/6.png)

* Check whether .cpp file created successfully or not, so enter **ls**
* Now compile your file using g++ tool 
  To compile enter **g++ add.cpp -o sum**
  ![](image/7.png)
  
* Now Execute your output file using ./add
![](image/8.png)

