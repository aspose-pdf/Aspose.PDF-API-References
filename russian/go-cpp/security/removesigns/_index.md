---
title: "RemoveSigns"
second_title: "Aspose.PDF для Go через C++"
description: "Удалить подписи из PDF-документа."
type: docs
url: /ru/go-cpp/security/removesigns/
---

_Удалить подписи из PDF-документа._

```go
func (document *Document) RemoveSigns(filename string) error
```

**Parameters**: 
  * **filename** - new filename, without signs

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// RemoveSigns(filename string) удаляет подписи из PDF-документа
	err = pdf.RemoveSigns("sample_RemoveSigns.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
