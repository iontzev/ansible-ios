Users
=========

Добавление/удаление пользователей на сетевом оборудовании Cisco

Requirements
------------

ansible-galaxy collection install cisco.ios 

Role Variables
--------------

Находятся в vars/default.yml
valid_users - словарь добавляемых/изменяемых пользователей
invalid_users - список удаляемых пользователей
add_valid_users - флаг добавления всех пользователей, указанных в словаре valid_users
remove_all_users_except_valid - флаг удаления всех пользователей, не указанных в словаре valid_users
remove_invalid_users - флаг удаления всех пользователей, указанных в словаре invalid_users
save_config - флаг сохранения конфигурации в NVRAM

Dependencies
------------

отстутствуют

License
-------

BSD

Author Information
------------------

Максим Ионцев
