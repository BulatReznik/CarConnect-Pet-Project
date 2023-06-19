# CarConnect
Разработка Web-приложения для автомобилистов.

Для разработки .NET 6 веб-приложения CarConnect были использованы следующие пакеты и библиотеки:
1. Emgu.CV 4.7.0.5276: Эта библиотека была использована для определения номера по фотографии. Emgu.CV предоставляет функциональность компьютерного зрения, включая обработку изображений, распознавание и анализ.
2. Emgu.CV.Bitmap 4.7.0.5276: Этот пакет был использован для работы с изображениями в формате Bitmap. Он предоставляет методы и классы для работы с пикселями и преобразованиями изображений.
3. Emgu.CV.runtime.windows 4.7.0.5276: Этот пакет представляет собой рантаймную библиотеку, необходимую для работы Emgu.CV на платформе Windows.
4. Microsoft.AspNetCore.Mvc.NewtonsoftJson: Этот пакет предоставляет поддержку сериализации и десериализации JSON с использованием Newtonsoft.Json в ASP.NET Core MVC.
5. Microsoft.EntityFrameworkCore 7.0.5: Библиотека Entity Framework Core используется для работы с базой данных. Она обеспечивает ORM-функциональность и упрощает взаимодействие с базой данных.
6. Microsoft.EntityFrameworkCore.SqlServer 7.0.5: Этот пакет предоставляет драйвер для работы с Microsoft SQL Server в Entity Framework Core.
7. Microsoft.EntityFrameworkCore.Tools 7.0.5: Этот пакет содержит инструменты для разработки и миграции базы данных с использованием Entity Framework Core.
8. Microsoft.VisualStudio.Web.CodeGeneration.Design 6.0.13: Этот пакет содержит инструменты для генерации кода, такие как генерация контроллеров и представлений, веб-API и других элементов проекта.
9. Newtonsoft.Json 13.0.3: Библиотека Newtonsoft.Json используется для сериализации и десериализации JSON-данных. В данном проекте она использовалась для передачи файлов в формате JSON.
10. Swashbuckle.AspNetCore 6.2.3: Этот пакет позволяет автоматически создавать документацию и интерактивную панель Swagger для вашего веб-приложения ASP.NET Core.
11. System.Drawing.Common 7.0.0: Этот пакет содержит классы и методы для работы с графикой и отрисовки изображений. В данном проекте он использовался для отрисовки номера на изображении.
Эти пакеты и библиотеки были использованы в проекте CarConnect на платформе .NET 6 для реализации функциональности, связанной с обработкой изображений, работой с базой данных, сериализацией и другими задачами, необходимыми для функционирования системы.

Главная страница является основной и предназначена для приветствия пользователя. 
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/5489ea94-034a-4833-a1f3-c985c0637021)

На странице входа нужно ввести Email и пароль пользователя, которые были заданы им при регистрации.
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/0b959180-20cb-424b-955e-8566b3891aa0)

При регистрации пользователю нужно указать свое Имя, Фамилию, Отчества, Пол, Email, телефоннный номер и два раза написать одинаковый пароль. 
 
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/2ffe8b5c-94d5-40a5-8aea-24e78195c851)

На странице с автомобилями можно увидеть все автомобили, которые зарегистрированы в системе, а так же краткую информацию о них.
 
Автомобили
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/810130ae-a57a-4088-8487-47dfed6f61de)

На странице информация об автомобиле, можно увидеть более подробную информацию об автомобиле.
 
Информация об автомобиле
На странице распознавания фото, пользователю нужно выбрать фото с его компьютера
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/e6d6200b-f793-431a-8a02-ddfb012f6c07)

Распознавание номера по фото
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/b06ea7e5-4cdf-45b5-bc58-0766056f7dcf)

Представляет фото того, как выглядит кран после выбора фотографии:
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/dee0cf32-3c2c-4ea8-97c6-43840e23e7bd)

На этой странице представлен поиск по номеру
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/5a5909fe-f900-4020-93ca-926443f6a40d)

Поиск авто
На этой странице можно увидеть страницу, которая выводит ошибку, что номер не был найден в системе и предлагает либо добавить автомобиль с таким номером, либо вернуться к поиску. 
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/f855182e-96aa-465c-b3e3-d5e8d7298abb)

Отображается найденный автомобиль, так же там можно ознакомиться с контактами владельца и оставить комментарий о нем и его автомобиле.
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/3bcb817b-9fe2-4150-a144-7b8c504d78cd)

Страница для отображения и обновления данных о пользовательском аккаунте.
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/1a145012-36e0-47db-ad83-aad76b03c824)
Представлена страница с личными автомобиля пользователя, от сюда можно перейти на изменение данных своего автомобиля, а также вовсе удаление его.
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/1797d560-100d-4be1-ac3a-654ddda855eb)

Возможность изменения данных о личном автомобиле
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/a9e6babb-bc1e-4a27-86a5-63c1d18d6703)

Страница с добавлением нового автомобиля
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/44c6a71c-af83-4324-b465-47e32fd1c856)


В близи как выглядят отзывы и их добавление.
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/97a492ca-251c-46da-8e10-043e889e3c09)


Диаграмма вариантов использования 

Диаграмма рассчитана на трех пользователей: Авторизованный пользователь, неаваторизованныйц пользователь и незарегестрированный пользователь. И демонстрирует какие действия доступны пользователю в данном веб-приложении с разными уровнями доступа. 
Общий вид
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/8f8988b2-8f0e-4fa0-bf6b-1fd06b4c3be8)

Часть схемы для незарегистрированного и неавторизированного пользователя: на этой схеме мы можем видеть что пользователи могут регестрироваться и авторизироваться. Если пользователь не зарегестрирован или не авторезирован, то ему доступен поиск автомобиля по номеру и распознование фотографии автомобиля, но при этом открывается страница с простым просмотром информации об автомобиле не включающие в себя отзывы и контакты других владельцев, так же такой пользователь не может добавлять/редактировать/удалять личные автомобили. 
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/bf863f79-c689-43d9-9b54-e4f4f859a685)

Часть схемы для авторизированного пользователя: для авторизованного пользователя доступны все пользовательские функции приложения.
 
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/df648738-e883-49c3-9808-0e76401ae8f2)

Диаграмма классов

Данная диаграмма классов включает в себя несколько проектов: CarConnect, CarConnectBusinessLogic, CarConnectContracts, CarConnectServer, CarConnectDataBase
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/dadacf6c-50db-4726-a8c6-718142c0cc79)

Проект CarConnect: представляет клиент для пользователя, здесь есть представления в формате cshtml и контроллер HomeController, который обрабатывает данные со страницы. Класс ApiClient позволяет формировать GET и POST запросы:  
Проект CarConnect
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/becfefab-384e-49a7-8ddb-a04920b4efc8)

Папка Controllers
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/6b126b76-fddc-43fa-a818-aca58f663ebe)

Проект CarConnectBusinessLogic
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/a4160230-76b7-43fe-a0fd-19c849a16bc1)

Папка CarRecognationLogic: содержит класс CarCheck, который является реализацией интерфейса IRecognationLogic и класс CarNumberRecognation, в котором проходят основная обработка фотографии.
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/90dcabae-ffe8-4960-98f4-eba8d4163e34)

Реализация логики: классы CarLogic, ReviewLogic, UserLogic – реализуют интерфейсы ICarLogic, IReviewLogic, IUserLogic
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/bd458ff1-ee7b-439c-8e98-2e09b46c0992)

Проект CarConnectContracts: содержит папки BindingModels, ViewModels, StrorageContracts, BusinessLogicsContracts
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/4d485ebd-4d7d-4229-98d2-3c534b314550)

Папка StorageContrcats: содержит интерфейсы связанные с запросами к базе данных
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/b9b9066f-83ba-4182-9fda-872d53876b41)

Папка BusinessLogicsContracts: содержит интерфейсы связанные с логикой программы
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/6fda6823-90f3-43ee-9ac7-78b84382cdfd)

Папка BusinessLogicsContracts
Папка Binding models: Содердит биндинг модели
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/aca3ebaf-7256-4f07-91d2-ee0962e5f25a)

Папка ViewModels: содержит ViewModels, которые будут отображаться на страницах
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/947106d5-301a-4770-bdfd-e47421f6242c)

Проект CarConnectRest: Содержит  контроллеры CarController, RecognationController, ReviewController, UserController.
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/574a7f86-a681-4829-8c77-2f10a7c18bb1)

Проект CarConnectDataBase: 
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/154ae880-fad9-4831-97a4-83759f3873fe)

Папка Implements: содержит классы реализующие интерфейсы ICarStorage, IUserStorage, IReviewStorage
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/9072c328-a0f5-456e-8969-16dce3f23ab1)

Работа с базой данный: здесь хранятся модели Car, хранящий в себе пользователя. Review, хранящий idUser, idCar. User хранящий список пользователей и автомобилей. Класс CarConnectDataBase – в котором происходит подключение к базе данных. И класс с управлением миграцией Migration.
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/1d8e48c2-f5bd-4371-80e8-3e031ac7dc7d)

Диаграмма Er
На данной диаграмме представлены данные, которые хранятся в базе данных:
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/16013b3a-9515-4f9c-9016-2c08ab400cbb)


Связи:
Один ко многим: User-Car, User-Review, Car-Review

Диаграмма последовательности

Данная диаграмма последовательности демонстрирует сквозную функциональность распознавание номера автомобиля, поиск по этому номеру и вывод страницы с информацией об автомобиле. 
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/0225ae70-c1aa-4faf-b3ff-04d7451cd022)

Левая часть: здесь можно увидеть, как пользователь взаимодействует со страницей CarSearch и страницей CarCheck, которые предоставляют пользовательский интерфейс для выбора фото из системы и распознавания номеров на нем, а также поиска по этой фотографии. Так же можно увидеть работу с контроллерами (HomeController который отсылает запросы на сервер приложения для последующей обработки).
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/3137a211-fb85-4382-9719-2116e4aabf1a)

Правая часть: здесь можно увидеть метод DetectLicensePlate, который отвечает за логику обработки изображения, так же можно заметить, что после обработки возвращается лист строк, с которым дальше идет работа в контроллерах. А также работу с бд для отображения автомобиля, который мы ищем и отзывов на него, конечный вывод использует CarViewReviewModel для отображения информации из двух сущностей базы данных, с которыми мы работаем. 
![image](https://github.com/BulatReznik/CarConnect-Pet-Project/assets/90419704/229b3a4c-2985-41a7-b3e0-89a285a848ff)

