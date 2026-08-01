---
title: "LoadOptions.DisableFontLicenseVerifications"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "LoadOptions プロパティ。ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。true の場合、フォントのライセンスで禁止されている操作（例として、このフォントを PDF ドキュメントに埋め込むこと）が許可されます。デフォルトは false です。"
type: docs
weight: 10
url: /ja/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## LoadOptions.DisableFontLicenseVerifications property

ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## 備考

このフラグを使用する際は注意してください。設定された場合、そのフラグを設定した人物が可能なライセンス／法的違反に対する全責任を負うことを意味します。したがって、自己のリスクで使用することになります。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。

### 関連項目

* class [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


