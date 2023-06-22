# Documentation de l‘api Iam 2023

* Installez Tomcat
* Déplacez le fichier *.war* dans le répertoire **webapps** ("C:\Program Files\Apache Software Foundation\Tomcat 10.1\webapps")
* Lancez le serveur Tomcat en double-cliquant sur *startup.bat* dans le dossier **bin** ("C:\Program Files\Apache Software Foundation\Tomcat 10.1\bin")

Tables
**Regions**
* Pour accéder à la liste des régions taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/regions/listRegions  
* Pour créer une région r taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/regions/createRegions
      
**Countries**
* Pour accéder à la liste des pays taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/countries/listCountries
* Pour créer un pays taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/countries/createCountries

**Locations**
* Pour accéder à la liste des locations taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/locations/listLocations
* Pour créer une location taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/locations/createLocation

**Departments**
* Pour accéder à la liste des départements taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/departments/listDepartments
* Pour créer une departement taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/departments/createDepartment
      
**Jobs**
* Pour accéder à la liste des jobs taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/jobs/listJobs
* Pour créer un job taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/jobs/createJobsEmployees

**Employees**
* Pour accéder à la liste des employés taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/employees/listEmployee
* Pour créer un employé taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/employees/createemployee
* Pour modifier un employé taper url suivant:
    * http://localhost:8080/apitomcat/api/iam/master1/employees/{id}

***Nb : apitomca est le nom du dossier  genere sur tomcat . Donc vous devez le modifier en fonction du nom de votre dossier.***
