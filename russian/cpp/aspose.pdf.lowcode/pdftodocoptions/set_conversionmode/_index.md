---
title: "Метод Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode"
linktitle: "set_ConversionMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode. Позволяет управлять тем, как PDF‑документ преобразуется в документ обработки текста в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.lowcode/pdftodocoptions/set_conversionmode/
---
## PdfToDocOptions::set_ConversionMode method


Позволяет управлять тем, как документ PDF преобразуется в документ обработки текста.

```cpp
void Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode(Aspose::Pdf::LowCode::ConversionMode value)
```

## Примечания


Используйте режим [ConversionMode::TextBox](../../conversionmode/), когда полученный документ не будет сильно редактироваться дальше. Текстовые поля легко изменять, если требуется небольшое количество правок.

Используйте режим [ConversionMode::Flow](../../conversionmode/), когда выходному документу требуется дальнейшее редактирование. [Paragraphs](../../../aspose.pdf/paragraphs/) и строки текста в режиме flow позволяют легко изменять текст, однако неподдерживаемые объекты форматирования будут выглядеть хуже, чем в режиме [ConversionMode::TextBox](../../conversionmode/).
## См. также

* Enum [ConversionMode](../../conversionmode/)
* Class [PdfToDocOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
