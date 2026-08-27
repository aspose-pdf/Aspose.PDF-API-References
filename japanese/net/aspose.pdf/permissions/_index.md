---
title: "Permissions 列挙体"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Permissions 列挙体。この列挙体は PDF に対するユーザーの権限を表します"
type: docs
weight: 8610
url: /ja/net/aspose.pdf/permissions/
---
## Permissions enumeration

この列挙体は PDF に対するユーザーの権限を表します。

```csharp
[Flags]
public enum Permissions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| PrintDocument | `4` | (リビジョン 2 のセキュリティハンドラ) Document を印刷します。(リビジョン 3 以上のセキュリティハンドラ) Document を印刷します（PrintingQuality が設定されているかどうかに応じて、最高品質でない場合があります）。 |
| ModifyContent | `8` | ModifyTextAnnotations、FillForm、および 11 によって制御される操作以外の操作で Document の内容を変更します。 |
| ExtractContent | `10` | (リビジョン 2 のセキュリティハンドラ) Document からテキストや画像をコピーまたは抽出します（障害を持つユーザーへのアクセシビリティ支援やその他の目的のための抽出を含む）。(リビジョン 3 以上のセキュリティハンドラ) Document からテキストや画像を、ExtractContentWithDisabilities によって制御される操作以外の操作でコピーまたは抽出します。 |
| ModifyTextAnnotations | `20` | テキスト注釈を追加または変更し、インタラクティブなフォームフィールドに入力し、さらに ModifyContent が設定されている場合は、インタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更します。 |
| FillForm | `100` | (リビジョン 3 以上のセキュリティハンドラ) ModifyTextAnnotations がクリアされていても、既存のインタラクティブなフォームフィールド（署名フィールドを含む）に入力します。 |
| ExtractContentWithDisabilities | `200` | (リビジョン 3 以上のセキュリティハンドラ) テキストや画像を抽出します（障害を持つユーザーへのアクセシビリティ支援やその他の目的のため）。 |
| AssembleDocument | `400` | (リビジョン 3 以上のセキュリティハンドラ) Document を組み立てます（ページの挿入、回転、削除やブックマークやサムネイル画像の作成を含む）。ModifyContent がクリアされていても適用されます。 |
| PrintingQuality | `800` | (リビジョン 3 以上のセキュリティハンドラ) ドキュメントを、PDF コンテンツの忠実なデジタルコピーを生成できる表現に印刷します。このビットがクリアされている場合 (ビット 3 が設定されている場合)、印刷は外観の低レベル表現に限定され、品質が低下する可能性があります。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


