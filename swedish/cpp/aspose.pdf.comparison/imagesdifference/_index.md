---
title: "Aspose::Pdf::Comparison::ImagesDifference klass"
linktitle: "ImagesDifference"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::ImagesDifference klass. Representerar resultatklassen för jämförelse av två PDF‑sidor i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class


Representerar resultatklassen för jämförelse av två PDF‑sidor.

```cpp
class ImagesDifference : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DifferenceToImage](./differencetoimage/)(const System::SharedPtr\<Color\>\&, const System::SharedPtr\<Color\>\&) | Konverterar skillnadsarrayen till en bitmap‑bild med de angivna färgerna. |
| [Dispose](./dispose/)() override | Utför eventuella nödvändiga städningsoperationer innan objektet förstörs. |
| [get_Difference](./get_difference/)() const | Hämtar skillnadsarrayen. Denna array liknar den ursprungliga bilddataarrayen som erhålls som ett resultat av LockBits‑metoden. |
| [get_Height](./get_height/)() const | Höjden på skillnaden. |
| [get_SourceImage](./get_sourceimage/)() const | Hämtar bilden av den första jämförda sidan. Bilden har pixelformatet 24bpp. |
| [get_Stride](./get_stride/)() const | Radsteget för skillnadsbildens data. |
| [GetDestinationImage](./getdestinationimage/)() | Returnerar en ny bitmap som representerar destinationsbilden genom att applicera skillnadsarrayen på källbilden. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
