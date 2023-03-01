# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
https://monosnap.com/file/hOsGMIzZNQd4RffHHcoBDKvvybKizv

# Получаем контакт по id

node index.js --action get --id 5
https://monosnap.com/file/x96EeOiDW6INeZnOWGVgaxAxBKOXMt

# Добавляем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/ALkFuyWXzET9He4y1tgpyTxH3ajbvA

# Удаляем контакт

node index.js --action remove --id=3
https://monosnap.com/file/mmcDN1wwbKVQ6s2QIAZ6vtdi5PZkeR
