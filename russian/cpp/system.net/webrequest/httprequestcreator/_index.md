---
title: "System::Net::WebRequest::HttpRequestCreator класс"
linktitle: "HttpRequestCreator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::WebRequest::HttpRequestCreator класс. Создаёт экземпляры класса WebRequest. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3900
url: /ru/cpp/system.net/webrequest/httprequestcreator/
---
## HttpRequestCreator class


Создаёт экземпляры класса WebRequest. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpRequestCreator : public System::Net::IWebRequestCreate
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Create](./create/)(System::SharedPtr\<Uri\>) | Создаёт новый экземпляр класса WebRequest, используя указанный URI. |
## См. также

* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
