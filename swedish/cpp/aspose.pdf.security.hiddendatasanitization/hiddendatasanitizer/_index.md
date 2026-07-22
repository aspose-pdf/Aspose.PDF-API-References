---
title: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer-klass"
linktitle: "HiddenDataSanitizer"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer-klass. Representerar en klass för att sanera dolda data i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/
---
## HiddenDataSanitizer class


Representerar en klass för att sanera dold data.

```cpp
class HiddenDataSanitizer : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [HiddenDataSanitizer](./hiddendatasanitizer/)(const System::SharedPtr\<HiddenDataSanitizationOptions\>\&) | Tillhandahåller funktionalitet för att sanera dolda data från ett PDF-dokument, och säkerställer att känslig eller onödig information såsom metadata, annotationer, JavaScript eller privat innehåll tas bort eller omvandlas. |
| [Sanitize](./sanitize/)(const System::SharedPtr\<Document\>\&) | Sanerar ett givet PDF-dokument genom att ta bort eller omvandla dolda data. |
| static [SanitizeAllToImages](./sanitizealltoimages/)(const System::SharedPtr\<Document\>\&, int32_t) | Ersätter sidinnehåll med bilder och tar bort annan dold data. Gör det möjligt att ta bort dold text med en bakgrundsfärg, samt text som är dold under bilder. Tar också helt bort alla interaktiva element. Dokumentet konverteras till bilder som det är, och rensas sedan på eventuell återstående dold data. Om du behöver rensa först och sedan konvertera, använd huvudklassens metod. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../)
* Library [Aspose.PDF for C++](../../)
