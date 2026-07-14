# bandi-analisi-files

Repository **pubblico** che ospita gli allegati generati dalle routine notturne di ricerca bandi
(principalmente i **PDF di analisi** di ogni opportunità), così che **Airtable** possa scaricarli
via URL `raw.githubusercontent.com` e conservarne una copia propria nel campo allegato "Analisi".

Le routine cloud girano in una sandbox che blocca i file-host generici: GitHub è l'unico host
raggiungibile, quindi i file transitano da qui.

I file sono organizzati per profilo:

- `PULIAMOMESSINA/` — profilo ETS (Puli-AMO Messina)
- `WHYNOT/` — profilo Startup AI (WHY NOT? Labs)
- `MARCOPIGNATARO/` — profilo P.IVA (Marco Pignataro)

> ⚠️ Questo repo NON contiene documenti di contesto sensibili (statuti, codici fiscali, CV):
> quelli restano nella repo privata `bandi-automation`. Qui solo output pubblicabile.
