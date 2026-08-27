---
title: "PageToPdf"
second_title: "Aspose.PDF for Go via C++"
description: "将指定页面转换并保存为 PDF。"
type: docs
url: /zh/go-cpp/convert/pagetopdf/
---

_转换并保存指定页面为 Pdf._

```go
func (document *Document) PageToPdf(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToPdf(num int32, filename string) 将指定页面保存为 Pdf 文件
	err = pdf.PageToPdf(1, "sample_page1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
