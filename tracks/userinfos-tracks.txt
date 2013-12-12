## TRACK RECORD userinfos
## VIRTUEPAD: V 2.1
## FILENAME: userinfos_b2b_export_in.csv
## FIELD SEPARATOR: ^
## TEXT DELIMITER: ~

- virtuemart_userinfo_id (int, reference to virtuemart system user)
- virtuemart_user_id (int, reference to joomla system user id)
- company (varchar)
- codext (int or varchar, reference to ERP system identificator)
- codag (int or varchar, reference to ERP system multivendor identificator)
- address_type (varchar, "Billing address" or "Shipping address")
- address_type_name (varchar, "Billing address" to define an ufficial company address. Set a text to identificate an address to deliver products, ex. "Store in Milan")
- address_1 (varchar)
- zip (int or varchar)
- city (varchar)
- state_name (varchar)
- country_name (varchar)
- phone_1 (varchar)
- phone_2 (varchar)
- vatnumber (int or varchar)
- ratecode (int or varchar)
- name (varchar, it's firt_name + last_name)
- first_name (varchar)
- last_name (varchar)
- email (varchar, valid email address or a construction of [codext]@[customerdomain])
- created_on (date time in YYYY-mm-dd H:i:s)


## TRACK RECORD userinfos
## VIRTUEPAD: V 2.1
## FILENAME: userinfos_b2b_import_out.csv
## FIELD SEPARATOR: ^
## TEXT DELIMITER: ~

- company (varchar)
- vatnumber (int or varchar)
- ratecode (int or varchar)
- address_type (varchar, "Billing address" to define an ufficial company address. Set a text to identificate an address to deliver products, ex. "Store in Milan")
- address_type_name (varchar, "Billing address" to define an ufficial company address. Set a text to identificate an address to deliver products, ex. "Store in Milan")
- address_1 (varchar)
- city (varchar)
- zip (int or varchar)
- state (varchar)
- country (varchar)
- email (varchar, valid email address or a construction of [codext]@[customerdomain])
- password (varchar, tipically set to [customerdomain])
- name (varchar, it's firt_name + last_name)
- first_name (varchar)
- last_name (varchar)
- fax (varchar)
- phone_2 (varchar)
- phone_1 (varchar)
- codag (int or varchar, reference to ERP system multivendor identificator)
- perms (varchar, set to "~shopper~")
- shopper_group_name (varchar, name of special group of customers)
- codext (int or varchar, reference to ERP system identificator)
- usergroup_name (varchar, set to "Registered")
- block (int, set to "1" to block customer or "0" to free access customer)