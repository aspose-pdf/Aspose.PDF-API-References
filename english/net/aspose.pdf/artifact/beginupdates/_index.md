---
title: "Artifact.BeginUpdates"
linktitle: "BeginUpdates"
articleTitle: "BeginUpdates"
second_title: "Aspose.PDF for .NET"
description: "Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed ..."
type: docs
weight: 140
url: "/net/aspose.pdf/artifact/beginupdates/"
product_version: "26.9.0"
---
## BeginUpdates() {#beginupdates}

Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. 
 Usually artifact operators are changed anytime when artifact property was changed. This causes changing of page contents
 everytime when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls.
 This allows to change page contents only once.

```csharp
public void BeginUpdates()
```

### See Also

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

