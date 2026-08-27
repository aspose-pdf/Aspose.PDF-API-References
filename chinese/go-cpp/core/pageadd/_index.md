---
title: "PageAdd"
second_title: "Aspose.PDF for Go via C++"
description: "在 PDF-document 中添加新页面。"
type: docs
url: /zh/go-cpp/core/pageadd/
---

_在 PDF-document 中添加新页面。_

```go
func (document *Document) PageAdd() error
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
	// PageAdd() 在 PDF-document 中添加新页面
	err = pdf.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Save() 保存先前打开的 PDF-document
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
