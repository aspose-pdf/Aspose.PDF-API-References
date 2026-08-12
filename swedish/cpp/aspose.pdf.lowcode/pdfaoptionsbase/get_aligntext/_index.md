---
title: "Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText metod"
linktitle: "get_AlignText"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText metod. Hämtar ett värde som indikerar om ytterligare åtgärder behövs för att bevara textjusteringen under PDF/A-konverteringsprocessen i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.lowcode/pdfaoptionsbase/get_aligntext/
---
## PdfAOptionsBase::get_AlignText method


Hämtar ett värde som indikerar om ytterligare åtgärder är nödvändiga för att bevara textjustering under PDF/A‑konverteringsprocessen.

```cpp
bool Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText()
```

## Anmärkningar


**true**

om textjusteringen ändras och ytterligare åtgärder är nödvändiga för att återställa den; annars, **false**

.

När den är inställd på **true**

, konverteringsprocessen kommer att försöka återställa de ursprungliga textsegmentgränserna. För de flesta dokument finns det inget behov av att ändra denna egenskap från standardvärdet **false**

värde, eftersom textjusteringen inte förändras under standardkonverteringsprocessen.
## Se även

* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
