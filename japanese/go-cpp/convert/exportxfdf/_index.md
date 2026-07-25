---
title: "ExportXfdf"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "AcroForm を含む以前に開いた PDF ドキュメントを XFDF ドキュメントにエクスポートします。"
type: docs
url: /ja/go-cpp/convert/exportxfdf/
---

_AcroForm を含む以前に開いた PDFドキュメントから XFDFドキュメントへエクスポートします。_

```go
func (document *Document) ExportXfdf(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// ExportXfdf(filename string) は、AcroForm を含む以前に開いた PDFドキュメントから指定されたファイル名で XFDFドキュメントへエクスポートします
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
