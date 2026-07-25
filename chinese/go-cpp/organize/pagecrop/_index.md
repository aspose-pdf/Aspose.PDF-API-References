---
title: "PageCrop"
second_title: "Aspose.PDF for Go via C++"
description: "裁剪页面。"
type: docs
url: /zh/go-cpp/organize/pagecrop/
---

_裁剪页面._

```go
func (document *Document) PageCrop(num int32, margin float64) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **margin** - page margin

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
        // PageCrop(num int32, margin float64) 裁剪页面
        err = pdf.PageCrop(1, 11.3)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
        err = pdf.SaveAs("sample_page1_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
