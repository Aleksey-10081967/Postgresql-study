### Что такое схема в Postgresql

Схема базы данных — это коллекция объектов базы данных, имеющая одного владельца и формирующая одно пространство имен. Две таблицы в одной и той же схеме не могут иметь одно и то же имя.

База данных содержит одну или несколько именованных схем, которые, в свою очередь, содержат таблицы. Схемы также содержат именованные объекты других видов, включая типы данных, функции и операторы. 

Одно и то же имя объекта можно свободно использовать в разных схемах, например, и schema1, и myschema могут содержать таблицы с именем mytable. 

В отличие от баз данных схемы не ограничивают доступ к данным: пользователи могут обращаться к объектам в любой схеме текущей базы данных, если им назначены соответствующие права.

Схема в БД это своего рода NAMESPACE т.е. пространство имен изолированное в рамках базы данных.

По умолчанию это схема - public.

Все пользователи по умолчанию все имеют права CREATE и USAGE в схеме public. Благодаря этому все пользователи могут подключаться к заданной базе данных и создавать объекты в её схеме public.

Чтобы убрать права по умолчанию в схеме public:

REVOKE CREATE ON SCHEMA public FROM PUBLIC; - Первое слово «public» обозначает схему, а второе означает «каждый пользователь»

По умолчанию таблицы (и другие объекты) автоматически помещаются в схему public.

Единственное, что отличает схему public от других, — это то, что она существует по умолчанию, хотя ее также можно удалить.
