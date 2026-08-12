---
title: "System::Net::Http::Headers::ObjectCollection класс"
linktitle: "ObjectCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::ObjectCollection класс. Представляет коллекцию объектов в C++."
type: docs
weight: 1600
url: /ru/cpp/system.net.http.headers/objectcollection/
---
## ObjectCollection class


Представляет коллекцию объектов. Экземпляры этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class ObjectCollection : public System::Collections::ObjectModel::Collection<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип объекта. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
## Методы

| Метод | Описание |
| --- | --- |
| [ObjectCollection](./objectcollection/)() | Информация RTTI. |
| [ObjectCollection](./objectcollection/)(Action\<T\>) | Создаёт новый экземпляр. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Устанавливает n‑й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |

## См. также

* Class [Collection](../../system.collections.objectmodel/collection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
