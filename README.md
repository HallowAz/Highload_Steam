# Курсовая работа. Проект - Steam

## Тема и целевая аудитория

В качестве высоконагруженной системы был выбран онлайн-сервис цифрового распростронения компьютерных игр и программ - Steam.

### Целевая Аудитория

#### Распределение по возрасту:

Даннные со [statista](https://www.statista.com/forecasts/1242344/steam-us-user-share-by-age) сообщают о следующем распределении по возрасту в США:


| Возраст, лет| %  |
|-------------|----|
| 18-19       | 6  |
| 20-29       | 32 |
| 30-39       | 35 |
| 40-49       | 18 |
| 50-59       | 7  |
| 60-64       | 2  |

Можно принять то, что в остальных странах показатели схожи. Но стоит учитывать, то что несовершеннолетние пользователи намеренно меняют возраст, чтобы получить доступ к играм с возрастным ограничением. Учитывая этот факт, можно считать целевую аудиторию, начиная с 10 и до 50 лет.

Тот же источник ([statista](https://www.statista.com/forecasts/1242343/steam-us-user-share-by-gender)) сообщает о соотношении полов среди пользователей.
- Мужской - 68%
- Женский - 32%

Таким образом, можно сделать вывод о том, что средний пользователь Steam - это __мужчина около 30 лет__.

### Активность пользователей

В день: ≈ 25 млн активных пользователей

В месяц: ≈ 130 млн активных пользователей

Данные взяты с [steamdb](https://steamdb.info/app/753/charts/#1m) и [backlinko](https://backlinko.com/steam-users#:~:text=Steam%20has%20120%20million%20monthly,Steam%20on%20a%20daily%20basis.\\)

После математических рассчётов количества пользователей в разных странах, их соотношения относительно друг друга и пропорционального распределения относительно месячной активности, было получено:

- США - 16.7 млн
- Китай - 14 млн
- Россия - 11.6 млн
- Бразилия - 6 млн
- Германия - 4.4 млн
- Канада - 3.67 млн
- Турция - 3.42 млн
- Франция - 3.42 млн
- Великобритания - 3.18 млн
- Польша - 2.93 млн
- Филиппины - 2.57 млн
- Украина - 2.44 млн
- Япония - 1.95 млн
- Южная Корея - 1.83 млн
- Индонезия - 1.71 млн
- Австралия - 1.71 млн
- Аргентина - 1.59 млн
- Таиланд - 1.47 млн
- Испания - 1.47 млн
- Италия - 1.34 млн
- Румыния - 1.22 млн
- Мексика - 1.22 млн
- Чили  - 1.22 млн
- Индия - 1.18 млн
- Швеция - 1.16 млн
- Перу - 1 млн

Итого выходит MAU по континентам:
- Северная Америка - 21.59 млн 
- Европа - 29.68 млн
- Азия - 31.61 млн
- Южная Америка - 9.81 млн
- Австралия - 1.59 млн

Данные стран, где пользователей меньше 1 млн в месяц не учитывались. Также стоит отметить, что в России 70% населения живут в европейской части страны, а 30% в азиатской. Было решено распределить пропорционально и самих пользователей.

Количество пользователей было взято из [worldpopulationview](https://worldpopulationreview.com/country-rankings/steam-users-by-country) 

### Функционал 

- Скачивание файлов игр с серверов Steam
- Пиковые нагрузки страниц игр в дни распродаж
- Транзакции, связяанные с покупкой игр и операциями с банками
- Микротранзакции внутри игры, где Steam выступает посредником
- Рейтинг игр во внутреннем магазине

<!-- ## Расчёт нагрузки

Размер карточки игры. Профиль пользователя, ава, библиотека игр, достижения, список никнеймов Разница открытия карточек и кол-ва скачиваний после открытия. -->
