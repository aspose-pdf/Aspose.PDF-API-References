---
title: "SaveDocX"
second_title: "Aspose.PDF for Go via C++"
description: "将先前打开的 PDF 文档转换并保存为 DocX 文档。"
type: docs
url: /zh/go-cpp/convert/savedocx/
---

_转换并保存先前打开的 PDF-document 为 DocX-document._

```go
func (document *Document) SaveDocX(filename string) error
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
	// Open(filename string) 使用文件名打开 PDF-document
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// SaveDocX(filename string) 将先前打开的 PDF-document 保存为 DocX-document，文件名为 filename
	err = pdf.SaveDocX("sample.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
