---
title: "CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable"
second_title: "Aspose.PDF for .NET API 参考"
description: "OriginalFontSpecification 属性。获取指示替换不可避免的值"
type: docs
weight: 20
url: /zh/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable property

获取一个值，指示替换是不可避免的。

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## 备注

如果因为缺少原始字体或原始字体在某些任务的上下文中无法使用而请求了替换，则返回 true。若用户忽略此标志并且未替换字体，则执行默认的字体替换过程。但这为用户提供了替代标准字体替换过程并将更好的字体设置到系统的机会。如果原始字体存在且有效，但允许用户替换，则返回 false。

### 另请参见

* class [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


