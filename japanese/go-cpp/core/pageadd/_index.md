---
title: "PageAdd"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントに新しいページを追加します。"
type: docs
url: /ja/go-cpp/core/pageadd/
---

_PDF ドキュメントに新しいページを追加します。_

```go
func (document *Document) PageAdd() error
```

**Parameters**: 

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
	// PageAdd() は PDF ドキュメントに新しいページを追加します
	err = pdf.PageAdd()
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
