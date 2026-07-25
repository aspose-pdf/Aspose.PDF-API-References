---
title: "PageMergeLayers"
second_title: "Aspose.PDF for Go via C++"
description: "将页面上的所有图层合并为单个图层，并使用指定的新图层名称。"
type: docs
url: /zh/go-cpp/organize/pagemergelayers/
---

_将页面上的所有图层合并为具有指定新图层名称的单个图层._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

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
	// PageMergeLayers(num int32, newLayerName string) 将页面上的所有图层合并为具有指定新图层名称的单个图层
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
