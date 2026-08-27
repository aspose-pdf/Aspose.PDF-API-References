---
title: "PageGrayscale"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "ページを白黒に変換する。"
type: docs
url: /ja/go-cpp/organize/pagegrayscale/
---

_ページを白黒に変換する._

```go
func (document *Document) PageGrayscale(num int32) error
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
	// PageGrayscale(num int32) ページを白黒に変換します
	err = pdf.PageGrayscale(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
	err = pdf.SaveAs("sample_page1_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
