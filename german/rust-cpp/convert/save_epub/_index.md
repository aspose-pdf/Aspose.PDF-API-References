---
title: "save_epub"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein EPUB-Dokument."
type: docs
url: /de/rust-cpp/convert/save_epub/
---

_Konvertiert und speichert das zuvor geöffnete PDF-Dokument als ein EPUB-Dokument._

```rust
pub fn save_epub(&self, filename: &str) -> Result<(), PdfError>
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

    // Konvertiere und speichere das zuvor geöffnete PDF-Dokument als Epub-Dokument
    pdf.save_epub("sample.epub")?;

    Ok(())
}

```