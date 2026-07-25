---
title: "Aspose.PDF for Go via C++"
description: "Aspose.PDF for Go via C++"
keywords:  "Go, Golang, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /zh/go-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Go via C++ allows developers manipulate them PDF files directly in the Go.

# Types

## Document
Document 表示一个 PDF 文档。

```go
type Document struct {
}
```

# Functions

## Convert from PDF functions

| 函数 | 描述 |
| -------- | ----------- |
| [SaveDocX](./convert/savedocx/) | 将先前打开的 PDF 文档转换并保存为 DocX 文档。 |
| [SaveDoc](./convert/savedoc/) | 将先前打开的 PDF 文档转换并保存为 Doc 文档。 |
| [SaveXlsX](./convert/savexlsx/) | 将先前打开的 PDF 文档转换并保存为 XlsX 文档。 |
| [SaveTxt](./convert/savetxt/) | 将先前打开的 PDF 文档转换并保存为 Txt 文档。 |
| [SavePptX](./convert/savepptx/) | 将先前打开的 PDF 文档转换并保存为 PptX 文档。 |
| [SaveXps](./convert/savexps/) | 将先前打开的 PDF 文档转换并保存为 Xps 文档。 |
| [SaveTeX](./convert/savetex/) | 将先前打开的 PDF 文档转换并保存为 TeX 文档。 |
| [SaveEpub](./convert/saveepub/) | 将先前打开的 PDF 文档转换并保存为 Epub 文档。 |
| [SaveBooklet](./convert/savebooklet/) | 将先前打开的 PDF 文档转换并保存为小册子 PDF 文档。 |
| [SaveNUp](./convert/savenup/) | 将先前打开的 PDF 文档转换并保存为 N-Up PDF 文档。 |
| [SaveMarkdown](./convert/savemarkdown/) | 将先前打开的 PDF 文档转换并保存为 Markdown 文档。 |
| [SaveTiff](./convert/savetiff/) | 将先前打开的 PDF 文档转换并保存为 Tiff 文档。 |
| [SaveDocXEnhanced](./convert/savedocxenhanced/) | 将先前打开的 PDF 文档转换并保存为 DocX 文档，使用增强识别模式（完全可编辑的表格和段落）。 |
| [SaveSvgZip](./convert/savesvgzip/) | 将先前打开的 PDF 文档转换并保存为 SVG 存档。 |
| [ExportFdf](./convert/exportfdf/) | 从先前打开的带有 AcroForm 的 PDF 文档导出为 FDF 文档。 |
| [ExportXfdf](./convert/exportxfdf/) | 从先前打开的带有 AcroForm 的 PDF 文档导出为 XFDF 文档。 |
| [ExportXml](./convert/exportxml/) | 从先前打开的带有 AcroForm 的 PDF 文档导出为 XML 文档。 |
| [PageToJpg](./convert/pagetojpg/) | 将指定页面转换并保存为 Jpg 图像。 |
| [PageToPng](./convert/pagetopng/) | 将指定页面转换并保存为 Png 图像。 |
| [PageToBmp](./convert/pagetobmp/) | 将指定页面转换并保存为 Bmp 图像。 |
| [PageToTiff](./convert/pagetotiff/) | 将指定页面转换并保存为 Tiff 图像。 |
| [PageToSvg](./convert/pagetosvg/) | 将指定页面转换并保存为 Svg 图像。 |
| [PageToPdf](./convert/pagetopdf/) | 将指定页面转换并保存为 PDF。 |
| [PageToDICOM](./convert/pagetodicom/) | 将指定页面转换并保存为 DICOM 图像。 |


## Organize PDF functions

| 函数 | 描述 |
| -------- | ----------- |
| [Optimize](./organize/optimize/) | 优化 PDF 文档内容。 |
| [OptimizeResource](./organize/optimizeresource/) | 优化 PDF 文档的资源。 |
| [Grayscale](./organize/grayscale/) | 将 PDF 文档转换为黑白。 |
| [Rotate](./organize/rotate/) | 旋转 PDF 文档。 |
| [SetBackground](./organize/setbackground/) | 设置 PDF 文档的背景颜色。 |
| [Repair](./organize/repair/) | 修复 PDF 文档。 |
| [ReplaceText](./organize/replacetext/) | 替换 PDF 文档中的文本。 |
| [AddPageNum](./organize/addpagenum/) | 向 PDF 文档添加页码。 |
| [AddTextHeader](./organize/addtextheader/) | 在 PDF 文档的页眉中添加文本。 |
| [AddTextFooter](./organize/addtextfooter/) | 在 PDF 文档的页脚中添加文本。 |
| [Flatten](./organize/flatten/) | 扁平化 PDF 文档。 |
| [RemoveAnnotations](./organize/removeannotations/) | 从 PDF 文档中移除注释。 |
| [RemoveAttachments](./organize/removeattachments/) | 从 PDF 文档中移除附件。 |
| [RemoveBlankPages](./organize/removeblankpages/) | 从 PDF 文档中移除空白页。 |
| [RemoveBookmarks](./organize/removebookmarks/) | 从 PDF 文档中移除书签。 |
| [RemoveHiddenText](./organize/removehiddentext/) | 从 PDF 文档中移除隐藏文本。 |
| [RemoveImages](./organize/removeimages/) | 从 PDF 文档中移除图像。 |
| [RemoveJavaScripts](./organize/removejavascripts/) | 从 PDF 文档中移除 Java 脚本。 |
| [RemoveTables](./organize/removetables/) | 从 PDF 文档中移除表格。 |
| [RemoveWatermarks](./organize/removewatermarks/) | 从 PDF 文档中移除水印。 |
| [AddWatermark](./organize/addwatermark/) | 向 PDF 文档添加水印。 |
| [EmbedFonts](./organize/embedfonts/) | 在 PDF 文档中嵌入字体。 |
| [UnembedFonts](./organize/unembedfonts/) | 取消嵌入 PDF 文档的字体。 |
| [OptimizeFileSize](./organize/optimizefilesize/) | 通过图像压缩质量优化 PDF 文档的大小。 |
| [RemoveTextHeaders](./organize/removetextheaders/) | 从 PDF 文档中删除文本页眉。 |
| [RemoveTextFooters](./organize/removetextfooters/) | 从 PDF 文档中删除文本页脚。 |
| [Crop](./organize/crop/) | 裁剪 PDF 文档的页面。 |
| [ReplaceFont](./organize/replacefont/) | 替换 PDF 文档中的字体。 |
| [Convert](./organize/convert/) | 将 PDF 文档转换为具有指定 PDF 格式的 PDF 文档。 |
| [Validate](./organize/validate/) | 验证 PDF 文档是否符合 PDF 格式。 |
| [RemovePdfaCompliance](./organize/removepdfacompliance/) | 从 PDF 文档中移除 PDF/A 合规性。 |
| [RemovePdfUaCompliance](./organize/removepdfuacompliance/) | 从 PDF 文档中移除 PDF/UA 合规性。 |
| [IsPdfaCompliant](./organize/ispdfacompliant/) | 获取 PDF 文档是否符合 PDF/A 标准。 |
| [IsPdfUaCompliant](./organize/ispdfuacompliant/) | 获取 PDF 文档是否符合 PDF/UA 标准。 |
| [PageRotate](./organize/pagerotate/) | 旋转页面。 |
| [PageSetSize](./organize/pagesetsize/) | 设置页面尺寸。 |
| [PageGrayscale](./organize/pagegrayscale/) | 将页面转换为黑白。 |
| [PageAddText](./organize/pageaddtext/) | 在页面上添加文本。 |
| [PageReplaceText](./organize/pagereplacetext/) | 替换页面上的文本。 |
| [PageAddPageNum](./organize/pageaddpagenum/) | 在页面上添加页码。 |
| [PageAddTextHeader](./organize/pageaddtextheader/) | 在页面页眉中添加文本。 |
| [PageAddTextFooter](./organize/pageaddtextfooter/) | 在页面页脚中添加文本。 |
| [PageRemoveAnnotations](./organize/pageremoveannotations/) | 删除页面中的注释。 |
| [PageRemoveHiddenText](./organize/pageremovehiddentext/) | 删除页面中的隐藏文本。 |
| [PageRemoveImages](./organize/pageremoveimages/) | 删除页面中的图像。 |
| [PageRemoveTables](./organize/pageremovetables/) | 删除页面中的表格。 |
| [PageRemoveWatermarks](./organize/pageremovewatermarks/) | 删除页面中的水印。 |
| [PageAddWatermark](./organize/pageaddwatermark/) | 在页面上添加水印。 |
| [PageRemoveTextHeaders](./organize/pageremovetextheaders/) | 删除页面中的文本页眉。 |
| [PageRemoveTextFooters](./organize/pageremovetextfooters/) | 删除页面中的文本页脚。 |
| [PageCrop](./organize/pagecrop/) | 裁剪页面。 |
| [PageReplaceFont](./organize/pagereplacefont/) | 替换页面中的字体。 |
| [PageMergeLayers](./organize/pagemergelayers/) | 将页面上的所有图层合并为单个图层，并使用指定的新图层名称。 |
| [PageLayers](./organize/pagelayers/) | 获取页面上图层的名称。 |


## Core PDF functions

| 函数 | 描述 |
| -------- | ----------- |
| [New](./core/new/) | 创建一个新的 PDF 文档。 |
| [Open](./core/open/) | 使用文件名打开 PDF 文档。 |
| [Save](./core/save/) | 保存先前打开的 PDF 文档。 |
| [SaveAs](./core/saveas/) | 使用新文件名保存先前打开的 PDF 文档。 |
| [Close](./core/close/) | 释放为 PDF 文档分配的资源。 |
| [SetLicense](./core/setlicense/) | 使用文件名设置许可证。 |
| [ExtractText](./core/extracttext/) | 以纯文本返回 PDF 文档的内容。 |
| [WordCount](./core/wordcount/) | 返回 PDF 文档中的单词数。 |
| [CharacterCount](./core/charactercount/) | 返回 PDF 文档中的字符数。 |
| [Append](./core/append/) | 追加来自另一个 PDF 文档的页面。 |
| [AppendPages](./core/appendpages/) | 追加来自另一个 PDF 文档的选定页面。 |
| [MergeDocuments](./core/mergedocuments/) | 通过合并提供的 PDF 文档创建一个新的 PDF 文档。 |
| [SplitDocument](./core/splitdocument/) | 通过从源 PDF 文档中提取页面创建多个新的 PDF 文档。 |
| [Split](./core/split/) | 通过从当前 PDF 文档中提取页面创建多个新的 PDF 文档。 |
| [SplitAtPage](./core/splitatpage/) | 将 PDF 文档拆分为两个新的 PDF 文档。 |
| [SplitAt](./core/splitat/) | 将当前 PDF 文档拆分为两个新的 PDF 文档。 |
| [Bytes](./core/bytes/) | 以字节切片返回 PDF 文档的内容。 |
| [GetMetaInfo](./core/getmetainfo/) | 获取 PDF 文档的元信息值.. |
| [SetMetaInfo](./core/setmetainfo/) | 设置 PDF-document 的元信息值.. |
| [ClearMetaInfo](./core/clearmetainfo/) | 清除 PDF-document 的所有元信息值.. |
| [IsLinearized](./core/islinearized/) | 获取指示文档是否线性化的值。 |
| [PageAdd](./core/pageadd/) | 在 PDF-document 中添加新页面。 |
| [PageInsert](./core/pageinsert/) | 在 PDF-document 中的指定位置插入新页面。 |
| [PageDelete](./core/pagedelete/) | 删除 PDF-document 中指定的页面。 |
| [PageCount](./core/pagecount/) | 返回 PDF-document 的页数。 |
| [PageWordCount](./core/pagewordcount/) | 返回 PDF-document 中指定页面的字数。 |
| [PageCharacterCount](./core/pagecharactercount/) | 返回 PDF-document 中指定页面的字符数。 |
| [PageIsBlank](./core/pageisblank/) | 返回 PDF-document 中页面是否为空白。 |


## Security

| 函数 | 描述 |
| -------- | ----------- |
| [OpenWithPassword](./security/openwithpassword/) | 打开受密码保护的 PDF-document。 |
| [Encrypt](./security/encrypt/) | 加密 PDF-document。 |
| [Decrypt](./security/decrypt/) | 解密 PDF-document。 |
| [SetPermissions](./security/setpermissions/) | 设置 PDF-document 的权限。 |
| [GetPermissions](./security/getpermissions/) | 获取 PDF-document 的当前权限。 |
| [IsEncrypted](./security/isencrypted/) | 获取 PDF-document 的加密状态。 |
| [SignPKCS7](./security/signpkcs7/) | 使用 PKCS#7 数字签名对 PDF-document 进行签名。 |
| [SignPKCS7Detached](./security/signpkcs7detached/) | 使用 PKCS#7 分离数字签名对 PDF-document 进行签名。 |
| [IsSigned](./security/issigned/) | 获取 PDF-document 的签名状态。 |
| [RemoveSigns](./security/removesigns/) | 从 PDF-document 中移除签名。 |


## Miscellaneous

| 函数 | 描述 |
| -------- | ----------- |
| [About](./miscellaneous/about/) | 返回关于通过 C++ 的 Aspose.PDF for Go 的元数据信息。 |


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
