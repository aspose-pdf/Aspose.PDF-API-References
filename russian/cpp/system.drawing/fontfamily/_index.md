---
title: "Класс System::Drawing::FontFamily"
linktitle: "FontFamily"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Drawing::FontFamily. Представляет группу шрифтов, имеющих схожий базовый дизайн. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system.drawing/fontfamily/
---
## FontFamily class


Представляет группу шрифтов, имеющих схожий базовый дизайн. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class FontFamily : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() | Возвращает копию текущего объекта [FontFamily](./). |
| [Dispose](./dispose/)() | Освобождает все ресурсы операционной системы, полученные текущим объектом. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Определяет, являются ли текущий и указанный объекты идентичными. |
| [FontFamily](./fontfamily/)(const String\&) | Создаёт новый экземпляр класса [FontFamily](./), представляющий семейство шрифтов с указанным именем. |
| [FontFamily](./fontfamily/)(const String\&, const SharedPtr\<Text::FontCollection\>\&) | Создаёт новый экземпляр [FontFamily](./) в указанной FontCollection с указанным именем. |
| [FontFamily](./fontfamily/)(Text::GenericFontFamilies) | Создаёт новый экземпляр [FontFamily](./) из указанного общего семейства шрифтов. |
| static [get_Families](./get_families/)() | Возвращает массив, содержащий все объекты [FontFamily](./), связанные с текущим графическим контекстом. |
| static [get_GenericMonospace](./get_genericmonospace/)() | Возвращает объект [FontFamily](./), представляющий общее моноширинное семейство шрифтов. |
| static [get_GenericSansSerif](./get_genericsansserif/)() | Возвращает объект [FontFamily](./), представляющий общее семейство шрифтов без засечек. |
| static [get_GenericSerif](./get_genericserif/)() | Возвращает объект [FontFamily](./), представляющий общее семейство шрифтов с засечками. |
| [get_Name](./get_name/)() const | Возвращает название семейства шрифтов, представленного текущим объектом. |
| [GetCellAscent](./getcellascent/)(FontStyle) | Возвращает подъем ячейки семейства шрифтов, представленного текущим объектом, для указанного стиля шрифта. |
| [GetCellDescent](./getcelldescent/)(FontStyle) | Возвращает спуск ячейки семейства шрифтов, представленного текущим объектом, для указанного стиля шрифта. |
| [GetEmHeight](./getemheight/)(FontStyle) | Возвращает высоту квадрата em в единицах проектирования шрифта для указанного стиля. |
| [GetLineSpacing](./getlinespacing/)(FontStyle) | Возвращает межстрочный интервал семейства шрифтов, представленного текущим объектом, для указанного стиля шрифта. |
| [GetName](./getname/)(int) const | Возвращает название семейства шрифтов, представленного текущим объектом. |
| [IsStyleAvailable](./isstyleavailable/)(FontStyle) | Определяет, доступен ли указанный стиль шрифта. |
| virtual [~FontFamily](./~fontfamily/)() | Деструктор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
