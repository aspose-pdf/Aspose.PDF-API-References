---
title: "System::Net::Cookie класс"
linktitle: "Cookie"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Cookie класс. Представляет HTTP‑куки. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.net/cookie/
---
## Cookie class


Представляет HTTP‑куки. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Cookie : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() | Создаёт копию текущего экземпляра. |
| [Cookie](./cookie/)() | Создаёт новый экземпляр. |
| [Cookie](./cookie/)(String, String) | Создаёт новый экземпляр. |
| [Cookie](./cookie/)(String, String, String) | Создаёт новый экземпляр. |
| [Cookie](./cookie/)(String, String, String, String) | Создаёт новый экземпляр. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Comment](./get_comment/)() const | Получает значение атрибута 'Comment'. |
| [get_CommentUri](./get_commenturi/)() const | Получает значение атрибута 'CommentURL'. |
| [get_Discard](./get_discard/)() const | Получает значение атрибута 'Discard'. |
| [get_Domain](./get_domain/)() const | Получает значение атрибута 'Domain'. |
| [get_DomainImplicit](./get_domainimplicit/)() | Получает значение, указывающее, является ли домен неявным. |
| [get_DomainKey](./get_domainkey/)() const | Возвращает ключ домена. |
| [get_Expired](./get_expired/)() | Получает значение, указывающее, истекло ли время действия cookie. |
| [get_Expires](./get_expires/)() | Получает значение атрибута 'Expires'. |
| [get_HttpOnly](./get_httponly/)() const | Получает значение атрибута 'HttpOnly'. |
| [get_Name](./get_name/)() const | Получает имя cookie. |
| [get_Path](./get_path/)() const | Получает значение атрибута 'Path'. |
| [get_Plain](./get_plain/)() const | Возвращает значение, указывающее, является ли спецификация cookie 'Plain'. |
| [get_Port](./get_port/)() const | Получает значение атрибута 'Port'. |
| [get_PortList](./get_portlist/)() const | Возвращает коллекцию значений атрибута 'Port'. |
| [get_Secure](./get_secure/)() const | Получает значение атрибута 'Secure'. |
| [get_TimeStamp](./get_timestamp/)() const | Возвращает время создания cookie. |
| [get_Value](./get_value/)() const | Получает значение cookie. |
| [get_Variant](./get_variant/)() const | Получает спецификацию cookie. |
| [get_Version](./get_version/)() const | Получает значение атрибута '[Version](../../system/version/)' |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [InternalSetName](./internalsetname/)(String) | Этот метод вызывается другими методами для установки имени метода. |
| [set_Comment](./set_comment/)(String) | Устанавливает значение атрибута 'Comment'. |
| [set_CommentUri](./set_commenturi/)(System::SharedPtr\<Uri\>) | Устанавливает значение атрибута 'CommentURL'. |
| [set_Discard](./set_discard/)(bool) | Устанавливает значение атрибута 'Discard'. |
| [set_Domain](./set_domain/)(String) | Устанавливает значение атрибута 'Domain'. |
| [set_DomainImplicit](./set_domainimplicit/)(bool) | Устанавливает значение, указывающее, является ли домен неявным. |
| [set_Expired](./set_expired/)(bool) | Устанавливает значение, указывающее, истекло ли время действия cookie. |
| [set_Expires](./set_expires/)(DateTime) | Устанавливает значение атрибута 'Expires'. |
| [set_HttpOnly](./set_httponly/)(bool) | Устанавливает значение атрибута 'HttpOnly'. |
| [set_Name](./set_name/)(String) | Устанавливает имя cookie. |
| [set_Path](./set_path/)(String) | Устанавливает значение атрибута 'Path'. |
| [set_Port](./set_port/)(String) | Устанавливает значение атрибута 'Port'. |
| [set_Secure](./set_secure/)(bool) | Устанавливает значение атрибута 'Secure'. |
| [set_Value](./set_value/)(String) | Устанавливает значение cookie. |
| [set_Variant](./set_variant/)(CookieVariant) | Устанавливает спецификацию cookie. |
| [set_Version](./set_version/)(int32_t) | Устанавливает значение атрибута '[Version](../../system/version/)'. |
| [ToServerString](./toserverstring/)() | Сериализует текущий экземпляр в строковое представление. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| [VerifySetDefaults](./verifysetdefaults/)(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) | Проверяет и устанавливает значения атрибутов по умолчанию. |
## Поля

| Поле | Описание |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Имя атрибута 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Имя атрибута 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Имя атрибута 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Имя атрибута 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Разделитель, используемый для разделения имени и значения атрибута. |
| static [ExpiresAttributeName](./expiresattributename/) | Имя атрибута 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Имя атрибута 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Имя атрибута 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Информация RTTI. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Строковое представление максимальной поддерживаемой версии. |
| static [PathAttributeName](./pathattributename/) | Имя атрибута 'Path'. |
| static [PortAttributeName](./portattributename/) | Имя атрибута 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Массив, содержащий разделители для значений атрибута 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | Символ, используемый для обрамления частей атрибута. |
| static [ReservedToName](./reservedtoname/) | Значение, зарезервированное для имени cookie. |
| static [ReservedToValue](./reservedtovalue/) | Значение, зарезервированное для значения cookie. |
| static [SecureAttributeName](./secureattributename/) | Имя атрибута 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Разделитель атрибутов. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Префикс имен специальных атрибутов. |
| static [VersionAttributeName](./versionattributename/) | Имя атрибута '[Version](../../system/version/)'. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
