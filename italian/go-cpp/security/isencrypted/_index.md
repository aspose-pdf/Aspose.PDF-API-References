---
title: "IsEncrypted"
second_title: "Aspose.PDF per Go via C++"
description: "Ottieni lo stato di cifratura del documento PDF."
type: docs
url: /it/go-cpp/security/isencrypted/
---

_Ottieni lo stato crittografato del documento PDF._

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
	// OpenWithPassword(filename string, password string) apre un PDF-document protetto da password
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// IsEncrypted() ottiene lo stato crittografato del documento PDF
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
