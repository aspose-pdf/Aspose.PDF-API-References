---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: OriginalFontSpecification 属性。获取一个值，指示替代是不可避免的
type: docs
weight: 20
url: /zh/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable 属性

获取一个值，指示替代是不可避免的。

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## 备注

如果由于缺少原始字体而请求替代，或者在某些任务的上下文中无法使用原始字体，则返回 true。如果用户忽略该标志并且不替代字体，则执行默认的字体替代过程。但它为用户提供了替代标准字体替代过程并为系统设置更好字体的机会。如果原始字体存在且有效，但允许用户替代，则返回 false。

### 另请参阅

* 类 [OriginalFontSpecification](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)