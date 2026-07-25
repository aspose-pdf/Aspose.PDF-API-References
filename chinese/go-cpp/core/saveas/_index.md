---
title: "SaveAs"
second_title: "Aspose.PDF for Go via C++"
description: "使用新文件名保存先前打开的 PDF 文档。"
type: docs
url: /zh/go-cpp/core/saveas/
---

_保存先前打开的 PDF-document 为新文件名._

```go
func (document *Document) SaveAs(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New 创建一个新的 PDF-document
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
