---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileInfo クラス。PDF ドキュメントのメタ情報にアクセスするためのクラスを表します。
type: docs
weight: 4520
url: /ja/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo クラス

PDF ドキュメントのメタ情報にアクセスするためのクラスを表します。

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | デフォルト値で Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | *document* に基づいて新しい `PdfFileInfo` オブジェクトを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | PDF ドキュメントの著者情報を取得または設定します。 |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | PDF ドキュメントの作成日情報を取得または設定します。 |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | PDF ドキュメントの作成者情報を取得または設定します。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | 現在の入力ファイルが PDF ファイルのコレクションを含む「ポートフォリオ」ファイルである場合は true を返します。 |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | 権限またはドキュメントセキュリティプロパティを変更するためにパスワードが必要な場合は true を返します。このプロパティは、`PdfFileInfo` コンストラクタに有効なパスワードが提供された場合にのみ読み取ることができます。PasswordType が Inaccessible の場合（無効なパスワードが提供されたことを意味します）、このプロパティを読み取ると [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/) が発生します。 |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | パスワード保護された PDF ドキュメントを開くためにパスワードが必要な場合は true を返します。 |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | PDF ドキュメントのカスタマイズされた情報を取得または設定します。 |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | PDF ドキュメントが暗号化されているかどうかを確認します。 |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | ソース入力が有効な PDF ファイルであるかどうかを確認します。 |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | PDF ドキュメントのキーワード情報を取得または設定します。 |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | PDF ドキュメントの最終更新日情報を取得または設定します。 |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | ドキュメントのページ数を取得します。 |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | PdfFileInfo インスタンスを作成するために渡されたパスワードの種類を返します。可能な値は [`PasswordType`](./passwordtype/) で確認できます。PDF ドキュメントは、ユーザー（またはオープン）パスワードとオーナー（または権限、編集）パスワードの両方を使用して開くことができます。 |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | PDF ドキュメントのプロデューサー情報を取得します。 |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | PDF ドキュメントの件名情報を取得または設定します。 |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | PDF ドキュメントのタイトル情報を取得または設定します。 |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | [`IsPdfFile`](./ispdffile/) プロパティを使用して厳密な検証ルールを使用します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | PDF ドキュメントのすべてのメタ情報をクリアします。 |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | インスタンスを非初期化します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | PDF ドキュメントの権限設定を取得します。 |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | プロパティ名を持つ PDF ドキュメントのカスタマイズされた情報を取得します。名前に一致するプロパティがない場合は空の文字列を返します。 |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | 指定されたページの高さを取得します。 |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | 指定されたページの回転を取得します。 |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | 指定されたページの幅を取得します。 |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | 指定されたページの表示領域の水平オフセットを取得します。 |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | 指定されたページの表示領域の垂直オフセットを取得します。 |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | PDF ドキュメントのバージョン情報を取得します。 |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | 指定されたファイルに PDF ドキュメントを保存します。 |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | 指定されたファイルに PDF ドキュメントを保存します。 |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | 更新された PDF ドキュメントを指定されたファイルに保存します。 |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | ファイル情報を設定することによって明示的に指定されたプロパティを変更し、他のプロパティはそのままにします。 |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | PDF ドキュメントのカスタマイズされた情報を設定します。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)