---
title: "Artifact.BeginUpdates"
linktitle: "BeginUpdates"
articleTitle: "BeginUpdates"
second_title: "Aspose.PDF for .NET API Reference"
description: "Artifact method. Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact opera..."
type: docs
weight: 140
url: "/net/aspose.pdf/artifact/beginupdates/"
product_version: "26.9.0"
---
## Artifact.BeginUpdates method

Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. 
 Usually artifact operators are changed anytime when artifact property was changed. This causes changing of page contents
 everytime when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls.
 This allows to change page contents only once.

```csharp
public void BeginUpdates()
```

## Examples

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### See Also

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

