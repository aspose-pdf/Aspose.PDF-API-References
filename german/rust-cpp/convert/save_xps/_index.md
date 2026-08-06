---
title: "save_xps"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als XPS-Dokument."
type: docs
url: /de/rust-cpp/convert/save_xps/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als XPS-Dokument._

```rust
pub fn save_xps(&self, filename: &str) -> Result<(), PdfError>
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

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als XPS-Dokument
    pdf.save_xps("sample.xps")?;

    Ok(())
}

```