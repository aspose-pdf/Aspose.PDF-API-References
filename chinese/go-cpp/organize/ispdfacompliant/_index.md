---
title: "IsPdfaCompliant"
second_title: "Aspose.PDF for Go via C++"
description: "获取 PDF 文档是否符合 PDF/A 标准。"
type: docs
url: /zh/go-cpp/organize/ispdfacompliant/
---

_Get 是符合 PDF/A 标准的 PDF 文档._

```go
func (document *Document) IsPdfaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/A compliant
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) 使用文件名打开 PDF-document
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// IsPdfaCompliant() 获取 PDF 文档的 PDF/A 合规状态
	isPdfa, _ := pdf.IsPdfaCompliant()
	if isPdfa {
		fmt.Println("IsPdfaCompliant() is true")
	} else {
		fmt.Println("IsPdfaCompliant() is false")
	}
}
```
