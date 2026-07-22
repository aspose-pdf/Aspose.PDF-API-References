---
title: "Aspose::Pdf::AssemblyConstants-klass"
linktitle: "AssemblyConstants"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::AssemblyConstants-klass. Definierar de konstanter som deltar i licenskontrollen för komponenten. Dessa definierades tidigare direkt som assembly-attribut, men jag flyttade dem till en separat klass eftersom jag i .NET Compact Framework inte kan komma åt assembly-attribut. Nu använder licenskoden när den kompileras för .NET Compact Framework dessa konstanter istället för assembly-attributen i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf/assemblyconstants/
---
## AssemblyConstants class


Definierar de konstanter som deltar i licenskontrollen för komponenten. Dessa definierades tidigare direkt som sammansättningsattribut, men jag flyttade dem till en separat klass eftersom jag i .NET Compact Framework inte kan komma åt sammansättningsattribut. Nu använder licenskoden, när den kompileras för .NET Compact Framework, dessa konstanter i stället för sammansättningsattributen.

```cpp
class AssemblyConstants : public System::Object
```

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Family](./family/) |  |
| static [MicrosoftExtensionsDataIngestionMarkdigVersion](./microsoftextensionsdataingestionmarkdigversion/) |  |
| static [MicrosoftExtensionsDataIngestionVersion](./microsoftextensionsdataingestionversion/) |  |
| static [MicrosoftMLTokenizersDataCl100kBaseVersion](./microsoftmltokenizersdatacl100kbaseversion/) |  |
| static [Platform](./platform/) |  |
| static [Producer](./producer/) | Producenten av [Pdf](../)-filen. |
| static [PRODUCT](./product/) |  |
| static [Product](./product/) | Detta används av **Aspose** licenskod för att verifiera att licensen är för rätt produkt. |
| static [ReleaseDate](./releasedate/) | Detta används av **Aspose** licenskod för att kontrollera prenumerationsutgång. Du måste sätta detta till datumet då du publicerar en version eller en hotfix. |
| static [Title](./title/) |  |
| static [VERSION](./version/) |  |
| static [Version](./version/) | Versionen av assemblyn. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
