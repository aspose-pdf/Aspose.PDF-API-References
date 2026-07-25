---
title: "RemoveHiddenText"
second_title: "Aspose.PDF para Go via C++"
description: "Remover texto oculto do documento PDF."
type: docs
url: /pt/go-cpp/organize/removehiddentext/
---

_Remover texto oculto do PDF-document._

```go
func (document *Document) RemoveHiddenText() error
```

**Parameters**: 

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
	// RemoveHiddenText() remove texto oculto do PDF-document
	err = pdf.RemoveHiddenText()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
	err = pdf.SaveAs("sample_RemoveHiddenText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
