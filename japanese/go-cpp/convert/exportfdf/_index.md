---
title: "ExportFdf"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "AcroForm を含む以前に開いた PDF ドキュメントを FDF ドキュメントにエクスポートします。"
type: docs
url: /ja/go-cpp/convert/exportfdf/
---

_AcroForm を含む以前に開いた PDF-document から FDF-document へエクスポートします。_

```go
func (document *Document) ExportFdf(filename string) error
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
	// ExportFdf(filename string) は、AcroForm を含む以前に開いた PDF-document から FDF-document を指定されたファイル名でエクスポートします
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
