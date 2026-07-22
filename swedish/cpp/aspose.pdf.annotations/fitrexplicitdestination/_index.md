---
title: "Aspose::Pdf::Annotations::FitRExplicitDestination‑klass"
linktitle: "FitRExplicitDestination"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::FitRExplicitDestination‑klass. Representerar en explicit destination som visar sidan med dess innehåll förstorat precis så mycket att rektangeln som anges av koordinaterna vänster, botten, höger och topp får plats helt inom fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringarna är olika, används den mindre av dem, och rektangeln centreras i fönstret i den andra dimensionen. Ett null‑värde för någon av parametrarna kan leda till oförutsägbart beteende i C++."
type: docs
weight: 3700
url: /sv/cpp/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class


Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att rektangeln som specificeras av koordinaterna left, bottom, right och top får plats helt i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är olika, använd den mindre av dem och centrera rektangeln i fönstret i den andra dimensionen. Ett null‑värde för någon av parametrarna kan leda till oförutsägbart beteende.

```cpp
class FitRExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [FitRExplicitDestination](./fitrexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double, double) | Skapar lokal explicit destination. |
| [FitRExplicitDestination](./fitrexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double, double, double, double) | Skapar fjärr explicit destination. |
| [FitRExplicitDestination](./fitrexplicitdestination/)(int32_t, double, double, double, double) | Skapar fjärr explicit destination. |
| [get_Bottom](./get_bottom/)() | Hämtar den nedre vertikala koordinaten för den synliga rektangeln. |
| [get_Left](./get_left/)() | Hämtar den vänstra horisontella koordinaten för den synliga rektangeln. |
| [get_Right](./get_right/)() | Hämtar den högra horisontella koordinaten för den synliga rektangeln. |
| [get_Top](./get_top/)() | Hämtar den övre vertikala koordinaten för den synliga rektangeln. |
| [ToString](./tostring/)() const override | Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 FitR 100 200 300 400". |
## Se även

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
