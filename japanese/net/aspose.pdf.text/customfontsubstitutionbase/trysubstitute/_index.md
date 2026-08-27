---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "CustomFontSubstitutionBase メソッド。元のフォントを別のフォントに置き換えます。"
type: docs
weight: 20
url: /ja/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

元のフォントを別のフォントに置き換えます。

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | 元のフォント仕様。 |
| substitutionFont | Font& | 置換フォント。 |

### 戻り値

置換が成功した場合は true。

## 備考

CustomFontSubstitutionBase クラスは、カスタムフォント置換ロジックを実装するために継承する必要があります。TrySubstitute メソッドは適切にオーバーライドする必要があります：置換が必要な場合は true を返す必要があります。substitutionFont は有効なフォントオブジェクトに設定する必要があります。置換が不要な場合は false を返す必要があります。substitutionFont は null に設定できる場合があります。

### 関連項目

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


