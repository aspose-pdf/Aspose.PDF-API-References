---
title: "Класс System::Xml::Resolvers::XmlPreloadedResolver"
linktitle: "XmlPreloadedResolver"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Resolvers::XmlPreloadedResolver. Представляет класс, используемый для предварительного заполнения кэша DTD или XML‑потоками в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml.resolvers/xmlpreloadedresolver/
---
## XmlPreloadedResolver class


Представляет класс, используемый для предварительного заполнения кэша DTD‑файлами или XML‑потоками.

```cpp
class XmlPreloadedResolver : public System::Xml::XmlResolver
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) | Добавляет массив байтов в хранилище [XmlPreloadedResolver](./) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Добавляет массив байтов в хранилище [XmlPreloadedResolver](./) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) | Добавляет поток Stream в хранилище [XmlPreloadedResolver](./) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const String\&) | Добавляет строку с предварительно загруженными данными в хранилище [XmlPreloadedResolver](./) и сопоставляет её с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется. |
| [get_PreloadedUris](./get_preloadeduris/)() | Возвращает коллекцию предварительно загруженных URI. |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Отображает URI на объект, содержащий фактический ресурс. |
| [Remove](./remove/)(const SharedPtr\<Uri\>\&) | Удаляет данные, соответствующие URI, из [XmlPreloadedResolver](./). |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Разрешает абсолютный URI из базового и относительного URI. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Устанавливает учётные данные, используемые для аутентификации базового [Net::WebRequest](../../system.net/webrequest/). |
| [SupportsType](./supportstype/)(SharedPtr\<Uri\>, const TypeInfo\&) override | Определяет, поддерживает ли резолвер другие типы, помимо Stream. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)() | Инициализирует новый экземпляр класса [XmlPreloadedResolver](./). |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(XmlKnownDtds) | Инициализирует новый экземпляр класса [XmlPreloadedResolver](./) с указанными предварительно загруженными известными DTD. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&) | Инициализирует новый экземпляр класса [XmlPreloadedResolver](./) с указанным резервным резолвером. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) | Инициализирует новый экземпляр класса [XmlPreloadedResolver](./) с указанным резервным резолвером и предварительно загруженными известными DTD. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) | Инициализирует новый экземпляр класса [XmlPreloadedResolver](./) с указанным резервным резолвером, предварительно загруженными известными DTD и сравнивателем равенства URI. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlResolver](../../system.xml/xmlresolver/)
* Namespace [System::Xml::Resolvers](../)
* Library [Aspose.PDF for C++](../../)
