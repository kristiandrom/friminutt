# Friminutt-timer

Timer for friminutt, laget for Embed-widgetet i [Classroomscreen](https://classroomscreen.com).
Teller ned, blir oransje det siste minuttet, og blir rød og teller oppover («Du er 00:01 for sen») når friminuttet er over.

## Bruk i Classroomscreen

Lim inn dette i Embed-widgetet og trykk «run code»:

```html
<iframe src="https://kristiandrom.github.io/friminutt/?min=10" width="600" height="450" style="border:0" allow="autoplay"></iframe>
```

## Innstillinger i adressen

| Parameter | Eksempel | Betyr |
|---|---|---|
| `min` | `?min=15` | Lengde i minutter |
| `sek` | `?min=0&sek=30` | Ekstra sekunder |
| `til` | `?til=10:15` | Tell ned til et klokkeslett i stedet |
| `tittel` | `?tittel=Lunsj` | Overskrift i ringen |
| `lyd` | `?lyd=0` | Slå av lyden når tiden er ute |

## Tastatur

Mellomrom: start/pause · ↑/↓: ett minutt mer/mindre · Esc: lukk innstillinger

---

# Dagens tips

Viser én hurtigtast eller kommando om dagen: VS Code, tastatur og nettleser, terminal, Git, HTML, CSS, JavaScript, React, nettverk, Photoshop og Premiere Pro. Windows- og Mac-variant vises side om side.

```html
<iframe src="https://kristiandrom.github.io/friminutt/dagens-tips/" width="600" height="420" style="border:0"></iframe>
```

| Parameter | Eksempel | Betyr |
|---|---|---|
| `kat` | `?kat=vscode,git,terminal` | Bare disse kategoriene (`vscode`, `tastatur`, `terminal`, `git`, `html`, `css`, `js`, `react`, `nett`, `ps`, `pr`) |
| `os` | `?os=win` | Vis bare Windows (`win`), bare Mac (`mac`) eller begge (`begge`) |
| `bytt` | `?bytt=10` | Nytt tips hvert 10. minutt i stedet for hver dag |
| `tittel` | `?tittel=Ukas%20triks` | Overskrift |

Tastatur: ←/→ forrige/neste · R tilfeldig. Nye tips legges inn i `TIPS`-lista øverst i scriptet i `dagens-tips/index.html`.
