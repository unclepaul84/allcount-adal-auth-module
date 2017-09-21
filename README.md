# allcount-adal-auth-module
Azure Active Directory plugin for allcountjs


### Sample configuration
```javascript
A.app({
    adal: {
        tenant: "paulkotlyarhotmail.onmicrosoft.com",  
        appId: "a0cad9b7-ac41-4470-9df3-494aea3f327d",
        appSecret: "DM0O9GndzCsGiAX0Jtda8z8fmn8BKk0l8FgXU2lDfnc=",
        authorizedAADGroups: ['Company Administrator'],
        aadGroup2RoleMapping: [ {group: "Company Administrator", role: "admin"}, {group: "allcountmanagers", role: "manager"}],
        isDefaultLoginMethod: true
    });
```

