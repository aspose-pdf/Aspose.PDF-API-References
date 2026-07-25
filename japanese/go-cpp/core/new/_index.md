---
title: "New"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "新しい PDF ドキュメントを作成します。"
type: docs
url: /ja/go-cpp/core/new/
---

_新しい PDF ドキュメントを作成します。_

```go
func New() (*Document, error)
```

**Parameters**: 

**Return**:
  * **\*Document** - pointer to document
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
