---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل على موارد الصفحة. يحتوي كائن الموارد على مجموعات من الصور والنماذج والخطوط. الموارد
type: docs
weight: 240
url: /ar/net/aspose.pdf/page/resources/
---
## خاصية Page.Resources

تحصل على موارد الصفحة. يحتوي كائن الموارد على مجموعات من الصور والنماذج والخطوط. `Resources`

```csharp
public Resources Resources { get; }
```

## أمثلة

المثال يوضح كيفية المسح عبر صور الصفحة:

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