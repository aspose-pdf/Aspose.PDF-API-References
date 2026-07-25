---
title: "Append"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "別の PDF ドキュメントからページを追加します。"
type: docs
url: /ja/go-cpp/core/append/
---

_別の PDFドキュメントからページを追加します。_

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

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

	// Open(filename string) は指定されたファイル名の別の PDFドキュメントを開きます
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) は別の PDFドキュメントからページを追加します。
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
