---
title: "SaveXps"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "以前に開いた PDF ドキュメントを Xps ドキュメントとして変換して保存します。"
type: docs
url: /ja/go-cpp/convert/savexps/
---

_以前に開いた PDF-document を Xps-document として変換して保存します._

```go
func (document *Document) SaveXps(filename string) error
```

**Parameters**: 
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
	// SaveXps(filename string) は、以前に開いた PDF-document を Xps-document として、指定したファイル名で保存します
	err = pdf.SaveXps("sample.xps")
	if err != nil {
		log.Fatal(err)
	}
}
```
