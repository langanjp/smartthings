# PI Connector for UFL Data Source Configuration
Create new PI Connector data source

1. Open UFL Connector admin (typically https://servername:5460/admin/ui)
2. Click on Data Source List
3. In the box, type in the Data Source Name: **TTVRestServer** and click "Add and configure"
4. Fill in the form with the values below

Field Name | Value
------------ | -------------
Data Source Name | TTVRestServer
Data Source Description | _(optional)_
Data Source Type | REST Server
Encoding | Unicode (UTF-8)
Address | _leave blank_
User Name (REST) | _desired username_
Password (REST) | _desired password_
Scan Time [s] | 1 _(or other desired frequency)_
New Line | _leave blank_
Word Wrap | -1
Store Mode | Insert
Locale | _tested with English - United States_
Incoming TimeStamps | UTC

5. Click Save
