---
title: "OpenWithPassword"
second_title: "Aspose.PDF для Go через C++"
description: "Открыть защищённый паролем PDF-документ."
type: docs
url: /ru/go-cpp/security/openwithpassword/
---

_Открыть защищённый паролем PDF-документ._

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
	// OpenWithPassword(filename string, password string) открывает PDF-документ, защищённый паролем
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// выполняется...
}
```
