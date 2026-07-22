---
title: "Aspose::Pdf::OptimizedMemoryStream::Write method"
linktitle: "Write"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OptimizedMemoryStream::Write method. När den åsidosätts i en avledd klass, skriver den en sekvens av byte till den aktuella strömmen och förflyttar den aktuella positionen i denna ström med antalet skrivna byte i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf/optimizedmemorystream/write/
---
## OptimizedMemoryStream::Write method


När den överskrivs i en avledd klass, skriver den en sekvens av byte till den aktuella strömmen och förflyttar den aktuella positionen i denna ström med antalet skrivna byte.

```cpp
void Aspose::Pdf::OptimizedMemoryStream::Write(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::ArrayPtr\<uint8_t\>\& | En array av byte. Denna metod kopierar *count* byte från *buffer* till den aktuella strömmen. |
| förskjutning | int32_t | Det nollbaserade byte‑offsetet i *buffer* där kopieringen av byte till den aktuella strömmen ska börja. |
| count | int32_t | Antalet byte som ska skrivas till den aktuella strömmen. |
## Anmärkningar



Summan av *offset* och *count* är större än buffertens längd.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
