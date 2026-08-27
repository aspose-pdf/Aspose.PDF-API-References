---
title: "OpenWithPassword"
second_title: "Aspose.PDF for Go via C++"
description: "打开受密码保护的 PDF-document。"
type: docs
url: /zh/go-cpp/security/openwithpassword/
---

_打开受密码保护的 PDF-document._

```go
func OpenWithPassword(filename string, password string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document
  * **password** - user/owner password of the password-protected PDF-document

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
	// 处理中...
}
```
