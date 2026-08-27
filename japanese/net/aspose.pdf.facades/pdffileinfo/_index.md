---
title: "クラス PdfFileInfo"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfFileInfo クラス。PDF Document のメタ情報にアクセスするためのクラスを表します。"
type: docs
weight: 4640
url: /ja/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

PDF ドキュメントのメタ情報にアクセスするクラスを表します。

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | デフォルト値で Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) |  *document* を基に新しい `PdfFileInfo` オブジェクトを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_6)(string, string) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_4)(Stream, string, ICustomSecurityHandler) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_7)(string, string, ICustomSecurityHandler) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | PDF Document の Author 情報を取得または設定します。 |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | PDF Document の CreationDate 情報を取得または設定します。 |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | PDF Document の Creator 情報を取得または設定します。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | 現在の入力ファイルが PDF ファイルのコレクションを含む 'Portfolio' ファイルである場合、true を返します。 |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | 権限または Document のセキュリティプロパティを変更するためにパスワードが必要な場合、true を返します。 このプロパティは、`PdfFileInfo` コンストラクタで有効なパスワードが提供された場合にのみ読み取ることができることに注意してください。PasswordType が Inaccessible（無効なパスワードが提供されたことを意味します）の場合、このプロパティの読み取りは [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/) で失敗します。 |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | パスワードで保護された pdf Document を開くためにパスワードが必要な場合、true を返します。 |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | PDF Document のカスタマイズされた情報を取得または設定します。 |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | PDF ドキュメントが暗号化されているかどうかをチェックします。 |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | ソース入力が有効な PDF ファイルかどうかをチェックします。 |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | PDF ドキュメントの Keywords 情報を取得または設定します。 |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | PDF ドキュメントの ModDate 日付情報を取得または設定します。 |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | ドキュメントページ数を取得します。 |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | PdfFileInfo インスタンス作成時に渡されたパスワードのタイプを返します。可能な値は [`PasswordType`](./passwordtype/) を参照してください。PDF ドキュメントはユーザー（またはオープン）パスワードとオーナー（または権限、編集）パスワードの両方で開くことができることに注意してください。 |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | PDF ドキュメントの Producer 情報を取得します。 |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | PDF ドキュメントの Subject 情報を取得または設定します。 |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | PDF ドキュメントの Title 情報を取得または設定します。 |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | [`IsPdfFile`](./ispdffile/) プロパティを使用して厳格な検証ルールを適用します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | PDF ドキュメントのすべてのメタ情報をクリアします。 |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | インスタンスの初期化を解除します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | PDF ドキュメントの特権設定を取得します。 |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | プロパティ名で PDF ドキュメントのカスタマイズ情報を取得します。該当するプロパティがない場合は空文字列を返します。 |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | 指定されたページの高さを取得します。 |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | 指定されたページの回転を取得します。 |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | 指定されたページの幅を取得します。 |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | 指定されたページ表示領域の水平オフセットを取得します。 |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | 指定されたページ表示領域の垂直オフセットを取得します。 |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | PDF ドキュメントのバージョン情報を取得します。 |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | PDF ドキュメントを指定されたファイルに保存します。 |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | PDF ドキュメントを指定されたファイルに保存します。 |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | 更新された PDF ドキュメントを指定されたファイルに保存します。 |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | ファイル情報を設定して明示的に指定されたプロパティを変更し、他のプロパティはそのままにします。 |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | PDF ドキュメントのカスタマイズ情報を設定します。 |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


