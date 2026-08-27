---
title: "Artifact.BeginUpdates"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Artifact metod. Starta fördröjda uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatorer när som helst när artefaktens egenskap har ändrats. Detta orsakar förändring av sidinnehåll varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta möjliggör att sidinnehållet bara ändras en gång."
type: docs
weight: 230
url: /sv/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

Starta försenade uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatorer varje gång en artefakt‑egenskap ändras. Detta leder till att sidans innehåll ändras varje gång artefakten ändras. För att undvika detta, placera alla artefaktuppdateringar mellan anropen StartUpdates/SaveUpdates. Detta möjliggör att sidans innehåll bara ändras en gång.

```csharp
public void BeginUpdates()
```

## Exempel

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Se även

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


