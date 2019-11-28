# Helpers

Хелперы предназначены для того, чтобы вынести часть логики (бизнес логики, или логики приложения) из контроллера.
Методы хелперов могут переиспользоваться в различных частях системы. Например Okay\Helpers\ProductsHelper::getProductList.
Также методы любого хелпера могут [расширяться из модуля](./modules/extenders.md).

Название всех сервисов хелперов заканчиваются на ключевое слово Helper.
По умолчанию все хелперы хранятся в директории Okay/Helpers/ и backend/Helpers/.
