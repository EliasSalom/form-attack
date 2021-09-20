# form-attack
this a test script to attack a every form in every website

## Installation
1. clone this repository 
2. make sure you have ***(Java 11)*** installed on your machine,
	1.  you can to check that by typing ```java -version``` ***in command line (CMD)***
3. if not install it by this links
    1. on abountu ```sudo apt-get install openjdk-11-jdk``` check more [here](https://stackoverflow.com/questions/52504825/how-to-install-jdk-11-under-ubuntu)
    2. on windows on this [website](https://www.techspot.com/downloads/5553-java-jdk.html)
## Using 
1. open command line
2. navigate to script folder 
3. run it with ```java -jar version1.jar```
	> if you won't provide any argument there, should appear HELP message
4. to run it with arguments just add
```sh
java -jar form-searsh.jar -links website1.com
```
> if you want to add multiple website just add a comma between the websites
```sh
java -jar form-searsh.jar -links website1.com,website2.com
```
## Version
|  Version   |  Description                                  |
| ---------- | --------------------------------------------- |
| Version 1  | Basic script to submit form with random data  |
| Version 2  | Fix issues: submit to offline website         |
| Version 3  | Add new future: write the data to a txt file  |
