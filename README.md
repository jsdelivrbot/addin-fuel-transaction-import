# addin-fuel-transaction-import
An add-in to read fuel card transactions from a file and import to MyGeotab database

### Installation
Add the configuration below to the to the system setting -> add-ins section of the MyGeotab database
```
{
  "name": "Fuel Transaction Import (by Geotab)",
  "supportEmail": "support@geotab.com",
  "version": "2.2.0",
  "items": [{
    "icon": "https://cdn.jsdelivr.net/gh/Geotab/addin-fuel-transaction-import@master/dist/images/icon.png",
    "path": "EngineMaintenanceLink/",
    "menuName": {
      "en": "Fuel Transaction Import"
    },
    "url": "https://cdn.rawgit.com/Geotab/addin-fuel-transaction-import/master/dist/importFuelTransactions.html"
  }]
}
```

### Contributing
If there's a fuel card provider file you would like to add a parser for, please do! We welcome pull requests.
