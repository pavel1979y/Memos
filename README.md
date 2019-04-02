# Memos



При бажанні запустити програму локально для тестування коду, внесення змін тощо:
1. Виконати `git clone https://github.com/pavel1979y/Memos.git`
2. Перейти в директорій проекту: `cd Memos`
3. Інсталювати залежності з package.json через команду `npm install`
4. Запустити програму локально через команду `npm run dev` 

При цьому зазначаємо, що у вас повинен бути встановлений на комп'ютер node.js : https://nodejs.org/uk/

При бажанні інтегрувати роботу сайту с вашою базою даних mongodb, необхідно в файлі `configs\db.js` вказати дані для доступу в вашу базу даних, а саме змінити параметри `url` та `dbName` на ваші особисті, за якою ви створили БД.
