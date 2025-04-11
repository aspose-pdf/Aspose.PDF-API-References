---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase プロパティ。検証または変換に使用される PDF/A 標準のバージョンを取得または設定します。
type: docs
weight: 110
url: /ja/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## PdfAOptionsBase.PdfAVersion プロパティ

検証または変換に使用される PDF/A 標準のバージョンを取得または設定します。

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### プロパティ値

PDF/A 標準のバージョン。これは [`PdfAStandardVersion`](../../pdfastandardversion/) 列挙型の値のいずれかです。

## 備考

PDF/A 標準バージョンは、PDF/A 検証および変換の準拠レベルを決定するために使用されます。バージョンが自動に設定されている場合、システムはドキュメントメタデータに基づいて検証のための適切な PDF/A 標準バージョンを自動的に決定します。PDF/A 変換プロセスでは、自動は PDF/A-1b 標準バージョンにデフォルト設定されます。

### 参照

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)