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
