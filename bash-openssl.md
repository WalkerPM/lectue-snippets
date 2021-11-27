# Разбираемся с SSH

Протокол удалённого соединения, шифрование на базе открытого и закрытого ключа с современными шифрами.

Описание хендшейка и методов аунтефикация.

Генерируем приватный и публичные ключи

'''bash
ssh-keygen
'''
Обмен публичным ключом
'''bash
ssh-copy-id user@target-host
'''

Проверяем

Работа с внешними ключами

'''bash
ssh-keygen -f filename
ssh-copy-id -i filename.pub user@target-host
'''

OpenSSL

'''bash
openssl genrsa > private_key

'''
