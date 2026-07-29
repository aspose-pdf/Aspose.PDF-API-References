---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Aspose.PDF for .NET API 参考"
description: "CustomFontSubstitutionBase 方法。将原始字体替换为另一个字体"
type: docs
weight: 20
url: /zh/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

将原始字体替换为另一种字体。

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | 原始字体规范。 |
| substitutionFont | Font& | 替换字体。 |

### 返回值

如果替换成功则为 True。

## 备注

应继承类 CustomFontSubstitutionBase 以实现自定义字体替换逻辑。应正确重写 TrySubstitute 方法：在需要替换时必须返回 true。substitutionFont 必须设置为有效的 Font 对象。若不需要替换则必须返回 false。substitutionFont 可以设置为 null。

### 另请参见

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


