---
title: "Aspose::Pdf::Forms::BarcodeField klass"
linktitle: "BarcodeField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::BarcodeField klass. Klass som representerar ett streckkodsfält i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.forms/barcodefield/
---
## BarcodeField class


Klassen representerar streckkodsfält.

```cpp
class BarcodeField : public Aspose::Pdf::Forms::TextBoxField
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BarcodeField](./barcodefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Initierar en ny instans av klassen [BarcodeField](./). |
| [BarcodeField](./barcodefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Initierar en ny instans av klassen [BarcodeField](./). |
| [get_Caption](./get_caption/)() | Hämtar rubriken för streckkodobjektet. |
| [get_ECC](./get_ecc/)() | Hämtar ett heltalsvärde som representerar felkorrigeringskoefficienten. För PDF417 ska det vara från 0 till 8. För QRCode ska det vara från 0 till 3 (0 för 'L', 1 för 'M', 2 för 'Q' och 3 för 'H'). |
| [get_Resolution](./get_resolution/)() | Hämtar upplösningen, i punkter per tum (dpi), som streckkodobjektet renderas med. |
| [get_Symbology](./get_symbology/)() | Anger vilken streckkod- eller glyfteknik som ska användas för denna annotation, se [Symbology](../symbology/) för detaljer. |
| [get_XSymHeight](./get_xsymheight/)() | Hämtar det vertikala avståndet mellan två streckkodmoduler, mätt i pixlar. Förhållandet XSymHeight/XSymWidth ska vara ett heltal. För PDF417 är det accepterade förhållandets intervall från 1 till 4. För QRCode och DataMatrix ska detta förhållande alltid vara 1. |
| [get_XSymWidth](./get_xsymwidth/)() | Hämtar det horisontella avståndet, i pixlar, mellan två streckkodmoduler. |
## Se även

* Class [TextBoxField](../textboxfield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
