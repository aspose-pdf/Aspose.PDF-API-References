---
title: "System::Drawing::Drawing2D::RegionData class"
linktitle: "RegionData"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Drawing::Drawing2D::RegionData. Содержит данные, определяющие область. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1300
url: /ru/cpp/system.drawing.drawing2d/regiondata/
---
## RegionData class


Содержит данные, определяющие область. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class RegionData : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Data](./get_data/)() | Возвращает массив байтов, содержащий данные, определяющие область. |
| [RegionData](./regiondata/)(const ArrayPtr\<uint8_t\>\&) | Создаёт новый экземпляр класса [RegionData](./) и инициализирует его указанными данными. |
| [set_Data](./set_data/)(const ArrayPtr\<uint8_t\>\&) | Устанавливает данные области для текущего объекта. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
