---
title: "OpenWithPassword"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "パスワードで保護されたPDFドキュメントを開きます。"
type: docs
url: /ja/go-cpp/security/openwithpassword/
---

_パスワードで保護された PDF-document を開きます。_

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
	// OpenWithPassword(filename string, password string) は、パスワードで保護された PDF ドキュメントを開きます
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// 処理中...
}
```
