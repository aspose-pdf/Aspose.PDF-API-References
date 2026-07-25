---
title: "AddPageNum"
second_title: "Aspose.PDF for Go via C++"
description: "向 PDF 文档添加页码。"
type: docs
url: /zh/go-cpp/organize/addpagenum/
---

_向 PDF-document 添加页码._

```go
func (document *Document) AddPageNum() error
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
	// Open(filename string) 使用文件名打开 PDF-document
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// AddPageNum() 向 PDF-document 添加页码
	err = pdf.AddPageNum()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
