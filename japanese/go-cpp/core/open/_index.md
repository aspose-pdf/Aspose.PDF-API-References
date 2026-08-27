---
title: "Open"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "ファイル名で PDF ドキュメントを開きます。"
type: docs
url: /ja/go-cpp/core/open/
---

_ファイル名で PDFドキュメントを開きます。_

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

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
	// Save() は以前に開いた PDFドキュメントを保存します
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
