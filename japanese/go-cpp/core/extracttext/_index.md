---
title: "ExtractText"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDF ドキュメントの内容をプレーンテキストとして返します。"
type: docs
url: /ja/go-cpp/core/extracttext/
---

_Return the PDF-document contents as plain text._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
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
	// ExtractText() は PDF ドキュメントの内容をプレーンテキストとして返します
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Extracted text:\n", txt)
}
```
