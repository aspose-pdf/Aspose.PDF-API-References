---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Permissions enum. この列挙型はPDFのユーザー権限を表します。
type: docs
weight: 8480
url: /ja/net/aspose.pdf/permissions/
---
## Permissions enumeration

この列挙型はPDFのユーザー権限を表します。

```csharp
[Flags]
public enum Permissions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PrintDocument | `4` | (セキュリティハンドラの改訂版2) ドキュメントを印刷します。 (セキュリティハンドラの改訂版3以上) ドキュメントを印刷します（PrintingQualityが設定されているかどうかに応じて、最高品質レベルでない可能性があります）。 |
| ModifyContent | `8` | ModifyTextAnnotations、FillForm、および11によって制御される操作以外の操作によってドキュメントの内容を変更します。 |
| ExtractContent | `10` | (セキュリティハンドラの改訂版2) ドキュメントからテキストやグラフィックスをコピーまたは抽出します（障害者向けのアクセシビリティをサポートするため、またはその他の目的のためにテキストやグラフィックスを抽出します）。 (セキュリティハンドラの改訂版3以上) ExtractContentWithDisabilitiesによって制御される操作以外の操作によってドキュメントからテキストやグラフィックスをコピーまたは抽出します。 |
| ModifyTextAnnotations | `20` | テキスト注釈を追加または変更し、インタラクティブなフォームフィールドに記入し、ModifyContentが設定されている場合はインタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更します。 |
| FillForm | `100` | (セキュリティハンドラの改訂版3以上) ModifyTextAnnotationsがクリアされていても、既存のインタラクティブなフォームフィールド（署名フィールドを含む）に記入します。 |
| ExtractContentWithDisabilities | `200` | (セキュリティハンドラの改訂版3以上) テキストやグラフィックスを抽出します（障害者向けのアクセシビリティをサポートするため、またはその他の目的のために）。 |
| AssembleDocument | `400` | (セキュリティハンドラの改訂版3以上) ドキュメントを組み立てます（ページを挿入、回転、削除し、ブックマークやサムネイル画像を作成します）、ModifyContentがクリアされていても。 |
| PrintingQuality | `800` | (セキュリティハンドラの改訂版3以上) PDFコンテンツの忠実なデジタルコピーを生成できる表現にドキュメントを印刷します。このビットがクリアされている場合（ビット3が設定されている場合）、印刷は外観の低レベルの表現に制限され、品質が劣化する可能性があります。 |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)