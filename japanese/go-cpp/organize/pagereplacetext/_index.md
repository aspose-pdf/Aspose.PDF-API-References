---
title: "PageReplaceText"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "ページ上のテキストを置換する。"
type: docs
url: /ja/go-cpp/organize/pagereplacetext/
---

_ページ上のテキストを置換します._

```go
func (document *Document) PageReplaceText(num int32, findText, replaceText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **findText** - text fragment to search
  * **replaceText** - text fragment to replace

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
	// PageReplaceText(num int32, findText, replaceText string) は ページ上のテキストを置換します
	err = pdf.PageReplaceText(1, "PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
	err = pdf.SaveAs("sample_page1_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
