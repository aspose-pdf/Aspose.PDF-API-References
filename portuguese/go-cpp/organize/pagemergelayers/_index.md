---
title: "PageMergeLayers"
second_title: "Aspose.PDF para Go via C++"
description: "Mesclar todas as camadas na página em uma única camada com o nome da nova camada especificado."
type: docs
url: /pt/go-cpp/organize/pagemergelayers/
---

_Mescle todas as camadas na página em uma única camada com o nome da nova camada especificado._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// PageMergeLayers(num int32, newLayerName string) mescla todas as camadas na página em uma única camada com o nome da nova camada especificado
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
