---
title: "page_remove_watermarks"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Wasserzeichen auf der Seite."
type: docs
url: /de/rust-cpp/organize/page_remove_watermarks/
---

_Entfernt Wasserzeichen auf der Seite._

```rust
pub fn page_remove_watermarks(&self, num: i32) -> Result<(), PdfError>
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

    // Entferne Wasserzeichen auf der Seite
    pdf.page_remove_watermarks(1)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_page1_remove_watermarks.pdf")?;

    Ok(())
}

```