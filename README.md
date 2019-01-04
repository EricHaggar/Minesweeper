# MineSweeper

MineSweeper is an assignment completed in the Introduction to Computing II (ITI 1521/1121) at the University of Ottawa. The purpose of this assignment was to familiarize ourselves with the **Model-View-Controller (MVC)** architectural pattern and **Stacks** while creating the famous [Minesweeper](https://en.wikipedia.org/wiki/Minesweeper_(video_game)) game.

The following images show the GUI created

<p align="center">
    <img src="screenshots/flags.JPG" width="500" /> 
    <img src="screenshots/gameover.JPG" width="500" />
</p>



## Getting Started 

Clone the repository with:

```
git clone https://github.com/EricHaggar/MineSweeper.git
```

Change your directory to the project

```
cd MineSweeper
```

### Prerequisites

Make sure you have the Java SE Development Kit 8 or higher. If not install it from:

    https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html


## Running the tests

Open a terminal within the directory and compile the all java files using:

```
javac *.java
```
Run the test 

```
java MineSweeper
```

## Built With

* [java.awt](https://docs.oracle.com/javase/7/docs/api/java/awt/package-summary.html)
* [javax.swing](https://docs.oracle.com/javase/7/docs/api/javax/swing/package-summary.html)

## More Information

For more information on the assignment requirements, please see 

* [Assignment Handout](https://github.com/EricHaggar/MineSweeper/blob/master/MineSweeper.pdf)

Note: to generate the Java Documentation, enter the following on the command line:

```
 javadoc -d doc .java -private
```