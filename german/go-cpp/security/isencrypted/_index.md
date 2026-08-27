---
title: "IsEncrypted"
second_title: "Aspose.PDF für Go über C++"
description: "Verschlüsselungsstatus des PDF-Dokuments abrufen."
type: docs
url: /de/go-cpp/security/isencrypted/
---

_Verschlüsselungsstatus des PDF-Dokuments abrufen._

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
	// OpenWithPassword(filename string, password string) öffnet ein passwortgeschütztes PDF-Dokument
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// IsEncrypted() ermittelt den Verschlüsselungsstatus des PDF-Dokuments
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
