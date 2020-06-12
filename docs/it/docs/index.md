<p align="center">
  <a href="https://fastapi.tiangolo.com"><img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" alt="FastAPI"></a>
</p>
<p align="center">
    <em>FastAPI framework, alte prestazioni, facile da imparare, veloce da programmare, pronto per il rilascio in produzione</em>
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
* **Veloce da programmare**: Rilascia nuove funzionalità tra il 200% e il 300% più velocemente. *
* **Meno bug**: Riduce di circa il 40% gli errori commessi dagli sviluppatori. *
* **Intuitivo**: Ottimo supporto per gli editor di testo con <abbr title="anche noto come IntelliSense">autocompletamento</abbr> dovunque. Spreca meno tempo a trovare errori.
* **Facile**: Progettato per essere facile da usare e imparare. Spreca meno tempo a consultare la documentazione.
* **Breve**: Minimizza la duplicazione di codice. Funzionalità multiple con ciascuna dichiarazione di parametri. Meno bug.
* **Robusto**: Scrivi codice pronto per essere rilasciato in produzione con documentazione automatica e interattiva.
* **Basato sugli standard**: Basato su (e pienamente compatibile con) gli open standard per le API: <a href="https://github.com/OAI/OpenAPI-Specification" class="external-link" target="_blank">OpenAPI</a> (prima conosciuto come Swagger) e <a href="http://json-schema.org/" class="external-link" target="_blank">JSON Schema</a>.

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

FastAPI si appoggia su queste librerie:

* <a href="https://www.starlette.io/" class="external-link" target="_blank">Starlette</a> per la parte web.
* <a href="https://pydantic-docs.helpmanual.io/" class="external-link" target="_blank">Pydantic</a> per la parte dei dati.

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

Se non lo sai, consulta la sezione _"In a hurry?"_ su <a href="https://fastapi.tiangolo.com/async/#in-a-hurry" target="_blank">`async` e `await` nella documentazione</a>.

</details>

### Fai partire il server

Puoi inizializzare il server così:

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

Il comando `uvicorn main:app` si riferisce a:

* `main`: il `main.py` (il "modulo" Python).
* `app`: l'oggetto creato dentro a `main.py` con la riga di codice `app = FastAPI()`.
* `--reload`: ricarica il server se ci sono cambiamenti del codice. Usalo solo nell'ambiente di sviluppo.

</details>

### Controllalo

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

Vedrai la documentazione interattiva dell'API (fornita da <a href="https://github.com/swagger-api/swagger-ui" class="external-link" target="_blank">Swagger UI</a>):

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-01-swagger-ui-simple.png)

### Alternative API docs

Adesso accedi su <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

Vedrai la documentazione interattiva dell'API (fornita da <a href="https://github.com/Rebilly/ReDoc" class="external-link" target="_blank">ReDoc</a>):

![ReDoc](https://fastapi.tiangolo.com/img/index/index-02-redoc-simple.png)

## Esempio più avanzato

Adesso modifica il file `main.py` per ricevere un _body_ da una richiesta `PUT`.

Dichiara il _body_ usando le annotazioni dei tipi standard di Python, grazie a Pydantic.

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

Il server dovrebbe ricaricarsi in automatico (perché hai aggiunto `--reload` al comando `uvicorn` qui sopra).

### Aggiornamento della documentazione API interattiva

Adesso vai su <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

* La documentazione interattiva dell'API verrà automaticamente aggiornata, includendo il nuovo _body_:

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-03-swagger-02.png)

* Fai click sul pulsante "Try it out", che ti permette di inserire i parametri per interagire direttamente con l'API:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-04-swagger-03.png)

* Successivamente fai click sul pulsante "Execute". L'interfaccia utente comunicherà con la tua API, invierà i parametri, riceverà i risultati della richiesta e li mostrerà sullo schermo:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-05-swagger-04.png)

### Aggiornamento della documentazione dell'API interattiva alternativa

Ora vai su <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

* Anche la documentazione alternativa dell'API mostrerà il nuovo parametro della query e il _body_:

![ReDoc](https://fastapi.tiangolo.com/img/index/index-06-redoc-02.png)

### Ricapitolando

Ricapitolando, è sufficiente dichiarare **solo una volta** i tipi dei parametri, del body, etc. come parametri di funzioni. 

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

* Supporto per gli editor di testo, inclusi:
    * Autocompletamento.
    * Controllo sulle annotazioni di tipo.
* Validazione dei dati:
    * Errori chiari e automatici quando i dati sono invalidi.
    * Validazione anche per gli oggetti JSON altamente nidificati.
* <abbr title="anche noto come: serializzazione, parsing, marshalling">Conversione</abbr> dei dati di input: da risorse esterne a dati e tipi di Python. Leggendo da:
    * JSON.
    * Path parameters.
    * Query parameters.
    * Cookies.
    * Headers.
    * Form.
    * File.
* <abbr title="also known as: serialization, parsing, marshalling">Conversion</abbr> of output data: converting from Python data and types to network data (as JSON):
    * Convert Python types (`str`, `int`, `float`, `bool`, `list`, etc).
    * `datetime` objects.
    * `UUID` objects.
    * Database models.
    * ...and many more.
* Automatic interactive API documentation, including 2 alternative user interfaces:
    * Swagger UI.
    * ReDoc.

---

Coming back to the previous code example, **FastAPI** will:

* Validate that there is an `item_id` in the path for `GET` and `PUT` requests.
* Validate that the `item_id` is of type `int` for `GET` and `PUT` requests.
    * If it is not, the client will see a useful, clear error.
* Check if there is an optional query parameter named `q` (as in `http://127.0.0.1:8000/items/foo?q=somequery`) for `GET` requests.
    * As the `q` parameter is declared with `= None`, it is optional.
    * Without the `None` it would be required (as is the body in the case with `PUT`).
* For `PUT` requests to `/items/{item_id}`, Read the body as JSON:
    * Check that it has a required attribute `name` that should be a `str`. 
    * Check that it has a required attribute `price` that has to be a `float`.
    * Check that it has an optional attribute `is_offer`, that should be a `bool`, if present.
    * All this would also work for deeply nested JSON objects.
* Convert from and to JSON automatically.
* Document everything with OpenAPI, that can be used by:
    * Interactive documentation systems.
    * Automatic client code generation systems, for many languages.
* Provide 2 interactive documentation web interfaces directly.

---

We just scratched the surface, but you already get the idea of how it all works.

Try changing the line with:

```Python
    return {"item_name": item.name, "item_id": item_id}
```

...from:

```Python
        ... "item_name": item.name ...
```

...to:

```Python
        ... "item_price": item.price ...
```

...and see how your editor will auto-complete the attributes and know their types:

![editor support](https://fastapi.tiangolo.com/img/vscode-completion.png)

For a more complete example including more features, see the <a href="https://fastapi.tiangolo.com/tutorial/">Tutorial - User Guide</a>.

**Spoiler alert**: the tutorial - user guide includes:

* Declaration of **parameters** from other different places as: **headers**, **cookies**, **form fields** and **files**.
* How to set **validation constraints** as `maximum_length` or `regex`.
* A very powerful and easy to use **<abbr title="also known as components, resources, providers, services, injectables">Dependency Injection</abbr>** system.
* Security and authentication, including support for **OAuth2** with **JWT tokens** and **HTTP Basic** auth.
* More advanced (but equally easy) techniques for declaring **deeply nested JSON models** (thanks to Pydantic).
* Many extra features (thanks to Starlette) as:
    * **WebSockets**
    * **GraphQL**
    * extremely easy tests based on `requests` and `pytest`
    * **CORS**
    * **Cookie Sessions**
    * ...and more.

## Performance

Independent TechEmpower benchmarks show **FastAPI** applications running under Uvicorn as <a href="https://www.techempower.com/benchmarks/#section=test&runid=7464e520-0dc2-473d-bd34-dbdfd7e85911&hw=ph&test=query&l=zijzen-7" class="external-link" target="_blank">one of the fastest Python frameworks available</a>, only below Starlette and Uvicorn themselves (used internally by FastAPI). (*)

To understand more about it, see the section <a href="https://fastapi.tiangolo.com/benchmarks/" class="internal-link" target="_blank">Benchmarks</a>.

## Optional Dependencies

Used by Pydantic:

* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - for faster JSON <abbr title="converting the string that comes from an HTTP request into Python data">"parsing"</abbr>.
* <a href="https://github.com/JoshData/python-email-validator" target="_blank"><code>email_validator</code></a> - for email validation.

Used by Starlette:

* <a href="http://docs.python-requests.org" target="_blank"><code>requests</code></a> - Required if you want to use the `TestClient`.
* <a href="https://github.com/Tinche/aiofiles" target="_blank"><code>aiofiles</code></a> - Required if you want to use `FileResponse` or `StaticFiles`.
* <a href="http://jinja.pocoo.org" target="_blank"><code>jinja2</code></a> - Required if you want to use the default template configuration.
* <a href="https://andrew-d.github.io/python-multipart/" target="_blank"><code>python-multipart</code></a> - Required if you want to support form <abbr title="converting the string that comes from an HTTP request into Python data">"parsing"</abbr>, with `request.form()`.
* <a href="https://pythonhosted.org/itsdangerous/" target="_blank"><code>itsdangerous</code></a> - Required for `SessionMiddleware` support.
* <a href="https://pyyaml.org/wiki/PyYAMLDocumentation" target="_blank"><code>pyyaml</code></a> - Required for Starlette's `SchemaGenerator` support (you probably don't need it with FastAPI).
* <a href="https://graphene-python.org/" target="_blank"><code>graphene</code></a> - Required for `GraphQLApp` support.
* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - Required if you want to use `UJSONResponse`.

Used by FastAPI / Starlette:

* <a href="http://www.uvicorn.org" target="_blank"><code>uvicorn</code></a> - for the server that loads and serves your application.
* <a href="https://github.com/ijl/orjson" target="_blank"><code>orjson</code></a> - Required if you want to use `ORJSONResponse`.

You can install all of these with `pip install fastapi[all]`.

## Licenza

Questo progetto è concesso in licenza in base ai termini della licenza MIT.
