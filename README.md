# notices_can

CAN / CAN FD knowledge base for GitHub Pages.

- Published page: <https://released.github.io/notices_can/>
- Related protocol: <https://released.github.io/notices_can_uds/>
- Editable source: `index.md`
- Entry page: `index.html`

UDS, ISO-TP, diagnostic services, and ECU bootloader material are maintained in
the separate `notices_can_uds` knowledge base.

The shared `assets/app.js` renderer also serves the RL78 Bootloader/ISP guides.
An optional body `data-markdown` attribute selects a chapter file;the default
remains `index.md`. After rendering,it emits `guide:ready` so guide-owned
navigation can resolve cross-chapter links without copying technical content.
