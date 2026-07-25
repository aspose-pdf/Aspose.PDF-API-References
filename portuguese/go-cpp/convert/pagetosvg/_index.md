---
title: "PageToSvg"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar a página especificada como imagem Svg."
type: docs
url: /pt/go-cpp/convert/pagetosvg/
---

_Converta e salve a página especificada como imagem Svg._

```go
func (document *Document) PageToSvg(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToSvg(num int32, filename string) salva a página especificada como arquivo de imagem Svg
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
