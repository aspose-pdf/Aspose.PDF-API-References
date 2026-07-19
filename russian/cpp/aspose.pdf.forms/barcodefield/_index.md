---
title: "Aspose::Pdf::Forms::BarcodeField класс"
linktitle: "BarcodeField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::BarcodeField класс. Класс, представляющий поле штрихкода в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.forms/barcodefield/
---
## BarcodeField class


Класс представляет поле штрих‑кода.

```cpp
class BarcodeField : public Aspose::Pdf::Forms::TextBoxField
```

## Методы

| Метод | Описание |
| --- | --- |
| [BarcodeField](./barcodefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Инициализирует новый экземпляр класса [BarcodeField](./). |
| [BarcodeField](./barcodefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Инициализирует новый экземпляр класса [BarcodeField](./). |
| [get_Caption](./get_caption/)() | Получает подпись объекта штрихкода. |
| [get_ECC](./get_ecc/)() | Получает целочисленное значение, представляющее коэффициент коррекции ошибок. Для PDF417 оно должно быть от 0 до 8. Для QRCode — от 0 до 3 (0 для 'L', 1 для 'M', 2 для 'Q' и 3 для 'H'). |
| [get_Resolution](./get_resolution/)() | Получает разрешение в точках на дюйм (dpi), с которым рендерится объект штрихкода. |
| [get_Symbology](./get_symbology/)() | Указывает, какая технология штрихкода или глифа будет использоваться в этой аннотации, см. [Symbology](../symbology/) для деталей. |
| [get_XSymHeight](./get_xsymheight/)() | Получает вертикальное расстояние между двумя модулями штрихкода, измеряемое в пикселях. Соотношение XSymHeight/XSymWidth должно быть целым числом. Для PDF417 допустимый диапазон соотношения от 1 до 4. Для QRCode и DataMatrix это соотношение всегда равно 1. |
| [get_XSymWidth](./get_xsymwidth/)() | Получает горизонтальное расстояние в пикселях между двумя модулями штрих‑кода. |
## См. также

* Class [TextBoxField](../textboxfield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
