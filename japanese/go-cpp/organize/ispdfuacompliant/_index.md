---
title: "IsPdfUaCompliant"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントがPDF/UAに準拠しているか取得する。"
type: docs
url: /ja/go-cpp/organize/ispdfuacompliant/
---

_PDFドキュメントがPDF/UAに準拠しているか取得します._

```go
func (document *Document) IsPdfUaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/UA compliant
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
	// IsPdfUaCompliant() PDFドキュメントのPDF/UA準拠ステータスを取得します
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
