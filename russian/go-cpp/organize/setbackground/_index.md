---
title: "SetBackground"
second_title: "Aspose.PDF для Go через C++"
description: "Установить цвет фона PDF-документа."
type: docs
url: /ru/go-cpp/organize/setbackground/
---

_Установить цвет фона PDF‑документа._

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
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// SetBackground(r, g, b int32) устанавливает цвет фона PDF‑документа
	err = pdf.SetBackground(200, 100, 101)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_SetBackground.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
