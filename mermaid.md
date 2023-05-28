---
marp: true
---

# Mermaidのデモ

<div class="mermaid">
flowchart TD
    A[Start] --> B{Is it?}
    B -->|Yes| C[OK]
    C --> D[Rethink]
    D --> B
    B ---->|No| E[End]
</div>

<!-- import mermaid -->
<script src="https://cdn.jsdelivr.net/npm/mermaid@9"></script>
<script>
    mermaid.initialize({startOnLoad: true});
</script>