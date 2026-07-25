---
title: "SetLicense"
second_title: "Aspose.PDF pour Go via C++"
description: "Définir la licence avec le nom de fichier."
type: docs
url: /fr/go-cpp/core/setlicense/
---

_Définit la licence avec le nom de fichier._

```go
func (document *Document) SetLicense(filename string) error
```

**Parameters**: 
  * **filename** - full name of the license file

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// SetLicense(filename string) applique la licence avec le nom de fichier
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Travailler avec le PDF-document
	// ...
}
```
