---
title: "OpenWithPassword"
second_title: "Aspose.PDF for Go via C++"
description: "Şifre korumalı PDF-dokümanını aç."
type: docs
url: /tr/go-cpp/security/openwithpassword/
---

_Şifre korumalı bir PDF-dökümanı aç._

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
	// OpenWithPassword(filename string, password string) şifre korumalı bir PDF-dökümanı açar
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// çalışıyor...
}
```
