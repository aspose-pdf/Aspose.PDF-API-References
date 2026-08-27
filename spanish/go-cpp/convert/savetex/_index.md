---
title: "SaveTeX"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como documento TeX."
type: docs
url: /es/go-cpp/convert/savetex/
---

_Convertir y guardar el PDF abierto previamente como documento TeX._

```go
func (document *Document) SaveTeX(filename string) error
```

**Parameters**: 
  * **filename** - new filename

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
	// SaveTeX(filename string) guarda el PDF abierto previamente como documento TeX con el nombre de archivo
	err = pdf.SaveTeX("sample.tex")
	if err != nil {
		log.Fatal(err)
	}
}
```
