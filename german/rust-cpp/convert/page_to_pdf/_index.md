---
title: "page_to_pdf"
second_title: "Aspose.PDF für Rust über C++"
description: "Konvertiert und speichert die angegebene Seite als ein PDF-Dokument."
type: docs
url: /de/rust-cpp/convert/page_to_pdf/
---

_Konvertiert und speichert die angegebene Seite als ein PDF-Dokument._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Konvertiere und speichere die angegebene Seite als PDF-Dokument
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```