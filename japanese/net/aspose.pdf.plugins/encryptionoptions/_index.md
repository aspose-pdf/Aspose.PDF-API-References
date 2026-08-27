---
title: "クラス EncryptionOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.EncryptionOptions クラス。Security プラグインの暗号化オプションを表します"
type: docs
weight: 8670
url: /ja/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions class

[`Security`](../security/) プラグインの暗号化オプションを表します。

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | デフォルトオプションで `EncryptionOptions` オブジェクトの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 操作完了後に入力ストリームを閉じます。 |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 操作完了後に出力ストリームを閉じます。 |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | 暗号アルゴリズム。詳細は [`CryptoAlgorithm`](./cryptoalgorithm/) を参照してください。 |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | ドキュメントの権限。詳細は [`Permissions`](../../aspose.pdf/permissions/) を参照してください。 |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | OrganizerOptions プラグインのデータコレクションを返します。 |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 保存操作結果のために追加されたターゲットのコレクションを取得します。 |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | 所有者パスワード。 |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | ユーザーパスワード。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | PdfOrganizer プラグインのデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | PdfOrganizer プラグインのデータコレクションに新しいデータソースを追加します。 |

### 関連項目

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


