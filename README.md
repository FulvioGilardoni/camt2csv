# CAMT2CSV Converter (Offline)

Converte estratti conto **CAMT.053 / CAMT.054 (ISO 20022)** in **CSV/Excel** — 100% offline.

- **Piattaforma**: Windows 10/11 (x64)
- **Rete**: non necessaria (nessun invio dati)
- **Versioni**: 
  - **CAMT2CSV Converter (Offline)** — versione completa a pagamento
  - **CAMT2CSV Free (Demo)** — versione gratuita limitata a **20 righe per file**

## Utilizzo rapido

```
CAMT2CSV.exe <percorso_input> [--out <file|cartella>] [--sep ;|,] [--culture it-IT|en-US] [--single]
```

**Esempi**
- `CAMT2CSV.exe estratto_camt053.xml`
- `CAMT2CSV.exe C:\Estratti\ --out C:\Output\ --single --sep , --culture en-US`

> **Demo**: la versione gratuita elabora fino a 20 righe per file e termina con un messaggio che invita all’acquisto della versione completa.

## Funzionalità principali
- Parsing di file **CAMT.053 / CAMT.054** (XML, ISO 20022)
- Esportazione in **CSV** compatibile Excel; supporto cultura/decimal separator
- Modalità **single-file** o batch su cartella
- **Totalmente offline**: nessun dato inviato in rete

## Requisiti
- Windows 10 o 11 (x64)
- Nessun prerequisito .NET da installare (self-contained)

## Supporto & Privacy
Documentazione, FAQ, contatti e informativa privacy:  
https://<TUO-USERNAME>.github.io/camt2csv-site/

Per assistenza diretta: fulvio.gilardoni@gmail.com

## Changelog
Vedi la pagina: https://<TUO-USERNAME>.github.io/camt2csv-site/#changelog

---

# CAMT2CSV Converter (Offline) — EN

Convert **CAMT.053 / CAMT.054 (ISO 20022)** bank statements to **CSV/Excel** — 100% offline.

- **Platform**: Windows 10/11 (x64)
- **Network**: not required (no data sent)
- **Editions**:
  - **CAMT2CSV Converter (Offline)** — paid full version
  - **CAMT2CSV Free (Demo)** — free, limited to **20 rows per file**

## Quick usage

```
CAMT2CSV.exe <input_path> [--out <file|folder>] [--sep ;|,] [--culture it-IT|en-US] [--single]
```

**Examples**
- `CAMT2CSV.exe statement_camt053.xml`
- `CAMT2CSV.exe C:\Statements\ --out C:\Output\ --single --sep , --culture en-US`

> **Demo**: the free edition processes up to 20 rows per file and exits with a message suggesting the full version.

## Key features
- Parse **CAMT.053 / CAMT.054** (XML, ISO 20022)
- Export to **CSV** (Excel-friendly); locale/decimal separator options
- **Single-file** or folder batch processing
- **Fully offline**: no network, no telemetry

## Requirements
- Windows 10 or 11 (x64)
- No .NET runtime required (self-contained)

## Support & Privacy
Docs, FAQ, contacts and privacy policy:  
https://fulviogilardoni.github.io/camt2csv-site/

Direct support: fulvio.gilardoni@gmail.com
