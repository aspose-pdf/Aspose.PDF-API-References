---
title: "SaveDocXEnhanced"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como documento DocX con Modo de Reconocimiento Mejorado (tablas y párrafos totalmente editables)."
type: docs
url: /es/go-cpp/convert/savedocxenhanced/
---

_Convertir y guardar el PDF-documento previamente abierto como documento DocX con Modo de Reconocimiento Mejorado (tablas y párrafos totalmente editables)._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
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
	// SaveDocX(filename string) guarda el PDF-documento previamente abierto como documento DocX con Modo de Reconocimiento Mejorado con el nombre de archivo
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
