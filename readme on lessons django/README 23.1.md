# project_online_shop
проект интернет-магазина, который будете дорабатываться на каждом уроке в течение всего курса Django

23.1 Права доступа (homework)

Задание 1

Продолжаем работать с проектом. Создайте группу для роли модератора и опишите необходимые доступы:

 1) может отменять публикацию продукта,
 2) может менять описание любого продукта,
 3) может менять категорию любого продукта.
+Недостающее поле признака публикации необходимо добавить таким образом, чтобы можно было определять статус продукта. Можно использовать 
BooleanField  со значением False  по умолчанию или CharField с указанием вариантов значений (choises). 
При этом по умолчанию должен быть вариант, который не предполагает публикацию продукта.

Задание 2
Реализуйте решение, которое проверит, что редактирование продукта доступно и его владельцу.
(модератору тоже можно, если прослушать видео к заданию)

* Дополнительное задание  (пока не буду делать)
Выделите отдельную роль для пользователя контент-менеджера, который может управлять публикациями в блоге. Также не забудьте реализовать проверки на то, что обычный пользователь или модератор из другого отдела не сможет ничего изменить в разделе блога.

Дополнительное задание, помеченное звездочкой, желательно, но не обязательно выполнять.

