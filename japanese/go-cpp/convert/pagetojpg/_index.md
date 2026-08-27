---
title: "PageToJpg"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "指定したページを Jpg 画像として変換して保存します。"
type: docs
url: /ja/go-cpp/convert/pagetojpg/
---

_指定されたページを Jpg-image として変換し、保存します。_

```go
func (document *Document) PageToJpg(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
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
	// PageToJpg(num int32, resolution_dpi int32, filename string) は、指定されたページを Jpg-image ファイルとして保存します
	err = pdf.PageToJpg(1, 100, "sample_page1.jpg")
	if err != nil {
		log.Fatal(err)
	}
}
```
