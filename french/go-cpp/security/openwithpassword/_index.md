---
title: "OpenWithPassword"
second_title: "Aspose.PDF pour Go via C++"
description: "Ouvrir un PDF-document protégé par mot de passe."
type: docs
url: /fr/go-cpp/security/openwithpassword/
---

_Ouvrir un document PDF protégé par mot de passe._

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
	// OpenWithPassword(filename string, password string) ouvre un PDF-document protégé par mot de passe
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// en cours...
}
```
