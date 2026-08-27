---
title: "PageMergeLayers"
second_title: "Aspose.PDF para Go vía C++"
description: "Combinar todas las capas en la página en una sola capa con el nombre de capa nuevo especificado."
type: docs
url: /es/go-cpp/organize/pagemergelayers/
---

_Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

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
	// PageMergeLayers(num int32, newLayerName string) fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
