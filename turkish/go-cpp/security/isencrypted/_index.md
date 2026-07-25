---
title: "IsEncrypted"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanının şifrelenme durumunu al."
type: docs
url: /tr/go-cpp/security/isencrypted/
---

_PDF-belgenin şifrelenmiş durumunu al._

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
	// OpenWithPassword(filename string, password string) şifre korumalı bir PDF-dökümanı açar
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// IsEncrypted() PDF-belgenin şifrelenmiş durumunu alır
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
