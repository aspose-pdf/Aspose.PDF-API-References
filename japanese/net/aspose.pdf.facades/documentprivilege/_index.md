---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.DocumentPrivilege クラス。Pdf ファイルへのアクセス権を表します。Refer toPdfFileSecurity。このクラスを使用する方法は 4 つあります。1. 定義済みの権限を直接使用する。2. 定義済みの権限に基づいて特定の権限を変更する。3. 定義済みの権限に基づいて特定の Adobe Professional 権限の組み合わせを変更する。4. 方法 2 と方法 3 を混合する。
type: docs
weight: 4230
url: /ja/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege クラス

Pdf ファイルへのアクセス権を表します。Refer to[`PdfFileSecurity`](../pdffilesecurity/)。このクラスを使用する方法は 4 つあります：1. 定義済みの権限を直接使用する。2. 定義済みの権限に基づいて特定の権限を変更する。3. 定義済みの権限に基づいて特定の Adobe Professional 権限の組み合わせを変更する。4. 方法 2 と方法 3 を混合する。

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | すべて許可。 |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | ファイルのアセンブリを許可します。 |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | ファイルのコピーを許可します。 |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | 劣化印刷を許可します。 |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | ファイル内のフォームの記入を許可します。 |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | すべて禁止。 |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | ファイルの注釈の変更を許可します。 |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | ファイルの変更を許可します。 |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | ファイルの印刷を許可します。 |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | 画面上のリーダーのみを許可します。 |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | アセンブリを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | コピーを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | 劣化印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | フォームの記入を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | 注釈の変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | 内容の変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | 印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | スクリーンリーダーを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | ドキュメントの権限の変更レベルを取得および設定します。Adobe Professional の変更許可設定と同様です。0: なし。1: ページの挿入、削除、回転。2: フォームフィールドの記入と既存の署名フィールドへの署名。3: コメント、フォームフィールドの記入、および既存の署名フィールドへの署名。4: ページの抽出を除くすべて。 |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | ドキュメントの権限のコピー レベルを取得および設定します。Adobe Professional の権限設定と同様です。0: なし。1: 視覚障害者用のスクリーンリーダー デバイスへのテキストアクセスを有効にします。2: テキスト、画像、およびその他のコンテンツのコピーを有効にします。 |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | ドキュメントの権限の印刷レベルを取得および設定します。Adobe Professional の印刷許可設定と同様です。0: なし。1: 低解像度 (150 dpi)。2: 高解像度。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | 2 つの `DocumentPrivilege` オブジェクトを比較します。比較対象のオブジェクト。 このインスタンスと値の相対的な値を示す符号付き整数。ゼロ未満の場合、このインスタンスは値より小さい。ゼロの場合、このインスタンスは値と等しい。ゼロより大きい場合、このインスタンスは値より大きい。 |

## 例

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
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

### 参照

* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)