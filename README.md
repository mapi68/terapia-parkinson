# Terapia Parkinson - Organizzatore dosi

![Licenza: tutti i diritti riservati](https://img.shields.io/badge/Licenza-Tutti_i_diritti_riservati-red?style=for-the-badge)

Applicazione web a **file singolo**, senza installazione e senza server: basta aprire `organizzatore_terapia_p.html` in un browser per gestire orari, dosi e diario sintomi di una terapia per il morbo di Parkinson.

Pensata per un uso personale o familiare, funziona anche offline dopo il primo caricamento, salva tutto localmente nel browser (nessun dato inviato altrove) e prevede il backup manuale su file.

L'interfaccia è pensata e ottimizzata per l'uso al computer: la disposizione di schede, tabelle e grafici sfrutta lo spazio di uno schermo desktop e l'interazione con mouse e tastiera. È utilizzabile anche da tablet o smartphone, ma l'esperienza migliore resta quella su PC.

<details>
<summary><strong>Licenza e diritti d'uso</strong> (da leggere prima di usare l'app)</summary>

Questa web app è pubblicata su GitHub solo a scopo dimostrativo e di trasparenza. Tutti i diritti sono riservati: nessuna licenza open source viene concessa, e non è consentito alcun uso commerciale, da parte di nessuno.

In particolare, senza il permesso scritto dell'autore non è consentito:

- l'uso commerciale della web app o del database farmaci, in tutto o in parte, da parte di aziende, associazioni, enti o singoli che ne traggano un guadagno diretto o indiretto, incluse aziende farmaceutiche, assicurazioni sanitarie e organizzazioni di qualunque tipo;
- la redistribuzione, la pubblicazione o l'integrazione di questa web app, modificata o meno, in altri prodotti o servizi, gratuiti o a pagamento;
- la rimozione o l'alterazione di questo avviso in eventuali copie della web app.

È invece benvenuto l'uso strettamente personale: scaricare il file, farlo girare sul proprio computer per la propria terapia o quella di un familiare. Per qualsiasi altro utilizzo, contattare l'autore per un permesso esplicito.

</details>

---

## Funzionalità principali

- **Giornata**: dosi previste per oggi, con orari, avvisi per i ritardi (notifica desktop e/o suono, configurabili) e possibilità di segnarle come prese, anche con quantità diversa dallo standard.
- **Farmaci al bisogno (PRN)**: registro delle assunzioni senza orario fisso.
- **Elenco farmaci**: ordinabile alfabeticamente o per prossima dose, con riepilogo automatico di dosi e milligrammi giornalieri per principio attivo.
- **Diario sintomi**: annotazioni con orario, stato motorio, sintomi per categoria e note libere, collegate automaticamente alle dosi delle ore precedenti.
- **Registro cadute**: form dedicato per orario, stato motorio, luogo, circostanza e conseguenza, incluso nelle stampe e nella Cronologia.
- **Cronologia**: grafici di aderenza e sintomi, vista giorno per giorno, riepilogo dei principi attivi realmente assunti rispetto al piano, e confronto tra periodi.
- **Riepilogo per la visita**: stampa su una pagina pensata per il neurologo, con aderenza, qualità di vita, farmaci in terapia e principi attivi assunti nel periodo scelto.
- **Proteine e levodopa**: segnalazione della possibile interferenza tra proteine ai pasti e assorbimento della levodopa.
- **Visite e più medici**: elenco visite con data, medico assegnato e note, con promemoria nei giorni precedenti.
- **Database farmaci integrato** per Italia e Svizzera, con equivalenze tra i due mercati.
- **Stampe**: scheda terapia, calendario settimanale/mensile, diario, riepilogo cronologia e riepilogo per la visita.
- **Tema chiaro/scuro**, testo ridimensionabile, modalità privata per nascondere il riferimento al Parkinson sullo schermo.
- **Note sui farmaci in Giornata**: disattivate di default; si possono attivare in Impostazioni per vedere anche lì l'etichetta con l'indicazione del pasto e le avvertenze (es. sulla levodopa), non solo in Farmaci.

L'elenco completo, con tutti i dettagli di comportamento di ogni funzione, è in [FEATURES.md](FEATURES.md).

## Come si usa

1. Apri il file `organizzatore_terapia_p.html` con un browser (Chrome, Firefox, Edge, Safari).
2. Alla prima apertura configura in **Impostazioni** il nome del paziente, il medico di riferimento e il paese (Italia/Svizzera, usato per il database farmaci).
3. Aggiungi i farmaci dalla scheda **Farmaci**, scegliendo da elenco oppure inserendoli manualmente.
4. Segna le dosi prese man mano dalla scheda **Giornata**.
5. Usa il **Diario** per annotare sintomi o eventi rilevanti.

Non serve connessione internet per l'uso quotidiano: tutti i dati restano salvati nel browser del dispositivo usato.

## Backup e ripristino

I dati vivono solo nel browser in cui viene usata la web app (nessun account, nessun cloud). Per non perderli:

- Usa **Salva su file** (in Impostazioni o nel menu File in alto) per salvare un file `.json` con tutta la terapia, lo storico e il diario. Il nome del file è personalizzabile in Impostazioni (base del nome, inclusione o meno di paziente e data).
- Usa **Carica da file** per ripristinare i dati da un file esportato in precedenza, anche su un altro dispositivo.

Si consiglia di esportare un backup periodicamente, specialmente dopo modifiche importanti alla terapia. Dettagli su cosa viene salvato e sulla pulizia dati in [FEATURES.md](FEATURES.md#backup-e-ripristino).

## Avvertenze

Questa applicazione è uno strumento di organizzazione personale e **non sostituisce in alcun modo il parere del medico**. Dosaggi, nomi commerciali e note presenti nel database farmaci sono indicativi: verificare sempre con il neurologo curante o il farmacista prima di qualsiasi decisione sulla terapia.

## Aspetti tecnici

- Nessuna dipendenza esterna: un solo file HTML con CSS e JavaScript incorporati.
- Compatibile con i principali browser desktop e mobile aggiornati.

## Contatti

Per permessi d'uso non personale o altre richieste: mapi68 (chiocciola) gmail (punto) com
