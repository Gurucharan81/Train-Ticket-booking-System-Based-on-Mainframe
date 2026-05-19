# Railway Ticket Booking System

## Overview

This project is a mini Railway Ticket Booking System developed on Mainframe using COBOL, CICS, VSAM and JCL concepts. The application simulates a real-time train reservation workflow including train search, seat availability check, passenger booking and waiting list management.

## Features

* Train search based on source, destination and travel date
* Passenger detail entry and ticket booking
* Seat availability validation
* Automatic ticket confirmation
* Waiting list generation when seats are unavailable
* Dynamic seat count updation
* CICS BMS screen-based interaction

## Technologies Used

* COBOL
* CICS
* VSAM KSDS
* JCL
* BMS Maps

## Modules Implemented

### 1. Train Search Module

* Displays available trains
* Retrieves train details from VSAM files
* Shows seat availability information

### 2. Ticket Booking Module

* Accepts passenger details
* Validates seat availability
* Confirms booking if seats are available
* Generates waiting list entry if seats are full

### 3. Waiting List Management

* Maintains waiting list records
* Updates booking status dynamically
* Handles seat allocation workflow

### 4. Transaction Processing

* VSAM browse operations using STARTBR / READNEXT
* Real-time seat updation
* File rewrite operations for availability management

## VSAM Files Used

* Train Master File
* Passenger File
* Booking File
* Waiting List File

## Key Concepts Covered

* Pseudo-conversational CICS programming
* COMMAREA-based navigation
* VSAM KSDS file handling
* Browse processing using STARTBR / READNEXT
* CICS BMS map development
* Validation and booking workflow handling

