---
title: "SetMetaInfo"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "Set meta information value of PDF-document."
type: docs
url: /ja/go-cpp/core/setmetainfo/
---

_Set meta information value of PDF-document._

```go
func (document *Document) SetMetaInfo(key, value string) error
```

**Parameters**: 
  * **key** - key whose value to set
  * **value** - value to be set

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
	// SetMetaInfo(key, value string) sets meta information value of PDF-document
	err = pdf.SetMetaInfo("Author", "Aspose")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
	err = pdf.SaveAs("sample_SetMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
