---
title: "PageIsBlank"
second_title: "Aspose.PDF for Go via C++"
description: "返回 PDF-document 中页面是否为空白。"
type: docs
url: /zh/go-cpp/core/pageisblank/
---

_返回 PDF 文档中页面是否为空白。_

```go
func (document *Document) PageIsBlank(num int32) (bool, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **bool** - the page is blank
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
	// PageIsBlank(num int32) 返回 PDF 文档中页面是否为空白。
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
