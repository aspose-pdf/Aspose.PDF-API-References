---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Artifact-metod. Starta fördröjda uppdateringar. Använd denna funktion om du behöver göra flera ändringar i samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatörer varje gång en artefaktens egenskap ändras. Detta orsakar en förändring av sidinnehållet varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta gör att sidinnehållet endast kan ändras en gång.
type: docs
weight: 230
url: /sv/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates metod

Starta fördröjda uppdateringar. Använd denna funktion om du behöver göra flera ändringar i samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatörer varje gång en artefaktens egenskap ändras. Detta orsakar en förändring av sidinnehållet varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates-anrop. Detta gör att sidinnehållet endast kan ändras en gång.

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

### Se Även

* klass [Artifact](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)