---
title: "remove_tables"
second_title: "Aspose.PDF für Rust über C++"
description: "Entfernt Tabellen aus dem PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/remove_tables/
---

_Entfernt Tabellen aus dem PDF-Dokument._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Tabellen aus dem PDF-Dokument entfernen
    pdf.remove_tables()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```