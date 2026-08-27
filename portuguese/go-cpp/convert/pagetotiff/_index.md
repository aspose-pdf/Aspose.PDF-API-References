---
title: "PageToTiff"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar a página especificada como imagem Tiff."
type: docs
url: /pt/go-cpp/convert/pagetotiff/
---

_Converter e salvar a página especificada como Tiff-image._

```go
func (document *Document) PageToTiff(num int32, resolution_dpi int32, filename string) error
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
	// PageToTiff(num int32, resolution_dpi int32, filename string) salva a página especificada como arquivo Tiff-image
	err = pdf.PageToTiff(1, 100, "sample_page1.tiff")
	if err != nil {
		log.Fatal(err)
	}
}
```
