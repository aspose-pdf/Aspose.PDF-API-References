---
title: "System::Drawing::Text::PrivateFontCollection класс"
linktitle: "PrivateFontCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Text::PrivateFontCollection класс. Представляет собой коллекцию семейств шрифтов, предоставляемую клиентским приложением. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.drawing.text/privatefontcollection/
---
## PrivateFontCollection class


Представляет собой коллекцию семейств шрифтов, предоставляемую клиентским приложением. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class PrivateFontCollection : public System::Drawing::Text::FontCollection
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddFont](./addfont/)(const System::ArrayPtr\<uint8_t\>\&, int) | Добавляет указанный шрифт в коллекцию. |
| [AddFontFile](./addfontfile/)(const String\&) | Добавляет шрифт из указанного файла в коллекцию. |
| [get_Families](./get_families/)() override | Возвращает массив объектов [FontFamily](../../system.drawing/fontfamily/), связанных с коллекцией шрифтов, представленной текущим объектом. |
## См. также

* Class [FontCollection](../fontcollection/)
* Namespace [System::Drawing::Text](../)
* Library [Aspose.PDF for C++](../../)
