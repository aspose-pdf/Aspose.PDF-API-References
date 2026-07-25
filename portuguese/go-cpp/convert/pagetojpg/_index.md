---
title: "PageToJpg"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar a página especificada como imagem Jpg."
type: docs
url: /pt/go-cpp/convert/pagetojpg/
---

_Converter e salvar a página especificada como Jpg-image._

```go
func (document *Document) PageToJpg(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
  * **filename** - new filename

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
	// PageToJpg(num int32, resolution_dpi int32, filename string) salva a página especificada como arquivo Jpg-image
	err = pdf.PageToJpg(1, 100, "sample_page1.jpg")
	if err != nil {
		log.Fatal(err)
	}
}
```
