---
title: "Aspose::Pdf::LowCode::PdfAOptionsBase::set_AlignText метод"
linktitle: "set_AlignText"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::PdfAOptionsBase::set_AlignText метод. Устанавливает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста во время процесса конвертации PDF/A в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf.lowcode/pdfaoptionsbase/set_aligntext/
---
## PdfAOptionsBase::set_AlignText method


Устанавливает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста во время процесса конвертации PDF/A.

```cpp
void Aspose::Pdf::LowCode::PdfAOptionsBase::set_AlignText(bool value)
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
