---
title: "SaveNUp"
second_title: "Aspose.PDF for Go via C++"
description: "将先前打开的 PDF 文档转换并保存为 N-Up PDF 文档。"
type: docs
url: /zh/go-cpp/convert/savenup/
---

_转换并保存先前打开的 PDF 文档为 N-Up PDF 文档._

```go
func (document *Document) SaveNUp(filename string, columns int32, rows int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **columns** - number of columns
  * **rows** - number of rows

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
	// SaveNUp(filename string, columns int32, rows int32) 将先前打开的 PDF 文档保存为 N-Up PDF 文档，使用指定的文件名
	err = pdf.SaveNUp("sample_NUp.pdf", 2, 2)
	if err != nil {
		log.Fatal(err)
	}
}
```
