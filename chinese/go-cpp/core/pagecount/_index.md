---
title: "PageCount"
second_title: "Aspose.PDF for Go via C++"
description: "返回 PDF-document 的页数。"
type: docs
url: /zh/go-cpp/core/pagecount/
---

_返回 PDF-document 中的页数._

```go
func (document *Document) PageCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - page count of the PDF-document
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
	// PageCount() 返回 PDF-document 中的页数
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Count:", count)
}
```
