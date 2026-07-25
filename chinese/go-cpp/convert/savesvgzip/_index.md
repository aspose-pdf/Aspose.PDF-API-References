---
title: "SaveSvgZip"
second_title: "Aspose.PDF for Go via C++"
description: "将先前打开的 PDF 文档转换并保存为 SVG 存档。"
type: docs
url: /zh/go-cpp/convert/savesvgzip/
---

_转换并保存先前打开的 PDF 文档为 SVG 存档._

```go
func (document *Document) SaveSvgZip(filename string) error
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
	// SaveSvgZip(filename string) 将先前打开的 PDF 文档保存为 SVG 存档，使用指定的文件名
	err = pdf.SaveSvgZip("sample_svg.zip")
	if err != nil {
		log.Fatal(err)
	}
}
```
