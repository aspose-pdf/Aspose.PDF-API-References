---
title: "MergeDocuments"
second_title: "Aspose.PDF for Go via C++"
description: "通过合并提供的 PDF 文档创建一个新的 PDF 文档。"
type: docs
url: /zh/go-cpp/core/mergedocuments/
---

_通过合并提供的 PDF 文档来创建一个新的 PDF 文档._

```go
func MergeDocuments(documents []*Document) (*Document, error)
```

**Parameters**: 
  * **documents** - slice of PDF-documents to be merged

**Return**: 
  * **\*Document** - new PDF-document containing all pages from the provided PDF-documents
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New 创建一个新的 PDF-document
	pdf1, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf1.Close()
	err = pdf1.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Open(filename string) 使用文件名打开 PDF-document
	pdf2, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf2.Close()
	// MergeDocuments(documents []*Document) 通过合并提供的文档创建一个新的 PDF 文档。
	pdf_merged, err := asposepdf.MergeDocuments([]*asposepdf.Document{pdf1, pdf2})
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf_merged.Close()
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf_merged.SaveAs("sample_MergeDocuments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
