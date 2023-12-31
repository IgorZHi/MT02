#  Тест-кейсы №1 для пароля <u>"standard_user"</u>

https://www.saucedemo.com/

### Тест-кейс №1.  Проверка успешного прохождения авторизации:
#### 1. Предшествующие условия: 
 - пользователь не авторизован; 
 - открыта страница https://www.saucedemo.com/.
#### 2. Шаги:
 - Перейти на страницу авторизации
 - В поле "Username" ввести "standart_user"
 - В поле "Password" ввести "secret_sauce"
 - Нажать на кнопку "LOGIN"
#### 3. Ожидаемый результат:
 - Нажатие на кнопку "LOGIN" или "Enter" на клавиатуре переводит нас на главную страницу   интернет-магазина. 
### Тест-кейс №2. Поиск товара:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - открыта главная страница сайта
#### 2. Шаги:
 - Просмотр доступного товара на главной странице с кнопкой прокрутки вверх,вниз
#### 3. Ожидаемый результат:
 - Страница открыта,товар виден,кнопка скрола перемещается
### Тест-кейс №3. Просмотр товара и цены:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - открыта главная страница
 - осмотрен товар
#### 2. Шаги:
 - Просмотр карточек товара и цены ,нажав на кнопу "Название товара"
 - Просмотр товара и цены ,нажав на кнопу "Фото"
#### 3. Ожидаемый результат:
  - открытие карточек товара и цены, нажав на кнопу "Название товара" и проход внутрь карточки с описанием товара  
  - открытие товара и цены, нажав на кнопу "Фото" и проход далее в меню карточки
### Тест-кейс №4. Проверка возврата из карточки товара в главное меню сайта:
#### 1. Предшествующие условия:
  - Авторизация на странице сайта
  - осмотрен товар и цена
  - Открытие карточки нажав на кнопку  "Наименование товара" или "Фото товара" и нахождение внутри карточки товара
#### 2. Шаги:
  - Нажать на кнопку "Back to products" (возврат на главную страницу сайта)
#### 3. Ожидаемый результат:
  - возврат на главную страницу сайта
### Тест-кейс №5. Сортировка товара по алфавиту ( с начала или конца) и цене (возрастание или убывание):
#### 1. Предшествующие шаги:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
#### 2. Шаги:
 - Нажать на кнопку "Воронка" и в чек-боксе выбрать сортировка товара по алфавиту ( с начальной буквы или с последней) или цене (восзрастание или убывание)
#### 3. Ожидаемый результат:
 - при переходе в воронку сортировки товара по алфавиту и выбору с какой буквы сортировать происходит сортировка товара,при сортировки товара по цене с больше на меньшую и наоборот -происходит отбор товара по заданным условиям
### Тест-кейс №6. Просмотр всего товара:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
#### 2. Шаги:
 - можно посмотреть весь товар представленный интернет магазином
 - Нажать на кнопку "Гамбургер" верхний левый угол
 - Нажать на кнопку "All items"
#### 3. Ожидаемый результат:
 - при нажатии на кнопки этого меню открывается весь товар на сайте 
### Тест-кейс №7. Переход на домашнюю страницу продавца:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер" 
#### 2. Шаги:
 - Нажать на кнопку "Гамбургер"
 - Нажать на кнопку "About"
 - Переход на домашнюю страницу на другой сайт продавца,где описывается род его деятельности
 - если есть интерес,идет ознакомление,если нет -выход с домашней страницы продавца и попадание на главную страницу сайта с товаром
#### 3. Ожидаемый результат:
 - при нажатие на эти кнопки происходят переходы в эти меню и переход на сайт продавца,при нежелании ознакомиться с деятельностью компании,возрат в главное меню сайта продавца с товаром ,для дальнейшего выбора или ознакомления с ассортиментом или схемой работы сайта
### Тест-кейс №8.  Выход из главной страницы сайта в меню авторизации:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 #### 2. Шаги:
 - Нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Logout"
 #### 3. Ожидаемый результат:
 - при нажатии на эти кнопки происходит выход со страницы сайта в меню авторизации
### Тест-кейс №9. Сброс цены товара из корзины из меню "Гамбургер":
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации 
#### 2. Шаги:
  - пользователь не авторизован;
  - открыта страница https://www.saucedemo.com/.
  - Авторизация на  странице сайта
  - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное количество товара будет видно в корзине
  - Нажать на кнопку "Гамбургер"
  - Нажать на кнопку "Reset App State"
#### 3. Ожидаемый результат:
  - После успешной авторизации добавление понравившегося товара в корзину в любом количестве нажатием кнопки"Add to cart" и из карточек товара и с главной страницы , путешествуя по сайту компании
  - находясь в меню "Гамбургера"можно скинуть количество помещенного товара из корзины,если передумал покупать, нажав на кнопку"Reset App State"
### Тест-кейс №10. Добавить товар в корзину:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное количество товара будет видно в корзине
 - Нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Reset App State"
#### 2. Шаги: 
 - Нажать на кнопку "App to cart" хоть на всех имеющихся в наличие товаров,хоть на один на главной странице сайта
 - Нажать на кнопку "Название" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart"
 - Нажать на кнопку "Фото" на карточке товара  с переходом внутрь карточки
 - Нажать на кнопку "App to cart'
#### 3. Ожидаемый результат:
 - авторизация прошла успешно,поиск товара,добавление в корзину в любом количестве,из всех точек меню сайта ,когда что то понравилось
### Тест-кейс №11. Убрать товар из корзины:
#### 1. Предшествующие условия: 
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное  -  - количество товара будет видно в корзине
 - Нажать на кнопку "Гамбургер"
 - жать на кнопку "Reset App State"
 - Нажать на кнопку "App to cart" хоть на всех имеющихся в наличие товаров,хоть на один на главной странице сайта
 - Нажать на кнопку "Название" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart"
 - Нажать на кнопку "Фото" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart'
#### 2. Шаги:
 - Нажать на кнопку 'App to cart" кнопка изменится на "Remove"
 - Нажать на кнопку "Remove" если один товар
 - Или нажать на кнопку "Гамбургер" 
 - Нажать на кнопку "Reset App State" если много товара и уберется все количество товара из корзины
#### 3. Ожидаемый результат:
 - после нажития кнопок "Remove" или "Reset App State" весь товар должен убраться из корзины
### Тест-кейс №12. Переход со страницы сайта в соц.сети "Twitter", "Facebook","In" в (Футере):
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное количество товара будет видно в корзине
 - Нажать на кнопку "Гамбургер"
 - нажать на кнопку "Reset App State"
 - Нажать на кнопку "App to cart" хоть на всех имеющихся в наличие товаров,хоть на один на главной странице сайта
 - Нажать на кнопку "Название" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart"
 - Нажать на кнопку "Фото" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart'
 - Нажать на кнопку 'App to cart" кнопка изменится на "Remove"
 - Нажать на кнопку "Remove" если один товар
 - Или нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Reset App State" если много товара и уберется все количество товара из корзины
#### 2. Шаги:
 - Нажать на кнопку "Скрол" вниз и опуститься в футер
 - Выбрать любую из нужных соц.сетей и нажать кнопку для прохода на сайт соцсетей
#### 3. Ожидаемый результат:
 - после прокрутки скрола до футера в самом низу сайта ,при нажатии на любую кнопку соцсетей проход по ссылке на сайт соцсетей
### Тест-кейс №13. Покупка товара:
#### 1. Предшествующие условия: 
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - ортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное количество товара будет видно в корзине
 - Нажать на кнопку "Гамбургер"
 - нажать на кнопку "Reset App State"
 - Нажать на кнопку "App to cart" хоть на всех имеющихся в наличие товаров,хоть на один на главной странице сайта
 - Нажать на кнопку "Название" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart"
 - Нажать на кнопку "Фото" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart'
 - Нажать на кнопку 'App to cart" кнопка изменится на "Remove"
 - Нажать на кнопку "Remove" если один товар
 - Или нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Reset App State" если много товара и уберется все количество товара из корзины
 - Нажать на кнопку 'App to cart" кнопка изменится на "Remove"
 - Нажать на кнопку "Remove" если один товар
 - Или нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Reset App State" если много товара и уберется все количество товара из корзины
#### 2. Шаги: 
 - Выбрать товар и нажать на кнопку "App to cart"
 - Нажать на кнопку "Корзина"
 - Нажать на кнопку "Checkout"
 - В поле ввода "First Name" ввести имя
 - В поле ввода "Last Name" ввести фамилию
 - В поле ввода "Zip/Postal code" ввести индекс своего адреса
 - Нажать на кнопку "Continue"
 - Нажать на кнопку "Finish"
 - Нажать на кнопку "Back Home"
#### 3. Ожидаемый вариант:
 - Выбранные товары верно отображаются в корзине;
 - Есть форма заполнения данных для доставки;
 - Нажатие "Finish" уведомляет нас об успешно оформленном заказе.





#  Тест-кейсы №2 для пароля <u>"locked_out_user"</u>
https://www.saucedemo.com/
### Тест-кейс №1.  Проверка успешного прохождения авторизации:
#### 1. Предшествующие условия: 
 - пользователь не авторизован; 
 - открыта страница https://www.saucedemo.com/.
#### 2. Шаги:
 - Перейти на страницу авторизации
 - В поле "Username" ввести <u>"locked_out_user"</u>
 - В поле "Password" ввести "secret_sauce"
 - Нажать на кнопку "LOGIN"
#### 3. Ожидаемый результат:
 - Нажатие на кнопку "LOGIN" или "Enter" на клавиатуре переводит нас на главную страницу   интернет-магазина. 
- - - 
Мы не  проходим на главную страницу сайта. выходит предупреждение "Epic sadface: Sorry, this user has been locked out."(Извините, этот пользователь заблокирован.)Мы не можем далее продолжать проверку функциональности сайта. Если бы могли,то аналогично Тест-кейса №1.






#  Тест-кейсы №3 для пароля <u>"problem_user"</u>

https://www.saucedemo.com/
### Тест-кейс №1.  Проверка успешного прохождения авторизации:
#### 1. Предшествующие условия: 
 - пользователь не авторизован; 
 - открыта страница https://www.saucedemo.com/.
#### 2. Шаги:
 - Перейти на страницу авторизации
 - В поле "Username" ввести <u>"problem_user"</u>
 - В поле "Password" ввести "secret_sauce"
 - Нажать на кнопку "LOGIN"
#### 3. Ожидаемый результат:
 - Нажатие на кнопку "LOGIN" или "Enter" на клавиатуре переводит нас на главную страницу   интернет-магазина. 
### Тест-кейс №2. Поиск товара:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - открыта главная страница сайта
#### 2. Шаги:
 - Просмотр доступного товара на главной странице с кнопкой прокрутки вверх,вниз
#### 3. Ожидаемый результат:
 - Страница открыта,товар виден,кнопка скрола перемещается
#### 4. Фактический результат:
 - страница открывается,скрол работает,товар другой(фото собаки) в отличие от названия и на все карточках товара одна и та же фото собаки
- - -
###### Выполняя <u>позитивный</u>  набор данных действий - мы видим что функция открывания фото отличается от ожидаемого результата ; размещено одинаковое фото на всех карточках товара и далее можно продолжать список выявления багов или ошибок или дефектов. Так как нам по заданию нужно описать и создать список сценариев <u>позитивного тестирования</u> для проверки функциональных возможностей системы(сайта) , мы останавливаем далее проверку "Список тестовых сценариев №3 для пароля <u>"problem_user"</u>" по причине начала негативного тестирования сайта с выявлением ошибок,багов,дефектов. 

 Если бы могли,то аналогично Тест-кейса №1.






#  Тест-кейсы №4 для пароля <u>"performance_glitch_userr"</u>
https://www.saucedemo.com/
### Тест-кейс №1.  Проверка успешного прохождения авторизации:
#### 1. Предшествующие условия: 
 - пользователь не авторизован; 
 - открыта страница https://www.saucedemo.com/.
#### 2. Шаги:
 - Перейти на страницу авторизации
 - В поле "Username" ввести <u>"performance_glitch_user"</u>
 - В поле "Password" ввести "secret_sauce"
 - Нажать на кнопку "LOGIN"
#### 3. Ожидаемый результат:
 - Нажатие на кнопку "LOGIN" или "Enter" на клавиатуре переводит нас на главную страницу   интернет-магазина. 
### Тест-кейс №2. Поиск товара:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - открыта главная страница сайта
#### 2. Шаги:
 - Просмотр доступного товара на главной странице с кнопкой прокрутки вверх,вниз
#### 3. Ожидаемый результат:
 - Страница открыта,товар виден,кнопка скрола перемещается
### Тест-кейс №3. Просмотр товара и цены:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - открыта главная страница
 - осмотрен товар
#### 2. Шаги:
 - Просмотр карточек товара и цены ,нажав на кнопу "Название товара"
 - Просмотр товара и цены ,нажав на кнопу "Фото"
#### 3. Ожидаемый результат:
  - открытие карточек товара и цены, нажав на кнопу "Название товара" и проход внутрь карточки с описанием товара  
  - открытие товара и цены, нажав на кнопу "Фото" и проход далее в меню карточки
### Тест-кейс №4. Проверка возврата из карточки товара в главное меню сайта:
#### 1. Предшествующие условия:
  - Авторизация на странице сайта
  - осмотрен товар и цена
  - Открытие карточки нажав на кнопку  "Наименование товара" или "Фото товара" и нахождение внутри карточки товара
#### 2. Шаги:
  - Нажать на кнопку "Back to products" (возврат на главную страницу сайта)
#### 3. Ожидаемый результат:
  - возврат на главную страницу сайта
### Тест-кейс №5. Сортировка товара по алфавиту ( с начала или конца) и цене (возрастание или убывание):
#### 1. Предшествующие шаги:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
#### 2. Шаги:
 - Нажать на кнопку "Воронка" и в чек-боксе выбрать сортировка товара по алфавиту ( с начальной буквы или с последней) или цене (восзрастание или убывание)
#### 3. Ожидаемый результат:
 - при переходе в воронку сортировки товара по алфавиту и выбору с какой буквы сортировать происходит сортировка товара,при сортировки товара по цене с больше на меньшую и наоборот -происходит отбор товара по заданным условиям
### Тест-кейс №6. Просмотр всего товара:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
#### 2. Шаги:
 - можно посмотреть весь товар представленный интернет магазином
 - Нажать на кнопку "Гамбургер" верхний левый угол
 - Нажать на кнопку "All items"
#### 3. Ожидаемый результат:
 - при нажатии на кнопки этого меню открывается весь товар на сайте 
### Тест-кейс №7. Переход на домашнюю страницу продавца:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер" 
#### 2. Шаги:
 - Нажать на кнопку "Гамбургер"
 - Нажать на кнопку "About"
 - Переход на домашнюю страницу на другой сайт продавца,где описывается род его деятельности
 - если есть интерес,идет ознакомление,если нет -выход с домашней страницы продавца и попадание на главную страницу сайта с товаром
#### 3. Ожидаемый результат:
 - при нажатие на эти кнопки происходят переходы в эти меню и переход на сайт продавца,при нежелании ознакомиться с деятельностью компании,возрат в главное меню сайта продавца с товаром ,для дальнейшего выбора или ознакомления с ассортиментом или схемой работы сайта
### Тест-кейс №8.  Выход из главной страницы сайта в меню авторизации:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 #### 2. Шаги:
 - Нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Logout"
 #### 3. Ожидаемый результат:
 - при нажатии на эти кнопки происходит выход со страницы сайта в меню авторизации
### Тест-кейс №9. Сброс цены товара из корзины из меню "Гамбургер":
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации 
#### 2. Шаги:
  - пользователь не авторизован;
  - открыта страница https://www.saucedemo.com/.
  - Авторизация на  странице сайта
  - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное количество товара будет видно в корзине
  - Нажать на кнопку "Гамбургер"
  - Нажать на кнопку "Reset App State"
#### 3. Ожидаемый результат:
  - После успешной авторизации добавление понравившегося товара в корзину в любом количестве нажатием кнопки"Add to cart" и из карточек товара и с главной страницы , путешествуя по сайту компании
  - находясь в меню "Гамбургера"можно скинуть количество помещенного товара из корзины,если передумал покупать, нажав на кнопку"Reset App State"
### Тест-кейс №10. Добавить товар в корзину:
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное количество товара будет видно в корзине
 - Нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Reset App State"
#### 2. Шаги: 
 - Нажать на кнопку "App to cart" хоть на всех имеющихся в наличие товаров,хоть на один на главной странице сайта
 - Нажать на кнопку "Название" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart"
 - Нажать на кнопку "Фото" на карточке товара  с переходом внутрь карточки
 - Нажать на кнопку "App to cart'
#### 3. Ожидаемый результат:
 - авторизация прошла успешно,поиск товара,добавление в корзину в любом количестве,из всех точек меню сайта ,когда что то понравилось
### Тест-кейс №11. Убрать товар из корзины:
#### 1. Предшествующие условия: 
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное  -  - количество товара будет видно в корзине
 - Нажать на кнопку "Гамбургер"
 - жать на кнопку "Reset App State"
 - Нажать на кнопку "App to cart" хоть на всех имеющихся в наличие товаров,хоть на один на главной странице сайта
 - Нажать на кнопку "Название" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart"
 - Нажать на кнопку "Фото" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart'
#### 2. Шаги:
 - Нажать на кнопку 'App to cart" кнопка изменится на "Remove"
 - Нажать на кнопку "Remove" если один товар
 - Или нажать на кнопку "Гамбургер" 
 - Нажать на кнопку "Reset App State" если много товара и уберется все количество товара из корзины
#### 3. Ожидаемый результат:
 - после нажития кнопок "Remove" или "Reset App State" весь товар должен убраться из корзины
### Тест-кейс №12. Переход со страницы сайта в соц.сети "Twitter", "Facebook","In" в (Футере):
#### 1. Предшествующие условия:
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное количество товара будет видно в корзине
 - Нажать на кнопку "Гамбургер"
 - нажать на кнопку "Reset App State"
 - Нажать на кнопку "App to cart" хоть на всех имеющихся в наличие товаров,хоть на один на главной странице сайта
 - Нажать на кнопку "Название" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart"
 - Нажать на кнопку "Фото" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart'
 - Нажать на кнопку 'App to cart" кнопка изменится на "Remove"
 - Нажать на кнопку "Remove" если один товар
 - Или нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Reset App State" если много товара и уберется все количество товара из корзины
#### 2. Шаги:
 - Нажать на кнопку "Скрол" вниз и опуститься в футер
 - Выбрать любую из нужных соц.сетей и нажать кнопку для прохода на сайт соцсетей
#### 3. Ожидаемый результат:
 - после прокрутки скрола до футера в самом низу сайта ,при нажатии на любую кнопку соцсетей проход по ссылке на сайт соцсетей
### Тест-кейс №13. Покупка товара:
#### 1. Предшествующие условия: 
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - ортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - выход со страницы сайта в меню авторизации
 - Авторизация на странице сайта
 - поиск товара
 - просмотр товара и цены
 - открытие и выход из карточек товара в главное меню сайта
 - сортировка товара по алфавиту и цене
 - просмотр всего товара через меню "Гамбургер"
 - переход на домашнюю страницу продавца и возврат на главную страницу сайта с товаром
 - Нажать на кнопку "Add to cart" можно на многих карточках товара и добавленное количество товара будет видно в корзине
 - Нажать на кнопку "Гамбургер"
 - нажать на кнопку "Reset App State"
 - Нажать на кнопку "App to cart" хоть на всех имеющихся в наличие товаров,хоть на один на главной странице сайта
 - Нажать на кнопку "Название" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart"
 - Нажать на кнопку "Фото" на карточке товара с переходом внутрь карточки
 - Нажать на кнопку "App to cart'
 - Нажать на кнопку 'App to cart" кнопка изменится на "Remove"
 - Нажать на кнопку "Remove" если один товар
 - Или нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Reset App State" если много товара и уберется все количество товара из корзины
 - Нажать на кнопку 'App to cart" кнопка изменится на "Remove"
 - Нажать на кнопку "Remove" если один товар
 - Или нажать на кнопку "Гамбургер"
 - Нажать на кнопку "Reset App State" если много товара и уберется все количество товара из корзины
#### 2. Шаги: 
 - Выбрать товар и нажать на кнопку "App to cart"
 - Нажать на кнопку "Корзина"
 - Нажать на кнопку "Checkout"
 - В поле ввода "First Name" ввести имя
 - В поле ввода "Last Name" ввести фамилию
 - В поле ввода "Zip/Postal code" ввести индекс своего адреса
 - Нажать на кнопку "Continue"
 - Нажать на кнопку "Finish"
 - Нажать на кнопку "Back Home"
#### 3. Ожидаемый вариант:
 - Выбранные товары верно отображаются в корзине;
 - Есть форма заполнения данных для доставки;
 - Нажатие "Finish" уведомляет нас об успешно оформленном заказе.

- - -
###### Выполняя <u>позитивный</u>  набор данных действий - мы видим что функции работы системы (сайта) не отличаются от ожидаемого результата. Весь функционал работает так же как и в тесте №1. Так как нам по заданию нужно описать и создать список сценариев <u>позитивного тестирования</u> для проверки функциональных возможностей системы(сайта) , мы не останавливаем далее проверку "Список тестовых сценариев №4 для пароля <u>"performance_glitch_user"</u> - хотя очень заметен  долгий отклик на реагирование при переходах и по ссылкам и по другим функциональным сценариям. Может это и есть какой то баг,но сейчас не возможно его характеризовать из -за недостатка накопленных знаний.
