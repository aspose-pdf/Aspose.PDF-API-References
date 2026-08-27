---
title: "SaveTxt"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "以前に開いた PDF ドキュメントを Txt ドキュメントとして変換して保存します。"
type: docs
url: /ja/go-cpp/convert/savetxt/
---

_以前に開いた PDFドキュメントを Txtドキュメントに変換して保存します。_

```go
func (document *Document) SaveTxt(filename string) error
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
	// SaveTxt(filename string) は、以前に開いた PDFドキュメントを指定されたファイル名で Txtドキュメントとして保存します
	err = pdf.SaveTxt("sample.txt")
	if err != nil {
		log.Fatal(err)
	}
}
```
