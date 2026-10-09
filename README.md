# Hospital Management System (C)

A console hospital management system in C, built as a university project during the pandemic. It covers five departments and saves records to text files.

## Features

- Login screen before the main menu
- Patient's Entry: add, view, search, edit and delete patient records
- Doctor's Records: add, view and search doctors
- Pharmaceutical department
- Employee's Records: add, view and search employees
- Parking Management: entry fees for cycles (Rs 10), bikes (Rs 30), rickshaws (Rs 50) and cars (Rs 100), plus status and deleting data
- Records stored in text files (`patient.txt`, doctor and employee records)

> **Note:** the demo login details are in `Documentation.txt`. They're hard-coded into the program and aren't real accounts.

## Credits

Built with a classmate (student ID SP20-BSE-106).

## Tech stack

C (Code::Blocks project; uses `windows.h` and `conio.h`, so Windows only)

## Getting started

```bash
git clone https://github.com/Matiz009/hospital-management-system-c.git
cd hospital-management-system-c
gcc -Ijunk main.c -o hospital && hospital.exe   # patient.h lives in junk/
```

## Project structure

```
main.c             Main program (all departments)
patient.h          Patient record header
patient.txt        Patient data file
Documentation.txt  Login details for the demo
junk/              patient.h, an older version and Code::Blocks project files
bin/, obj/         Build outputs
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
