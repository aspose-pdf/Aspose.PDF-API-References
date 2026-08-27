---
title: "Crop"
second_title: "Aspose.PDF for Go via C++"
description: "裁剪 PDF 文档的页面。"
type: docs
url: /zh/go-cpp/organize/crop/
---

_裁剪 PDF-document 的页面。_

```go
func (document *Document) Crop(margin float64) error
```

**Parameters**: 
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
        // Crop(margin float64) 裁剪 PDF-document 的页面
        err = pdf.Crop(0)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
        err = pdf.SaveAs("sample_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
