---
title: "page_remove_text_footers"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Textfußzeilen auf der Seite."
type: docs
url: /de/rust-cpp/organize/page_remove_text_footers/
---

_Entfernt Textfußzeilen auf der Seite._

```rust
pub fn page_remove_text_footers(&self, num: i32) -> Result<(), PdfError>
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

    // Entferne Textfußzeilen auf der Seite
    pdf.page_remove_text_footers(1)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_remove_text_footers.pdf")?;

    Ok(())
}

```