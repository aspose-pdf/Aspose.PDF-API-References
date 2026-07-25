---
title: "Repair"
second_title: "Aspose.PDF for Go via C++"
description: "修复 PDF 文档。"
type: docs
url: /zh/go-cpp/organize/repair/
---

_修复 PDF 文档。_

```go
func (document *Document) Repair() error
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
	// Repair() 修复 PDF 文档
	err = pdf.Repair()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_Repair.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
