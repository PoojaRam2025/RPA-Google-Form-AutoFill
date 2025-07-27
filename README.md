# 🤖 RPA-Based Google Form Auto-Fill Project using UiPath Studio

## 📌 Project Overview

This project automates the process of filling out a *Google Form* using *UiPath Studio*, a leading Robotic Process Automation (RPA) tool. The automation reads user input data from an Excel sheet named forminputdata.xlsx and automatically fills out the form named *Google Form* with the following fields:

- Name  
- Department  
- Year  
- Mail  
- Phone Number  

Upon successful submission, the Google Form displays a confirmation message: *"Form filled successfully."*  
The workflow also simulates clicking the *“Create Account”* button as part of the automated form submission.

---

## 🎯 Objective

The goal of this project is to gain *hands-on experience* with UiPath Studio and RPA automation by applying theoretical concepts from the modules I have completed.

---

## 📘 What is UiPath Studio?

*UiPath Studio* is a powerful automation design tool that enables users to create software robots (bots) to automate repetitive and manual tasks. It provides a *drag-and-drop interface* for building automation workflows without writing extensive code, making it accessible to both technical and non-technical users.

---

## 💡 What is RPA?

*Robotic Process Automation (RPA)* is a technology that uses software bots to automate structured, rule-based digital tasks across various applications. It helps save time, reduce errors, and boost productivity in both small and large organizations.

---

## 🧰 UiPath Studio Tools Used & Their Purpose

| Tool / Activity             | Purpose                                                                 |
|----------------------------|-------------------------------------------------------------------------|
| *Excel Application Scope*| To read the Excel file forminputdata.xlsx containing form input data. |
| *Read Range*             | To extract data from the Excel sheet into a DataTable.                  |
| *For Each Row*           | To loop through each row of Excel data and automate form filling.       |
| *Open Browser*           | To launch the Google Form in the default browser.                       |
| *Type Into*              | To fill each field (Name, Mail, etc.) in the Google Form using data.    |
| *Click*                  | To perform the "Create Account" button action in the form.              |
| *Delay*                  | To wait for form submission confirmation.                               |
| *Log Message*            | To track progress and display status during automation.                 |
| *Close Tab*              | To close the browser once the automation is completed.                  |

---

## 📂 Input Files

- forminputdata.xlsx: Excel file with the columns: *Name, **Department, **Year, **Mail, **Phone Number*
- googleform.html: The locally saved Google Form file used for automation (opens in Microsoft Edge)
- RPA Google Form Automate Fill.mp4: Demonstration video showing the full automation in action

---

## 📈 Modules Completed (from UiPath Academy)

1. *Automation Explorer Training*  
2. *Automation Starter*  
3. *Agentic Prompt Engineering*

These modules gave me a strong foundation in RPA concepts and practical exposure using UiPath Studio.

---

## 🔧 Future Enhancements

- I will continue to explore more advanced modules in UiPath  
- I will create and share *more RPA-based projects* to strengthen my automation skills

---

## 🔗 Connect with Me

- [LinkedIn – Pooja Ramachandran](https://www.linkedin.com/in/pooja-ramachandran-09a400324?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

---

✅ Thank you for visiting this project! Feel free to give feedback or suggestions.
