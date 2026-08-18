---
title: "replace_font"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengganti font dalam dokumen PDF."
type: docs
url: /id/rust-cpp/organize/replace_font/
---

_Mengganti font dalam dokumen PDF._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Ganti font dalam PDF-document.
    pdf.replace_font("Helvetica", "Courier")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```