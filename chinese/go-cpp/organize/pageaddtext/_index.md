---
title: "PageAddText"
second_title: "Aspose.PDF for Go via C++"
description: "在页面上添加文本。"
type: docs
url: /zh/go-cpp/organize/pageaddtext/
---

_在页面上添加文本。_

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string) 在页面上添加文本
	err = pdf.PageAddText(1, "added text")
	if err != nil {
		log.Fatal(err)
	}
	// Save() 保存先前打开的 PDF-document
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
