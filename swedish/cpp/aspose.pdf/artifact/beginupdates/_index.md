---
title: "Aspose::Pdf::Artifact::BeginUpdates metod"
linktitle: "BeginUpdates"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Artifact::BeginUpdates metod. Startar försenade uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktens operatorer varje gång en egenskap ändras. Detta leder till att sidinnehållet ändras varje gång artefakten ändras. För att undvika detta placerar du alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta möjliggör att sidinnehållet ändras endast en gång i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/artifact/beginupdates/
---
## Artifact::BeginUpdates method


Starta försenade uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatorer när artefaktens egenskap ändras. Detta orsakar att sidinnehållet ändras varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta möjliggör att sidinnehållet bara ändras en gång.

```cpp
void Aspose::Pdf::Artifact::BeginUpdates()
```

## Se även

* Class [Artifact](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
