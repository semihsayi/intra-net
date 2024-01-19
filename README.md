# Intranet Application
Intranet application provides many features in local network environment.

## Features
 - Dynamic blog publishing
 - Simple task management
 - Contact form management
 - URL management
 - Visitor management

## Integrations

Application |URL| Description
|--|--|--|
|KPS| [Turkey Republic Health Ministry-Identity Sharing System](https://kpsv2.saglik.gov.tr/)
|LDAP| [Microsoft LDAP Protocol](https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-adts/3c5916a9-f1a0-429d-b937-f8fe672d777c)


## Getting started

### Application Modules ###
  
#### Blogs
Blog editors can add new blog posts. The blog posts added can be sent to a specific organization or organizations. With the IP subnet information of the user's computer, the organization is detected automatically and the relevant posts are listed.  
  
Blog posts can be edited or deleted by blog editors with the ckeditor plugin  

#### Links
The link listing feature has been developed for the links used within the organization to reach the users from their home pages. Link management provides easy access to the links used in the organization and in external web services.
  
#### Contact forms
Users can send their opinions, suggestions and complaints via contact forms.  
  
Contact form managers are informed by SMS and / or e-mail notifications of contact forms sent to the organizations they are authorized to. Contact form managers also can review the contact forms sent by users, send messages to users via SMS and / or e-mail, and close these contact forms.

#### Staff Visitors
A visitor registration module was developed to record and monitor visits to employees working in the organization. Visitors can be registered to units or employees in the organization. Whether the visitors are risky in terms of covid-19 is automatically checked with the HES service integrated into this application.

While registering visitors to employees, the organization's microsoft active directory user database is used.

#### Task Management
Task management module has been developed in order to monitor the tasks assigned to employees. With the task management module, task assignment, management and monitoring can be done in a simple way.

