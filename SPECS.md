## SPECS 

- Framework
  - Express
- **Authentication**
  - JWT
  - Social Login (Github, Twitter)
- **Authorization**
  - User Roles: Admins, Commer Users
- **Users profile**
  - Saves the profile information for users + Image
  - Admins can edit all users
  - Common users can edit their own profile
- **API Support**
  - Dynamic Implementation ([pattern migrated](https://github.com/app-generator/devtool-django-dynamic-api) from `Django`)
- **DataTables Support**
  - Paginated data, search. export, server side pagination
  - Dynamic Implementation ([pattern migrated](https://github.com/app-generator/devtool-django-dynamic-datatb) from `Django`)
- **ORM**
  - To be discused - Here is a comparision:
    - https://romeerez.hashnode.dev/nodejs-orms-overview-and-comparison
  - `Sequelize`
  - `TypeORM`
- **Storage** - used by upload
  - Local
  - AWS
- Deployment
  - `Docker` 
- Middlewere 
  - [morgan](https://expressjs.com/en/resources/middleware/morgan.html) is a logging utility
  - [cors](http://expressjs.com/en/resources/middleware/cors.html) - utility for configuring cross-origin request security
- Background tasks 
  - Async execution (full management):
    - create, cancel, check status 
  
<br />

## MISC 

- Charts
  - the information can be consumed via the API
  - TBD if an extra aggreagation layer is need to process the data via tables or a LIVE proxy 
  
<br />

--- 
Rocket API Node/Express - Specs file 

  
