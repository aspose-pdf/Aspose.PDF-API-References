---
title: "変換"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントを指定されたPDF形式のPDFドキュメントに変換する。"
type: docs
url: /ja/go-cpp/organize/convert/
---

_指定された PDF フォーマットで PDF ドキュメントを PDF ドキュメントに変換します。_

```go
func (document *Document) Convert(pdfFormat PdfFormat, action ConvertErrorAction) (bool, string, error)
```

**Parameters**: 
  * **pdfFormat** - PDF format:
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
  * **action** - conversion errors action:
```go
// 可能な変換エラー アクションの列挙。
type ConvertErrorAction int32
const (
	Delete ConvertErrorAction = iota // Delete convert errors.
	None                             // Do nothing with convert errors.
)
```

**Return**: 
  * **bool** - contains conversion result
  * **string** - contains conversion log
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()

	// Convert(pdfFormat PdfFormat, action ConvertErrorAction) は PDF ドキュメントを PDF/A に変換します
	ok, logStr, err := pdf.Convert(asposepdf.PDF_A_2A, asposepdf.Delete)
	if err != nil {
		log.Fatal("Convert PDF/A error:", err)
	}

	// 変換結果と完全なログを出力
	fmt.Printf("Convert PDF/A result: %v\n", ok)
	fmt.Printf("Convert PDF/A log:\n%s\n", logStr)

	// 変換された PDF ドキュメントを保存
	err = pdf.SaveAs("sample_Convert.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
