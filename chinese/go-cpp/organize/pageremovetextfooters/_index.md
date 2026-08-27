---
title: "PageRemoveTextFooters"
second_title: "Aspose.PDF for Go via C++"
description: "删除页面中的文本页脚。"
type: docs
url: /zh/go-cpp/organize/pageremovetextfooters/
---

_移除页面中的文本页脚。_

```go
func (document *Document) PageRemoveTextFooters(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
        // PageRemoveTextFooters(num int32) 移除页面中的文本页脚
        err = pdf.PageRemoveTextFooters(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
        err = pdf.SaveAs("sample_page1_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
