# Informativa sulla Privacy — help2you

**Ultimo aggiornamento:** 10 giugno 2026 · **Versione:** 1.0

La presente informativa è resa ai sensi degli artt. 13 e 14 del Regolamento (UE) 2016/679 (**GDPR**) e del D.Lgs. 196/2003 come modificato dal D.Lgs. 101/2018 (**Codice Privacy**) a tutte le persone che utilizzano l'applicazione **help2you** ("App").

help2you è progettata secondo i principi di **privacy by design e by default** (art. 25 GDPR): la maggior parte dei tuoi dati **resta sul tuo dispositivo** e non viene trasmessa ad alcun server, salvo nei casi espressamente indicati di seguito.

---

## 1. Titolare del Trattamento

**Matteo Bonetti** — libero professionista
- Email: **info@mn99-lab.it**
- Telefono: **+39 389 934 9483**

Il Titolare non ha nominato un Responsabile della Protezione dei Dati (DPO), non essendovi obbligo ai sensi dell'art. 37 GDPR. Per qualsiasi richiesta in materia di privacy puoi scrivere all'indirizzo sopra indicato.

---

## 2. Natura dell'App e approccio ai dati

help2you è uno strumento di **supporto al benessere emotivo**. **Non è un dispositivo medico, non fornisce diagnosi né cure e non sostituisce un professionista sanitario** (vedi il *Disclaimer medico e AI*).

I tuoi contenuti personali (umore, diario, riflessioni, questionari, conversazioni con il Compagno) sono archiviati **localmente** sul dispositivo (tecnologia Apple SwiftData) e nel **Portachiavi (Keychain)** di sistema. Vengono trasmessi all'esterno **soltanto**:
- al **Compagno AI**, e **solo se hai prestato l'apposito consenso** (vedi §5);
- ai contatti che **scegli tu** durante un SOS (tramite l'app Messaggi del tuo dispositivo, vedi §7).

---

## 3. Categorie di dati trattati

| Categoria | Esempi | Dove risiede |
|---|---|---|
| **Dati identificativi** | Identificativo stabile *Sign in with Apple*; nome (se lo fornisci); nome scelto per il Compagno | Dispositivo + Keychain |
| **Dati sulla salute / categorie particolari (art. 9 GDPR)** | Umore, diario, riflessioni quotidiane, risultati dei questionari di benessere (non diagnostici), contenuto delle conversazioni con il Compagno, "memoria" del Compagno | Dispositivo (e Compagno AI solo con consenso, §5) |
| **Dati di Apple Salute** | Ore di sonno, minuti di mindfulness | Dispositivo (lettura) — **non trasmessi a terzi** |
| **Dati relativi alla sicurezza (SOS)** | Trascrizione/registrazione audio del momento, posizione, contatto fidato avvisato, esito dell'allarme | Dispositivo; inviati **solo** al contatto scelto da te (§7) |
| **Contatti fidati** | Nome e numero di telefono inseriti manualmente da te | Dispositivo |
| **Dati di utilizzo tecnici minimi** | Contatori d'uso (messaggi giornalieri, saldo gettoni) | Keychain |
| **Dati di pagamento** | Acquisti e abbonamenti | Gestiti **interamente da Apple** — il Titolare non vi accede (§8) |

**help2you non utilizza cookie di profilazione, non effettua tracciamento pubblicitario, non integra SDK di analytics o advertising di terze parti.**

---

## 4. Finalità del trattamento e basi giuridiche

| Finalità | Base giuridica |
|---|---|
| Erogare le funzioni di benessere dell'App (umore, diario, esercizi, statistiche) elaborate **sul dispositivo** | Esecuzione del contratto, art. 6(1)(b); per i dati sulla salute: **consenso esplicito**, art. 9(2)(a) |
| Far funzionare il **Compagno AI** trasmettendo il contesto necessario a fornitori esterni (§5) | **Consenso esplicito**, art. 9(2)(a) — revocabile in ogni momento |
| **Rete di sicurezza e Modalità SOS** (numeri di aiuto, allarme a un contatto, posizione) | Salvaguardia di interessi vitali, art. 6(1)(d), e art. 9(2)(c); legittimo interesse alla sicurezza della persona, art. 6(1)(f) |
| Accesso e autenticazione tramite **Sign in with Apple** | Esecuzione del contratto, art. 6(1)(b) |
| **Acquisti e abbonamenti** | Esecuzione del contratto e obblighi di legge (fiscali), art. 6(1)(b) e (c) |
| **Notifiche** gentili e promemoria (locali) | Consenso, art. 6(1)(a) |
| Sicurezza dell'App e prevenzione abusi | Legittimo interesse, art. 6(1)(f) |

Il conferimento dei dati sanitari e l'uso del Compagno AI sono **facoltativi**: senza consenso l'App resta utilizzabile nelle sue funzioni locali e la rete di sicurezza resta **sempre gratuita e disponibile**.

---

## 5. Il Compagno AI (intelligenza artificiale)

Quando usi il Compagno AI **e hai prestato il consenso al trattamento dei dati**, l'App trasmette i messaggi della conversazione e un **contesto sintetico** (nome di battesimo, umore recente, stato di benessere stimato, sintesi del profilo, "memoria" e preferenze di stile) a:

1. un **endpoint server gestito dal Titolare su Cloudflare Workers** (che custodisce le credenziali e inoltra la richiesta, senza conservare le conversazioni);
2. il fornitore del modello di intelligenza artificiale **Anthropic PBC** (modello "Claude"), con server **negli Stati Uniti**.

**Stai interagendo con un'intelligenza artificiale, non con una persona** (obbligo di trasparenza ai sensi dell'art. 50 del Regolamento UE 2024/1689 — "AI Act"). L'AI può commettere errori e non eroga prestazioni sanitarie.

- Anthropic tratta i dati come **responsabile del trattamento** ai sensi del proprio *Data Processing Addendum* e, secondo le sue condizioni per le API commerciali, **non utilizza i contenuti per addestrare i propri modelli**; può conservarli per un periodo limitato per finalità di sicurezza/abuso.
- Cloudflare agisce come **responsabile** per il trasporto della richiesta.
- Il trasferimento verso gli Stati Uniti è descritto al §10.

Se **non** presti il consenso, al Compagno **non** viene inviato alcun dato di profilazione o sulla salute.

---

## 6. Apple Salute (HealthKit)

Con la tua autorizzazione, l'App **legge** dati di **sonno** e **mindfulness** da Apple Salute per mostrarteli nel Diario. Questi dati **restano sul dispositivo**, **non** vengono trasmessi al Compagno AI né ad alcun server e **non** vengono usati per finalità pubblicitarie o di marketing (in conformità alle linee guida Apple su HealthKit). Puoi revocare l'accesso in qualsiasi momento da *Impostazioni iOS → Privacy e sicurezza → Salute*.

---

## 7. Rete di sicurezza e Modalità SOS

La rete di sicurezza è **sempre gratuita**. La Modalità SOS, se attivata, può:
- **registrare un breve audio** del momento e produrne una **trascrizione** (il riconoscimento vocale avviene **sul dispositivo** quando supportato; in caso contrario può avvenire tramite i servizi Apple di riconoscimento vocale);
- rilevare la **posizione** ("solo mentre usi l'app") da includere nel messaggio;
- preparare un **messaggio di allerta** verso un **contatto fidato scelto da te**.

L'invio avviene **tramite l'app Messaggi del tuo dispositivo**: sei tu a inviare, e i dati (audio, posizione, testo) vanno **solo** al destinatario che scegli. Audio e dettagli dell'evento sono conservati **localmente** nell'Archivio SOS finché non li elimini. La base giuridica è la **salvaguardia di interessi vitali** (artt. 6(1)(d) e 9(2)(c) GDPR).

> ⚠️ help2you **non è un servizio di emergenza**. In caso di pericolo immediato va sempre contattato il **112**.

---

## 8. Pagamenti, abbonamenti e gettoni

Gli acquisti (abbonamenti Plus/Pro e pacchetti di gettoni) avvengono tramite il sistema **In‑App Purchase di Apple**. Il pagamento è gestito **interamente da Apple**: il Titolare **non riceve né tratta** i dati della tua carta o di pagamento. I rapporti con Apple sono regolati dalla privacy policy di Apple.

---

## 9. Destinatari e Responsabili del trattamento

I tuoi dati non sono diffusi né venduti. Possono essere trattati, nei limiti sopra descritti, dai seguenti soggetti in qualità di **Responsabili del trattamento** (art. 28 GDPR) o autonomi titolari, ciascuno con propria informativa:

- **Apple Inc. / Apple Distribution International Ltd.** — sistema operativo, Sign in with Apple, HealthKit, notifiche, distribuzione e pagamenti App Store.
- **Cloudflare, Inc.** — infrastruttura dell'endpoint server (proxy del Compagno AI).
- **Anthropic PBC** — fornitore del modello di intelligenza artificiale (solo con consenso, §5).

L'elenco aggiornato dei responsabili è disponibile su richiesta al Titolare.

---

## 10. Trasferimenti verso Paesi terzi (extra‑UE)

L'uso del Compagno AI comporta un **trasferimento di dati verso gli Stati Uniti** (Anthropic; eventualmente Cloudflare per l'instradamento). Tale trasferimento avviene sulla base di:
- il tuo **consenso esplicito** all'uso del Compagno AI e al relativo trattamento (artt. 9(2)(a) e 49(1)(a) GDPR), e/o
- le **Clausole Contrattuali Standard** (SCC) della Commissione UE previste dai contratti di trattamento dati dei fornitori, con misure supplementari adeguate.

Se non desideri che i tuoi dati siano trasferiti, è sufficiente **non usare il Compagno AI / non prestare il consenso**: tutte le altre funzioni restano disponibili.

---

## 11. Periodo di conservazione

- **Dati locali** (umore, diario, chat, ecc.): conservati sul dispositivo **finché non li elimini** dall'App o disinstalli l'App. Puoi eliminarli in qualsiasi momento da *Profilo → Privacy e dati*.
- **Keychain** (identificativo Apple, contatori d'uso, saldo gettoni): per loro natura **sopravvivono alla disinstallazione**; vengono rimossi eliminando i dati dall'App o tramite richiesta al Titolare.
- **Dati presso il Compagno AI**: conservati dal fornitore per il periodo limitato previsto dalle sue condizioni (per finalità di sicurezza), e **non** usati per addestramento.
- **Dati di legge (fiscali)**: i documenti contabili relativi agli acquisti sono conservati per il termine di legge (10 anni).

---

## 12. I tuoi diritti

In qualità di interessato puoi esercitare in ogni momento i diritti di cui agli artt. 15‑22 GDPR:
- **accesso** ai dati e copia;
- **rettifica** e **cancellazione** ("diritto all'oblio");
- **limitazione** e **opposizione** al trattamento;
- **portabilità** dei dati (l'App offre l'esportazione da *Profilo → Privacy e dati*);
- **revoca del consenso** in qualsiasi momento (senza pregiudicare i trattamenti già effettuati);
- **reclamo** all'autorità di controllo: **Garante per la protezione dei dati personali** (www.garanteprivacy.it).

Per esercitarli scrivi a **info@mn99-lab.it**. Risponderemo entro un mese (art. 12 GDPR). Molti diritti (accesso, cancellazione, esportazione) sono inoltre esercitabili **direttamente dall'App**.

---

## 13. Minori

help2you è **riservata esclusivamente alle persone maggiorenni (18 anni compiuti)**. L'App **non è destinata né rivolta a minori** e non ne raccoglie consapevolmente i dati. In fase di registrazione l'utente dichiara di essere maggiorenne; la data di nascita eventualmente fornita può essere utilizzata anche per verificare il requisito di età. Qualora il Titolare venga a conoscenza di dati raccolti da un minore, provvederà a cancellarli. Sull'App Store l'App è classificata per un pubblico adulto (rating 17+).

---

## 14. Sicurezza dei dati

Adottiamo misure tecniche e organizzative adeguate (art. 32 GDPR): archiviazione locale, uso del Keychain di sistema, cifratura in transito (HTTPS/TLS) verso l'endpoint server, accesso autenticato, minimizzazione dei dati inviati al Compagno AI e custodia delle credenziali dei servizi lato server (mai nell'App).

---

## 15. Cookie

L'App **non utilizza cookie**. L'eventuale sito web che ospita questa informativa è statico e non installa cookie di profilazione.

---

## 16. Modifiche

Il Titolare può aggiornare la presente informativa. La versione vigente è sempre disponibile nell'App e all'URL pubblico indicato in App Store. In caso di modifiche sostanziali ti sarà richiesto un nuovo consenso ove necessario.

---

*help2you — Informativa resa dal Titolare Matteo Bonetti. Per domande: info@mn99-lab.it*
