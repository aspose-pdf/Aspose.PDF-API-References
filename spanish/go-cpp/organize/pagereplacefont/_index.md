---
title: "PageReplaceFont"
second_title: "Aspose.PDF para Go vía C++"
description: "Reemplazar fuente en la página."
type: docs
url: /es/go-cpp/organize/pagereplacefont/
---

_Reemplazar fuente en la página._

```go
func (document *Document) PageReplaceFont(num int32, findFontName, replaceFontName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **findFontName** - font name to search
  * **replaceFontName** - font name to replace

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
        // PageReplaceFont(num int32, findFontName, replaceFontName string) reemplaza la fuente en la página
        err = pdf.PageReplaceFont(1, "Times-BoldItalic", "Helvetica-Bold")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_page1_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
