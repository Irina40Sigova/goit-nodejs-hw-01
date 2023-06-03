# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"
https://monosnap.com/file/0qnCFV45pP81bL2jrWXoLpV1R1PLJu;

# Отримуємо контакт по id

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/da4hcPw5Y0jRUiezmBRw7uJ9QmwqEw;

# Додаємо контакт

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/dul0JP8F3M7Zh6ClH80dlLHVYZQKdF;

# Видаляємо контакт

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/tATi7qCzqj4pFHRumbLyje1LrPn7SV;
