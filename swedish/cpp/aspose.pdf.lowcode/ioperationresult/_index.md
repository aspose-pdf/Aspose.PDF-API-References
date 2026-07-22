---
title: "Aspose::Pdf::LowCode::IOperationResult class"
linktitle: "IOperationResult"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::IOperationResult class. Allmänt gränssnitt för operationresultat som definierar gemensamma metoder som konkreta plugin-operationresultat ska implementera i C++."
type: docs
weight: 3800
url: /sv/cpp/aspose.pdf.lowcode/ioperationresult/
---
## IOperationResult class


Allmänt gränssnitt för resultat av operation som definierar gemensamma metoder som konkreta plugin‑operationsresultat ska implementera.

```cpp
class IOperationResult : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_Data](./get_data/)() | Hämtar rådata. |
| virtual [get_IsFile](./get_isfile/)() | Indikerar om resultatet är en sökväg till en utdatafil. |
| virtual [get_IsStream](./get_isstream/)() | Anger om resultatet är en utmatningsström. |
| virtual [get_IsString](./get_isstring/)() | Anger om resultatet är en textsträng. |
| virtual [ToFile](./tofile/)() | Försöker konvertera resultatet till filen. |
| virtual [ToStream](./tostream/)() | Försöker konvertera resultatet till strömobjektet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
