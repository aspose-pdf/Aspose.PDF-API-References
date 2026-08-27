---
title: "PageToSvg"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "指定されたページをSvg画像として変換し保存します。"
type: docs
url: /ja/go-cpp/convert/pagetosvg/
---

_指定されたページを Svg-image として変換し保存します._

```go
func (document *Document) PageToSvg(num int32, filename string) error
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
	// PageToSvg(num int32, filename string) は、指定されたページを Svg画像 ファイルとして保存します
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
