---
title: "PageToBmp"
second_title: "Aspose.PDF for Go via C++"
description: "将指定页面转换并保存为 Bmp 图像。"
type: docs
url: /zh/go-cpp/convert/pagetobmp/
---

_转换并保存指定页面为 Bmp-image。_

```go
func (document *Document) PageToBmp(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
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
	// PageToBmp(num int32, resolution_dpi int32, filename string) 将指定页面保存为 Bmp-image 文件
	err = pdf.PageToBmp(1, 100, "sample_page1.bmp")
	if err != nil {
		log.Fatal(err)
	}
}
```
