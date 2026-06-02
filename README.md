# Payroll Calculator — Lick2theStickLollipops Company
## About The Project

A multi-form Windows Forms application built in VB.NET that calculates weekly payroll for both salaried and hourly employees.  It assists a payroll clerk in processing weekly payroll for employees living 
in Ohio, Indiana, and Kentucky.

## Features

- Supports both Salaried and Hourly employees
- Calculates Gross Pay with overtime support (time and a half over 40 hours)
- Calculates FICA (Social Security + Medicare)
- Calculates State Tax for Ohio, Indiana, and Kentucky
- Calculates Federal Tax based on tax brackets
- Calculates Net Pay
- Tracks Daily Totals of Gross Pay and Net Pay across all employees
- Full input validation on all fields
- Menu bar on every form that mirrors all buttons

## Design Documentation

The following design documents are included in this repository:

design.docx: Full design document including inputs, outputs, pseudocode, variables, and test cases |
structure_chart: Structure chart for the Salaried Employee and hourly employee form

## Project Structure

frmMain.vb (Main form)- opens salaried or hourly form, shows daily totals 
frmSalariedEmployee.vb (Salaried employee form) - enters yearly salary 
frmHourlyEmployee.vb (Hourly employee form) - enters hours worked and wage 
modStandard.vb (Standard module) - shared functions used by both forms 

## Standard Module — modStandard

The standard module contains all shared calculations used by both 
the salaried and hourly forms:

## Forms and purpose

Main Form: Choose salaried or hourly employee, view daily totals 
Salaried Form: Enter yearly salary and calculate payroll 
Hourly Form: Enter hours worked and wage, calculate payroll 

## Built With

- Visual Basic .NET (VB.NET)
- Visual Studio
