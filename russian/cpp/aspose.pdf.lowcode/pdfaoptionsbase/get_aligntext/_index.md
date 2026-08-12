---
title: "Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText метод"
linktitle: "get_AlignText"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText метод. Возвращает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста во время процесса конвертации PDF/A в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.lowcode/pdfaoptionsbase/get_aligntext/
---
## PdfAOptionsBase::get_AlignText method


Возвращает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста во время процесса конвертации PDF/A.

```cpp
bool Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText()
```

## Примечания


**true**

если выравнивание текста изменилось и требуются дополнительные действия для его восстановления; в противном случае, **false**

.

Когда установлено в **true**

, процесс конвертации попытается восстановить исходные границы сегментов текста. Для большинства документов нет необходимости изменять это свойство от значения по умолчанию **false**

значение, так как выравнивание текста не меняется во время процесса конвертации по умолчанию.
## См. также

* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
