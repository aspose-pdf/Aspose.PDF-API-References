---
title: "Save"
second_title: "Aspose.PDF for Go via C++"
description: "保存先前打开的 PDF 文档。"
type: docs
url: /zh/go-cpp/core/save/
---

_保存先前打开的 PDF-document。_

```go
func (document *Document) Save() error
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
	// Save() 保存先前打开的 PDF-document
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
