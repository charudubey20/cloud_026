# Executing CPP file using Linux Command Line
* Check whether you have g++ tool in your linux system or not by using
g++ --version
If not then enter this command- **sudo yum -y install gcc-c++**
![1](https://user-images.githubusercontent.com/61387192/80870810-7609fa00-8cc6-11ea-8cb3-9bb226bfd6b3.PNG)

* To check whether g++ tool installed succesfully use this command- **g++ --version**
![2](https://user-images.githubusercontent.com/61387192/80870811-77d3bd80-8cc6-11ea-8364-28501ac331fa.PNG)

## CREATE DIRECTORY
* To create directory use **mkdir directory_name**
Here directory name is **_sum_**
![3](https://user-images.githubusercontent.com/61387192/80870814-799d8100-8cc6-11ea-897c-f91b98a098c8.PNG)

* To check whether directory is created or not, enter **ls**,it will list all files and directory of current working directory

* Now change current path to **sum** by using following command
cd sum

## COMPILING CPP CODE
Create cpp file using vi tool by using **vi add.cpp**
![4](https://user-images.githubusercontent.com/61387192/80870825-8621d980-8cc6-11ea-86c3-028cd2e93355.PNG)

* Enter **_i_** for inserting
![5](https://user-images.githubusercontent.com/61387192/80870826-87530680-8cc6-11ea-87ff-3d6b7bbf1a4c.PNG)

* Now enter your code

* Once done press **esc** key and enter **:wq** to save your code into .cpp file and exit from current file
![6](https://user-images.githubusercontent.com/61387192/80870829-8a4df700-8cc6-11ea-890c-7a965591f279.PNG)

* Check whether .cpp file created successfully or not, so enter **ls**
* Now compile your file using g++ tool 
  To compile enter **g++ add.cpp -o sum**
  ![7](https://user-images.githubusercontent.com/61387192/80870835-920d9b80-8cc6-11ea-84a9-e2f4b3d4009f.PNG)
  
* Now Execute your output file using ./add
![8](https://user-images.githubusercontent.com/61387192/80870839-95088c00-8cc6-11ea-8fd2-e794469ef7a0.PNG)

