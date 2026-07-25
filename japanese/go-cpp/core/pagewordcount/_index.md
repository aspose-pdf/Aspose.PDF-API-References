---
title: "PageWordCount"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントの指定ページの単語数を返します。"
type: docs
url: /ja/go-cpp/core/pagewordcount/
---

_指定されたページの単語数を PDF ドキュメントから返します。_

```go
func (document *Document) PageWordCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - word count on the page
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
	// PageWordCount(num int32) は指定されたページの単語数を PDF ドキュメントから返します。
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count on the first page:", page_word_count)
}
```
