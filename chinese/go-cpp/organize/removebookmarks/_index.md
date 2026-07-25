---
title: "RemoveBookmarks"
second_title: "Aspose.PDF for Go via C++"
description: "从 PDF 文档中移除书签。"
type: docs
url: /zh/go-cpp/organize/removebookmarks/
---

_从 PDF 文档中移除书签。_

```go
func (document *Document) RemoveBookmarks() error
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
	// RemoveBookmarks() 移除 PDF 文档中的书签
	err = pdf.RemoveBookmarks()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_RemoveBookmarks.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
