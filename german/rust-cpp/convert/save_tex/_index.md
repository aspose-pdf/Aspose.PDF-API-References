---
title: "save_tex"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als TeX-Dokument."
type: docs
url: /de/rust-cpp/convert/save_tex/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als TeX-Dokument._

```rust
pub fn save_tex(&self, filename: &str) -> Result<(), PdfError>
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

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als TeX-Dokument
    pdf.save_tex("sample.tex")?;

    Ok(())
}

```