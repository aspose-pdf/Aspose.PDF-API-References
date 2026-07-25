---
title: "RemovePdfUaCompliance"
second_title: "Aspose.PDF for Go via C++"
description: "从 PDF 文档中移除 PDF/UA 合规性。"
type: docs
url: /zh/go-cpp/organize/removepdfuacompliance/
---

_从 PDF-document 中移除 PDF/UA 合规性._

```go
func (document *Document) RemovePdfUaCompliance() error
```

**Parameters**: 

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
	// RemovePdfUaCompliance() 从 PDF-document 中移除 PDF/UA 合规性
	err = pdf.RemovePdfUaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_RemovePdfUaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
