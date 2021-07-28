# :zap: Java Section15 Challenge1
 
* Java code to display operations on bank account
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/java-section15-challenge1?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/java-section15-challenge1?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/java-section15-challenge1?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/java-section15-challenge1?style=plastic)

## :page_facing_up: Table of contents

* [:zap: Java Section15 Challenge1](#zap-java-section15-challenge1)
  * [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal_strength: Technologies](#signal_strength-technologies)
  * [:floppy_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status & To-Do List](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* Code from Java Programming Masterclass Section 15-288 to 15-292 - see [:clap: Inspiration](#clap-inspiration) below
* [Lock framework](https://www.geeksforgeeks.org/lock-framework-vs-thread-synchronization-in-java/) used instead of synchronized block for increased concurrency and overall performance.

## :camera: Screenshots

N/A

## :signal_strength: Technologies

* [Java v11](https://www.java.com/en/)
* [synchronized method](https://docs.oracle.com/javase/tutorial/essential/concurrency/syncmeth.html) only one synchronised method can operate on an object block at a time. This makes it thread-safe
* [Interface Lock](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/locks/Lock.html) a tool for controlling access to a shared resource by multiple threads.
* [Enum Timeunit](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/TimeUnit.html)

## :floppy_disk: Setup

* Open folder in an IDE such as IntelliJ. Run  from `Main.java`

## :computer: Code Examples

* Interface lock code format

````java
Lock l = ...;
    l.lock();
    try {
    // access the resource protected by this lock
    } finally {
     l.unlock();
    }
````

## :cool: Features

* N/A

## :clipboard: Status & To-Do List

* Status: Working
* To-Do: Complete

## :clap: Inspiration

* [Udemy: Java Programming Masterclass for Software Developers](https://www.udemy.com/course/java-the-complete-java-developer-course/learn/lecture/3561816#overview)

## :file_folder: License

* N/A

## :envelope: Contact

* Repo created by [ABateman](https://www.andrewbateman.org), email: gomezbateman@yahoo.com
