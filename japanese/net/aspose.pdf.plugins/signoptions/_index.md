---
title: "クラス SignOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.SignOptions クラス。Signature プラグインのサインオプションを表します。"
type: docs
weight: 9400
url: /ja/net/aspose.pdf.plugins/signoptions/
---
## SignOptions class

[`Signature`](../signature/) プラグインのサインオプションを表します。

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | `SignOptions` オブジェクトの新しいインスタンスをデフォルトオプションで初期化します。 |
| [SignOptions](signoptions/#constructor_1)(string, string) | `SignOptions` オブジェクトの新しいインスタンスをデフォルトオプションで初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 操作完了後に入力ストリームを閉じます。 |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 操作完了後に出力ストリームを閉じます。 |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | 署名の連絡先。 |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | OrganizerOptions プラグインのデータコレクションを返します。 |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | 署名の場所。 |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | 既存の署名フィールドの名前。null は新しいフィールドを作成するために使用します。 |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 保存操作結果のために追加されたターゲットのコレクションを取得します。 |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | 署名が行われるページ番号。 |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | 署名の理由。 |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | 署名の矩形。 |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | 署名の可視性。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | PdfOrganizer プラグインのデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | PdfOrganizer プラグインのデータコレクションに新しいデータソースを追加します。 |

### 関連項目

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


