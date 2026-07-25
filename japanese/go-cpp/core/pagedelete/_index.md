---
title: "PageDelete"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントの指定されたページを削除します。"
type: docs
url: /ja/go-cpp/core/pagedelete/
---

_指定したページを PDFドキュメントから削除します。_

```go
func (document *Document) PageDelete(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageDelete(num int32) は指定したページを PDFドキュメントから削除します
	err = pdf.PageDelete(1)
	if err != nil {
		log.Fatal(err)
	}
	// Save() は以前に開いた PDFドキュメントを保存します
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
