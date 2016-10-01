# Come trasformare l'open-source in un lavoro
*Una guida pratica per sviluppatori squattrinati*

In questa guida verranno illustrati tutti i metodi che conosco per venire pagati per i propri lavori open-source, grezzamente ordinati dal più piccolo al più grande. Ogni categoria contiene dei link ad esempi reali. (Dove possibile, ho provato a linkare ad articoli utili o pagine invece che a semplici homepage.).

Le categorie non si escludono mutualmente. Per esempio, un progetto potrebbe avere una fondazione ma comunque utilizzare il crowdfunding per ottenere fondi. Altri potrebbero fare consulenze ed allo stesso tempo avere un bottone di donazione e così via. L'obbiettivo di questa guida è fornire una lista esaustiva di tutti i metodi per ottenere fondi, in modo che ognuno possa individuare il migliore per il proprio progetto.

---


# Sommario dei contenuti
1. [Pulsante di donazione](#pulsante-di-donazione)
2. [Bounty](#bounty)
3. [Raccolta fondi iniziale](#raccolta-fondi-iniziale)
4. [Raccolta fondi ricorrente](#raccolta-fondi-ricorrente)
5. [Libri e merchandise](#libri-e-merchandise)
6. [Pubblicità e sponsorizzazioni](#pubblicità-e-sponsorizzazioni)
7. [Farti assumere da un'azienda per lavorare al progetto](#farti-assumere-da-un-azienda-per-lavorare-al-progetto)
8. [Iniziare un progetto mentre si è assunti in un'azienda](#iniziare-un-progetto-mentre-si-è-assunti-in-un-azienda)
9. [Grant](#grant)
10. [Consulenza e servizi](#consulenza-e-servizi)
11. [SaaS](#saas)
12. [Licenza freemium](#licenza-freemium)
13. [Doppia licenza](#doppia-licenza)
14. [Open core](#open-core)
15. [Fondazioni e consorzi](#fondazioni-e-consorzi)
16. [Venture capital](#venture-capital)

APPENDICE: [Contribuire a questa guida](#contributing-to-this-guide) // [Licenza e attribuzione](#license-and-attribution)
TRADUZIONI: [Chinese(中文版)](https://github.com/wizicer/FinancialSupportForopen-source) // [Inglese(english)](https://github.com/nayafia/lemonade-stand)

**le note "sforzo personale" si riferiscono ad esempi di finanziamento dove è interessato un singolo utente e non un progetto

##Pulsante di donazione
*Inserisci un pulsante di donazione nel tuo sito. Stripe e PayPal sono alcuni esempi di servizi che ti permettono di accettare donazioni.*

####Vantaggi
* Few strings attached
* Comporta poco sforzo per l'integrazione, da svolgere una sola volta

####Svantaggi
* Solitamente non raccimolano molti soldi, a meno che non venga dedicato del tempo a promuovere la raccolta
* Necessita di una terza parte per accettare le donazioni, questo comporta la presenza di fee sulle donazioni. Esempi sono Stripe e PayPal
* Per ottenere donazioni senza che il donatore venga tassato, in alcuni stati è necessario avere un'organizzazione no-profit per accettare donazioni, difficilmente gestibili da singole persone. [SFC](http://sfconservancy.org), [OpenCollective](http://opencollective.com), e [NumFOCUS](http://www.numfocus.org) sono alcuni esempi.
* Molte volte non è chiaro chi merita i soldi raccolti con le donazioni o come verranno distribuiti tra gli sviluppatori del progetto. Un servizio come [OpenCollective](http://opencollective.com) potrebbe aiutare a mitigare questo fatto.

####Casi di studio
* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)

##Bounties
*A volte, progetti e aziende pubblicano dei "bounty" per svolgere del lavoro su un progetto open-source (per esempio "risolvi il bug ed ottieni $100). Ci sono vari siti internet, elencati più avanti, che facilitano l'inserimento e la ricerca di bounty.

####Vantaggi
* Open to community participation
* Il denaro è destinato al adempimento di uno specifico task (più simile ad un pagamento che ad una donazione)
* Molto popolare per i task relativi alla sicurezza

####Svantaggi
* Potrebbe creare meccanismi perversi nel progetto (codice di bassa qualità, distrazione dalle priorità del progetto)
* Solitamente il compenso per un bounty non è molto alto (~<€500)
* Non fornisce un entrata costante

####Casi di studio
* [Bountysource](http://bountysource.com)
* [GitHub Bug Bounty Program](https://bounty.github.com/)

##Raccolta fondi iniziale
*Se hai un'idea specifica che ti piacerebbe implementare (piuttosto che un progetto già avviato), una campagna di raccolta fondi iniziale può aiutare a raccimolare il denaro necessario. Sia singoli utenti che aziende potrebbero essere interessate a donare per la tua campagna.*

####Vantaggi
* Few strings attached
* Può essere semplice da gestire (legalmente) tramite servizi come [Kickstarter](https://kickstarter.com/)

####Svantaggi
* Molto lavoro necessario per curare la campagna di raccolta
* I donatori si aspettano solitamente un risultato concreto dalla raccolta fondi, e quindi dei vantaggi
* Solitamente non raccolgono molti fondi (~€50.000)
* Le aziende spesso non sono a loro agio nel donare in una raccolta fondi

####Casi di studio
* [Michal Papis + Rvm (sforzo personale)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Andrew Godwin + Django (sforzo personale)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [ribasushi + CPAN (sforzo personale)](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)
* [RESTful WP-CLI](https://poststatus.com/kickstarter-open-source-project/)

##Raccolta fondi ricorrente
*Se necessiti un finanziamento per un progetto in corso, puoi creare una raccolta fondi ricorrente nel tempo, con cadenza mensile o annuale. Coloro che utilizzano il tuo progetto regolarmente (sia singoli che aziende) potrebbero essere interessati a finanziare il tuo lavoro.*

####Vantaggi
* Few strings attached
* Può essere semplice da gestire (legalmente) tramite servizi come [Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Gratipay](https://gratipay.com/) e [OpenCollective](https://opencollective.com)

####Svantaggi
* Difficile trovare utenti disposti a donare per più di una volta (è necessario che il progetto sia già popolare ed utilizzato)
* I donatori si aspettano solitamente un risultato concreto dalla raccolta fondi, e quindi dei vantaggi; nelle raccolte ricorrenti questo aspetto è più accentuato
* Solitamente non raccolgono molti fondi (~€1.000-4.000 mensili)
* Le aziende spesso non sono a loro agio nel donare in una raccolta fondi

####Casi di studio
* [MochaJS](https://opencollective.com/mochajs)
* [React-boilerplate](https://opencollective.com/react-boilerplate)
* [jsbin](https://gratipay.com/jsbin/)
* [Tom Christie + Django REST framework (sforzo personale)](https://fund.django-rest-framework.org/topics/funding/)
* [Ruby Together](https://rubytogether.org)

##Libri e merchandise
*Se sei un esperto in un determinato campo che altre persone reputano interessante o del quale vogliono acquisire maggiori conoscenze, puoi scrivere e vendere un libro o una serie di libri a riguardo. Puoi trovare un editore (come O'Reilly per esempio) oppure pubblicarlo autonomamente. Oltre ai libri, alcuni progetti vendono anche merchandise (come magliette, portachiavi, adesivi) per supportare il loro lavoro.*

####Vantaggi
* Outcome not tied to project work itself, so you retain creative freedom
* Can serve as marketing for the project itself
* Can be recurring source of revenue after initial development

####Svantaggi
* Spesso non sono una fonte di fondi significativa
* Può distrarre dallo sviluppo del progetto
* Il merchandise può avere dei costi da anticipare

####Casi di studio
* [Lua](https://www.lua.org/pil/)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (sforzo personale)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (sforzo personale)](http://www.poodr.com/)
* [Kyle Simpson + You Don't Know JS (sforzo personale)](https://github.com/getify/You-Dont-Know-JS)
* [CocoaPods (fundraising for charity)](https://cocoapods.org/socks)

##Pubblicità e sponsorizzazioni
*Se il tuo progetto ha un vasto numero di utenti, puoi vendere delle sponsorizzazioni alle aziende che sono interessate alla tipologia di utenti che utilizzano il tuo progetto. Probabilmente avrai un pubblico dagli interessi ben definiti (per esempio in un progetto Python, puoi assumere che i tuoi utenti sono familiari con Python), quindi puoi utilizzare questa caratteristica a tuo vantaggio.*

####Vantaggi
* Business model aligned with something people are willing to pay for

####Svantaggi
* E' necessario un gran numero di utenti per giustificare una sponsorizzazione
* Bisogna mantenere la fiducia e la trasparenza con gli utenti (per esempio, non tracciando gli utenti)
* Può essere molto dispendioso in termini di tempo trovare nuovi clienti

####Casi di studio
* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)

##Farti assumere da un'azienda per lavorare al progetto
*Le aziende a volte assumono personale per lavorare a software open-source. Trova un'azienda che usa un progetto al quale vorresti lavorare. Spesso viene proposto un contratto che prevede per esempio il 50% di lavoro per l'azienda ed il 50% di lavoro al progetto open-source. ALternativamente, se hai un'idea per un nuovo progetto, puoi trovare un'azienda che potrebbe essere interessata nell'utilizzare tale prodotto. In queste situazioni, avere dell'esperienza dimostrata having demonstrated experience you can point to will be very helpful.*

####Vantaggi
* Taps into those who have resources (i.e. companies)
* Può essere ben allineato con le necessità dell'azienda
* Entrate costanti

####Svantaggi
* Bisogna essere fortunati: non esiste un modo prestabilito per attuare questo tipo di soluzione
* Il progetto deve essere già conosciuto ed usato
* Person not contributing to company’s bottom line, which makes them expendable
* Governance issues, company could have undue influence over project
* Can affect project dynamics + balance

####Casi di studio
* [Donald Stufft + Hewlett-Packard and Python packaging (sforzo personale)](https://twitter.com/dstufft/status/594119386333609984)
* [Rich Hickey + Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [Aaron Patterson + ManageIQ and Ruby, Rails (sforzo personale)](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Ryan Dahl + Joyent and Node.js (opens a YouTube video) (sforzo personale)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)

##Iniziare un progetto mentre si è assunti in un'azienda
*Molti progetti open-source iniziano come side project di un dipendente di un'azienda. The project might eventually outgrow the company, but starting it as a side project can be a great way to incubate the idea.*

*Se vuoi seguire questa strada, assicurati di aver capito le politiche dell'azienda riguardo la produzione di software open-source. Alcune aziende incoraggiano i dipendenti a contribuire all'open-source durante le ore lavorative, mentre altre potrebbero trattare il tuo lavoro open-source come un prodotto dell'azienda. Non assumere nulla, chiedi ai tuoi datori di lavori prima di iniziare.*

####Vantaggi
* Libertà di dedicarsi a nuove idee senza la preoccupazione del salario
* Può essere ben allineato con le necesità dell'azienda
* Ideale per idee nuove e sperimentali

####Svantaggi
* Need to do it as a side project or be approved to work on it during salaried time
* Risk of undue company influence
* Can lead to complicated governance later down the line

####Casi di studio
* [Mozilla and Rust](https://www.rust-lang.org/faq.html#is-this-project-controlled-by-mozilla)
* [Google and Go](https://golang.org/doc/faq#history)
* [Facebook and React](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)
* [Futurice's open-source program](http://futurice.com/blog/sponsoring-free-time-open-source-activities)

##Grant
*I Grant sono grosse donazioni che non richiedono una restituzione. Spesso chi emana i grant riceve altri benefici, come un accesso a te (cosa vuol dire?), dimostrazione di impatto del progetto, un report del tuo lavoro o benefici riguardanti le tasse.*

*I grant possono arrivare da diverse fonti, incluse aziende, fondazioni software, fondazioni filantropiche o dal governo. L'aspetto tecnico e legale di un grant varia a seconda della fonte: per esempio, un'azienda potrebbe darti un grant ma trattarlo legalmente come una fattura di consulenza. Una fondazione filantropica può inviare grant solo a no-profit, quindi dovresti avere una no-profit anche tu, o (più comunemente) trovare una noprofit che ti sponsorizzi. Se non sei familiare coi grant, il miglior modo per capire come funzionano è parlare con qualcuno che ne ha ricevuto uno. Alcuni esempi di progetti che hanno ricevuto un grant li puoi trovare più avanti.*


####Vantaggi
* Fewer strings attached
* Guaranteed money can help project focus for an unbroken period of time
* Gives project room to breathe and experiment

####Svantaggi
* Non esistono molti donatori di grant per progetti relativi a software 
* I grant finiscono; devi comunque trovare un modo per sostenerti anche dopo aver terminato i soldi del grant

####Casi di studio
* [Dat](https://usopendata.org/)
* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Django + Mozilla open-source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)

##Consulenza e servizi
*La consulenza è un ottimo modo per ricevere fondi per un progetto open-source. Hai più libertà nella gestione del tempo (per esempio, consulenze per 30 ore alla settimana e 10 ore per lo sviluppo). I consulenti sono pagati solitamente di più rispetto ad un dipendente salariato in quanto il loro lavoro è meno costante, non ricevono benefici, ecc. Se hai pianificato di fare questo tipo di attività regolarmente, può essere necessario istituire una SRL (od un tipo di società equivalente in un altro stato).*

*Se il tuo progetto è popolare, puoi anche offrire consulenza e servizi riguardanti il progetto stesso. Per esempio, un cliente potrebbe pagarti per implementare il progetto per conto loro, creare delle funzionalità custom, o istruirli riguardo l'utilizzo del software.*


####Vantaggi
* Le aziende sono spesso disposte a pagare per attività di consulenza

####Svantaggi
* Le consulenze richiedono tempo e risorse umane, è difficile scalare questo approccio
* Le necessità del business possono distrarre dalla scrittura del codice e da altre attività legate al progetto
* Può essere in contrasto con la realizzazione di un software semplice da utilizzare
* Per essere disposti a pagare per servizi correlati ad esso, il progetto necessità di avere sufficiente popolarità


####Casi di studio
* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)

##SaaS
*SaaS è l'acronimo di [Software as a Service](https://en.wikipedia.org/wiki/Software_as_a_service). In questo modello, il codice principale è open-source, ma puoi offrire servizi aggiuntivi a pagamento che permettono ad altre persone di utilizzare il tuo progetto con facilità. Un esempio di servizio a pagamento potrebbe essere far pagare per l'hosting.*

####Vantaggi
* Can build community around open project and make money off of services for hosting
* Allows open-source project to focus on users and as needs grow to help enterprises adopt the project
* Can scale by number of users

####Svantaggi
* Often means the hosting needs to be cheaper than hiring a dev to run the project for you.
* “Two tiers” of product support can make free users unhappy

####Casi di studio
* [WordPress.com](http://wordpress.com/)
* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [GitLab](https://gitlab.com)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [Ghost](https://ghost.org/)

##Licenze freemium
*Le licenze "Freemium" non sono open-source, in quanto non offrono contemporaneamente tutte le [libertà richieste](https://en.wikipedia.org/wiki/The_Open_Source_Definition) da una licenza open-source (per esempio, il codice sorgente non è allo stesso tempo visibile liberamente e disponibile per la redistribuzione e modifica). Still, they are tangentially related to open-source work.*

*Una licenza freemium restringe alcune libertà dell'open-source; per esempio il codice potrebbe essere visibile, ma viene richiesta una licenza commerciale per utilizzarlo.*


####Vantaggi
* Business model aligned with something people are willing to pay for
* Alto potenziale di scalabilità
* Adatto per prodotti end-user

####Svantaggi
* Non propriamente definibile open-source
* Ancora un area in esplorazione (correlato al movimento [shareware](https://en.wikipedia.org/wiki/Shareware)) e non ancora ben collaudato

####Casi di studio
* [Fair Source](https://fair.io/), used by [Sourcegraph](https://sourcegraph.com/)
* [BSL (Business Source License)](https://mariadb.com/bsl-faq-adopting), used by [MariaDB](https://mariadb.com/)


##Doppia license
*A volte, un progetto può offrire lo stesso codice con due differenti licenze: una licenza commerciale ed una open-source (per esempio GPL). La seconda è gratuita per chiunque, ma le aziende pagano la prima per stare tranquille legalmente.*

####Vantaggi
* Business model aligned with something people are willing to pay for
* Alto potenziale di scalabilità

####Svantaggi
* Can be at odds with making software freely accessible
* Il progetto deve essere abbastanza grande in modo da motivare la sua esistenza ed il pagamento di una licenza commerciale


####Casi di studio
* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [SQLite](https://www.sqlite.org/copyright.html)

##Open core (Nucleo aperto)
*In un modello [open core](https://en.wikipedia.org/wiki/Open_core), alcune parti del progetto sono gratuite, mentre altre funzionalità sono proprietarie e disponibili solo per utenti paganti. Solitamente questo modello funziona quando c'è una richiesta di funzionalità enterprise del prodotto.*

####Vantaggi
* Business model aligned with something people are willing to pay for
* Alto potenziale di scalabilità

####Svantaggi
* Il progetto deve possedere delle funzionalità che possono essere rese a pagamento (quindi avere delle funzionalità esclusive per le quali qualcuno pagherebbe)
* Can be at odds with making software freely accessible
* “Two tiers” of product support can make free users unhappy

####Casi di studio
* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Sidekiq](http://sidekiq.org/)

##Fondazioni e consorzi
*Una [fondazione](https://it.wikipedia.org/wiki/Fondazione_(ente)) è un entità legale che può accettare o emanare donazioni. Dato che il suo scopo primario non è fare profitto, possono essere un ottima scelta per guidare un progetto in modo neutrale. In Italia, le fondazioni vengono classificate come organizzazioni non a scopo di lucro (anche note come no-profit).


####Vantaggi
* Neutralità. Le fondazioni proteggono il codice ed aiutano lo svilupo della comunità attorno al software
* Influence distributed across multiple donors
* Can legitimize project, companies might feel more comfortable giving to foundations than individuals

####Svantaggi
* Vale la pena solo per grossi progetti
* Difficult to set up for IRS reasons (many do 501(c)(6) instead of 501(c)(3)), restrictions on what you can do
* Requires serious community effort and diverse skills (you still need to fundraise after setting up the entity!)

####Casi di studio
* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)

##Venture capital
*I Venture capital sono un metodo di finanziamento per business a crescita rapida. Al contrario di prestiti bancari o ad altre forme di finanziamento tramite debito, i venture capital acquisiscono una equity (una quota percentuale di possesso del business) in cambio di un finanziamento. Il vantaggio rispetto ad un prestito è che nel caso di fallimento del progetto non devi ripagare un debito con qualcuno. Se invece il progetto ha successo, devi aspettarti di rendere il capitale investito dai VC ad un multiplo.*

*I Venture capital sono ad "alto rischio ed alto profitto". I VC sono più tolleranti al rischio rispetto ad una banca, ma si aspettano un grande guadagno nel caso che il business abbia successo. Se pianifichi di ottenere dei fondi da un venture capital, è necessario creare una società, in Italia può essere una SRL. Se non sei familiare con il processo dei venture capital, il modo migliore per iniziare è contattare altri come te che hanno già ottenuto dei fondi da un venture.*

####Vantaggi
* Il supporto di un Venture capital può essere di aiuto per la creazione di un business
* Grande quantità di capitale disponibile

####Svantaggi
* I Venture capital finanziano i progetti nella prospettiva di una futura exit (ovvero la vendita delle proprie quote per un valore superiore all'investimento iniziale). L'esperienza suggerisce che questo è difficilmente attuabile con i business basati sull'open-source
* I Venture capital possono cambiare prospettiva, distraendo lo sviluppo dalle priorità reali

####Casi di studio
* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)

---

### Contribuire alla guida

Chiunque voglia contribuire a questa guida con ulteriori integrazioni, modifiche, nuove categorie e suggerimenti, può farlo tramite una pull-request o inserendo una issue nel repository. I vantaggi e svantaggi descritti sono soggettivi, dunque rispecchiano il punto di vista dell'autore e di coloro che hanno apportato delle modifiche.


### Licenza e attribuzione
Questa guida è disponibile sotto licenza "Creative Commons CC-BY 3.0 License", sei libero di usarla per qualsiasi scopo, commerciale e non commerciale, con il solo obbligo di citare l'autore originale. 

La guida è stata realizzata da Davide Gessa ([@dakk](http://github.com/dakk), [mail](mailto:gessadavide@gmail.com)). Il documento si basa su un progetto in lingua inglese denominato [lemonade-stand](https://github.com/nayafia/lemonade-stand).


### Donazioni
Chi vuole può fare una donazione tramite Bitcoin all'indirizzo: 13gbybVyaYy5yA7Z7si2zJfo2Aat6d7c8z

![Donation QR code](https://blockchain.info/qr?data=13gbybVyaYy5yA7Z7si2zJfo2Aat6d7c8z&size=200)


