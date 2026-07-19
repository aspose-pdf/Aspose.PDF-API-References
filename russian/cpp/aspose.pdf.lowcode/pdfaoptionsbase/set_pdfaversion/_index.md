---
title: "Aspose::Pdf::LowCode::PdfAOptionsBase::set_PdfAVersion метод"
linktitle: "set_PdfAVersion"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::PdfAOptionsBase::set_PdfAVersion метод. Устанавливает версию стандарта PDF/A, которая будет использоваться для проверки или конвертации на C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf.lowcode/pdfaoptionsbase/set_pdfaversion/
---
## PdfAOptionsBase::set_PdfAVersion method


Устанавливает версию стандарта PDF/A, которая будет использоваться для проверки или конвертации.

```cpp
void Aspose::Pdf::LowCode::PdfAOptionsBase::set_PdfAVersion(PdfAStandardVersion value)
```

## Примечания


Версия стандарта PDF/A. Это может быть одно из значений перечисления [PdfAStandardVersion](../../pdfastandardversion/).

Версия стандарта PDF/A используется для определения уровня соответствия при проверке и конвертации PDF/A. Если версия установлена в [PdfAStandardVersion::Auto](../../pdfastandardversion/), система автоматически определит подходящую версию стандарта PDF/A для проверки на основе метаданных документа. Для процесса конвертации PDF/A значение [PdfAStandardVersion::Auto](../../pdfastandardversion/) по умолчанию соответствует версии стандарта PDF/A-1b.
## См. также

* Enum [PdfAStandardVersion](../../pdfastandardversion/)
* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
