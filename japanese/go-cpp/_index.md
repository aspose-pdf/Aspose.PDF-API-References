---
title: "C++ 経由の Go 用 Aspose.PDF"
description: "C++ 経由の Go 用 Aspose.PDF"
keywords:  "Go, Golang, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /ja/go-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Go via C++ allows developers manipulate them PDF files directly in the Go.

# Types

## Document
Document は PDF ドキュメントを表します。

```go
type Document struct {
}
```

# Functions

## Convert from PDF functions

| 関数 | 説明 |
| -------- | ----------- |
| [SaveDocX](./convert/savedocx/) | 以前に開いた PDF ドキュメントを DocX ドキュメントとして変換して保存します。 |
| [SaveDoc](./convert/savedoc/) | 以前に開いた PDF ドキュメントを Doc ドキュメントとして変換して保存します。 |
| [SaveXlsX](./convert/savexlsx/) | 以前に開いた PDF ドキュメントを XlsX ドキュメントとして変換して保存します。 |
| [SaveTxt](./convert/savetxt/) | 以前に開いた PDF ドキュメントを Txt ドキュメントとして変換して保存します。 |
| [SavePptX](./convert/savepptx/) | 以前に開いた PDF ドキュメントを PptX ドキュメントとして変換して保存します。 |
| [SaveXps](./convert/savexps/) | 以前に開いた PDF ドキュメントを Xps ドキュメントとして変換して保存します。 |
| [SaveTeX](./convert/savetex/) | 以前に開いた PDF ドキュメントを TeX ドキュメントとして変換して保存します。 |
| [SaveEpub](./convert/saveepub/) | 以前に開いた PDF ドキュメントを Epub ドキュメントとして変換して保存します。 |
| [SaveBooklet](./convert/savebooklet/) | 以前に開いた PDF ドキュメントを 小冊子 PDF ドキュメントとして変換して保存します。 |
| [SaveNUp](./convert/savenup/) | 以前に開いた PDF ドキュメントを N-Up PDF ドキュメントとして変換して保存します。 |
| [SaveMarkdown](./convert/savemarkdown/) | 以前に開いた PDF ドキュメントを Markdown ドキュメントとして変換して保存します。 |
| [SaveTiff](./convert/savetiff/) | 以前に開いた PDF ドキュメントを Tiff ドキュメントとして変換して保存します。 |
| [SaveDocXEnhanced](./convert/savedocxenhanced/) | 以前に開いた PDF ドキュメントを 強化認識モード（完全に編集可能な表と段落）付きの DocX ドキュメントとして変換して保存します。 |
| [SaveSvgZip](./convert/savesvgzip/) | 以前に開いた PDF ドキュメントを SVG アーカイブとして変換して保存します。 |
| [ExportFdf](./convert/exportfdf/) | AcroForm を含む以前に開いた PDF ドキュメントを FDF ドキュメントにエクスポートします。 |
| [ExportXfdf](./convert/exportxfdf/) | AcroForm を含む以前に開いた PDF ドキュメントを XFDF ドキュメントにエクスポートします。 |
| [ExportXml](./convert/exportxml/) | AcroForm を含む以前に開いた PDF ドキュメントを XML ドキュメントにエクスポートします。 |
| [PageToJpg](./convert/pagetojpg/) | 指定したページを Jpg 画像として変換して保存します。 |
| [PageToPng](./convert/pagetopng/) | 指定したページを Png 画像として変換して保存します。 |
| [PageToBmp](./convert/pagetobmp/) | 指定したページを Bmp 画像として変換して保存します。 |
| [PageToTiff](./convert/pagetotiff/) | 指定したページを Tiff 画像として変換して保存します。 |
| [PageToSvg](./convert/pagetosvg/) | 指定されたページをSvg画像として変換し保存します。 |
| [PageToPdf](./convert/pagetopdf/) | 指定されたページをPdfとして変換し保存します。 |
| [PageToDICOM](./convert/pagetodicom/) | 指定されたページをDICOM画像として変換し保存します。 |


## Organize PDF functions

| 関数 | 説明 |
| -------- | ----------- |
| [Optimize](./organize/optimize/) | PDF-document のコンテンツを最適化します。 |
| [OptimizeResource](./organize/optimizeresource/) | PDF-document のリソースを最適化します。 |
| [Grayscale](./organize/grayscale/) | PDF-document を白黒に変換します。 |
| [Rotate](./organize/rotate/) | PDF-document を回転させます。 |
| [SetBackground](./organize/setbackground/) | PDF-document の背景色を設定します。 |
| [Repair](./organize/repair/) | PDF-document を修復します。 |
| [ReplaceText](./organize/replacetext/) | PDF-document のテキストを置換します。 |
| [AddPageNum](./organize/addpagenum/) | PDF-document にページ番号を追加します。 |
| [AddTextHeader](./organize/addtextheader/) | PDF-document のヘッダーにテキストを追加します。 |
| [AddTextFooter](./organize/addtextfooter/) | PDF-document のフッターにテキストを追加します。 |
| [Flatten](./organize/flatten/) | PDF-document をフラット化します。 |
| [RemoveAnnotations](./organize/removeannotations/) | PDF-document から注釈を削除します。 |
| [RemoveAttachments](./organize/removeattachments/) | PDF-document から添付ファイルを削除します。 |
| [RemoveBlankPages](./organize/removeblankpages/) | PDF-document から空白ページを削除します。 |
| [RemoveBookmarks](./organize/removebookmarks/) | PDF-document からブックマークを削除します。 |
| [RemoveHiddenText](./organize/removehiddentext/) | PDF-document から隠しテキストを削除します。 |
| [RemoveImages](./organize/removeimages/) | PDF-document から画像を削除します。 |
| [RemoveJavaScripts](./organize/removejavascripts/) | PDF-document から JavaScript を削除します。 |
| [RemoveTables](./organize/removetables/) | PDF-document から表を削除します。 |
| [RemoveWatermarks](./organize/removewatermarks/) | PDF-document から透かしを削除します。 |
| [AddWatermark](./organize/addwatermark/) | PDF-document に透かしを追加します。 |
| [EmbedFonts](./organize/embedfonts/) | PDF-document にフォントを埋め込みます。 |
| [UnembedFonts](./organize/unembedfonts/) | PDFドキュメントのフォントを埋め込み解除する。 |
| [OptimizeFileSize](./organize/optimizefilesize/) | 画像圧縮品質でPDFドキュメントのサイズを最適化する。 |
| [RemoveTextHeaders](./organize/removetextheaders/) | PDFドキュメントからテキストヘッダーを削除する。 |
| [RemoveTextFooters](./organize/removetextfooters/) | PDFドキュメントからテキストフッターを削除する。 |
| [Crop](./organize/crop/) | PDFドキュメントのページをトリミングする。 |
| [ReplaceFont](./organize/replacefont/) | PDFドキュメントのフォントを置換する。 |
| [Convert](./organize/convert/) | PDFドキュメントを指定されたPDF形式のPDFドキュメントに変換する。 |
| [Validate](./organize/validate/) | PDFドキュメントがPDF形式に準拠しているか検証する。 |
| [RemovePdfaCompliance](./organize/removepdfacompliance/) | PDFドキュメントからPDF/A準拠を削除する。 |
| [RemovePdfUaCompliance](./organize/removepdfuacompliance/) | PDFドキュメントからPDF/UA準拠を削除する。 |
| [IsPdfaCompliant](./organize/ispdfacompliant/) | PDFドキュメントがPDF/Aに準拠しているか取得する。 |
| [IsPdfUaCompliant](./organize/ispdfuacompliant/) | PDFドキュメントがPDF/UAに準拠しているか取得する。 |
| [PageRotate](./organize/pagerotate/) | ページを回転する。 |
| [PageSetSize](./organize/pagesetsize/) | ページのサイズを設定する。 |
| [PageGrayscale](./organize/pagegrayscale/) | ページを白黒に変換する。 |
| [PageAddText](./organize/pageaddtext/) | ページにテキストを追加する。 |
| [PageReplaceText](./organize/pagereplacetext/) | ページ上のテキストを置換する。 |
| [PageAddPageNum](./organize/pageaddpagenum/) | ページにページ番号を追加する。 |
| [PageAddTextHeader](./organize/pageaddtextheader/) | ページヘッダーにテキストを追加する。 |
| [PageAddTextFooter](./organize/pageaddtextfooter/) | ページフッターにテキストを追加する。 |
| [PageRemoveAnnotations](./organize/pageremoveannotations/) | ページの注釈を削除する。 |
| [PageRemoveHiddenText](./organize/pageremovehiddentext/) | ページの非表示テキストを削除する。 |
| [PageRemoveImages](./organize/pageremoveimages/) | ページの画像を削除する。 |
| [PageRemoveTables](./organize/pageremovetables/) | ページの表を削除する。 |
| [PageRemoveWatermarks](./organize/pageremovewatermarks/) | ページの透かしを削除する。 |
| [PageAddWatermark](./organize/pageaddwatermark/) | ページに透かしを追加します。 |
| [PageRemoveTextHeaders](./organize/pageremovetextheaders/) | ページのテキストヘッダーを削除します。 |
| [PageRemoveTextFooters](./organize/pageremovetextfooters/) | ページのテキストフッターを削除します。 |
| [PageCrop](./organize/pagecrop/) | ページをトリミングします。 |
| [PageReplaceFont](./organize/pagereplacefont/) | ページのフォントを置換します。 |
| [PageMergeLayers](./organize/pagemergelayers/) | ページ上のすべてのレイヤーを、指定された新しいレイヤー名で単一のレイヤーに結合します。 |
| [PageLayers](./organize/pagelayers/) | ページ上のレイヤー名を取得します。 |


## Core PDF functions

| 関数 | 説明 |
| -------- | ----------- |
| [New](./core/new/) | 新しい PDF ドキュメントを作成します。 |
| [Open](./core/open/) | ファイル名で PDF ドキュメントを開きます。 |
| [Save](./core/save/) | 以前に開いた PDF ドキュメントを保存します。 |
| [SaveAs](./core/saveas/) | 以前に開いた PDF ドキュメントを新しいファイル名で保存します。 |
| [Close](./core/close/) | PDF ドキュメントの割り当てられたリソースを解放します。 |
| [SetLicense](./core/setlicense/) | ファイル名でライセンスを設定します。 |
| [ExtractText](./core/extracttext/) | PDF ドキュメントの内容をプレーンテキストとして返します。 |
| [WordCount](./core/wordcount/) | PDF ドキュメントの単語数を返します。 |
| [CharacterCount](./core/charactercount/) | PDF ドキュメントの文字数を返します。 |
| [Append](./core/append/) | 別の PDF ドキュメントからページを追加します。 |
| [AppendPages](./core/appendpages/) | 別の PDF ドキュメントから選択したページを追加します。 |
| [MergeDocuments](./core/mergedocuments/) | 提供された PDF ドキュメントを結合して新しい PDF ドキュメントを作成します。 |
| [SplitDocument](./core/splitdocument/) | ソース PDF ドキュメントからページを抽出して複数の新しい PDF ドキュメントを作成します。 |
| [Split](./core/split/) | 現在の PDF ドキュメントからページを抽出して複数の新しい PDF ドキュメントを作成します。 |
| [SplitAtPage](./core/splitatpage/) | PDF ドキュメントを 2 つの新しい PDF ドキュメントに分割します。 |
| [SplitAt](./core/splitat/) | 現在の PDF ドキュメントを 2 つの新しい PDF ドキュメントに分割します。 |
| [Bytes](./core/bytes/) | PDF ドキュメントの内容をバイトスライスとして返します。 |
| [GetMetaInfo](./core/getmetainfo/) | PDF ドキュメントのメタ情報の値を取得します。 |
| [SetMetaInfo](./core/setmetainfo/) | PDFドキュメントのメタ情報の値を設定します.. |
| [ClearMetaInfo](./core/clearmetainfo/) | PDFドキュメントのすべてのメタ情報の値をクリアします.. |
| [IsLinearized](./core/islinearized/) | ドキュメントがリニアライズされているかどうかを示す値を取得します。 |
| [PageAdd](./core/pageadd/) | PDFドキュメントに新しいページを追加します。 |
| [PageInsert](./core/pageinsert/) | PDFドキュメントの指定された位置に新しいページを挿入します。 |
| [PageDelete](./core/pagedelete/) | PDFドキュメントの指定されたページを削除します。 |
| [PageCount](./core/pagecount/) | PDFドキュメントのページ数を返します。 |
| [PageWordCount](./core/pagewordcount/) | PDFドキュメントの指定ページの単語数を返します。 |
| [PageCharacterCount](./core/pagecharactercount/) | PDFドキュメントの指定ページの文字数を返します。 |
| [PageIsBlank](./core/pageisblank/) | PDFドキュメントのページが空白かどうかを返します。 |


## Security

| 関数 | 説明 |
| -------- | ----------- |
| [OpenWithPassword](./security/openwithpassword/) | パスワードで保護されたPDFドキュメントを開きます。 |
| [Encrypt](./security/encrypt/) | PDFドキュメントを暗号化します。 |
| [Decrypt](./security/decrypt/) | PDFドキュメントの暗号化を解除します。 |
| [SetPermissions](./security/setpermissions/) | PDFドキュメントの権限を設定します。 |
| [GetPermissions](./security/getpermissions/) | PDFドキュメントの現在の権限を取得します。 |
| [IsEncrypted](./security/isencrypted/) | PDFドキュメントの暗号化状態を取得します。 |
| [SignPKCS7](./security/signpkcs7/) | PKCS#7 デジタル署名を使用して PDFドキュメントに署名します。 |
| [SignPKCS7Detached](./security/signpkcs7detached/) | PKCS#7 デタッチド デジタル署名を使用して PDFドキュメントに署名します。 |
| [IsSigned](./security/issigned/) | PDFドキュメントの署名状態を取得します。 |
| [RemoveSigns](./security/removesigns/) | PDFドキュメントから署名を削除します。 |


## Miscellaneous

| 関数 | 説明 |
| -------- | ----------- |
| [About](./miscellaneous/about/) | C++ 経由で Aspose.PDF for Go に関するメタデータ情報を返します。 |


# Types secondary

## ProductInfo contains metadata about the Aspose.PDF for Go via C++.
```go
type ProductInfo struct {
	Product     string `json:"product"`     // Name
	Family      string `json:"family"`      // Family (e.g., "Aspose.PDF")
	Version     string `json:"version"`     // Version
	ReleaseDate string `json:"releasedate"` // Release date in ISO format (YYYY-MM-DD)
	Producer    string `json:"producer"`    // Producer
	IsLicensed  bool   `json:"islicensed"`  // License status (true if licensed)
}
```


# Constants

## Enumeration of possible rotation values.
```go
const (
    RotationNone  int32 = 0 // Non-rotated.
    RotationOn90  int32 = 1 // Rotated on 90 degrees clockwise.
    RotationOn180 int32 = 2 // Rotated on 180 degrees.
    RotationOn270 int32 = 3 // Rotated on 270 degrees clockwise.
    RotationOn360 int32 = 4 // Rotated on 360 degrees clockwise.
)
```

## Enumeration of possible page size values.
```go
const (
    PageSizeA0         int32 = 0  // A0 size.
    PageSizeA1         int32 = 1  // A1 size.
    PageSizeA2         int32 = 2  // A2 size.
    PageSizeA3         int32 = 3  // A3 size.
    PageSizeA4         int32 = 4  // A4 size.
    PageSizeA5         int32 = 5  // A5 size.
    PageSizeA6         int32 = 6  // A6 size.
    PageSizeB5         int32 = 7  // B5 size.
    PageSizePageLetter int32 = 8  // PageLetter size.
    PageSizePageLegal  int32 = 9  // PageLegal size.
    PageSizePageLedger int32 = 10 // PageLedger size.
    PageSizeP11x17     int32 = 11 // P11x17 size.
)
```

## Enumeration of possible crypto algorithms.
```go
type CryptoAlgorithm int32
const (
	RC4x40  CryptoAlgorithm = 0 // RC4 with key length 40.
	RC4x128 CryptoAlgorithm = 1 // RC4 with key length 128.
	AESx128 CryptoAlgorithm = 2 // AES with key length 128.
	AESx256 CryptoAlgorithm = 3 // AES with key length 256.
)
```

## Enumeration of possible PDF formats.
```go
type PdfFormat int32
const (
	PDF_A_1A      PdfFormat = iota // Pdf/A-1a format.
	PDF_A_1B                       // Pdf/A-1b format.
	PDF_A_2A                       // Pdf/A-2a format.
	PDF_A_3A                       // Pdf/A-3a format.
	PDF_A_2B                       // Pdf/A-2b format.
	PDF_A_2U                       // Pdf/A-2u format.
	PDF_A_3B                       // Pdf/A-3b format.
	PDF_A_3U                       // Pdf/A-3u format.
	V_1_0                          // Adobe version 1.0.
	V_1_1                          // Adobe version 1.1.
	V_1_2                          // Adobe version 1.2.
	V_1_3                          // Adobe version 1.3.
	V_1_4                          // Adobe version 1.4.
	V_1_5                          // Adobe version 1.5.
	V_1_6                          // Adobe version 1.6.
	V_1_7                          // Adobe version 1.7.
	V_2_0                          // ISO Standard PDF 2.0.
	PDF_UA_1                       // PDF/UA-1 format.
	PDF_X_1A_2001                  // PDF/X-1a-2001 format.
	PDF_X_1A                       // PDF/X-1a format.
	PDF_X_3                        // PDF/X-3 format.
	ZUGFeRD                        // ZUGFeRD format.
	PDF_A_4                        // PDF/A-4 format.
	PDF_A_4E                       // PDF/A-4e format.
	PDF_A_4F                       // PDF/A-4f format.
	PDF_X_4                        // PDF/X-4 format.
	PDF_E_1                        // PDF/E-1 (PDF 1.6) format.
)
```

## Enumeration of possible conversion errors action.
```go
type ConvertErrorAction int32
const (
	Delete ConvertErrorAction = iota // Delete convert errors.
	None                             // Do nothing with convert errors.
)
```

## Bitflag set representing PDF permission capabilities.
```go
type Permissions int32
const (
    PrintDocument                  Permissions = 1 << 2  // 4
    ModifyContent                  Permissions = 1 << 3  // 8
    ExtractContent                 Permissions = 1 << 4  // 16
    ModifyTextAnnotations          Permissions = 1 << 5  // 32
    FillForm                       Permissions = 1 << 8  // 256
    ExtractContentWithDisabilities Permissions = 1 << 9  // 512
    AssembleDocument               Permissions = 1 << 10 // 1024
    PrintingQuality                Permissions = 1 << 11 // 2048
)
```
