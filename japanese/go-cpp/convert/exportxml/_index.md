---
title: "ExportXml"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "AcroForm を含む以前に開いた PDF ドキュメントを XML ドキュメントにエクスポートします。"
type: docs
url: /ja/go-cpp/convert/exportxml/
---

_AcroForm を含む以前に開いた PDF-document から XML-document へエクスポートします._

```go
func (document *Document) ExportXml(filename string) error
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
	// ExportXml(filename string) は、AcroForm を含む以前に開いた PDF-document から XML-document へ、指定したファイル名でエクスポートします
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
