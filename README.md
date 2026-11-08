[![Python Version](https://img.shields.io/badge/python-3.15.2-blue)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
# Bounced list processor
This project intent is to collect bounced emails. <br>
It is based on reading .eml file and fetching email address which did not receive sent e-mail.

## Purpose
This project collects bounced email addresses by:
- Reading `.eml` files
- Extracting email addresses from "Final-Recipient" headers
- Excluding specified no-reply addresses
- Generating reports of bounced emails

## Software requirements
Requirements for project to run with success are:
- have installed [Python](https://www.python.org/downloads/). It was tested and implemented on version `3.15.2`
  - useful guide on how to setup Python in Windows OS: https://realpython.com/python-coding-setup-windows 
- have prepared `.eml` files

## First run of main.py
Open `main.py` and check `TODO` comments
  -  update a directory path
  -  update excluded email address list
