---
title: "PageAddText"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "ページにテキストを追加する。"
type: docs
url: /ja/go-cpp/organize/pageaddtext/
---

_ページにテキストを追加します._

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string) ページにテキストを追加します
	err = pdf.PageAddText(1, "added text")
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
