---
title: "CharacterCount"
second_title: "Aspose.PDF for Go via C++"
description: "返回 PDF 文档中的字符数。"
type: docs
url: /zh/go-cpp/core/charactercount/
---

_返回 PDF-document 中的字符计数._

```go
func (document *Document) CharacterCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - character count of the PDF-document
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
	// CharacterCount() 返回 PDF-document 中的字符计数
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count:", character_count)
}
```
