---
title: "Page.Resources"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Page property. يحصل على موارد الصفحة. كائن Resources يحتوي على مجموعات من الصور والنماذج والخطوط. Resources"
type: docs
weight: 240
url: /ar/net/aspose.pdf/page/resources/
---
## Page.Resources property

يحصل على موارد الصفحة. كائن Resources يحتوي على مجموعات من الصور والنماذج والخطوط. `Resources`

```csharp
public Resources Resources { get; }
```

## أمثلة

يوضح المثال عملية المسح عبر صور الصفحة:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### انظر أيضًا

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


