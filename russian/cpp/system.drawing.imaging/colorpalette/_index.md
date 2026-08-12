---
title: "System::Drawing::Imaging::ColorPalette class"
linktitle: "ColorPalette"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Imaging::ColorPalette class. Представляет набор 32-битных цветов ARGB, составляющих цветовую палитру. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.drawing.imaging/colorpalette/
---
## ColorPalette class


Представляет набор 32-битных цветов ARGB, составляющих цветовую палитру. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ColorPalette : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Entries](./get_entries/)() const | Возвращает массив объектов [Color](../../system.drawing/color/), представленных текущим объектом. |
| [get_Flags](./get_flags/)() const | Возвращает значение, определяющее, как следует интерпретировать цветовые значения в массиве цветов. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
