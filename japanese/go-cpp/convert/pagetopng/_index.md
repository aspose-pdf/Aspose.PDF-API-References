---
title: "PageToPng"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "指定したページを Png 画像として変換して保存します。"
type: docs
url: /ja/go-cpp/convert/pagetopng/
---

_指定されたページを Png-image として変換し、保存します。_

```go
func (document *Document) PageToPng(num int32, resolution_dpi int32, filename string) error
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
	// PageToPng(num int32, resolution_dpi int32, filename string) は、指定されたページを Png-image ファイルとして保存します
	err = pdf.PageToPng(1, 100, "sample_page1.png")
	if err != nil {
		log.Fatal(err)
	}
}
```
