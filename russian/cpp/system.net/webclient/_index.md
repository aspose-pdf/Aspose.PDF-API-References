---
title: "System::Net::WebClient класс"
linktitle: "WebClient"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::WebClient. WebClient предоставляет общие методы для отправки и получения данных. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3500
url: /ru/cpp/system.net/webclient/
---
## WebClient class


[WebClient](./) provides common methods for sending and receiving data. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebClient : public System::ComponentModel::Component
```

## Методы

| Метод | Описание |
| --- | --- |
| [DownloadData](./downloaddata/)(const String\&) const | Загружает указанный ресурс в виде массива байтов. |
| [DownloadData](./downloaddata/)(const SharedPtr\<Uri\>\&) const | Загружает указанный ресурс в виде массива байтов. |
| [DownloadString](./downloadstring/)(const String\&) const | Загружает указанный ресурс в виде строки. |
| [DownloadString](./downloadstring/)(const SharedPtr\<Uri\>\&) const | Загружает указанный ресурс в виде строки. |
| [get_Encoding](./get_encoding/)() const | Получает кодировку, используемую для загрузки или выгрузки строк. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<Text::Encoding\>\&) | Устанавливает кодировку, используемую для загрузки или выгрузки строк. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | НЕ РЕАЛИЗОВАНО. |
| [WebClient](./webclient/)() | Информация RTTI. |
| [~WebClient](./~webclient/)() | Разрушает текущий экземпляр. |
## См. также

* Class [Component](../../system.componentmodel/component/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
