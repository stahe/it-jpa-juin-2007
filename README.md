# JPA – Introduzione e implementazione

🔗 **Corso correlato:**
[https://stahe.github.io/it-jpa-juin-2007/](https://stahe.github.io/it-jpa-juin-2007/)

---

## Panoramica

Questo documento fornisce un'introduzione ai concetti fondamentali della **persistenza dei dati utilizzando la JPA (Java Persistence API)**.

Dopo aver studiato e sperimentato con gli esempi forniti, il lettore avrà le basi necessarie per utilizzare la JPA in modo autonomo.

La JPA è stata introdotta con **Java 5 (JDK 1.5)** e fa parte di un'architettura software a più livelli.

---

## Architettura multilivello

Questo documento si basa su una classica architettura a tre livelli:

* **[ui]** — Interfaccia utente (Swing, console, web)
* **[business]** — Logica di business
* **[DAO]** — Accesso ai dati persistenti
* **[JDBC]** — Accesso al database a basso livello

L'obiettivo di JPA è standardizzare e semplificare il livello **DAO**.

---

## ORM e standardizzazione

Prima di JPA, soluzioni come **Hibernate** o **Toplink** offrivano meccanismi ORM (Object Relational Mapping).

JPA introduce una **specifica standard**:

* Il livello DAO comunica con un'**interfaccia JPA**
* L'implementazione può essere Hibernate, Toplink, ecc.
* La logica di business rimane indipendente dal provider ORM

---

## Argomenti trattati

Questo documento tratta i seguenti argomenti:

### 1️⃣ Mappatura relazionale/oggetti

Configurazione tramite annotazioni Java 5 per gestire:

* Relazioni **uno-a-uno**
* Relazioni **uno-a-molti**
* Relazioni **molti-a-molti**

---

### 2️⃣ Ambiente Java SE

* Applicazioni console di test
* Manipolazione diretta dell'API JPA
* Introduzione ai metodi chiave (CRUD)
---
### 3️⃣ Architettura multilivello avanzata
Integrazione di:
* **Spring**
* **JBoss EJB3**
Utilizzo di:

* Pool di connessioni
* Gestori di transazioni
* Iniezione di dipendenze
* POJO annotati

---

### 4️⃣ Esempio di applicazione web

Il documento si conclude con un'applicazione web a tre livelli che integra:

* Web
* Logica di business
* DAO
* JPA
* Implementazione ORM
* Spring Framework

---

## Obiettivi di apprendimento

Questo materiale mira a:

* Comprendere il ruolo di JPA in un'architettura aziendale
* Padroneggiare la mappatura relazionale/oggetti
* Utilizzare JPA in ambienti SE ed EE
* Confrontare Spring ed EJB3 per la gestione dei servizi tecnici

---

## Destinatari

Sviluppatori Java che desiderano:

* Comprendere le basi della persistenza con JPA
* Strutturare correttamente un'architettura multilivello
* Prepararsi ad approfondire le proprie competenze in Java EE

---

## Autore

**Serge Tahé** – Giugno 2007

---
