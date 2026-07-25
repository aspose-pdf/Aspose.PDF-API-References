---
title: "PageReplaceText"
second_title: "Aspose.PDF for Go via C++"
description: "替换页面上的文本。"
type: docs
url: /zh/go-cpp/organize/pagereplacetext/
---

_在页面上替换文本._

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
	// Open(filename string) 使用文件名打开 PDF-document
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// PageReplaceText(num int32, findText, replaceText string) 在页面上替换文本
	err = pdf.PageReplaceText(1, "PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_page1_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
