# Employee Management System

## Overview

The Employee Management System is a RESTful API designed to manage employee records. It supports CRUD (Create, Read, Update, Delete) operations. This documentation provides details on the available endpoints, request formats, and responses.

## Technology Stack

- **Backend:** Java with Spring Boot
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript

## API Endpoints

### Base URL
http://localhost:8080/api/employees


### Endpoints

#### 1. Create Employee

- **URL:** `/api/employees`
- **Method:** `POST`
- **Description:** Adds a new employee to the system.

**Request Body:**

```json
{
    "name": "John Doe",
    "position": "Developer",
    "salary": 50000
}

