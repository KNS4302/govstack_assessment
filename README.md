# GovStack MoA Assessment - Joget Cloud Deployment

## Overview

This document provides instructions for instructors to review and evaluate the GovStack MoA Assessment, which has been deployed on Joget Cloud.

This assessment implements the following components:

* **MyGovService Portal:** Built with Joget and integrated with Keycloak for authentication and SSO.
* **MoA Frontend:** A web application for farmers and survey teams to submit registration data.
* **MoA Backend:** Implements the Registration BB API for application review and approval.
* **Farmlands Registry:** Implements the Digital Registry BB API for storing farmland registry data.

## Accessing the Application

1.  **URL:** hosted instance can be found [here](https://fundmo.on.joget.cloud/jw/web/userview/appcenter/home/_/home)
2.  **Login Credentials:**
    * **Administrator (for overall portal access):**
        * Username: admin
        * Password: Khetha/Fundmo_2025
    * **Case Officer (for MoA Backend review):**
        * Username: cat
        * Password: Fundmo_password1
    * **Farmer (for MoA Frontend submission):**
        * Username: cat
        * Password: Fundmo_password1

## Navigation and Testing

### 1. MyGovService Portal

1.  Log in using the Administrator credentials.
2.  Navigate to the "MyGovService_portal" application.
3.  test out functionality for backend and frontend respectively from there

`NB: the application will provide links to the Submit the application and review them respectively`

### 2. MoA Backend (Case Officer Review)

1.  Log in as a Case Officer.
2.  Navigate to the "MoA Farmland Registration" application.
3.  Locate the "Application Review" section.
4.  Review the submitted applications.
5.  Approve or reject applications as appropriate.
6.  Verify that approved applications are sent to the Farmlands Registry (you can verify this later from the Farmlands Registry).
