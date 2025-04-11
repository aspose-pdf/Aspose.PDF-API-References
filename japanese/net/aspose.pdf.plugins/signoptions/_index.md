---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.SignOptions クラス。署名プラグインの署名オプションを表します
type: docs
weight: 9250
url: /ja/net/aspose.pdf.plugins/signoptions/
---
## SignOptions クラス

[`Signature`](../signature/) プラグインの署名オプションを表します。

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | デフォルトオプションで `SignOptions` オブジェクトの新しいインスタンスを初期化します。 |
| [SignOptions](signoptions/#constructor_1)(string, string) | デフォルトオプションで `SignOptions` オブジェクトの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 操作が完了した後に入力ストリームを閉じます。 |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 操作が完了した後に出力ストリームを閉じます。 |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | 署名の連絡先。 |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | OrganizerOptions プラグインデータコレクションを返します。 |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | 署名の場所。 |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | 既存の署名フィールドの名前。新しいフィールドを作成するには null を指定します。 |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 保存操作結果のために追加されたターゲットのコレクションを取得します。 |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | 署名が行われるページ番号。 |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | 署名の理由。 |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | 署名の矩形。 |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | 署名の可視性。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | PdfOrganizer プラグインデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | PdfOrganizer プラグインデータコレクションに新しいデータソースを追加します。 |

### 参照

* クラス [OrganizerBaseOptions](../organizerbaseoptions/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)