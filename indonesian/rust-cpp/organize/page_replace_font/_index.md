---
title: "page_replace_font"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengganti font pada halaman."
type: docs
url: /id/rust-cpp/organize/page_replace_font/
---

_Mengganti font pada halaman._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Ganti font pada halaman
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```