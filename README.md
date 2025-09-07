# 📂 social-content-store

Repozytorium służy jako **centralny magazyn danych JSON** generowanych przez integrację **Content Processor Agent v_2.7 Justyna**.

## 🔹 Zawartość

- `data/social_posts.json` – aktualny znormalizowany plik z postami społecznościowymi (Facebook + Instagram).  
- Struktura pliku odpowiada formatowi wyjściowemu bloku **11 (Social JSON Packager)**:

```json
{
  "items": [
    {
      "type": "Facebook",
      "title": null,
      "summary": "Engage students with Cosmic Battle...",
      "url": "https://www.facebook.com/reel/675163292163333/",
      "image_url": null,
      "audience_tags": ["spike-essential", "spike-word-blocks", "coding-for-kids"]
    },
    {
      "type": "Instagram",
      "title": null,
      "summary": "Build an anemometer using SPIKE Prime...",
      "url": "https://www.instagram.com/p/DKMwH6wxFp2/",
      "image_url": null,
      "audience_tags": ["3d-printing", "tinkercad", "spike-prime", "python"]
    }
  ]
}
