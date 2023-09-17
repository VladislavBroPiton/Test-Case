# Тест кейс
**Тест кейс**-это пошаговая инструкция к функционалу приложения. Он дает представление о том, какое поведение ожидается от приложения и любое отклонение от предполагаемого результата, будет являться багом.     
Мы пошагово (1.. 2.. 3.. и т.д.) описываем необходимые действия и их результаты (1 - результат на 1 шаг, 2 - результат на 2 шаг и т.д.)  для воспроизведения определенного пользовательского сценария (use case).   
В тест кейсе всегда каждому действию (шагу) обязательно соответствует ожидаемый результат.    
### Пример:   

ID | Summary | Pre-conditions | Steps | Expected results
:--|:-------:|:--------------:|:-----:|-----------------:
**1** | Registration by Email of a new user (Регистрация по почте нового пользователя) | **1**.The email lfl92@mail.ru was created (Почта lfl92@mail.ru создана)    **2**.The user is not registered (Пользователь не зарегистрирован) | **1**.Go to https://best.aliexpress.com/   **2**.Go to Account > Register button (Перейти в раздел «Учетная запись» > кнопка «Регистрация».)   **3**.Choose a place (Выбрать место)    **4**.Input email (Ввести адрес электронной почты)  **5**.Input a password (6-20 symbols) (Ввести пароль)   **6**.Click 'Create accout' button (Нажать кнопку «Создать аккаунт»)    **7**.Check a mailbox (Проверить почтовый ящик)     **8**.Copy the verification code and fill in the confirmation box (Скопировать проверочный код и заполните окно подтверждения) **9**.Click the "Verify Email Address" button (Нажать кнопку «Подтвердить адрес электронной почты»)     **10**.Go out (Выйти)   **11**.Try to login with user credentials (Попробовать войти в систему с учетными данными пользователя) |   **1**.The Main page is open (Главная страница открыта)  **2**.The registration window is opened (Окно регистрации открыто)  **3**.The list opens. User selects a location (Открывается список. Пользователь выбирает место)     **4**.Email is displayed, no error message (Почта отображается, нет сообщения об ошибке)    **5**.The password is displayed, there is no error message. (Пароль отображается, сообщения об ошибке нет)  **6**.The verification window is dispalyed. The 'Verify Email' button is disabled (Отображается окно проверки. Кнопка «Подтвердить адрес электронной почты» отключена)  **7**.The verification code was received (Код подтверждения получен)    **8**.Confirm button is active (Кнопка подтвердить активна)     **9**.User registered (Пользователь зарегистрирован)    **10**.User logged out (Пользователь вышел из системы)  **11**.User logged in (Пользователь вошел в систему) |
  
**Тестировщик пишет тест кейсы для того**, чтобы продукт можно было проверить без ознакомления со всей документацией. Написав один раз тест кейс (хороший и удобный в поддержке), тестировщик экономит много времени и сил себе и другим тестировщикам.   

Что еще необходимо знать, перед созданием тест-кейса?
Во-первых, каждый выполненный тест-кейс, дает нам один из трех результатов:
