# Miro

**Ich baue Systeme, die echte Probleme lösen, und liefere sie aus.**
Realtime-Kommunikation, Remote-Access und Desktop-Software in Rust und TypeScript, von der Architektur bis zum Installer.

---

### Wie ich arbeite

- **Problem → Release, ohne Umweg.** Kein Ticket, kein Standup. Ich zerlege das Problem, baue, teste und shippe. Meine Voice- & Chat-App hat über 25 Releases, davon 5 an einem einzigen Tag.
- **Agentic Coding ist mein Standard-Workflow.** Claude Code und Cursor stecken in jedem Schritt: Prototyping, Refactoring, Tests, Release-Notes. Die Architektur und die Verantwortung für den Code bleiben bei mir.
- **Erst automatisieren, dann skalieren.** Wenn ich etwas zweimal von Hand mache, wird beim dritten Mal ein Skript, ein Agent oder eine CI-Pipeline daraus.
- **Ich verstehe, was ich baue.** Transportwege, Sicherheitsgrenzen und bekannte Einschränkungen schreibe ich offen in die Doku, statt sie zu verstecken.
- **Der Stack folgt dem Problem.** InfinityNotes ist zum Beispiel von Supabase auf lokale SQLite umgezogen, weil die Daten auf das Gerät der Nutzer gehören.

---

### Ausgewählte Projekte

| Projekt | Was es löst | Stack |
|---|---|---|
| **[Voice- & Chat-App](https://github.com/miro187/Schisscord-releases)** | Verschlüsselter Chat mit 1:1- und Gruppen-Calls, Screensharing mit App-Audio, Dateitransfer bis 50 MB mit Resume, eigene Relay-Infrastruktur. | Rust · Tauri 2 · React · Nostr · VPS (systemd, Caddy) |
| **[RustScreen](https://github.com/miro187/rustscreen)** | Selbst gehostetes Screensharing und Fernsteuerung im Browser, ohne Client-Installation und ohne Portweiterleitung: Zugriff per Code und PIN über ein Relay. | Rust · axum · tokio · ffmpeg/H.264 · WebCodecs · Cloudflare Tunnel |
| **[InfinityNotes](https://github.com/miro187/InfinityNotes)** | KI-Workspace auf einer unendlichen Canvas: Aus Chats werden Notizen, Aufgaben und Projektpläne, alles lokal gespeichert. | Tauri 2 · Rust · React · SQLite · Gemini |

---

### Stack

- **Sprachen:** Rust, TypeScript
- **Backend und Networking:** axum, tokio, WebSockets, Relays, Nostr, Cloudflare Tunnel
- **Media:** ffmpeg, H.264, NVENC/QSV/AMF, WebCodecs, MSE
- **Desktop und Frontend:** Tauri 2, React, Vite, Tailwind
- **Daten und Infra:** SQLite, VPS, systemd, Caddy, GitHub Actions
- **Workflow:** Claude Code, Cursor, Agentic Coding
