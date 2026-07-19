---
title: "Класс Aspose::Pdf::PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::PsLoadOptions. Представляет параметры загрузки/импорта .mht‑файла в PDF‑документ на C++."
type: docs
weight: 16100
url: /ru/cpp/aspose.pdf/psloadoptions/
---
## PsLoadOptions class


Представляет параметры загрузки/импорта .mht-файла в документ PDF.

```cpp
class PsLoadOptions : public Aspose::Pdf::LoadOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_ConvertFontsToTTF](./get_convertfontstottf/)() const | Указывает, сохранять ли шрифты, не являющиеся TrueType, в TTF. Это значительно уменьшает объём получаемого документа при конвертации PS в PDF и повышает скорость конвертации PS‑файлов с большим количеством текста в шрифтах, не являющихся TrueType, в любой формат вывода. Однако при конвертации PostSctipt‑файла в изображение наблюдается небольшое вертикальное смещение текста. |
| [get_FontsFolders](./get_fontsfolders/)() const | Получает пути к папкам шрифтов. |
| [PsLoadOptions](./psloadoptions/)() | Создаёт параметры загрузки для конвертации PostScript в PDF‑документ с пустым базовым путём. |
| [set_ConvertFontsToTTF](./set_convertfontstottf/)(bool) | Указывает, сохранять ли шрифты, не являющиеся TrueType, в TTF. Это значительно уменьшает объём получаемого документа при конвертации PS в PDF и повышает скорость конвертации PS‑файлов с большим количеством текста в шрифтах, не являющихся TrueType, в любой формат вывода. Однако при конвертации PostSctipt‑файла в изображение наблюдается небольшое вертикальное смещение текста. |
| [set_FontsFolders](./set_fontsfolders/)(const System::ArrayPtr\<System::String\>\&) | Устанавливает пути к папкам шрифтов. |
## См. также

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
