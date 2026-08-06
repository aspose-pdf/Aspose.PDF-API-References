---
title: "page_replace_text"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengganti teks pada halaman."
type: docs
url: /id/rust-cpp/organize/page_replace_text/
---

_Mengganti teks pada halaman._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Ganti teks pada halaman
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```