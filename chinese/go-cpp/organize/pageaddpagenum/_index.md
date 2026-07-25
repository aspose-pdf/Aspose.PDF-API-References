---
title: "PageAddPageNum"
second_title: "Aspose.PDF for Go via C++"
description: "在页面上添加页码。"
type: docs
url: /zh/go-cpp/organize/pageaddpagenum/
---

_在页面上添加页码。_

```go
func (document *Document) PageAddPageNum(num int32) error
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
	// PageAddPageNum(num int32) 在页面上添加页码
	err = pdf.PageAddPageNum(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_page1_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
