---
title: "PageInsert"
second_title: "Aspose.PDF for Go via C++"
description: "在 PDF-document 中的指定位置插入新页面。"
type: docs
url: /zh/go-cpp/core/pageinsert/
---

_在 PDF 文档的指定位置插入新页面。_

```go
func (document *Document) PageInsert(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageInsert(num int32) 在 PDF 文档的指定位置插入新页面
	err = pdf.PageInsert(1)
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
