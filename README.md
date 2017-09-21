# allcount-adal-auth-module
Azure Active Directory plugin for allcountjs


### Sample configuration
```javascript
A.app({
    adal: {
        tenant: "<AAD Tenant>",  
        appId: "<AAD App ID>",
        appSecret: "<AAD App Secret>",
        authorizedAADGroups: ['Company Administrator'],
        aadGroup2RoleMapping: [ {group: "Company Administrator", role: "admin"}, {group: "allcountmanagers", role: "manager"}],
        isDefaultLoginMethod: true
    });
```

