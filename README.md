# Educational Management System – Class Diagram

## 📘 Overview

This repository contains the **Class Diagram** for an Educational Management System, visualized in the `class Diagram.drawio.svg` file. The diagram illustrates the structure of the system, showcasing the main classes and their relationships.

## 🖼️ Diagram

![Class Diagram](class%20Diagram.drawio.svg)

## 🎯 Key Classes

* **Student**

  * Attributes: `studentID`, `name`, `email`, `enrollmentDate`
  * Methods: `enrollInCourse()`, `dropCourse()`, `viewGrades()`

* **Course**

  * Attributes: `courseID`, `courseName`, `credits`
  * Methods: `addStudent()`, `removeStudent()`, `assignInstructor()`

* **Instructor**

  * Attributes: `instructorID`, `name`, `email`
  * Methods: `assignGrade()`, `createAssignment()`

* **Administrator**

  * Attributes: `adminID`, `name`, `email`
  * Methods: `addCourse()`, `assignInstructor()`, `manageUsers()`

## 📂 Files

* `class Diagram.drawio.svg`: Visual representation of the class diagram.
