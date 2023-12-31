# Practice_Linq

- Клонувати репозиторій:
https://github.com/IlonaShevchenko/Practice_Linq.git
У проєкті є частковий код:

  - опис класу FootballGame, який описує футбольний матч (FootballGame.сs);
  - у файлі Program.cs вже реалізований метод ReadFromFileJson(), який десеріалізаціє json-файл (data/results_2010.json) у колекцію List;
  - також у файлі Program.cs повністю реалізований метод Main().

Склонований проект має запускатися і виводити на екран тестове
значення 13049 (це кількість всіх матчів збірних, які були проведені з 2010 року включно).

- Необхідно реалізувати методи Query1(), Query2(), …, Query10(), шаблони цих методів наявні в проекті. Завдання (запити для реалізації) див. у вигляді коментарів до кожного методу.

Крім запиту у кожному методі має бути реалізований вивід на екран результатів запиту (приклад оформлення виводу див. файл output.txt).

- Для проекту має бути створений власний локальний і віддалений репозиторії. Після реалізації кожного методу QueryN() необхідно робити коміт, вказуючи номер N реалізованого запиту.




## Виконання роботи

Під час виконання роботи були реалізовані наступні запити:

- Запит 1: Вивести всі матчі, які відбулися в Україні у 2012 році.

- Запит 2: Вивести Friendly матчі збірної Італії, які вона провела з 2020 року.

- Запит 3: Вивести всі домашні матчі збірної Франції за 2021 рік, де вона зіграла у нічию.

- Запит 4: Вивести всі матчі збірної Германії з 2018 року по 2020 рік (включно), в яких вона на виїзді програла.

- Запит 5: Вивести всі кваліфікаційні матчі (UEFA Euro qualification), які відбулися у Києві чи у Харкові, а також за умови перемоги української збірної.

- Запит 6: Вивести всі матчі останнього чемпіоната світу з футболу (FIFA World Cup), починаючи з чвертьфіналів (тобто останні 8 матчів). Матчі мають відображатися від фіналу до чвертьфіналів (тобто у зворотній послідовності).

- Запит 7: Вивести перший матч у 2023 році, в якому збірна України виграла.

- Запит 8: Перетворити всі матчі Євро-2012 (UEFA Euro), які відбулися в Україні, на матчі з наступними властивостями: MatchYear - рік матчу, Team1 - назва приймаючої команди, Team2 - назва гостьової команди, Goals - сума всіх голів за матч.

- Запит 9: Перетворити всі матчі UEFA Nations League у 2023 році на матчі з наступними властивостями: MatchYear – рік матчу, Game – назви обох команд через дефіс (першою – Home_team), Result - результат для першої команди (Win, Loss, Draw)

- Запит 10: Вивести з 5-го по 10-тий (включно) матчі Gold Cup, які відбулися у липні 2023 р.

## Висновок

У результаті виконання практичної роботи було розроблено та реалізовано LINQ-запити (Query1()-Query10()), які вирішують конкретні завдання, використовуючи дані про футбольні матчі. Було проведено тестування кожного LINQ-запиту та перевірено його результати на відповідність очікуваним. Було створено локальний та віддалений репозиторії, у які додавалися коміти після реалізації кожного запиту. 
