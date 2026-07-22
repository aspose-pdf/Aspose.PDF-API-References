---
title: "Aspose::Pdf::Comparison::SideBySideComparisonOptions klass"
linktitle: "SideBySideComparisonOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::SideBySideComparisonOptions-klass. Representerar en alternativklass för att jämföra dokument med sida‑vid‑sida‑utdata i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class


Representerar en alternativklass för att jämföra dokument med sida-vid-sida-utdata.

```cpp
class SideBySideComparisonOptions : public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AdditionalChangeMarks](./get_additionalchangemarks/)() const | Hämta och ange egenskapen som bestämmer om ytterligare förändringsmarkörer visas. Om den är satt visas förändringsmarkeringar som inte finns på den aktuella sidan men som finns på en annan sida. Om förändringen ligger mellan ord kan markeringen eventuellt inte placeras exakt i förhållande till mellanslagstecknet. Standardvärdet är **false**. |
| [get_ComparisonArea1](./get_comparisonarea1/)() const | Hämta och ange jämförelseområdet. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte anges tillsammans med [ExcludeTables](../), [ExcludeAreas1](../) och [ExcludeAreas2](../) alternativ. |
| [get_ComparisonArea2](./get_comparisonarea2/)() const | Hämta och ange jämförelseområdet. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte anges tillsammans med [ExcludeTables](../), [ExcludeAreas1](../) och [ExcludeAreas2](../) alternativ. |
| [get_ComparisonMode](./get_comparisonmode/)() const | Hämtar och anger ett jämförelseläge. Standardvärdet är [Comparison::ComparisonMode::IgnoreSpaces](../comparisonmode/). |
| [get_DeleteColor](./get_deletecolor/)() const | Hämtar färgen som används för att markera raderat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för raderingar i jämförelsesresultatet. |
| [get_ExcludeAreas1](./get_excludeareas1/)() const | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan anges tillsammans med [ExcludeTables](../). Detta alternativ kan inte anges tillsammans med [ComparisonArea1](../) alternativ. |
| [get_ExcludeAreas2](./get_excludeareas2/)() const | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan anges tillsammans med [ExcludeTables](../). Detta alternativ kan inte anges tillsammans med [ComparisonArea2](../) alternativ. |
| [get_ExcludeTables](./get_excludetables/)() const | Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte anges tillsammans med [ComparisonArea1](../) och [ComparisonArea2](../). Standardvärdet är **false**. |
| [get_InsertColor](./get_insertcolor/)() const | Hämtar färgen som används för att markera infogat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för insättningar i jämförelsesresultatet. |
| [set_AdditionalChangeMarks](./set_additionalchangemarks/)(bool) | Hämta och ange egenskapen som bestämmer om ytterligare förändringsmarkörer visas. Om den är satt visas förändringsmarkeringar som inte finns på den aktuella sidan men som finns på en annan sida. Om förändringen ligger mellan ord kan markeringen eventuellt inte placeras exakt i förhållande till mellanslagstecknet. Standardvärdet är **false**. |
| [set_ComparisonArea1](./set_comparisonarea1/)(const System::SharedPtr\<Rectangle\>\&) | Hämta och ange jämförelseområdet. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte anges tillsammans med [ExcludeTables](../), [ExcludeAreas1](../) och [ExcludeAreas2](../) alternativ. |
| [set_ComparisonArea2](./set_comparisonarea2/)(const System::SharedPtr\<Rectangle\>\&) | Hämta och ange jämförelseområdet. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte anges tillsammans med [ExcludeTables](../), [ExcludeAreas1](../) och [ExcludeAreas2](../) alternativ. |
| [set_ComparisonMode](./set_comparisonmode/)(Aspose::Pdf::Comparison::ComparisonMode) | Hämtar och anger ett jämförelseläge. Standardvärdet är [Comparison::ComparisonMode::IgnoreSpaces](../comparisonmode/). |
| [set_DeleteColor](./set_deletecolor/)(const System::SharedPtr\<Color\>\&) | Anger färgen som används för att markera raderat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för raderingar i jämförelsesresultatet. |
| [set_ExcludeAreas1](./set_excludeareas1/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan anges tillsammans med [ExcludeTables](../). Detta alternativ kan inte anges tillsammans med [ComparisonArea1](../) alternativ. |
| [set_ExcludeAreas2](./set_excludeareas2/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan anges tillsammans med [ExcludeTables](../). Detta alternativ kan inte anges tillsammans med [ComparisonArea2](../) alternativ. |
| [set_ExcludeTables](./set_excludetables/)(bool) | Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte anges tillsammans med [ComparisonArea1](../) och [ComparisonArea2](../). Standardvärdet är **false**. |
| [set_InsertColor](./set_insertcolor/)(const System::SharedPtr\<Color\>\&) | Anger färgen som används för att markera infogat innehåll under en sida‑vid‑sida‑jämförelse. Denna egenskap definierar den visuella representationen för insättningar i jämförelsesresultatet. |
| [SideBySideComparisonOptions](./sidebysidecomparisonoptions/)() | Skapar en instans av klassen [SideBySideComparisonOptions](./). |
## Se även

* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
