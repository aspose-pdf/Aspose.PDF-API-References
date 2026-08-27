---
title: "ExportFdf"
second_title: "Aspose.PDF for Go via C++"
description: "从先前打开的带有 AcroForm 的 PDF 文档导出为 FDF 文档。"
type: docs
url: /zh/go-cpp/convert/exportfdf/
---

_从先前打开的带有 AcroForm 的 PDF-document 导出为 FDF-document._

```go
func (document *Document) ExportFdf(filename string) error
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
	// ExportFdf(filename string) 将先前打开的带有 AcroForm 的 PDF-document 导出为 FDF-document，文件名为 filename
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
