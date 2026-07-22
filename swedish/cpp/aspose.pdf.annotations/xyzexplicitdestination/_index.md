---
title: "Aspose::Pdf::Annotations::XYZExplicitDestination class"
linktitle: "XYZExplicitDestination"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::XYZExplicitDestination class. Representerar en explicit destination som visar sidan med koordinaterna (vänster, topp) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorade med zoomfaktorn. Ett null‑värde för någon av parametrarna vänster, topp eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoomvärde på 0 har samma betydelse som ett null‑värde i C++."
type: docs
weight: 12000
url: /sv/cpp/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class


Representerar en explicit destination som visar sidan med koordinaterna (left, top) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorade med zoomfaktorn. Ett null‑värde för någon av parametrarna left, top eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoom‑värde på 0 har samma betydelse som ett null‑värde.

```cpp
class XYZExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CreateDestination](./createdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double, bool) | Skapa destination till angiven plats på sidan med hänsyn till sidrotation om det krävs. |
| static [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Skapa destination till det övre vänstra hörnet på den angivna sidan. |
| static [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Skapa destination till angiven sida. |
| [get_Left](./get_left/)() | Hämtar vänstra horisontella koordinaten för fönstrets övre vänstra hörn. |
| [get_Top](./get_top/)() | Hämtar övre vertikala koordinaten för fönstrets övre vänstra hörn. |
| [get_Zoom](./get_zoom/)() | Hämtar zoomfaktor. |
| [ToString](./tostring/)() const override | Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 XYZ 100 200 3". |
| [XYZExplicitDestination](./xyzexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double) | Skapar lokal explicit destination. |
| [XYZExplicitDestination](./xyzexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double, double, double) | Skapar fjärr explicit destination. |
| [XYZExplicitDestination](./xyzexplicitdestination/)(int32_t, double, double, double) | Skapar fjärr explicit destination. |
## Se även

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
