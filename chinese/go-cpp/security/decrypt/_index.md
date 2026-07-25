---
title: "Decrypt"
second_title: "Aspose.PDF for Go via C++"
description: "解密 PDF-document。"
type: docs
url: /zh/go-cpp/security/decrypt/
---

_解密 PDF 文档。_

```go
func (document *Document) Decrypt() error
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
	// OpenWithPassword(filename string, password string) 打开受密码保护的 PDF 文档
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// Decrypt() 解密 PDF 文档
	err = pdf.Decrypt()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_without_password.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
