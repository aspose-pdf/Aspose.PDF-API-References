---
title: "SaveDocX"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "以前に開いた PDF ドキュメントを DocX ドキュメントとして変換して保存します。"
type: docs
url: /ja/go-cpp/convert/savedocx/
---

_変換して、以前に開いた PDF-document を DocX-document として保存します。_

```go
func (document *Document) SaveDocX(filename string) error
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
	// SaveDocX(filename string) は、以前に開いた PDF-document を DocX-document として、指定されたファイル名で保存します
	err = pdf.SaveDocX("sample.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
