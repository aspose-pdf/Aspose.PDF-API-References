---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: OriginalFontSpecification プロパティ。置換が避けられないことを示す値を取得します
type: docs
weight: 20
url: /ja/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable プロパティ

置換が避けられないことを示す値を取得します。

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## 備考

元のフォントが存在しないために置換が要求された場合、または元のフォントが特定のタスクの文脈で使用できない場合に true を返します。ユーザーがフラグを無視してフォントを置換しない場合は、デフォルトのフォント置換手順が実行されます。しかし、ユーザーが標準のフォント置換手順を変更し、システムにより良いフォントを設定する機会を提供します。元のフォントが存在し、有効であるが、ユーザーが置換することが許可されている場合は false を返します。

### 参照

* クラス [OriginalFontSpecification](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)