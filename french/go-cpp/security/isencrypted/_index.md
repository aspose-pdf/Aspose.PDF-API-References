---
title: "IsEncrypted"
second_title: "Aspose.PDF pour Go via C++"
description: "Obtenir le statut de chiffrement du PDF-document."
type: docs
url: /fr/go-cpp/security/isencrypted/
---

_Obtenir le statut chiffré du PDF-document._

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
	// OpenWithPassword(filename string, password string) ouvre un PDF-document protégé par mot de passe
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// IsEncrypted() obtient le statut chiffré du PDF-document
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
