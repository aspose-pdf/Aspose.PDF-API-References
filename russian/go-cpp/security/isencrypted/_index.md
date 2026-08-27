---
title: "IsEncrypted"
second_title: "Aspose.PDF для Go через C++"
description: "Получить статус шифрования PDF-документа."
type: docs
url: /ru/go-cpp/security/isencrypted/
---

_Получить зашифрованный статус PDF-документа._

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
	// OpenWithPassword(filename string, password string) открывает PDF-документ, защищённый паролем
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// IsEncrypted() получает зашифрованный статус PDF-документа
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
