---
title: "save_doc"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein DOC-Dokument."
type: docs
url: /de/rust-cpp/convert/save_doc/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein DOC-Dokument._

```rust
pub fn save_doc(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als Doc-Dokument
    pdf.save_doc("sample.doc")?;

    Ok(())
}

```