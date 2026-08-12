---
title: "Aspose::Pdf::WarningType-enum"
linktitle: "WarningType"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::WarningType-enum. Enum som representerar varningstyp i C++."
type: docs
weight: 27300
url: /sv/cpp/aspose.pdf/warningtype/
---
## WarningType enum


Enum representerade varningstyp.

```cpp
enum class WarningType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| SourceFileCorruption | 0 | Filen är skadad. |
| DataLoss | 1 | Text/diagram/bild eller annan data saknas helt från antingen dokumentträdet efter inläsning, eller det skapade dokumentet efter sparning. |
| MajorFormattingLoss | 2 | Stora formateringsförluster jämfört med originaldokumentet. Detta gäller situationer där formateringsförlusten är betydande men datan fortfarande finns kvar. |
| MinorFormattingLoss | 3 | Mindre formateringsförluster jämfört med originaldokumentet. Detta är för mindre förluster av noggrannhet. |
| CompatibilityIssue | 4 | Känt problem som kommer att förhindra att dokumentet öppnas av vissa användaragenter, eller tidigare versioner av användaragenter. |
| InvalidInputStreamType | 5 | Ogiltig inmatningsströmtyp. |
| UnexpectedContent | 99 | Filen har oväntat innehåll. |

## Se även

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
