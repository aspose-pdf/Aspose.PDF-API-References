---
title: "PageRemoveTables"
second_title: "Aspose.PDF for Go via C++"
description: "删除页面中的表格。"
type: docs
url: /zh/go-cpp/organize/pageremovetables/
---

_移除页面中的表格。_

```go
func (document *Document) PageRemoveTables(num int32) error
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
	// PageRemoveTables(num int32) 移除页面中的表格
	err = pdf.PageRemoveTables(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_page1_RemoveTables.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
