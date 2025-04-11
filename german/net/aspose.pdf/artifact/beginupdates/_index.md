---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Artifact-Methode. Beginnen Sie mit verzögerten Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden Artefaktoperatoren jedes Mal geändert, wenn die Artefakteigenschaft geändert wird. Dies führt dazu, dass der Seiteninhalt jedes Mal geändert wird, wenn das Artefakt geändert wird. Um diesen Effekt zu vermeiden, setzen Sie alle Artefaktupdates zwischen den Aufrufen von StartUpdates/SaveUpdates. Dies ermöglicht es, den Seiteninhalt nur einmal zu ändern.
type: docs
weight: 230
url: /de/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates-Methode

Beginnen Sie mit verzögerten Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden Artefaktoperatoren jedes Mal geändert, wenn die Artefakteigenschaft geändert wird. Dies führt dazu, dass der Seiteninhalt jedes Mal geändert wird, wenn das Artefakt geändert wird. Um diesen Effekt zu vermeiden, setzen Sie alle Artefaktupdates zwischen den Aufrufen von StartUpdates/SaveUpdates. Dies ermöglicht es, den Seiteninhalt nur einmal zu ändern.

```csharp
public void BeginUpdates()
```

## Beispiele

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Siehe auch

* Klasse [Artifact](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)