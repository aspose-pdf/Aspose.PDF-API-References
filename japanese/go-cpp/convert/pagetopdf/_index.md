---
title: "PageToPdf"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "指定されたページをPdfとして変換し保存します。"
type: docs
url: /ja/go-cpp/convert/pagetopdf/
---

_指定されたページを Pdf として変換し、保存します。_

```go
func (document *Document) PageToPdf(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToPdf(num int32, filename string) は、指定されたページを Pdf ファイルとして保存します
	err = pdf.PageToPdf(1, "sample_page1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
