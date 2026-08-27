---
title: "C++를 통한 Go용 Aspose.PDF"
description: "C++를 통한 Go용 Aspose.PDF"
keywords:  "Go, Golang, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /ko/go-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Go via C++ allows developers manipulate them PDF files directly in the Go.

# Types

## Document
Document는 PDF-document를 나타냅니다.

```go
type Document struct {
}
```

# Functions

## Convert from PDF functions

| 함수 | 설명 |
| -------- | ----------- |
| [SaveDocX](./convert/savedocx/) | 이전에 열었던 PDF-document를 DocX-document로 변환하고 저장합니다. |
| [SaveDoc](./convert/savedoc/) | 이전에 열었던 PDF-document를 Doc-document로 변환하고 저장합니다. |
| [SaveXlsX](./convert/savexlsx/) | 이전에 열었던 PDF-document를 XlsX-document로 변환하고 저장합니다. |
| [SaveTxt](./convert/savetxt/) | 이전에 열었던 PDF-document를 Txt-document로 변환하고 저장합니다. |
| [SavePptX](./convert/savepptx/) | 이전에 열었던 PDF-document를 PptX-document로 변환하고 저장합니다. |
| [SaveXps](./convert/savexps/) | 이전에 열었던 PDF-document를 Xps-document로 변환하고 저장합니다. |
| [SaveTeX](./convert/savetex/) | 이전에 열었던 PDF-document를 TeX-document로 변환하고 저장합니다. |
| [SaveEpub](./convert/saveepub/) | 이전에 열었던 PDF-document를 Epub-document로 변환하고 저장합니다. |
| [SaveBooklet](./convert/savebooklet/) | 이전에 열었던 PDF-document를 소책자 PDF-document로 변환하고 저장합니다. |
| [SaveNUp](./convert/savenup/) | 이전에 열었던 PDF-document를 N-Up PDF-document로 변환하고 저장합니다. |
| [SaveMarkdown](./convert/savemarkdown/) | 이전에 열었던 PDF-document를 Markdown-document로 변환하고 저장합니다. |
| [SaveTiff](./convert/savetiff/) | 이전에 열었던 PDF-document를 Tiff-document로 변환하고 저장합니다. |
| [SaveDocXEnhanced](./convert/savedocxenhanced/) | 이전에 열었던 PDF-document를 향상된 인식 모드가 적용된 DocX-document로 변환하고 저장합니다(완전 편집 가능한 표와 단락). |
| [SaveSvgZip](./convert/savesvgzip/) | 이전에 열었던 PDF-document를 SVG-archive로 변환하고 저장합니다. |
| [ExportFdf](./convert/exportfdf/) | AcroForm이 포함된 이전에 열었던 PDF-document를 FDF-document로 내보냅니다. |
| [ExportXfdf](./convert/exportxfdf/) | AcroForm이 포함된 이전에 열었던 PDF-document를 XFDF-document로 내보냅니다. |
| [ExportXml](./convert/exportxml/) | AcroForm이 포함된 이전에 열었던 PDF-document를 XML-document로 내보냅니다. |
| [PageToJpg](./convert/pagetojpg/) | 지정된 페이지를 Jpg-image로 변환하고 저장합니다. |
| [PageToPng](./convert/pagetopng/) | 지정된 페이지를 Png-image로 변환하고 저장합니다. |
| [PageToBmp](./convert/pagetobmp/) | 지정된 페이지를 Bmp-image로 변환하고 저장합니다. |
| [PageToTiff](./convert/pagetotiff/) | 지정된 페이지를 Tiff-image로 변환하고 저장합니다. |
| [PageToSvg](./convert/pagetosvg/) | 지정된 페이지를 Svg-image로 변환하고 저장합니다. |
| [PageToPdf](./convert/pagetopdf/) | 지정된 페이지를 Pdf로 변환하고 저장합니다. |
| [PageToDICOM](./convert/pagetodicom/) | 지정된 페이지를 DICOM 이미지로 변환하고 저장합니다. |


## Organize PDF functions

| 함수 | 설명 |
| -------- | ----------- |
| [Optimize](./organize/optimize/) | PDF-document의 콘텐츠를 최적화합니다. |
| [OptimizeResource](./organize/optimizeresource/) | PDF-document의 리소스를 최적화합니다. |
| [Grayscale](./organize/grayscale/) | PDF-document를 흑백으로 변환합니다. |
| [Rotate](./organize/rotate/) | PDF-document를 회전합니다. |
| [SetBackground](./organize/setbackground/) | PDF-document 배경 색상을 설정합니다. |
| [Repair](./organize/repair/) | PDF-document를 복구합니다. |
| [ReplaceText](./organize/replacetext/) | PDF-document의 텍스트를 교체합니다. |
| [AddPageNum](./organize/addpagenum/) | PDF-document에 페이지 번호를 추가합니다. |
| [AddTextHeader](./organize/addtextheader/) | PDF-document의 헤더에 텍스트를 추가합니다. |
| [AddTextFooter](./organize/addtextfooter/) | PDF-document의 푸터에 텍스트를 추가합니다. |
| [Flatten](./organize/flatten/) | PDF-document를 평탄화합니다. |
| [RemoveAnnotations](./organize/removeannotations/) | PDF-document에서 주석을 제거합니다. |
| [RemoveAttachments](./organize/removeattachments/) | PDF-document에서 첨부 파일을 제거합니다. |
| [RemoveBlankPages](./organize/removeblankpages/) | PDF-document에서 빈 페이지를 제거합니다. |
| [RemoveBookmarks](./organize/removebookmarks/) | PDF-document에서 북마크를 제거합니다. |
| [RemoveHiddenText](./organize/removehiddentext/) | PDF-document에서 숨겨진 텍스트를 제거합니다. |
| [RemoveImages](./organize/removeimages/) | PDF-document에서 이미지를 제거합니다. |
| [RemoveJavaScripts](./organize/removejavascripts/) | PDF-document에서 자바스크립트를 제거합니다. |
| [RemoveTables](./organize/removetables/) | PDF-document에서 표를 제거합니다. |
| [RemoveWatermarks](./organize/removewatermarks/) | PDF-document에서 워터마크를 제거합니다. |
| [AddWatermark](./organize/addwatermark/) | PDF-document에 워터마크를 추가합니다. |
| [EmbedFonts](./organize/embedfonts/) | PDF-document에 글꼴을 포함합니다. |
| [UnembedFonts](./organize/unembedfonts/) | PDF-document에서 글꼴 포함을 해제합니다. |
| [OptimizeFileSize](./organize/optimizefilesize/) | 이미지 압축 품질을 사용하여 PDF-document의 크기를 최적화합니다. |
| [RemoveTextHeaders](./organize/removetextheaders/) | PDF-document에서 텍스트 헤더를 제거합니다. |
| [RemoveTextFooters](./organize/removetextfooters/) | PDF-document에서 텍스트 푸터를 제거합니다. |
| [Crop](./organize/crop/) | PDF-document의 페이지를 자릅니다. |
| [ReplaceFont](./organize/replacefont/) | PDF-document의 글꼴을 교체합니다. |
| [Convert](./organize/convert/) | PDF-document를 지정된 PDF 형식의 PDF-document로 변환합니다. |
| [Validate](./organize/validate/) | PDF-document가 PDF 형식에 부합하는지 검증합니다. |
| [RemovePdfaCompliance](./organize/removepdfacompliance/) | PDF-document에서 PDF/A 준수를 제거합니다. |
| [RemovePdfUaCompliance](./organize/removepdfuacompliance/) | PDF-document에서 PDF/UA 준수를 제거합니다. |
| [IsPdfaCompliant](./organize/ispdfacompliant/) | PDF-document가 PDF/A 준수인지 확인합니다. |
| [IsPdfUaCompliant](./organize/ispdfuacompliant/) | PDF-document가 PDF/UA 준수인지 확인합니다. |
| [PageRotate](./organize/pagerotate/) | 페이지를 회전합니다. |
| [PageSetSize](./organize/pagesetsize/) | 페이지 크기를 설정합니다. |
| [PageGrayscale](./organize/pagegrayscale/) | 페이지를 흑백으로 변환합니다. |
| [PageAddText](./organize/pageaddtext/) | 페이지에 텍스트를 추가합니다. |
| [PageReplaceText](./organize/pagereplacetext/) | 페이지의 텍스트를 교체합니다. |
| [PageAddPageNum](./organize/pageaddpagenum/) | 페이지에 페이지 번호를 추가합니다. |
| [PageAddTextHeader](./organize/pageaddtextheader/) | 페이지 헤더에 텍스트를 추가합니다. |
| [PageAddTextFooter](./organize/pageaddtextfooter/) | 페이지 푸터에 텍스트를 추가합니다. |
| [PageRemoveAnnotations](./organize/pageremoveannotations/) | 페이지의 주석을 제거합니다. |
| [PageRemoveHiddenText](./organize/pageremovehiddentext/) | 페이지의 숨겨진 텍스트를 제거합니다. |
| [PageRemoveImages](./organize/pageremoveimages/) | 페이지의 이미지를 제거합니다. |
| [PageRemoveTables](./organize/pageremovetables/) | 페이지의 표를 제거합니다. |
| [PageRemoveWatermarks](./organize/pageremovewatermarks/) | 페이지의 워터마크를 제거합니다. |
| [PageAddWatermark](./organize/pageaddwatermark/) | 페이지에 워터마크를 추가합니다. |
| [PageRemoveTextHeaders](./organize/pageremovetextheaders/) | 페이지의 텍스트 헤더를 제거합니다. |
| [PageRemoveTextFooters](./organize/pageremovetextfooters/) | 페이지에서 텍스트 바닥글을 제거합니다. |
| [PageCrop](./organize/pagecrop/) | 페이지를 자릅니다. |
| [PageReplaceFont](./organize/pagereplacefont/) | 페이지의 글꼴을 교체합니다. |
| [PageMergeLayers](./organize/pagemergelayers/) | 페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어로 병합합니다. |
| [PageLayers](./organize/pagelayers/) | 페이지의 레이어 이름을 가져옵니다. |


## Core PDF functions

| 함수 | 설명 |
| -------- | ----------- |
| [New](./core/new/) | 새 PDF 문서를 생성합니다. |
| [Open](./core/open/) | 파일 이름으로 PDF 문서를 엽니다. |
| [Save](./core/save/) | 이전에 연 PDF 문서를 저장합니다. |
| [SaveAs](./core/saveas/) | 이전에 연 PDF 문서를 새 파일 이름으로 저장합니다. |
| [Close](./core/close/) | PDF 문서에 할당된 리소스를 해제합니다. |
| [SetLicense](./core/setlicense/) | 파일 이름으로 라이선스를 설정합니다. |
| [ExtractText](./core/extracttext/) | PDF 문서 내용을 일반 텍스트로 반환합니다. |
| [WordCount](./core/wordcount/) | PDF 문서의 단어 수를 반환합니다. |
| [CharacterCount](./core/charactercount/) | PDF 문서의 문자 수를 반환합니다. |
| [Append](./core/append/) | 다른 PDF 문서에서 페이지를 추가합니다. |
| [AppendPages](./core/appendpages/) | 다른 PDF 문서에서 선택한 페이지를 추가합니다. |
| [MergeDocuments](./core/mergedocuments/) | 제공된 PDF 문서를 병합하여 새 PDF 문서를 생성합니다. |
| [SplitDocument](./core/splitdocument/) | 소스 PDF 문서에서 페이지를 추출하여 여러 새 PDF 문서를 생성합니다. |
| [Split](./core/split/) | 현재 PDF 문서에서 페이지를 추출하여 여러 새 PDF 문서를 생성합니다. |
| [SplitAtPage](./core/splitatpage/) | PDF 문서를 두 개의 새 PDF 문서로 분할합니다. |
| [SplitAt](./core/splitat/) | 현재 PDF 문서를 두 개의 새 PDF 문서로 분할합니다. |
| [Bytes](./core/bytes/) | PDF 문서의 내용을 바이트 슬라이스로 반환합니다. |
| [GetMetaInfo](./core/getmetainfo/) | PDF 문서의 메타 정보 값을 가져옵니다. |
| [SetMetaInfo](./core/setmetainfo/) | PDF 문서의 메타 정보 값을 설정합니다. |
| [ClearMetaInfo](./core/clearmetainfo/) | PDF 문서의 모든 메타 정보 값을 삭제합니다. |
| [IsLinearized](./core/islinearized/) | 문서가 선형화되었는지 여부를 나타내는 값을 가져옵니다. |
| [PageAdd](./core/pageadd/) | PDF-document에 새 페이지를 추가합니다. |
| [PageInsert](./core/pageinsert/) | PDF-document에서 지정된 위치에 새 페이지를 삽입합니다. |
| [PageDelete](./core/pagedelete/) | PDF-document에서 지정된 페이지를 삭제합니다. |
| [PageCount](./core/pagecount/) | PDF-document의 페이지 수를 반환합니다. |
| [PageWordCount](./core/pagewordcount/) | PDF-document의 지정된 페이지에 대한 단어 수를 반환합니다. |
| [PageCharacterCount](./core/pagecharactercount/) | PDF-document의 지정된 페이지에 대한 문자 수를 반환합니다. |
| [PageIsBlank](./core/pageisblank/) | PDF-document의 페이지가 비어 있는지 반환합니다. |


## Security

| 함수 | 설명 |
| -------- | ----------- |
| [OpenWithPassword](./security/openwithpassword/) | 암호로 보호된 PDF-document를 엽니다. |
| [Encrypt](./security/encrypt/) | PDF-document를 암호화합니다. |
| [Decrypt](./security/decrypt/) | PDF-document를 복호화합니다. |
| [SetPermissions](./security/setpermissions/) | PDF-document에 대한 권한을 설정합니다. |
| [GetPermissions](./security/getpermissions/) | PDF-document의 현재 권한을 가져옵니다. |
| [IsEncrypted](./security/isencrypted/) | PDF-document의 암호화 상태를 가져옵니다. |
| [SignPKCS7](./security/signpkcs7/) | PKCS#7 디지털 서명을 사용하여 PDF-document에 서명합니다. |
| [SignPKCS7Detached](./security/signpkcs7detached/) | PKCS#7 Detached 디지털 서명을 사용하여 PDF-document에 서명합니다. |
| [IsSigned](./security/issigned/) | PDF-document의 서명 상태를 가져옵니다. |
| [RemoveSigns](./security/removesigns/) | PDF-document에서 서명을 제거합니다. |


## Miscellaneous

| 함수 | 설명 |
| -------- | ----------- |
| [About](./miscellaneous/about/) | C++를 통해 Aspose.PDF for Go에 대한 메타데이터 정보를 반환합니다. |


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
