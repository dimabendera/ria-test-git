# Test ria git

**Завдання**

1. Створіть репозиторій на гітхаб.
2. Зклонуйте його собі локально.
3. Створіть файл .gitignore який забороняє комітити файл someSensetiveInformation.txt
4. Створіть файл readme.md і зробіть коротенький опис на маркдауні. Що завгодно.
5. Створіть файл index.js. У файлі напишіть: console.log(‘this is my first commit’);
6. Створіть файл second.js, напишіть у ноьму “console.log(‘log from second file’)”
7. Зробіть коміт з меседжом “initial commit”
8. Змініть текст логів у файлах відповідно
    * index.js - “some eversome feature”
    * second.js - “new log from second file”
9. Зробіть коміт у новий бранч myFeatureName
10. Змініть текст логу у файлі index.js на “I’ve changed this file while you were making your
feature :)”. І зробіть коміт у “master”
11. Злийте гілку myFeatureName в гілку master. Зверніть увагу, що файл second.js злився
автоматично, тому що він не змінювався у двох різних гілках одночасно, а файл
index.js потребує вашої участі при злитті. Змініть текст логу при злитті на “log after
merge”.
12. Не забудьте запушити все що ви наробили на гітхаб і скинути мені ссилочку на
репозиторій.