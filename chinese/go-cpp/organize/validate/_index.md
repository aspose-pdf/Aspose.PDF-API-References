---
title: "Validate"
second_title: "Aspose.PDF for Go via C++"
description: "验证 PDF 文档是否符合 PDF 格式。"
type: docs
url: /zh/go-cpp/organize/validate/
---

_验证 PDF 文档是否符合 PDF 格式的规范。_

```go
func (document *Document) Validate(pdfFormat PdfFormat) (bool, string, error)
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

**Return**: 
  * **bool** - contains validation result
  * **string** - contains validation log
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
	// Open(filename string) 使用文件名打开 PDF-document
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()

	// Validate(pdfFormat PdfFormat) 验证 PDF 文档的 PDF/A 合规性
	ok, logStr, err := pdf.Validate(asposepdf.PDF_A_2A)
	if err != nil {
		log.Fatal("Validate PDF/A error:", err)
	}

	// 打印验证结果和完整日志
	fmt.Printf("Validate PDF/A result: %v\n", ok)
	fmt.Printf("Validate PDF/A log:\n%s\n", logStr)
}
```
