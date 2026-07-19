---
title: "System::Net::Http::Headers::AuthenticationHeaderValue класс"
linktitle: "AuthenticationHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::AuthenticationHeaderValue класс. Представляет значения заголовков ''Authorization'', ''ProxyAuthorization'', ''WWW-Authenticate'' и ''Proxy-Authenticate''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.net.http.headers/authenticationheadervalue/
---
## AuthenticationHeaderValue class


Представляет значения заголовков 'Authorization', 'ProxyAuthorization', 'WWW-Authenticate' и 'Proxy-Authenticate'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class AuthenticationHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [AuthenticationHeaderValue](./authenticationheadervalue/)(String) | Конструктор. |
| [AuthenticationHeaderValue](./authenticationheadervalue/)(String, String) | Конструктор. |
| [Clone](./clone/)() override | Информация RTTI. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Parameter](./get_parameter/)() | Получает учётные данные, содержащие информацию об аутентификации. |
| [get_Scheme](./get_scheme/)() | Информация RTTI. |
| static [GetAuthenticationLength](./getauthenticationlength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Разбирает указанную строку и возвращает последний индекс строкового представления. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [AuthenticationHeaderValue](./). |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) | Попытка преобразовать переданную строку в экземпляр класса [AuthenticationHeaderValue](./). |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
