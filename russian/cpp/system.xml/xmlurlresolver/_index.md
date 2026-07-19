---
title: "System::Xml::XmlUrlResolver класс"
linktitle: "XmlUrlResolver"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlUrlResolver класс. Разрешает внешние XML-ресурсы, указанные Uniform Resource Identifier (URI), в C++."
type: docs
weight: 4100
url: /ru/cpp/system.xml/xmlurlresolver/
---
## XmlUrlResolver class


Разрешает внешние XML‑ресурсы, указанные унифицированным идентификатором ресурса (URI).

```cpp
class XmlUrlResolver : public System::Xml::XmlResolver
```

## Методы

| Метод | Описание |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Отображает URI на объект, содержащий фактический ресурс. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Разрешает абсолютный URI из базового и относительного URI. |
| [set_CachePolicy](./set_cachepolicy/)(const SharedPtr\<Net::Cache::RequestCachePolicy\>\&) | Устанавливает политику кэширования для базового объекта WebRequest. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Устанавливает учетные данные, используемые для аутентификации веб‑запросов. |
| [set_Proxy](./set_proxy/)(const SharedPtr\<Net::IWebProxy\>\&) | Устанавливает сетевой прокси для базового объекта WebRequest. |
| [XmlUrlResolver](./xmlurlresolver/)() | Инициализирует новый экземпляр класса [XmlUrlResolver](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlResolver](../xmlresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
