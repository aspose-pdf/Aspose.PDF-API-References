---
title: "PageIsBlank"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントのページが空白かどうかを返します。"
type: docs
url: /ja/go-cpp/core/pageisblank/
---

_PDF ドキュメントのページが空白かどうかを返します。_

```go
func (document *Document) PageIsBlank(num int32) (bool, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **bool** - the page is blank
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// PageIsBlank(num int32) は、PDF ドキュメントのページが空白かどうかを返します。
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
