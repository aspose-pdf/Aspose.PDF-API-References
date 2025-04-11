---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: CustomFontSubstitutionBase 方法。用另一种字体替换原始字体
type: docs
weight: 20
url: /zh/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute 方法

用另一种字体替换原始字体。

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | 原始字体规范。 |
| substitutionFont | Font& | 替换字体。 |

### 返回值

如果替换成功，则返回 true。

## 备注

类 CustomFontSubstitutionBase 应该被继承以实现自定义字体替换逻辑。TrySubstitute 方法应该被正确重写：如果需要替换，必须返回 true。substitutionFont 必须设置为有效的 Font 对象。如果不需要替换，则必须返回 false。substitutionFont 可以设置为 null。

### 另请参见

* 类 [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* 类 [Font](../../font/)
* 类 [CustomFontSubstitutionBase](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)