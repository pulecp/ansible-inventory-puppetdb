# ansible-inventory-puppetdb
This script will return inventory from puppetdb ordered per environment

## Example 

```
[kayn@puppetdb ~]$ ./puppetdb.py
{
  "production": [
    "prod1.example.com", 
    "prod2.example.com"
  ], 
  "development": [
    "dev1.example.com", 
    "dev2.example.com", 
  ]
}
```
