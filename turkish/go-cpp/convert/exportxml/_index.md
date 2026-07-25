---
title: "ExportXml"
second_title: "Aspose.PDF for Go via C++"
description: "AcroForm içeren önceden açılmış PDF-dokümanını XML-dokümanına dışa aktar."
type: docs
url: /tr/go-cpp/convert/exportxml/
---

_AcroForm içeren önceden açılmış PDF-belgesinden XML-belgesine dışa aktar._

```go
func (document *Document) ExportXml(filename string) error
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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// ExportXml(filename string) AcroForm içeren önceden açılmış PDF-belgesini dosya adıyla XML-belgesi olarak dışa aktarır
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
