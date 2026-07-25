---
title: "RemoveSigns"
second_title: "Aspose.PDF for Go via C++"
description: "从 PDF-document 中移除签名。"
type: docs
url: /zh/go-cpp/security/removesigns/
---

_从 PDF-document 中移除签名._

```go
func (document *Document) RemoveSigns(filename string) error
```

**Parameters**: 
  * **filename** - new filename, without signs

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) 使用文件名打开 PDF-document
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// RemoveSigns(filename string) 从 PDF-document 中移除签名
	err = pdf.RemoveSigns("sample_RemoveSigns.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
