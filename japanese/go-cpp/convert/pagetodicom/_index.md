---
title: "PageToDICOM"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "指定されたページをDICOM画像として変換し保存します。"
type: docs
url: /ja/go-cpp/convert/pagetodicom/
---

_指定されたページを DICOM-image として変換し保存します._

```go
func (document *Document) PageToDICOM(num int32, resolution_dpi int32, filename string) error
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
	// PageToDICOM(num int32, resolution_dpi int32, filename string) は、指定されたページを DICOM-image ファイルとして保存します
	err = pdf.PageToDICOM(1, 100, "sample_page1.dcm")
	if err != nil {
		log.Fatal(err)
	}
}
```
