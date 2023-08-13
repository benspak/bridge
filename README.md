# bridge

## Project Table of Contents

 * Environment Setup
 * Database Configuration
 * User Authentication and Registration
 * User Profiles
 * Dashboard and Following Functionality
 * Search Functionality
 * Contact Details Management
 * Rate Limiting
 * Account Deletion
 * Error Tracking with Sentry
 * Templates
 * Hosting on Heroku
 * Final Checklist and Review

### Environment Setup

#### Resources

* https://python.land/virtual-environments/virtualenv

#### Helpful Commands

```
python -m venv venv
venv\Scripts\Activate.ps1
```

### Database Configuration

#### Resources

* https://www.postgresql.org/download/windows/

* Open `SQL Shell (psql)`
* Create local DB. In shell `CREATE DATABASE bridge;`
* Configure .env in the root directory:

```
DB_NAME=bridge
DB_USER=postgres
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432

```

### User Authentication and Registration
