---
title: 實驗室成員
type: landing

sections:

  - block: markdown
    content:
      title: "實驗室成員"
      text: |
        本實驗室包含在學學生與畢業校友，持續進行微生物與生技研究。

        <div style="margin-top:20px;">
          <a href="/#current" style="padding:10px 14px; background:#1f4e79; color:white; border-radius:6px; text-decoration:none; margin-right:8px;">在學成員</a>

          <a href="/#alumni" style="padding:10px 14px; background:#555; color:white; border-radius:6px; text-decoration:none;">畢業成員</a>
        </div>

  - block: collection
    id: current
    content:
      title: "👩‍🔬 在學成員"
      filters:
        folder: authors
        tag: current
    design:
      view: card

  - block: collection
    id: alumni
    content:
      title: "🎓 已畢業成員"
      filters:
        folder: authors
        tag: alumni
    design:
      view: card

---
