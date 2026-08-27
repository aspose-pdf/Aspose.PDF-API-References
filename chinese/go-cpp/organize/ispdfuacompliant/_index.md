---
title: "IsPdfUaCompliant"
second_title: "Aspose.PDF for Go via C++"
description: "获取 PDF 文档是否符合 PDF/UA 标准。"
type: docs
url: /zh/go-cpp/organize/ispdfuacompliant/
---

_获取 PDF 文档是否符合 PDF/UA 标准._

```go
func (document *Document) IsPdfUaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/UA compliant
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
	// IsPdfUaCompliant() 获取 PDF 文档的 PDF/UA 合规状态
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
