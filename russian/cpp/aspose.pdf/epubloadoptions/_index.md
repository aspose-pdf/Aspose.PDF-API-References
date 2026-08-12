---
title: "Aspose::Pdf::EpubLoadOptions класс"
linktitle: "EpubLoadOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::EpubLoadOptions класс. Содержит параметры для загрузки/импорта EPUB‑файла в PDF‑документ на C++."
type: docs
weight: 4500
url: /ru/cpp/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class


Содержит параметры для загрузки/импорта файла EPUB в PDF‑документ.

```cpp
class EpubLoadOptions : public Aspose::Pdf::LoadOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [EpubLoadOptions](./epubloadoptions/)() | Создаёт параметры загрузки по умолчанию для преобразования EPUB‑файла в PDF‑документ. Размер страницы PDF по умолчанию — A4 300 dpi 2480 × 3508. |
| [EpubLoadOptions](./epubloadoptions/)(System::Drawing::SizeF) | Создаёт параметры загрузки с указанным размером страницы. |
| [get_CustomCss](./get_customcss/)() const | Получает пользовательский CSS, применяемый при открытии EPUB‑документа. |
| [get_Margin](./get_margin/)() const | Получает ссылку на объект, представляющий информацию о полях. |
| [get_PageSize](./get_pagesize/)() const | Получает размер выходной страницы для импорта. |
| [set_CustomCss](./set_customcss/)(const System::String\&) | Устанавливает пользовательский CSS, применяемый при открытии EPUB‑документа. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Получает ссылку на объект, представляющий информацию о полях. |
## См. также

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
