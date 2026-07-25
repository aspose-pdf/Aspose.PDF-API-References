---
title: "SetLicense"
second_title: "Aspose.PDF para Go vía C++"
description: "Establecer licencia con nombre de archivo."
type: docs
url: /es/go-cpp/core/setlicense/
---

_Establece la licencia con el nombre de archivo._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// SetLicense(filename string) establece la licencia con el nombre de archivo
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Trabajando con PDF-documento
	// ...
}
```
