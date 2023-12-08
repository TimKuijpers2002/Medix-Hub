<div align="center">
  <h3 align="center">Medix-Hub Documentation</h3>
    
  <a>
    <img src="https://github.com/TimKuijpers2002/Medix-Hub/blob/master/Medix-logo.jpg" alt="Logo" width="250" height="250">
  </a>
</div>

# Developer(s) SEP 2023 - JAN 2024
</div>

---

<table align=center>
  <tbody>
    <tr>
     <td align="center"><a><img src="https://github.com/TimKuijpers2002.png" width="100px;" alt="Tim Kuijpers"/><br /><sub><b>Tim Kuijpers</b></a></td>
  </tbody>
</table>

# :man_technologist: Short Introduction
Medix Hub is a platform where hospital personnel can bring up the clinical picture and history of treatments/surgeries of a patient. This includes all medication used by the patient in their past or present situation(s).

The hospital personnel can also create, delete or update medical data of patients.

Patient data and certain actions are obtainable/executable based on the users role within the system. Examples of roles are:
- Nurse
- Doctor 
- GP (General Practitioner)
- Administrator
- SuperAdmin

<br/>


### Languages and Tools used
These following technologies are used the most frequent amount within this project:
<div align=center>
  <img src="https://avatars.githubusercontent.com/u/7802525?s=48&v=4" title="GRPC" alt="GRPC" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/csharp/csharp-original.svg" title="Csharp" alt="Csharp" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/dotnetcore/dotnetcore-original.svg" title="dotnet" alt="dotnet" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/microsoftsqlserver/microsoftsqlserver-plain-wordmark.svg" title="MSSQL"  alt="MSSQL" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/kubernetes/kubernetes/9884746f0fd338c393d23dbb2a87d118a34fe5e5/logo/logo.svg" title="Kubernetes" alt="Kubernetes" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/github/github-original.svg" title="Git" **alt="Git" width="60" height="60"/>
  <img src="https://avatars.githubusercontent.com/u/92540622?s=48&v=4" title="KrakenD" **alt="KrakenD" width="60" height="60"/>
  <img src="https://avatars.githubusercontent.com/u/4921466?s=48&v=4" title="KeyCloak" **alt="KeyCloak" width="60" height="60"/>
  <img src="https://avatars.githubusercontent.com/u/47359?s=48&v=4" title="Apache Cassandra" **alt="Apache Cassandra" width="60" height="60"/>
</div>
<br/>

The following technologies also contribute to this project:
- Entity Framework
- Snyk
- SonarCloud
- Azure
- K6 by Grafana
- Grafana
- Influx DB
- Proto
- JSON Transcoding
- Postman
- GHZ performance tests

## Architecture diagram
<img src="https://github.com/TimKuijpers2002/Medix-Hub/blob/master/C4%20model%20-%20Level%202.png" height="auto" width="auto">

## Event Storming results
<img src="https://github.com/TimKuijpers2002/Medix-Hub/blob/master/Medix%20Hub%20-%20Event%20Storming%20v2.0.jpg" height="auto" width="auto">


## API Endpoints (from gateway)
The application has the following endpoints:

HTTP method | API endpoints             | Description
------------|---------------------------|---------------------------
 GET        | /api/v1/patient           | Get all patients
 GET        | /api/v1/patient/{id}      | Get patient by ID
 POST       | /api/v1/patient           | Create patient
 POST       | /api/v1/deceased          | Declare patient as deceased
 PUT        | /api/v1/patient           | Update patient
 DELETE     | /api/v1/patient/{id}      | Delete patient
 GET        | /api/v1/report            | Get all reports
 GET        | /api/v1/report/{id}       | Get report by ID
 POST       | /api/v1/report            | Create report
 PUT        | /api/v1/report            | Update report
 DELETE     | /api/v1/report/{id}       | Delete report

(Upcoming with enterprise KrakenD)

GRCP method | API endpoints             | Description
------------|---------------------------|---------------------------
 GET        | /grpc/v1/patient           | Get all patients
 GET        | /grpc/v1/patient/{id}      | Get patient by ID
 POST       | /grpc/v1/patient           | Create patient
 POST       | /grpc/v1/deceased          | Declare patient as deceased
 PUT        | /grpc/v1/patient           | Update patient
 DELETE     | /grpc/v1/patient/{id}      | Delete patient
 GET        | /grpc/v1/report            | Get all reports
 GET        | /grpc/v1/report/{id}       | Get report by ID
 POST       | /grpc/v1/report            | Create report
 PUT        | /grpc/v1/report            | Update report
 DELETE     | /grpc/v1/report/{id}       | Delete report

## Contributing
Pull requests are not desired. This was a project for school within my study at Fontys HBO-ICT Software engineering.

## License
[MIT](https://choosealicense.com/licenses/mit/)
