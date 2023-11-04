# Тестовое задание на вакансию DevOps.
----

###Данный проект является решением тестового задания на вакансию DevOps'а, которым поделился со мной мой товарищ, когда пробовался устроится в один крупный и известный банк нашей страны.

----

##Задание 

Даны три машины: 
  *А* - машина, которая выполняет функцию Ansible-мастер и отсылает команды другим.
  *В* и *С* - две машины, которые выступают в качестве серверов.

Задачи:
1. На "*В*" отключить авторизацию по паролю.
2. На "*В*" добавить пользователя <b>*DevOps*</b>, настроить авторизацию по ключам и предоставить ему доступ "*sudo*" без пароля.
3. На "*В*" установить PostgreSQL, создать БД *myapp* и *myauth*. Добавить пользователя *developer* и дать доступ к БД: *myapp* - на запись и чтение, *myauth* - на чтение.
4. Настроить доступ пользователя *developer* только с сервера "*С*".
5. Проверка выполнения запроса с сервера "*С*" к PostgresSQL под *developer*.
6. На "*В*" и "*С*" можно зайти только с "*А*". При этом PostrgesSQL доступен только "*С*".

<b>НА МАШИНЫ "В" И "С" ДО ВЫПОЛНЕНИЯ ВСЕХ ЗАДАЧ КАТЕГОРИЧЕСКИ НЕЛЬЗЯ ЗАХОДИТЬ, ВЫПОЛНИТЬ ИСКЛЮЧИТЕЛЬНО ЧЕРЕЗ ANSIBLE!!!
