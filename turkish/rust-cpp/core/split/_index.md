---
title: "split"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Mevcut PDF belgesinden sayfaları çıkararak birden fazla yeni PDF belgesi oluşturur."
type: docs
url: /tr/rust-cpp/core/split/
---

_Mevcut PDF belgesinden sayfaları çıkararak birden fazla yeni PDF belgesi oluşturur._

```rust
pub fn split(&self, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample.pdf" adlı bir PDF-document aç
    let pdf_split = Document::open("sample.pdf")?;

    // Mevcut PDF belgesinden sayfaları çıkararak birden fazla yeni PDF belgesi oluştur
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Her bölünmüş parçayı ayrı bir PDF-document olarak kaydet
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```