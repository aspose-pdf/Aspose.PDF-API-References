---
title: "System::Drawing::Imaging::Encoder class"
linktitle: "Encoder"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Imaging::Encoder class. Представляет GUID, связанный с набором параметров кодировщика изображений. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.drawing.imaging/encoder/
---
## Encoder class


Представляет GUID, связанный с набором параметров кодировщика изображений. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Encoder : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Encoder](./encoder/)(const Guid\&) | Создаёт новый экземпляр класса [Encoder](./). |
| [get_Guid](./get_guid/)() const | Возвращает GUID, который определяет набор параметров кодировщика изображений, представляемый текущим объектом. |
## Поля

| Поле | Описание |
| --- | --- |
| static [ChrominanceTable](./chrominancetable/) | Экземпляр класса [Encoder](./), представляющий категорию параметра таблицы хроминанс. |
| static [ColorDepth](./colordepth/) | Экземпляр класса [Encoder](./), представляющий категорию параметра глубины цвета. |
| static [Compression](./compression/) | Экземпляр класса [Encoder](./), представляющий категорию параметра сжатия. |
| static [LuminanceTable](./luminancetable/) | Экземпляр класса [Encoder](./), представляющий категорию параметра таблицы яркости. |
| static [Quality](./quality/) | Экземпляр класса [Encoder](./), представляющий категорию параметра качества. |
| static [RenderMethod](./rendermethod/) | Экземпляр класса [Encoder](./), представляющий категорию параметра метода рендеринга. |
| static [SaveFlag](./saveflag/) | Экземпляр класса [Encoder](./), представляющий категорию параметра флага сохранения. |
| static [ScanMethod](./scanmethod/) | Экземпляр класса [Encoder](./), представляющий категорию параметра метода сканирования. |
| static [Transformation](./transformation/) | Экземпляр класса [Encoder](./), представляющий категорию параметра трансформации. |
| static [Version](./version/) | Экземпляр класса [Encoder](./), представляющий категорию параметра версии. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
