---
title: "IsEncrypted"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントの暗号化状態を取得します。"
type: docs
url: /ja/go-cpp/security/isencrypted/
---

_PDF-document の暗号化状態を取得します。_

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
	// OpenWithPassword(filename string, password string) は、パスワードで保護された PDF ドキュメントを開きます
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// IsEncrypted() は PDF-document の暗号化状態を取得します
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
