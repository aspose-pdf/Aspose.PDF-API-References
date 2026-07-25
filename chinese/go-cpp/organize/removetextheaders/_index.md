---
title: "RemoveTextHeaders"
second_title: "Aspose.PDF for Go via C++"
description: "从 PDF 文档中删除文本页眉。"
type: docs
url: /zh/go-cpp/organize/removetextheaders/
---

_从 PDF-document 中移除文本标题._

```go
func (document *Document) RemoveTextHeaders() error
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
        // RemoveTextHeaders() 从 PDF-document 中移除文本标题
        err = pdf.RemoveTextHeaders()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
        err = pdf.SaveAs("sample_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
