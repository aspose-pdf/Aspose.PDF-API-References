---
title: "ReplaceFont"
second_title: "Aspose.PDF for Go via C++"
description: "替换 PDF 文档中的字体。"
type: docs
url: /zh/go-cpp/organize/replacefont/
---

_在 PDF 文档中替换字体._

```go
func (document *Document) ReplaceFont(findFontName, replaceFontName string) error
```

**Parameters**: 
  * **findFontName** - font name to search
  * **replaceFontName** - font name to replace

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
        // ReplaceFont(findFontName, replaceFontName string) 在 PDF 文档中替换字体
        err = pdf.ReplaceFont("Helvetica", "Courier")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
        err = pdf.SaveAs("sample_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
