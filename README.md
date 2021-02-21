/******Respository description*********/
Shop - test project for study automation testing for REST API with Postman
REST API, Postman, javascript, Chai.js 

/******Creadentials******/
Shop
http://shop.bugred.ru/ 

DB: https://46.36.217.134:8888/phpmyadmin/sql.php?server=1&db=shop_bugred_r_db&table=items&pos=0
DB Documentation - https://testbase.atlassian.net/wiki/spaces/SHOP/pages/1971978345

login - view_user
password -  ZQl3Ea1uhHTzzl3j

Shop Documentation — https://testbase.atlassian.net/wiki/spaces/SHOP/overview

/******Shop methods*****/
All methods are available via both REST and SOAP
WSDL для SOAP -  http://shop.bugred.ru/soap.php?wsdl
URL fot REST - http://shop.bugred.ru/api/items/<method_name>
All methods are realized via POST

List of available methods:
    - Create item  
    - Update item 
    - Upload photo 
    - Get item 
    - Delete item 
    - Search 
    - Select from DB 
    
REST API URLs:
    - Create item  - http://shop.bugred.ru/api/items/create/ 
    - Update item  - http://shop.bugred.ru/api/items/update/ 
    - Upload photo - http://shop.bugred.ru/api/items/upload_photo/ 
    - Get item - http://shop.bugred.ru/api/items/get/ 
    - Delete item - http://shop.bugred.ru/api/items/delete/ 
    - Search - http://shop.bugred.ru/api/items/search/ 
    - Select from DB - http://shop.bugred.ru/api/items/select/ 


REST API Requirements:
    - Create item  - https://testbase.atlassian.net/wiki/spaces/SHOP/pages/1957496610/Create+item
    - Update item  - https://testbase.atlassian.net/wiki/spaces/SHOP/pages/1969422366/Update+item
    - Upload photo - https://testbase.atlassian.net/wiki/spaces/SHOP/pages/1969487957/Upload+photo
    - Get item - https://testbase.atlassian.net/wiki/spaces/SHOP/pages/1969291375/Get+item
    - Delete item - https://testbase.atlassian.net/wiki/spaces/SHOP/pages/1969160261/Delete+item
    - Search - https://testbase.atlassian.net/wiki/spaces/SHOP/pages/1957464487/Search
    - Select from DB - https://testbase.atlassian.net/wiki/spaces/SHOP/pages/1969258788/Select