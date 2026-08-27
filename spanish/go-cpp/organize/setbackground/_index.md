---
title: "SetBackground"
second_title: "Aspose.PDF para Go vía C++"
description: "Establecer el color de fondo del PDF-document."
type: docs
url: /es/go-cpp/organize/setbackground/
---

_Establecer color de fondo del documento PDF._

```go
func (document *Document) SetBackground(r, g, b int32) error
```

**Parameters**: 
  * **r** - Red color of RGB color model (0-255)
  * **g** - Green color of RGB color model (0-255)
  * **b** - Blue color of RGB color model (0-255)

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
	// SetBackground(r, g, b int32) establece el color de fondo del documento PDF
	err = pdf.SetBackground(200, 100, 101)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_SetBackground.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
