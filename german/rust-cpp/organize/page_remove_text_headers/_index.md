---
title: "page_remove_text_headers"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Textkopfzeilen in der Seite."
type: docs
url: /de/rust-cpp/organize/page_remove_text_headers/
---

_Entfernt Textkopfzeilen in der Seite._

```rust
pub fn page_remove_text_headers(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document aus einer Datei
    let pdf = Document::open("sample.pdf")?;

    // Entferne Textkopfzeilen in der Seite
    pdf.page_remove_text_headers(1)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_remove_text_headers.pdf")?;

    Ok(())
}

```