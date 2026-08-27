---
title: "SplitAtPage"
second_title: "Aspose.PDF for Go via C++"
description: "将 PDF 文档拆分为两个新的 PDF 文档。"
type: docs
url: /zh/go-cpp/core/splitatpage/
---

_将 PDF 文档拆分为两个新的 PDF 文档。_

```go
func SplitAtPage(document *Document, page int) (*Document, *Document, error)
```

**Parameters**: 
  * **document** - pointer to document
  * **page** - page number at which to split the PDF-document. Pages up to and including this page go into the first PDF-document

**Return**: 
  * **\*Document** - new PDF-document containing pages 1 to page (inclusive)
  * **\*Document** - new PDF-document containing pages from page + 1 to the end
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) 使用文件名打开 PDF-document
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf_split.Close()

	// SplitAtPage(document *Document, page int) 创建两个新的 PDF 文档
	left, right, err := asposepdf.SplitAtPage(pdf_split, 2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为生成的 PDF 文档分配的资源
	defer left.Close()
	defer right.Close()

	// 将每个部分另存为单独的文件
	err = left.SaveAs("sample_SplitAtPage_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAtPage_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
