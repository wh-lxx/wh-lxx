# Авторизация приложения

Токен приложения необходимо сгенерировать 1 раз.
В случае, если токен был скомпрометирован, его нужно запросить еще раз. При этом ранее выданный токен отзывается.
Владелец приложения может посмотреть актуальный `access_token` для приложения на сайте [https://dev.hh.ru/admin](https://dev.hh.ru/admin). В случае, если вы еще ни разу [не получали токен приложения](https://api.hh.ru/openapi/redoc#tag/Avtorizaciya-prilozheniya), токен отображаться не будет.

<a name="get-client-auth"></a>
## Получение токена приложения
> > !! Данный метод доступен в [OpenAPI](https://api.hh.ru/openapi/redoc#tag/Avtorizaciya-prilozheniya)