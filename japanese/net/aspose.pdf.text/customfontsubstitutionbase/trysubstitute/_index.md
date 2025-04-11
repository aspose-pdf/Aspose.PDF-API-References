---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: CustomFontSubstitutionBase メソッド。元のフォントを別のフォントに置き換えます
type: docs
weight: 20
url: /ja/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute メソッド

元のフォントを別のフォントに置き換えます。

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | 元のフォント仕様。 |
| substitutionFont | Font& | 置き換えフォント。 |

### 戻り値

置き換えが成功した場合は true を返します。

## 備考

CustomFontSubstitutionBase クラスは、カスタムフォント置き換えロジックを実装するために継承する必要があります。TrySubstitute メソッドは適切にオーバーライドする必要があります：置き換えが必要な場合は true を返さなければなりません。substitutionFont は有効な Font オブジェクトに設定する必要があります。置き換えが必要ない場合は false を返さなければなりません。substitutionFont は null に設定することもできます。

### 参照

* クラス [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* クラス [Font](../../font/)
* クラス [CustomFontSubstitutionBase](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)