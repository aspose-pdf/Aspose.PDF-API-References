---
title: BeginUpdates
second_title: Aspose.PDF لمرجع .NET API
description: بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء عدة تغييرات على نفس الأداة لتحسين الأداء. عادةً ما يتم تغيير عوامل التشغيل الأثرية في أي وقت عند تغيير خاصية الأداة. يؤدي هذا إلى تغيير محتويات الصفحة في كل مرة يتم فيها تغيير الأداة. لتجنب هذا التأثير  ضع جميع التحديثات الأثرية بين مكالمات StartUpdates / SaveUpdates . وهذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط.
type: docs
weight: 230
url: /ar/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء عدة تغييرات على نفس الأداة لتحسين الأداء. عادةً ما يتم تغيير عوامل التشغيل الأثرية في أي وقت عند تغيير خاصية الأداة. يؤدي هذا إلى تغيير محتويات الصفحة في كل مرة يتم فيها تغيير الأداة. لتجنب هذا التأثير ، ضع جميع التحديثات الأثرية بين مكالمات StartUpdates / SaveUpdates . وهذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط.

```csharp
public void BeginUpdates()
```

### أمثلة

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### أنظر أيضا

* class [Artifact](../../artifact)
* مساحة الاسم [Aspose.Pdf](../../artifact)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
