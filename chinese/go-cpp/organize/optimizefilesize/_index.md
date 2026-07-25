---
title: "OptimizeFileSize"
second_title: "Aspose.PDF for Go via C++"
description: "通过图像压缩质量优化 PDF 文档的大小。"
type: docs
url: /zh/go-cpp/organize/optimizefilesize/
---

_通过图像压缩质量优化 PDF 文档的大小。_

```go
func (document *Document) OptimizeFileSize(imageQuality int32) error
```

**Parameters**: 
  * **imageQuality** - image compression quality 

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
        // OptimizeFileSize(imageQuality int32) 通过图像压缩质量优化 PDF 文档的大小
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
