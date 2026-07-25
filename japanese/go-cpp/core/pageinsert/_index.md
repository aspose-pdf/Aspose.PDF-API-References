---
title: "PageInsert"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントの指定された位置に新しいページを挿入します。"
type: docs
url: /ja/go-cpp/core/pageinsert/
---

_指定された位置に新しいページを PDF ドキュメントに挿入します。_

```go
func (document *Document) PageInsert(num int32) error
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
	// PageInsert(num int32) は、指定された位置に新しいページを PDF ドキュメントに挿入します
	err = pdf.PageInsert(1)
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
