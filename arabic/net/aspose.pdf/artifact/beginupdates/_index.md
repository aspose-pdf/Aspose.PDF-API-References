---
title: "Artifact.BeginUpdates"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Artifact. ابدأ التحديثات المتأخرة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء عدة تغييرات على نفس القطعة لتحسين الأداء. عادةً ما يتم تغيير مشغلي القطعة في أي وقت يتم فيه تغيير خاصية القطعة. هذا يتسبب في تغيير محتوى الصفحة في كل مرة يتم فيها تغيير القطعة. لتجنب هذا التأثير ضع جميع تحديثات القطعة بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتوى الصفحة مرة واحدة فقط."
type: docs
weight: 230
url: /ar/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

ابدأ التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة لإجراء عدة تغييرات على نفس العنصر لتحسين الأداء. عادةً ما يتم تغيير مشغلي العنصر في أي وقت يتم فيه تغيير خاصية العنصر. هذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير العنصر. لتجنب هذا التأثير ضع جميع تحديثات العنصر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط.

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


