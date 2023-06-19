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
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/fdf881ef-ee0a-4028-b820-94f7fdf2e10b)

На странице входа нужно ввести Email и пароль пользователя, которые были заданы им при регистрации.
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/7da841b6-05e1-41bf-bc1e-1a355e157fc1)

При регистрации пользователю нужно указать свое Имя, Фамилию, Отчества, Пол, Email, телефоннный номер и два раза написать одинаковый пароль. 
 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/5b3e246b-7e4c-43b1-9bcb-bb3ae607c562)

На странице с автомобилями можно увидеть все автомобили, которые зарегистрированы в системе, а так же краткую информацию о них.
 
Автомобили
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/5547caca-4525-44d6-b8c1-5d21e0becc37)

На странице информация об автомобиле, можно увидеть более подробную информацию об автомобиле.
 
Информация об автомобиле
На странице распознавания фото, пользователю нужно выбрать фото с его компьютера
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/5951683b-90c1-49ca-87fa-0272dd075368)
 
Распознавание номера по фото
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/f94574ba-5073-45a3-9078-f2a75c7e44e3)

Представляет фото того, как выглядит кран после выбора фотографии:
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/dee0cf32-3c2c-4ea8-97c6-43840e23e7bd)

На этой странице представлен поиск по номеру
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/02331271-3331-4ca1-93c8-4615febdfa26)
 
Поиск авто
На этой странице можно увидеть страницу, которая выводит ошибку, что номер не был найден в системе и предлагает либо добавить автомобиль с таким номером, либо вернуться к поиску. 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/a8f68b23-b7e7-4d60-bd79-346a7dcaa955)

Отображается найденный автомобиль, так же там можно ознакомиться с контактами владельца и оставить комментарий о нем и его автомобиле.
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/019e5822-b6f0-42d7-a9f7-88995969e02d)

Страница для отображения и обновления данных о пользовательском аккаунте.
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/1a145012-36e0-47db-ad83-aad76b03c824)
Представлена страница с личными автомобиля пользователя, от сюда можно перейти на изменение данных своего автомобиля, а также вовсе удаление его.
 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/716543f6-c1ba-40f2-9c46-16835937f28c)

Возможность изменения данных о личном автомобиле
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/d3673958-a2a1-46ad-b503-4c294ce64850)

Страница с добавлением нового автомобиля
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/7207b0ea-12e1-4713-bddd-f193caeb6361)

В близи как выглядят отзывы и их добавление.
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/28d8b0a5-474e-4f41-bcc3-f99e119e1aa9)

Диаграмма вариантов использования 

Диаграмма рассчитана на трех пользователей: Авторизованный пользователь, неаваторизованныйц пользователь и незарегестрированный пользователь. И демонстрирует какие действия доступны пользователю в данном веб-приложении с разными уровнями доступа. 
Общий вид
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/6b868759-3319-4a25-8fa5-8eb84dc1b086)
Часть схемы для незарегистрированного и неавторизированного пользователя: на этой схеме мы можем видеть что пользователи могут регестрироваться и авторизироваться. Если пользователь не зарегестрирован или не авторезирован, то ему доступен поиск автомобиля по номеру и распознование фотографии автомобиля, но при этом открывается страница с простым просмотром информации об автомобиле не включающие в себя отзывы и контакты других владельцев, так же такой пользователь не может добавлять/редактировать/удалять личные автомобили. 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/e6d0db49-64c7-4446-94b8-cdfe28e54378)
Часть схемы для авторизированного пользователя: для авторизованного пользователя доступны все пользовательские функции приложения.
 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/b46a927c-10f6-4215-b2ea-d6ae27dcdab3)
Диаграмма классов

Данная диаграмма классов включает в себя несколько проектов: CarConnect, CarConnectBusinessLogic, CarConnectContracts, CarConnectServer, CarConnectDataBase
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/484ba005-b428-4134-abc6-e4429d422ce6)

Проект CarConnect: представляет клиент для пользователя, здесь есть представления в формате cshtml и контроллер HomeController, который обрабатывает данные со страницы. Класс ApiClient позволяет формировать GET и POST запросы:  
Проект CarConnect
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/69ebdebb-861a-4a56-acaf-d830742c38f9)

Папка Controllers
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/6de43f20-efe8-42fc-a426-afde4e3b0dc5)
 
Проект CarConnectBusinessLogic
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/e257315e-ae2a-4ce6-922c-a6c3b1730f48)

Папка CarRecognationLogic: содержит класс CarCheck, который является реализацией интерфейса IRecognationLogic и класс CarNumberRecognation, в котором проходят основная обработка фотографии.
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/f53ad283-f7a8-4b98-89b5-727bc9af91b8)

Реализация логики: классы CarLogic, ReviewLogic, UserLogic – реализуют интерфейсы ICarLogic, IReviewLogic, IUserLogic
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/a3556377-ca1b-4f0f-b36e-71f2a6173db5)


Проект CarConnectContracts: содержит папки BindingModels, ViewModels, StrorageContracts, BusinessLogicsContracts
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/878c8bd7-2324-49b9-b545-72549af04cd5)

 
Проект CarConnectContracts
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/be6283cd-32e4-442a-9d8a-dd724d89e310)

Папка StorageContrcats: содержит интерфейсы связанные с запросами к базе данных

![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/b4fe9103-8c06-4b74-887d-3a1074a4cf08)

Папка BusinessLogicsContracts: содержит интерфейсы связанные с логикой программы
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/3a81cf86-0c27-4435-bd7d-46d63d7f55cc)

Папка BusinessLogicsContracts
Папка Binding models: Содердит биндинг модели
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/b4370b17-d271-4641-a29e-ea9a330e6cdf)

Папка ViewModels: содержит ViewModels, которые будут отображаться на страницах
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/94cfb7b8-6291-4c77-b240-8b0de3b38a6b)

Проект CarConnectRest: Содержит  контроллеры CarController, RecognationController, ReviewController, UserController.
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/03948488-4754-4905-a9e3-bc02ffeb9ac3)

Проект CarConnectDataBase: 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/6fe857d7-540b-41ff-93d5-81be8bbe43e4)

Папка Implements: содержит классы реализующие интерфейсы ICarStorage, IUserStorage, IReviewStorage
 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/3766f14d-0e66-488a-8b67-e13fc665abec)
Работа с базой данный: здесь хранятся модели Car, хранящий в себе пользователя. Review, хранящий idUser, idCar. User хранящий список пользователей и автомобилей. Класс CarConnectDataBase – в котором происходит подключение к базе данных. И класс с управлением миграцией Migration.

Рисунок 36 Работа с базой данный
 
Диаграмма Er
На данной диаграмме представлены данные, которые хранятся в базе данных:
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/6d2645ce-e69f-444c-a7b3-7c6b88962da7)

Связи:
Один ко многим: User-Car, User-Review, Car-Review

Диаграмма последовательности

Данная диаграмма последовательности демонстрирует сквозную функциональность распознавание номера автомобиля, поиск по этому номеру и вывод страницы с информацией об автомобиле. 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/b0dcd262-3a09-41cb-9612-d452b48b87ad)

Левая часть: здесь можно увидеть, как пользователь взаимодействует со страницей CarSearch и страницей CarCheck, которые предоставляют пользовательский интерфейс для выбора фото из системы и распознавания номеров на нем, а также поиска по этой фотографии. Так же можно увидеть работу с контроллерами (HomeController который отсылает запросы на сервер приложения для последующей обработки).

![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/e19a2976-fac0-4bf2-b8a0-277fb6fc98e0)
Правая часть: здесь можно увидеть метод DetectLicensePlate, который отвечает за логику обработки изображения, так же можно заметить, что после обработки возвращается лист строк, с которым дальше идет работа в контроллерах. А также работу с бд для отображения автомобиля, который мы ищем и отзывов на него, конечный вывод использует CarViewReviewModel для отображения информации из двух сущностей базы данных, с которыми мы работаем. 
![image](https://github.com/BulatReznik/CarConnect-Pet-project/assets/90419704/fe90f415-d4ff-4946-bb41-870af1e24bb8)
