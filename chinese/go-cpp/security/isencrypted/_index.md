---
title: "IsEncrypted"
second_title: "Aspose.PDF for Go via C++"
description: "获取 PDF-document 的加密状态。"
type: docs
url: /zh/go-cpp/security/isencrypted/
---

_获取 PDF 文档的加密状态。_

```go
func (document *Document) IsEncrypted() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is encrypted
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// OpenWithPassword(filename string, password string) 打开受密码保护的 PDF 文档
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()
	// IsEncrypted() 获取 PDF 文档的加密状态
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
