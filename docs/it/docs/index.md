<p align="center">
  <a href="https://fastapi.tiangolo.com"><img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" alt="FastAPI"></a>
</p>
<p align="center">
    <em>Framework FastAPI, alte prestazioni, facile da imparare, veloce da programmare, pronto per il rilascio in produzione</em>
</p>
<p align="center">
<a href="https://travis-ci.com/tiangolo/fastapi" target="_blank">
    <img src="https://travis-ci.com/tiangolo/fastapi.svg?branch=master" alt="Build Status">
</a>
<a href="https://codecov.io/gh/tiangolo/fastapi" target="_blank">
    <img src="https://img.shields.io/codecov/c/github/tiangolo/fastapi" alt="Coverage">
</a>
<a href="https://pypi.org/project/fastapi" target="_blank">
    <img src="https://badge.fury.io/py/fastapi.svg" alt="Package version">
</a>
<a href="https://gitter.im/tiangolo/fastapi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge" target="_blank">
    <img src="https://badges.gitter.im/tiangolo/fastapi.svg" alt="Join the chat at https://gitter.im/tiangolo/fastapi">
</a>
</p>

---

**Documentazione**: <a href="https://fastapi.tiangolo.com" target="_blank">https://fastapi.tiangolo.com</a>

**Codice Sorgente**: <a href="https://github.com/tiangolo/fastapi" target="_blank">https://github.com/tiangolo/fastapi</a>

---

FastAPI è un web framework moderno e veloce (ad alte prestazioni) per progettare API con Python 3.6+, basato sulle annotazioni di tipo standard di Python.

Le sue caratteristiche principali sono:

* **Veloce**: Prestazioni elevate, alla pari di **NodeJS** e **Go** (grazie a Starlette e Pydantic). [Uno dei framework in Python più veloci in circolazione](#performance).
* **Veloce da programmare**: Velocizza il lavoro consentendoti di rilasciare nuove funzionalità tra il 200% e il 300% più velocemente. *
* **Meno errori**: Riduce di circa il 40% gli erorri commessi dagli sviluppatori. *
* **Intuitivo**: Ottimo supporto per gli editor di testo con <abbr title="anche noto come IntelliSense">autocompletamento</abbr> ovunque. Perdi meno tempo a trovare errori.
* **Facile**: Progettato per essere facile da usare e imparare. Perdi meno tempo a consultare la documentazione.
* **Breve**: Minimizza la duplicazione di codice. Multiple funzionalità con ciascuna dichiarazione di parametri. Meno errori.
* **Robusto**: Scrivi codice pronto per essere rilasciato in produzione con una documentazione dell'API interattiva generata automaticamente.
* **Basato sugli standard**: Pienamente compatibile con gli open standard per le API: <a href="https://github.com/OAI/OpenAPI-Specification" class="external-link" target="_blank">OpenAPI</a> (prima conosciuto come Swagger) e <a href="http://json-schema.org/" class="external-link" target="_blank">JSON Schema</a>.

<small>* Questa stima è basata su test eseguiti all'interno di un team di sviluppo di applicazioni professionali.</small>

## Recensioni

"_[...] I'm using **FastAPI** a ton these days. [...] I'm actually planning to use it for all of my team's **ML services at Microsoft**. Some of them are getting integrated into the core **Windows** product and some **Office** products._"

<div style="text-align: right; margin-right: 10%;">Kabir Khan - <strong>Microsoft</strong> <a href="https://github.com/tiangolo/fastapi/pull/26" target="_blank"><small>(ref)</small></a></div>

---

"_We adopted the **FastAPI** library to spawn a **REST** server that can be queried to obtain **predictions**. [for Ludwig]_"

<div style="text-align: right; margin-right: 10%;">Piero Molino, Yaroslav Dudin, and Sai Sumanth Miryala - <strong>Uber</strong> <a href="https://eng.uber.com/ludwig-v0-2/" target="_blank"><small>(ref)</small></a></div>

---

"_**Netflix** is pleased to announce the open-source release of our **crisis management** orchestration framework: **Dispatch**! [built with **FastAPI**]_"

<div style="text-align: right; margin-right: 10%;">Kevin Glisson, Marc Vilanova, Forest Monsen - <strong>Netflix</strong> <a href="https://netflixtechblog.com/introducing-dispatch-da4b8a2a8072" target="_blank"><small>(ref)</small></a></div>

---

"_I’m over the moon excited about **FastAPI**. It’s so fun!_"

<div style="text-align: right; margin-right: 10%;">Brian Okken - <strong><a href="https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855" target="_blank">Python Bytes</a> podcast host</strong> <a href="https://twitter.com/brianokken/status/1112220079972728832" target="_blank"><small>(ref)</small></a></div>

---

"_Honestly, what you've built looks super solid and polished. In many ways, it's what I wanted **Hug** to be - it's really inspiring to see someone build that._"

<div style="text-align: right; margin-right: 10%;">Timothy Crosley - <strong><a href="http://www.hug.rest/" target="_blank">Hug</a> creator</strong> <a href="https://news.ycombinator.com/item?id=19455465" target="_blank"><small>(ref)</small></a></div>

---

"_If you're looking to learn one **modern framework** for building REST APIs, check out **FastAPI** [...] It's fast, easy to use and easy to learn [...]_"

"_We've switched over to **FastAPI** for our **APIs** [...] I think you'll like it [...]_"

<div style="text-align: right; margin-right: 10%;">Ines Montani - Matthew Honnibal - <strong><a href="https://explosion.ai" target="_blank">Explosion AI</a> founders - <a href="https://spacy.io" target="_blank">spaCy</a> creators</strong> <a href="https://twitter.com/_inesmontani/status/1144173225322143744" target="_blank"><small>(ref)</small></a> - <a href="https://twitter.com/honnibal/status/1144031421859655680" target="_blank"><small>(ref)</small></a></div>

---

## **Typer**, il FastAPI dei CLI

<a href="https://typer.tiangolo.com" target="_blank"><img src="https://typer.tiangolo.com/img/logo-margin/logo-margin-vector.svg" style="width: 20%;"></a>

Se stai sviluppando un'app <abbr title="Command Line Interface (interfaccia della riga di comando)">CLI</abbr> per essere usata nel terminale invece che una web API, ti consigliamo <a href="https://typer.tiangolo.com/" class="external-link" target="_blank">**Typer**</a>.

**Typer** è il fratello minore di FastAPI. Ed è stato ideato per essere il **FastAPI dei CLI**. ⌨️ 🚀

## Requisiti

Python 3.6+

FastAPI si appoggia a queste librerie:

* <a href="https://www.starlette.io/" class="external-link" target="_blank">Starlette</a> per la parte web.
* <a href="https://pydantic-docs.helpmanual.io/" class="external-link" target="_blank">Pydantic</a> per la parte dati.

## Installazione

<div class="termy">

```console
$ pip install fastapi

---> 100%
```

</div>

Avrai anche bisogno di un server ASGI per il rilascio in produzione come <a href="http://www.uvicorn.org" class="external-link" target="_blank">Uvicorn</a> oppure <a href="https://gitlab.com/pgjones/hypercorn" class="external-link" target="_blank">Hypercorn</a>.

<div class="termy">

```console
$ pip install uvicorn

---> 100%
```

</div>

## Esempio

### Crea un file

* Crea un file `main.py` con:

```Python
from fastapi import FastAPI

app = FastAPI()


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: str = None):
    return {"item_id": item_id, "q": q}
```

<details markdown="1">
<summary>Oppure usa <code>async def</code>...</summary>

Se il tuo codice usa `async` / `await`, allora usa `async def`:

```Python hl_lines="7 12"
from fastapi import FastAPI

app = FastAPI()


@app.get("/")
async def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
async def read_item(item_id: int, q: str = None):
    return {"item_id": item_id, "q": q}
```

**Nota**:

Se vuoi approfondire, consulta la sezione _"In a hurry?"_ su <a href="https://fastapi.tiangolo.com/async/#in-a-hurry" target="_blank">`async` e `await` nella documentazione</a>.

</details>

### Carica il server

Puoi far partire il server così:

<div class="termy">

```console
$ uvicorn main:app --reload

INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [28720]
INFO:     Started server process [28722]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```

</div>

<details markdown="1">
<summary>Informazioni sul comando <code>uvicorn main:app --reload</code>...</summary>

Vediamo il comando `uvicorn main:app` in dettaglio:

* `main`: il `main.py` (il "modulo" Python).
* `app`: l'oggetto creato dentro `main.py` con la riga di codice `app = FastAPI()`.
* `--reload`: ricarica il server se vengono rilevati cambiamenti del codice. Usalo solo durante la fase di sviluppo.

</details>

### Testa l'API

Apri il browser all'indirizzo <a href="http://127.0.0.1:8000/items/5?q=somequery" class="external-link" target="_blank">http://127.0.0.1:8000/items/5?q=somequery</a>.

Vedrai la seguente risposta JSON:

```JSON
{"item_id": 5, "q": "somequery"}
```

Hai appena creato un'API che:

* Riceve richieste HTTP ai _paths_ `/` e `/items/{item_id}`.
* Entrambi i _paths_ ricevono `GET` <em>operations</em> (anche chiamati <abbr title="metodi HTTP">HTTP _methods_</abbr>).
* Il _path_ `/items/{item_id}` ha un _path parameter_ `item_id` che deve essere un `int`.
* Il _path_ `/items/{item_id}` ha una `str` _query parameter_ `q`.

### Documentazione interattiva dell'API

Adesso vai su <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

Vedrai la documentazione interattiva dell'API (offerta da <a href="https://github.com/swagger-api/swagger-ui" class="external-link" target="_blank">Swagger UI</a>):

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-01-swagger-ui-simple.png)

### Documentazione interattiva alternativa

Adesso accedi su <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

Vedrai la documentazione interattiva dell'API (offerta da <a href="https://github.com/Rebilly/ReDoc" class="external-link" target="_blank">ReDoc</a>):

![ReDoc](https://fastapi.tiangolo.com/img/index/index-02-redoc-simple.png)

## Esempio più avanzato

Adesso modifica il file `main.py` per ricevere un _body_ da una richiesta `PUT`.

Dichiara il _body_ usando le annotazioni di tipo standard di Python, grazie a Pydantic.

```Python hl_lines="2  7 8 9 10  23 24 25"
from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()


class Item(BaseModel):
    name: str
    price: float
    is_offer: bool = None


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: str = None):
    return {"item_id": item_id, "q": q}


@app.put("/items/{item_id}")
def update_item(item_id: int, item: Item):
    return {"item_name": item.name, "item_id": item_id}
```

Il server dovrebbe ricaricarsi in automatico (perché hai specificato `--reload` al comando `uvicorn` qui sopra).

### Aggiornamento della documentazione interattiva

Adesso vai su <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

* La documentazione interattiva dell'API verrà automaticamente aggiornata, includendo il nuovo _body_:

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-03-swagger-02.png)

* Fai click sul pulsante "Try it out", che ti permette di inserire i parametri per interagire direttamente con l'API:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-04-swagger-03.png)

* Successivamente, fai click sul pulsante "Execute". L'interfaccia utente comunicherà con la tua API, invierà i parametri, riceverà i risultati della richiesta, e li mostrerà sullo schermo:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-05-swagger-04.png)

### Aggiornamento della documentazione alternativa

Ora vai su <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

* Anche la documentazione alternativa dell'API mostrerà il nuovo parametro della query e il _body_:

![ReDoc](https://fastapi.tiangolo.com/img/index/index-06-redoc-02.png)

### Ricapitolando

Ricapitolando, è sufficiente dichiarare **una sola volta** i tipi dei parametri, del body, ecc. come parametri di funzioni.

Puoi farlo usando le annotazioni di tipo standard di Python.

Non c'è bisogno di imparare una nuova sintassi, metodi o classi specifici a una libreria, ecc.

È sufficiente usare **Python 3.6+**.

Per esempio, per un `int`:

```Python
item_id: int
```

o per un modello più complesso `Item`:

```Python
item: Item
```

...solo con quella dichiarazione ottieni:

* Supporto per gli editor di testo, incluso:
    * Autocompletamento.
    * Controllo sulle annotazioni di tipo.
* Validazione dei dati:
    * Errori chiari e automatici quando i dati sono invalidi.
    * Validazione anche per gli oggetti JSON altamente nidificati.
* <abbr title="anche noto come: serializzazione, parsing, marshalling">Conversione</abbr> dei dati di input: da risorse esterne a dati e tipi di Python. È possibile leggere da:
    * JSON.
    * Path parameters.
    * Query parameters.
    * Cookies.
    * Headers.
    * Form.
    * File.
* <abbr title="also known as: serialization, parsing, marshalling">Conversione</abbr> dei dati di output: converte dati e tipi di Python a dati per la rete (come JSON):
    * Converte i tipi di Python (`str`, `int`, `float`, `bool`, `list`, ecc).
    * Oggetti `datetime`.
    * Oggetti `UUID`.
    * Modelli del database.
    * ...e molto di più.
* Generazione di una documentazione dell'API interattiva, con scelta dell'interfaccia grafica:
    * Swagger UI.
    * ReDoc.

---

Tornando al precedente esempio, **FastAPI**:

* Validerà che c'è un `item_id` nel percorso delle richieste `GET` e `PUT`.
* Validerà che `item_id` è di tipo `int` per le richieste `GET` e `PUT`.
    * Se non lo è, il client vedrà un errore chiaro e utile.
* Controllerà se c'è un parametro opzionale chiamato `q` (per esempio `http://127.0.0.1:8000/items/foo?q=somequery`) per le richieste `GET`.
    * Siccome il parametro `q` è dichiarato con `= None`, è opzionale.
    * Senza il `None` sarebbe stato obbligatorio specificarlo (come lo è il corpo della richiesta `PUT`).
* Per le richieste `PUT` su `/items/{item_id}`, leggerà il corpo come JSON e
    * Controlle che abbia un attributo obbligatorio `name`, e che sia una `str`.
    * Controlla che abbia un attributo obbligatorio `price`, e che sia un `float`.
    * Controlla che abbia un attributo opzionale `is_offer`, e che sia un `bool`, se presente.
    * Tutto questo funzionerebbe anche con oggetti JSON altamente nidificati.
* Convertirà da JSON a JSON automaticamente.
* Documenterà tutto con OpenAPI, che può essere usato per:
    * Sistemi di documentazione interattivi.
    * Sistemi di generazione di codice dal lato client, per molti linguaggi.
* Fornirà 2 interfacce di documentazione dell'API interattive.

---

Questa è solo la punta dell'iceberg, ma dovresti avere già un'idea di come il tutto funziona.

Trova questa riga di codice:

```Python
    return {"item_name": item.name, "item_id": item_id}
```

e cambiala da...

```Python
        ... "item_name": item.name ...
```

...a questa:

```Python
        ... "item_price": item.price ...
```

...e osserva come il tuo editor di testo autocompleterà gli attributi e saprà i loro tipi:

![editor support](https://fastapi.tiangolo.com/img/vscode-completion.png)

Per un esempio più completo che mostra più funzionalità del framework, consulta <a href="https://fastapi.tiangolo.com/tutorial/">Tutorial - User Guide</a>.

**Avviso spoiler**: il Tutorial - User Guide include:

* Dichiarazione di **parameters** da diversi posti come: **headers**, **cookies**, **form fields** e **files**.
* Come stabilire **vincoli di validazione** come `maximum_length` o `regex`.
* Un sistema di **<abbr title="also known as components, resources, providers, services, injectables">Dependency Injection</abbr>** facile e potente.
* Sicurezza e autenticazione, incluso il supporto per **OAuth2** con **token JWT** e autenticazione **HTTP Basic**.
* Tecniche più avanzate (ma ugualmente semplici) per dichiarare **modelli JSON altamente nidificati** (grazie a Pydantic).
* E altre funzionalità (grazie a Starlette) come:
    * **WebSockets**
    * **GraphQL**
    * test molto facili basati su `requests` e `pytest`
    * **CORS**
    * **Cookie Sessions**
    * ...e molto di più.

## Prestazioni

Benchmark indipendenti di TechEmpower mostrano che **FastAPI** basato su Uvicorn è <a href="https://www.techempower.com/benchmarks/#section=test&runid=7464e520-0dc2-473d-bd34-dbdfd7e85911&hw=ph&test=query&l=zijzen-7" class="external-link" target="_blank">uno dei framework in Python più veloci in circolazione</a>, solamente dietro a Starlette e Uvicorn (usate internamente da FastAPI). (*)

Per approfondire, consulta la sezione <a href="https://fastapi.tiangolo.com/benchmarks/" class="internal-link" target="_blank">Benchmarks</a>.

## Dipendenze opzionali

Usate da Pydantic:

* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - per un <abbr title="convertire la stringa che proviene da una richiesta HTTP in dati Python">"parsing"</abbr> di JSON più veloce.
* <a href="https://github.com/JoshData/python-email-validator" target="_blank"><code>email_validator</code></a> - per la validazione di email.

Usate da Starlette:

* <a href="http://docs.python-requests.org" target="_blank"><code>requests</code></a> - Richiesto se vuoi usare il `TestClient`.
* <a href="https://github.com/Tinche/aiofiles" target="_blank"><code>aiofiles</code></a> - Richiesto se vuoi usare `FileResponse` o `StaticFiles`.
* <a href="http://jinja.pocoo.org" target="_blank"><code>jinja2</code></a> - Richiesto se vuoi usare la configurazione template di default.
* <a href="https://andrew-d.github.io/python-multipart/" target="_blank"><code>python-multipart</code></a> - Richiesto se vuoi supportare il <abbr title="convertire la stringa che proviene da una richiesta HTTP in dati Python">"parsing"</abbr> con `request.form()`.
* <a href="https://pythonhosted.org/itsdangerous/" target="_blank"><code>itsdangerous</code></a> - Richiesto per usare `SessionMiddleware`.
* <a href="https://pyyaml.org/wiki/PyYAMLDocumentation" target="_blank"><code>pyyaml</code></a> - Richiesto per il supporto dello `SchemaGenerator` di Starlette (probabilmente non ti serve con FastAPI).
* <a href="https://graphene-python.org/" target="_blank"><code>graphene</code></a> - Richiesto per il supporto di `GraphQLApp`.
* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - Richiesto se vuoi usare `UJSONResponse`.

Usate da FastAPI / Starlette:

* <a href="http://www.uvicorn.org" target="_blank"><code>uvicorn</code></a> - per il server che carica e serve la tua applicazione.
* <a href="https://github.com/ijl/orjson" target="_blank"><code>orjson</code></a> - Richiesto se vuoi usare `ORJSONResponse`.

Puoi installare tutte queste con `pip install fastapi[all]`.

## Licenza

Questo progetto è concesso in licenza in base ai termini della licenza MIT.
