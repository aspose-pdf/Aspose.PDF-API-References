---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل وضع استخدام مساحة الهوامش أثناء التحويل (مثل HTML، EPUB إلخ)، يحدد معالجة تعليمات التنسيق المستورد المتعلقة باستخدام الهوامش."
type: docs
weight: 2800
url: /ar/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

يمثل وضع استخدام مساحة الهوامش أثناء التحويل (مثل HTML، EPUB إلخ)، يحدد معالجة تعليمات التنسيق المستورد المتعلقة باستخدام الهوامش.

## الحقول

| حقل | الوصف |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | هذا الوضع يمنع تمامًا استخدام مساحة الهوامش، لذا لن يستخدم المحول مساحة الهوامش أبدًا في العرض، حتى إذا كان CSS أو تنسيق المستند المصدر يسمح بذلك أو يتطلبه. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | في هذا الوضع يلتزم المحول بتنسيق المستند المستورد (مثلاً CSS للـ HTML المستورد) في استخدام مساحة الهوامش. لذا، إذا كان تنسيق المستند المستورد يتطلب استخدام مساحة الهوامش للعرض، سيسمح المحول بذلك. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

هذا الوضع يمنع تمامًا استخدام مساحة الهوامش، لذا لن يستخدم المحول مساحة الهوامش أبدًا في العرض، حتى إذا كان CSS أو تنسيق المستند المصدر يسمح بذلك أو يتطلبه.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

في هذا الوضع يلتزم المحول بتنسيق المستند المستورد (مثلاً CSS للـ HTML المستورد) في استخدام مساحة الهوامش. لذا، إذا كان تنسيق المستند المستورد يتطلب استخدام مساحة الهوامش للعرض، سيسمح المحول بذلك.
