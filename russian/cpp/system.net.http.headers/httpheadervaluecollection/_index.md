---
title: "System::Net::Http::Headers::HttpHeaderValueCollection класс"
linktitle: "HttpHeaderValueCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::HttpHeaderValueCollection класс. Представляет коллекцию значений заголовков. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 800
url: /ru/cpp/system.net.http.headers/httpheadervaluecollection/
---
## HttpHeaderValueCollection class


Представляет коллекцию значений заголовков. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class HttpHeaderValueCollection : public System::Collections::Generic::ICollection<T>
```


| Параметр | Описание |
| --- | --- |
| Эта | тип значений заголовков, представленных в коллекции. |
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const T\&) override | Добавляет элемент в коллекцию. |
| [Clear](./clear/)() override | Удаляет все элементы из коллекции. |
| [Contains](./contains/)(const T\&) const override | Проверяет, присутствует ли элемент в коллекции. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int32_t) override | Копирует все элементы коллекции в существующие элементы массива. |
| [get_Count](./get_count/)() const override | Информация RTTI. |
| [get_IsReadOnly](./get_isreadonly/)() | Возвращает значение, указывающее, является ли текущая коллекция только для чтения. |
| [get_IsSpecialValueSet](./get_isspecialvalueset/)() | Возвращает значение, указывающее, содержит ли текущая коллекция "специальное значение". |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель. |
| [GetHeaderStringWithoutSpecial](./getheaderstringwithoutspecial/)() | Возвращает строковое представление текущей коллекции без "специального значения". |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>) | Создаёт новый экземпляр. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) | Создаёт новый экземпляр. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, T) | Создаёт новый экземпляр. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) | Создаёт новый экземпляр. |
| [ParseAdd](./parseadd/)(String) | Разбирает строковое представление заголовка и добавляет его в текущую коллекцию. |
| [Remove](./remove/)(const T\&) override | Удаляет элемент из коллекции. |
| [RemoveSpecialValue](./removespecialvalue/)() | Удаляет "специальное значение". |
| [SetSpecialValue](./setspecialvalue/)() | Устанавливает "специальное значение". |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Устанавливает n‑й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| [TryParseAdd](./tryparseadd/)(String) | Пытается разобрать строковое представление заголовка и добавить его в текущую коллекцию. |

## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
