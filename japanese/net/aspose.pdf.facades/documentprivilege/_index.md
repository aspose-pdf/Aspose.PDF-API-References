---
title: "クラス DocumentPrivilege"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.DocumentPrivilege クラス。Pdf ファイルへのアクセス権限を表します。PdfFileSecurity を参照してください。このクラスの使用方法は 4 つあります：1. 事前定義された権限を直接使用する。2. 事前定義された権限に基づき、特定の権限を変更する。3. 事前定義された権限に基づき、特定の Adobe Professional 権限の組み合わせを変更する。4. 方法2 と方法3 を組み合わせる。"
type: docs
weight: 4350
url: /ja/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Pdf ファイルへのアクセス権限を表します。[`PdfFileSecurity`](../pdffilesecurity/) を参照してください。このクラスの使用方法は 4 つあります：1. 事前定義された権限を直接使用する。2. 事前定義された権限に基づき、特定の権限を変更する。3. 事前定義された権限に基づき、特定の Adobe Professional 権限の組み合わせを変更する。4. 方法2 と方法3 を組み合わせる。

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | すべて許可されています。 |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | ファイルの組み立てを許可します。 |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | ファイルのコピーを許可します。 |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | 低品質印刷を許可します。 |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | ファイル内のフォームへの入力を許可します。 |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | すべて禁止されています。 |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | ファイルの注釈の変更を許可します。 |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | ファイルの変更を許可します。 |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | ファイルの印刷を許可します。 |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | 画面上での閲覧のみを許可します。 |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | 組み立てを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | コピーを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | 低品質印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | フォームへの入力を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | 注釈の変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | コンテンツの変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | 印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | スクリーンリーダーを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | ドキュメントの権限の変更レベルを取得および設定します。Adobe Professional の「Changes Allowed」設定と同様です。0: なし。1: ページの挿入、削除、回転。2: フォームフィールドへの入力と既存の署名フィールドへの署名。3: コメント、フォームフィールドへの入力、既存の署名フィールドへの署名。4: ページの抽出を除くすべて。 |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | ドキュメントの権限のコピーレベルを取得および設定します。Adobe Professional の権限設定と同様です。0: なし。1: 視覚障害者向けスクリーンリーダーデバイスのテキストアクセスを有効にする。2: テキスト、画像、その他のコンテンツのコピーを有効にする。 |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | ドキュメントの権限の印刷レベルを取得および設定します。Adobe Professional の「Printing Allowed」設定と同様です。0: なし。1: 低解像度（150 dpi）。2: 高解像度。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | 2つの `DocumentPrivilege` オブジェクトを比較します。比較対象のオブジェクト。戻り値は、このインスタンスと value の相対的な値を示す符号付き整数です。0 未満の場合、このインスタンスは value 未満です。0 の場合、このインスタンスは value と等しいです。0 超の場合、このインスタンスは value より大きいです。 |

## 例

```csharp
[C#]	
//方法1: 事前定義された権限を直接使用します。
DocumentPrivilege privilege = DocumentPrivilege.Print;

//方法2: 事前定義された権限を基に、特定の権限をいくつか変更します。
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//方法3: 事前定義された権限を基に、特定の Adobe Professional 権限の組み合わせを変更します。
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//方法4: 方法2 と 方法3 を組み合わせます。
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### 関連項目

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


