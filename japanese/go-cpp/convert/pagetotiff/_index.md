---
title: "PageToTiff"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "指定したページを Tiff 画像として変換して保存します。"
type: docs
url: /ja/go-cpp/convert/pagetotiff/
---

_指定されたページを Tiff-image として変換し、保存します。_

```go
func (document *Document) PageToTiff(num int32, resolution_dpi int32, filename string) error
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
	// PageToTiff(num int32, resolution_dpi int32, filename string) は、指定されたページを Tiff-image ファイルとして保存します
	err = pdf.PageToTiff(1, 100, "sample_page1.tiff")
	if err != nil {
		log.Fatal(err)
	}
}
```
