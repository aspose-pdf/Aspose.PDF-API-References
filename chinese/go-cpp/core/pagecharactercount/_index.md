---
title: "PageCharacterCount"
second_title: "Aspose.PDF for Go via C++"
description: "返回 PDF-document 中指定页面的字符数。"
type: docs
url: /zh/go-cpp/core/pagecharactercount/
---

_返回 PDF 文档中指定页面的字符数。_

```go
func (document *Document) PageCharacterCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - character count on the page
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
	// PageCharacterCount(num int32) 返回 PDF 文档中指定页面的字符数。
	page_character_count, err := pdf.PageCharacterCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count on the first page:", page_character_count)
}
```
