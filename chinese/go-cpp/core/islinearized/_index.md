---
title: "IsLinearized"
second_title: "Aspose.PDF for Go via C++"
description: "获取指示文档是否线性化的值。"
type: docs
url: /zh/go-cpp/core/islinearized/
---

_获取一个指示文档是否线性化的值。_

```go
func (document *Document) IsLinearized() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is linearized
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
	// IsLinearized() 获取一个指示文档是否线性化的值
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
