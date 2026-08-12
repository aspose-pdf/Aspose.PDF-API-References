---
title: "Класс System::Uri"
linktitle: "Uri"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Uri. Унифицированный идентификатор ресурса. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 7000
url: /ru/cpp/system/uri/
---
## Uri class


Унифицированный идентификатор ресурса. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Uri : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [CheckHostName](./checkhostname/)(String) | Определяет тип указанного имени хоста. |
| static [CheckSchemeName](./checkschemename/)(const String\&) | Определяет, действительна ли указанная схема. |
| static [Compare](./compare/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) | Сравнивает указанные объекты [Uri](./) с использованием заданных правил сравнения. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Определяет, равны ли URI, представленные текущим и указанным объектами. |
| static [EscapeDataString](./escapedatastring/)(const String\&) | Преобразует строку в её экранированное представление. |
| static [EscapeUriString](./escapeuristring/)(const String\&) | Преобразует строку URI в её экранированное представление. |
| static [FromHex](./fromhex/)(char16_t) | Получает десятичное значение шестнадцатеричной цифры. |
| [get_AbsolutePath](./get_absolutepath/)() const | Возвращает абсолютный путь URI. |
| [get_AbsoluteUri](./get_absoluteuri/)() const | Возвращает абсолютный URI. |
| [get_Authority](./get_authority/)() const | Возвращает имя хоста и номер порта для сервера. |
| [get_DnsSafeHost](./get_dnssafehost/)() const | Возвращает незакодированное имя хоста. |
| [get_Fragment](./get_fragment/)() const | Возвращает закодированный фрагмент URI. |
| [get_Host](./get_host/)() const | Возвращает имя хоста. |
| [get_HostNameType](./get_hostnametype/)() const | Возвращает тип имени хоста. |
| [get_IdnHost](./get_idnhost/)() const | Возвращает международное доменное имя (IDN) хоста. |
| [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Определяет, является ли URI, представленный текущим объектом, абсолютным. |
| [get_IsDefaultPort](./get_isdefaultport/)() const | Определяет, имеет ли URI, представленный текущим объектом, порт по умолчанию для схемы URI. |
| [get_IsFile](./get_isfile/)() const | Определяет, является ли URI, представленный текущим объектом, файлом. |
| [get_IsLoopback](./get_isloopback/)() const | Определяет, ссылается ли URI, представленный текущим объектом, на локальный хост. |
| [get_IsUnc](./get_isunc/)() const | Определяет, является ли URI, представленный текущим объектом, UNC‑путём. |
| [get_LocalPath](./get_localpath/)() const | Возвращает представление имени файла, на которое ссылается URI, представленный текущим объектом, в виде строки операционной системы. |
| [get_OriginalString](./get_originalstring/)() const | Возвращает строку URI, переданную конструктору при создании текущего объекта. |
| [get_PathAndQuery](./get_pathandquery/)() const | Возвращает абсолютный путь и компоненты запроса URI, представленного текущим объектом, разделённые вопросительным знаком (?). |
| [get_Port](./get_port/)() const | Возвращает номер порта URI, представленного текущим объектом. |
| [get_Query](./get_query/)() const | Возвращает информацию запроса, включённую в URI, представленный текущим объектом. |
| [get_Scheme](./get_scheme/)() const | Возвращает схему URI, представленного текущим объектом. |
| [get_Segments](./get_segments/)() const | Возвращает массив строк, содержащих сегменты пути URI, представленного текущим объектом. |
| [get_UserEscaped](./get_userescaped/)() const | Определяет, была ли строка URI, переданная конструктору текущего объекта, полностью экранирована. |
| [get_UserInfo](./get_userinfo/)() const | Возвращает имя пользователя, пароль и другую пользовательскую информацию, связанную с URI, представленного текущим объектом. |
| [GetComponents](./getcomponents/)(UriComponents, UriFormat) const | Возвращает указанные компоненты URI, представленного текущим объектом, с использованием указанного экранирования. |
| [GetHashCode](./gethashcode/)() const override | Получает хеш‑код для URI. |
| [GetLeftPart](./getleftpart/)(UriPartial) | Возвращает указанную часть URI, представленного текущим объектом. |
| static [HexEscape](./hexescape/)(char16_t) | Возвращает шестнадцатеричный эквивалент указанного символа. |
| static [HexUnescape](./hexunescape/)(const String\&, int32_t\&) | Преобразует указанное шестнадцатеричное представление символа в символ. |
| [IsBaseOf](./isbaseof/)(const SharedPtr\<Uri\>\&) const | Определяет, является ли URI, представленный текущим объектом [Uri](./), базовым URI, представляемым указанным объектом [Uri](./). |
| static [IsHexDigit](./ishexdigit/)(char16_t) | Определяет, представляет ли указанный символ допустимую шестнадцатеричную цифру. |
| static [IsHexEncoding](./ishexencoding/)(const String\&, int32_t) | Определяет, закодирован ли символ в указанной строке на указанной позиции в шестнадцатеричном виде. |
| [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Указывает, является ли строка, использованная для создания этого [Uri](./), корректно сформированной и не требует дальнейшего экранирования. |
| static [IsWellFormedUriString](./iswellformeduristring/)(const String\&, UriKind) | Определяет, является ли указанная строка корректно сформированным URI. |
| [MakeRelative](./makerelative/)(const SharedPtr\<Uri\>\&) | Определяет разницу между двумя экземплярами [Uri](./). |
| [MakeRelativeUri](./makerelativeuri/)(const SharedPtr\<Uri\>\&) | Определяет разницу между URI, представленными текущим и указанным объектами [Uri](./). |
| [ToString](./tostring/)() const override | Возвращает строковое представление URI, представленного текущим объектом. |
| static [TryCreate](./trycreate/)(const String\&, UriKind, SharedPtr\<Uri\>\&) | Создаёт объект [Uri](./), представляющий указанный URI; аргумент определяет тип URI. |
| static [TryCreate](./trycreate/)(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) | Создаёт объект [Uri](./) из указанного объекта [Uri](./), представляющего базовый URI, и строкового представления относительного URI. |
| static [TryCreate](./trycreate/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) | Создаёт объект [Uri](./) из указанных базового и относительного URI. |
| static [UnescapeDataString](./unescapedatastring/)(const String\&) | Удаляет экранирование из указанной экранированной строки. |
| [Uri](./uri/)(const String\&) | Создаёт объект [Uri](./), представляющий указанный URI. |
| [Uri](./uri/)(const String\&, bool) | Создаёт объект [Uri](./), представляющий указанный URI; аргумент определяет, следует ли экранировать URI. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const String\&, bool) | Создаёт объект [Uri](./) из указанного объекта [Uri](./), представляющего базовый URI, и строкового представления относительного URI; аргумент определяет, следует ли экранировать URI. |
| [Uri](./uri/)(const String\&, UriKind) | Создаёт объект [Uri](./), представляющий указанный URI; аргумент определяет тип URI. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const String\&) | Создаёт объект [Uri](./) из указанных базового и относительного URI. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) | Создаёт объект [Uri](./) из указанных базового и относительного URI. |
## Поля

| Поле | Описание |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Указывает символы, разделяющие схему коммуникационного протокола и часть адреса [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Указывает, что [Uri](./) является указателем на файл. |
| static [UriSchemeFtp](./urischemeftp/) | Указывает, что [Uri](./) доступен через протокол передачи файлов (FTP). |
| static [UriSchemeGopher](./urischemegopher/) | Указывает, что [Uri](./) доступен через протокол Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Указывает, что [Uri](./) доступен через протокол гипертекстовой передачи (HTTP). |
| static [UriSchemeHttps](./urischemehttps/) | Указывает, что [Uri](./) доступен через защищённый протокол гипертекстовой передачи (HTTPS). |
| static [UriSchemeMailto](./urischememailto/) | Указывает, что [Uri](./) является адресом электронной почты и доступен через простой протокол передачи почты (SMTP). |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Указывает, что [Uri](./) доступен через схему NetPipe, используемую в [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Указывает, что [Uri](./) доступен через схему NetTcp, используемую в [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Указывает, что [Uri](./) является интернет‑новостной группой и доступен через протокол Network News Transport Protocol. |
| static [UriSchemeNntp](./urischemenntp/) | Указывает, что [Uri](./) является интернет‑новостной группой и доступен через протокол Network News Transport Protocol. |
## Примечания



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
This code example produces the following output:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## См. также

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
