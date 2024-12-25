# Spatial Database - TD-1

This repository contains the practical steps for *Installing and Setting Up a Spatial Database* using PostgreSQL and PostGIS. These instructions guide users through the process of downloading, installing, and configuring PostgreSQL along with its spatial extension PostGIS, and creating a spatial database.

## Overview

The tutorial is divided into the following sections:

1. *Installing PostgreSQL*  
   - Download and install PostgreSQL suitable for your operating system.
   - Set a password for the postgres user during installation.

2. *Installing PostGIS*  
   - Use Stack Builder to download and install PostGIS.
   - Ensure the correct version of PostgreSQL is selected for compatibility.

3. *Creating a Spatial Database*  
   - Use PgAdmin 4 to create a new PostgreSQL database.
   - Add the PostGIS extension to the database by executing the appropriate SQL command.

## Installation Steps

### 1. Install PostgreSQL
- Visit [PostgreSQL Downloads](https://www.postgresql.org/download/).
- Follow the installation guide for your platform (Windows, macOS, Linux).
- During installation, set a password for the postgres user.

### 2. Install PostGIS
- Ensure the "Stack Builder" option is selected during PostgreSQL installation.
- Use Stack Builder to download and install the PostGIS extension.
- Follow the wizard to complete the installation.

### 3. Create a Spatial Database
#### Using PgAdmin 4:
1. Launch PgAdmin 4 and log in using the postgres password.
2. Navigate to Servers > PostgreSQL > Create > Database.
3. Name your database (e.g., spatial-db-1) and save.

