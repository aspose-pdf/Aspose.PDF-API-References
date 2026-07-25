---
title: "AddTextFooter"
second_title: "Aspose.PDF for Go via C++"
description: "在 PDF 文档的页脚中添加文本。"
type: docs
url: /zh/go-cpp/organize/addtextfooter/
---

_在 PDF-document 的页脚添加文本._

```go
func (document *Document) AddTextFooter(footer string) error
```

**Parameters**: 
  * **footer** - pages footer

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
	// AddTextFooter(footer string) 在 PDF-document 的页脚添加文本
	err = pdf.AddTextFooter("Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_AddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
