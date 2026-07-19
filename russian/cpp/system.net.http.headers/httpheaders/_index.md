---
title: "Класс System::Net::Http::Headers::HttpHeaders"
linktitle: "HttpHeaders"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::Http::Headers::HttpHeaders. Коллекция HTTP‑заголовков. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 700
url: /ru/cpp/system.net.http.headers/httpheaders/
---
## HttpHeaders class


Коллекция HTTP‑заголовков. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpHeaders : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Collections::Generic::IEnumerable<System::String>>>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Проверяет новую пару имя‑значения и добавляет её в текущую коллекцию. |
| [Add](./add/)(String, String) | Проверяет новую пару имя‑значение и добавляет её в текущую коллекцию. |
| virtual [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) | Объединяет указанный экземпляр класса HttpHeaders с текущим. |
| [AddParsedValue](./addparsedvalue/)(String, System::SharedPtr\<Object\>) | Получает заголовок по указанному имени и добавляет разобранное значение к заголовку. |
| [Clear](./clear/)() | Удаляет все элементы из коллекции. |
| [Contains](./contains/)(String) |  |
| [ContainsParsedValue](./containsparsedvalue/)(String, System::SharedPtr\<Object\>) | Проверяет, содержит ли заголовок указанное значение. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель. |
| [GetHeaderString](./getheaderstring/)(String) | Возвращает строковое представление значений по указанному имени заголовка. |
| [GetHeaderString](./getheaderstring/)(String, System::SharedPtr\<Object\>) | Возвращает строковое представление значений по указанному имени заголовка. |
| [GetHeaderStrings](./getheaderstrings/)() | Возвращает коллекцию, содержащую строковые представления значений заголовков. |
| [GetParsedValues](./getparsedvalues/)(String) | Возвращает разобранные значения по указанному имени заголовка. |
| [GetValues](./getvalues/)(String) | Возвращает соответствующие значения по указанному имени. |
| static [ParsedValuesAsList](./parsedvaluesaslist/)(const System::SharedPtr\<Object\>) | Преобразует разобранные значения в список. |
| [Remove](./remove/)(String) | Пытается удалить элемент по указанному имени. |
| [RemoveParsedValue](./removeparsedvalue/)(String, System::SharedPtr\<Object\>) | Получает заголовок по указанному имени и удаляет разобранное значение из заголовка. |
| [SetConfiguration](./setconfiguration/)(System::SharedPtr\<Collections::Generic::Dictionary\<String, System::SharedPtr\<HttpHeaderParser\>\>\>, System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) |  |
| [SetOrRemoveParsedValue](./setorremoveparsedvalue/)(String, System::SharedPtr\<Object\>) | Получает заголовок по указанному имени и задаёт или удаляет его значение. Значение заголовка будет удалено, когда параметр 'value' равен nullptr, иначе будет установлено разобранное значение. |
| [SetParsedValue](./setparsedvalue/)(String, System::SharedPtr\<Object\>) | Получает заголовок по указанному имени и задаёт заголовку разобранное значение. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, String) | Пытается добавить новую пару имя‑значение в текущую коллекцию. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Добавляет коллекцию пар имя‑значение в текущую коллекцию. |
| [TryGetValues](./trygetvalues/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) | Пытается получить соответствующие значения по указанному имени. |
| [TryParseAndAddValue](./tryparseandaddvalue/)(String, String) | Пытается разобрать указанное значение и добавить его к значениям заголовка. |
## См. также

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
