---
title: "Close"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDF ドキュメントの割り当てられたリソースを解放します。"
type: docs
url: /ja/go-cpp/core/close/
---

_Release allocated resources for PDF-document._

```go
func (document *Document) Close() error
```

**Parameters**: 

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
