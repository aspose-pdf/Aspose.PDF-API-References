---
title: "IsPdfaCompliant"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントがPDF/Aに準拠しているか取得する。"
type: docs
url: /ja/go-cpp/organize/ispdfacompliant/
---

_PDFドキュメントがPDF/Aに準拠しているか取得します._

```go
func (document *Document) IsPdfaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/A compliant
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// IsPdfaCompliant() は PDF ドキュメントの PDF/A 準拠ステータスを取得します
	isPdfa, _ := pdf.IsPdfaCompliant()
	if isPdfa {
		fmt.Println("IsPdfaCompliant() is true")
	} else {
		fmt.Println("IsPdfaCompliant() is false")
	}
}
```
