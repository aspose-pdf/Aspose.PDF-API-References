---
title: "replace_text"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengganti teks."
type: docs
url: /id/rust-cpp/organize/replace_text/
---

_Mengganti teks._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Ganti teks dalam PDF-document
    pdf.replace_text("PDF", "TXT")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```