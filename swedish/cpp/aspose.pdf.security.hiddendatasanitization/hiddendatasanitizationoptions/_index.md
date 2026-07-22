---
title: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizationOptions klass"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizationOptions-klass. Representerar konfigurationsalternativen för att sanera dold data i ett dokument i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/
---
## HiddenDataSanitizationOptions class


Representerar konfigurationsalternativen för att sanera dold data i ett dokument.

```cpp
class HiddenDataSanitizationOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [All](./all/)() | Skapar en ny instans av klassen [HiddenDataSanitizationOptions](./) med alla alternativ inställda för sanering. Detta inkluderar att aktivera borttagning av anteckningar, JavaScript, metadata, bilagor, sökindex, privat information, plattläggning av formulär och lager, samtidigt som alternativet för att konvertera sidor till bilder inaktiveras. Valfria konfigurationer som [ImageCompressionOptions](../) eller [ConvertPagesToImages](../) kan ändras manuellt efter att instansen erhållits, eftersom de inte är aktiva som standard. |
| [get_ConvertPagesToImages](./get_convertpagestoimages/)() const | Hämtar alternativet för att konvertera sidor till bilder. Om detta alternativ är aktiverat kommer alternativet ImageCompressionOptions att ignoreras. Alternativet måste aktiveras manuellt när metoden [All](./all/) används om det behövs. Konverteringen av sidor till bilder sker efter att den huvudsakliga dolda datan har rensats, vilket styrs av andra alternativ. |
| [get_FlattenForms](./get_flattenforms/)() const | Hämtar ett värde som indikerar om formulär i dokumentet ska plattläggas under saneringsprocessen. Plattläggning av formulär konverterar interaktiva formulärfält till statiskt innehåll, vilket gör dem icke-redigerbara eller ifyllbara. |
| [get_FlattenLayers](./get_flattenlayers/)() const | Hämtar alternativet för att plattlägga lagren i PDF-dokumentet. När det är aktiverat slås alla lager i dokumentet samman till ett enda lager, vilket tar bort deras separata struktur. Detta alternativ är användbart för att sanera dokument genom att förenkla deras innehåll och säkerställa att ingen dold data finns i lager. |
| [get_ImageCompressionOptions](./get_imagecompressionoptions/)() const | Hämtar alternativet för dokumentets bildkonvertering. Alternativet måste aktiveras manuellt när metoden [All](./all/) används om det krävs. |
| [get_ImageDpi](./get_imagedpi/)() const | Hämtar alternativet för att lösa upp sidbilder under konvertering. |
| [get_RemoveAnnotations](./get_removeannotations/)() const | Hämtar ett värde som indikerar om anteckningar ska tas bort från dokumentet. När det är aktiverat kommer alla anteckningar i dokumentet att tas bort under saneringsprocessen. Redigeringsanteckningar kommer att tillämpas. |
| [get_RemoveAttachments](./get_removeattachments/)() const | Hämtar alternativet för att ta bort alla bifogade filer från dokumentet. När det är aktiverat säkerställer det att alla bilagor i PDF-filen elimineras under saneringsprocessen. |
| [get_RemoveJavaScriptsAndActions](./get_removejavascriptsandactions/)() const | Hämtar ett värde som indikerar om JavaScript och tillhörande åtgärder ska tas bort från dokumentet. Detta alternativ är användbart för att eliminera potentiella säkerhetsrisker som införs av inbäddade skript. |
| [get_RemoveMetadata](./get_removemetadata/)() const | Hämtar ett alternativ för att ta bort metadata från dokumentet. Om det sätts till true kommer metadata såsom dokumentegenskaper och ytterligare inbäddad metadata att tas bort under saneringen. |
| [get_RemoveSearchIndexAndPrivateInfo](./get_removesearchindexandprivateinfo/)() const | Hämtar ett värde som indikerar om sökindexet och privat information ska tas bort från dokumentet. Aktiverar borttagning av inbäddade sökindex och privat data för att förbättra dokumentets säkerhet och integritet. |
| [HiddenDataSanitizationOptions](./hiddendatasanitizationoptions/)() |  |
| [set_ConvertPagesToImages](./set_convertpagestoimages/)(bool) | Ställer in alternativet för att konvertera sidor till bilder. Om detta alternativ är aktiverat kommer alternativet ImageCompressionOptions att ignoreras. Alternativet måste aktiveras manuellt när metoden [All](./all/) används om det behövs. Konverteringen av sidor till bilder sker efter att den huvudsakliga dolda datan har rensats, vilket styrs av andra alternativ. |
| [set_FlattenForms](./set_flattenforms/)(bool) | Ställer in ett värde som indikerar om formulär i dokumentet ska plattläggas under saneringsprocessen. Plattläggning av formulär konverterar interaktiva formulärfält till statiskt innehåll, vilket gör dem icke-redigerbara eller ifyllbara. |
| [set_FlattenLayers](./set_flattenlayers/)(bool) | Ställer in alternativet för att plattlägga lagren i PDF-dokumentet. När det är aktiverat slås alla lager i dokumentet samman till ett enda lager, vilket tar bort deras separata struktur. Detta alternativ är användbart för att sanera dokument genom att förenkla deras innehåll och säkerställa att ingen dold data finns i lager. |
| [set_ImageCompressionOptions](./set_imagecompressionoptions/)(const System::SharedPtr\<Aspose::Pdf::Optimization::ImageCompressionOptions\>\&) | Ställer in alternativet för dokumentets bildkonvertering. Alternativet måste aktiveras manuellt när metoden [All](./all/) används om det krävs. |
| [set_ImageDpi](./set_imagedpi/)(int32_t) | Ställer in alternativet för att lösa upp sidbilder under konvertering. |
| [set_RemoveAnnotations](./set_removeannotations/)(bool) | Ställer in ett värde som indikerar om anteckningar ska tas bort från dokumentet. När det är aktiverat kommer alla anteckningar i dokumentet att tas bort under saneringsprocessen. Redigeringsanteckningar kommer att tillämpas. |
| [set_RemoveAttachments](./set_removeattachments/)(bool) | Ställer in alternativet för att ta bort alla bifogade filer från dokumentet. När det är aktiverat säkerställer det att alla bilagor i PDF-filen elimineras under saneringsprocessen. |
| [set_RemoveJavaScriptsAndActions](./set_removejavascriptsandactions/)(bool) | Ställer in ett värde som indikerar om JavaScript och tillhörande åtgärder ska tas bort från dokumentet. Detta alternativ är användbart för att eliminera potentiella säkerhetsrisker som införs av inbäddade skript. |
| [set_RemoveMetadata](./set_removemetadata/)(bool) | Ställer in ett alternativ för att ta bort metadata från dokumentet. Om det sätts till true kommer metadata såsom dokumentegenskaper och ytterligare inbäddad metadata att tas bort under saneringen. |
| [set_RemoveSearchIndexAndPrivateInfo](./set_removesearchindexandprivateinfo/)(bool) | Ställer in ett värde som indikerar om sökindexet och privat information ska tas bort från dokumentet. Aktiverar borttagning av inbäddade sökindex och privat data för att förbättra dokumentets säkerhet och integritet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../)
* Library [Aspose.PDF for C++](../../)
