---
title: "SaveAs"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "以前に開いた PDF ドキュメントを新しいファイル名で保存します。"
type: docs
url: /ja/go-cpp/core/saveas/
---

_以前に開いた PDFドキュメントを新しいファイル名で保存します。_

```go
func (document *Document) SaveAs(filename string) error
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
	// New は新しい PDFドキュメントを作成します。
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
