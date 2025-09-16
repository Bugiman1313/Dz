База данных по интернет-магазину
Описание таблиц и полей:
Категории продуктов (categories):  

Id – ID категории;  
Name – название категории.

Поставщики (suppliers):  

Id – идентификатор поставщика;  
Name – название поставщика;  
Contacts – контакты поставщика;  
Address – адрес поставщика.

Производитель (manufacturer):  

Id – идентификатор производителя;  
Name – наименование производителя;  
Address – адрес производителя;  
Contacts – контакты производителя;  
Product description – описание продукта;  
Price – цена продукта.

Продукты (products):  

Id – ID продукта;  
category_id – ID категории продукта;  
name – наименование продукта;  
manufacturer_id – идентификатор производителя;  
suppliers_id – идентификатор поставщика.

Клиент (client):  

Id – ID клиента;  
Name – имя клиента;  
Contacts – контакты клиента;  
delivery address – адрес доставки клиента.

Покупки (purchases):  

Id – ID покупки;  
product_id – ID продукта;  
client_id – ID клиента;  
prices_id – ID цены;  
purchase_data – дата покупки.

Цены (prices):  

Id – ID цены;  
products_id – ID продукта;  
price – цена.
