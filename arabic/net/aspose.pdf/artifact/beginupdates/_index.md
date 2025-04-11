---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: طريقة Artifact. بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء تغييرات متعددة على نفس العنصر لتحسين الأداء. عادةً ما يتم تغيير مشغلات العنصر في أي وقت يتم فيه تغيير خاصية العنصر. هذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير العنصر. لتجنب هذا التأثير، ضع جميع تحديثات العنصر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط.
type: docs
weight: 230
url: /ar/net/aspose.pdf/artifact/beginupdates/
---
## طريقة Artifact.BeginUpdates

ابدأ التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء تغييرات متعددة على نفس العنصر لتحسين الأداء. عادةً ما يتم تغيير مشغلات العنصر في أي وقت يتم فيه تغيير خاصية العنصر. هذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير العنصر. لتجنب هذا التأثير، ضع جميع تحديثات العنصر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط.

```csharp
public void BeginUpdates()
```

## أمثلة

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### انظر أيضًا

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)