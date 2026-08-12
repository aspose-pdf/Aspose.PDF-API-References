---
title: "System::Drawing::Imaging::FrameDimension класс"
linktitle: "FrameDimension"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Imaging::FrameDimension класс. Предоставляет свойства, позволяющие получить размеры кадра изображения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 800
url: /ru/cpp/system.drawing.imaging/framedimension/
---
## FrameDimension class


Предоставляет свойства, позволяющие получить размеры кадра изображения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class FrameDimension : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(FrameDimensionPtr) | Определяет, является ли указанный объект [FrameDimension](./) эквивалентным текущему объекту. |
| [FrameDimension](./framedimension/)(const System::Guid\&) | Создаёт новый объект [FrameDimension](./) и инициализирует его указанным GUID. |
| [get_Guid](./get_guid/)() const | Возвращает GUID, связанный с текущим объектом. |
| static [get_Page](./get_page/)() | Возвращает размер страницы. |
| static [get_Resolution](./get_resolution/)() | Возвращает размер разрешения. |
| static [get_Time](./get_time/)() | Возвращает размер времени. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
