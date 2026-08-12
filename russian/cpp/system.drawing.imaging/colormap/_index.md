---
title: "System::Drawing::Imaging::ColorMap class"
linktitle: "ColorMap"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Imaging::ColorMap class. Представляет карту для преобразования цветов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведет к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.drawing.imaging/colormap/
---
## ColorMap class


Представляет карту для преобразования цветов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведет к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ColorMap : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_NewColor](./get_newcolor/)() const | Возвращает новый объект [Color](../../system.drawing/color/), представляющий цвет, в который нужно преобразовать. |
| [get_OldColor](./get_oldcolor/)() const | Возвращает старый объект [Color](../../system.drawing/color/), представляющий цвет, который нужно преобразовать. |
| [set_NewColor](./set_newcolor/)(const Color\&) | Устанавливает новый объект [Color](../../system.drawing/color/), представляющий цвет, в который нужно преобразовать. |
| [set_OldColor](./set_oldcolor/)(const Color\&) | Устанавливает старый объект [Color](../../system.drawing/color/), представляющий цвет, который нужно преобразовать. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
