---
title: "save_markdown"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dan menyimpan dokumen PDF yang sebelumnya dibuka sebagai dokumen Markdown."
type: docs
url: /id/rust-cpp/convert/save_markdown/
---

_Mengonversi dan menyimpan dokumen PDF yang sebelumnya dibuka sebagai dokumen Markdown._

```rust
pub fn save_markdown(&self, filename: &str) -> Result<(), PdfError>
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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Konversi dan simpan dokumen PDF yang sebelumnya dibuka sebagai dokumen Markdown
    pdf.save_markdown("sample.md")?;

    Ok(())
}
```