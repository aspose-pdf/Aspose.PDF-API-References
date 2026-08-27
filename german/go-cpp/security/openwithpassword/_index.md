---
title: "OpenWithPassword"
second_title: "Aspose.PDF für Go über C++"
description: "Ein passwortgeschütztes PDF-Dokument öffnen."
type: docs
url: /de/go-cpp/security/openwithpassword/
---

_Ein passwortgeschütztes PDF-Dokument öffnen._

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
	// OpenWithPassword(filename string, password string) öffnet ein passwortgeschütztes PDF-Dokument
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// arbeite...
}
```
