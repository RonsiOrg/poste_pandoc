## 3. Overview Architetturale
 
### 3.1 Information System Architecture
Stato: <mark>[Bozza]</mark>
 
> Vista ad alto livello dei sistemi coinvolti e delle loro interazioni
 
- Sistemi front-end
- Sistemi backend
- Sistemi esterni
 
./ISA_Diagramma.PNG
 
| Flusso Dati | Descrizione | Tipo |
|------------|------------|------|
| Flusso 1 | Frontend → Backend | Nuovo |
| Flusso 2 | Backend → Sistema Esterno | Modificato |
 
---
 
### 3.2 Scenari di Integrazione (High Level)
Stato: <mark>[Bozza]</mark>
 
#### Scenario 1 – Processo principale
 
> Descrizione funzionale dello scenario:
 
- Attori coinvolti
- Sistemi coinvolti
- Obiettivo del flusso
 
> Flusso ad alto livello:
 
1. Utente interagisce con sistema
2. Sistema orchestration
3. Interazione con sistemi esterni
 
---
 
#### Scenario 2 – Caso alternativo
 
> Come sopra (senza dettaglio tecnico)
 
---
 
### 3.3 Modello Dati (opzionale)
Stato: <mark>[Bozza]</mark>
 
> Vista concettuale delle entità principali
 
- Customer
- Order
- Transaction
 
## 4. Architectural View
 
### 4.1 Application Technical Architecture
Stato: <mark>[Bozza]</mark>
 
> Vista high-level dello stack tecnologico
 
| Sistema | Tecnologia | Tipologia | Note |
|--------|-----------|----------|------|
| Frontend | Web App | Presentazione | Nuovo |
| Backend | Microservizi | Business | Nuovo |
| DB | RDBMS | Data | Esistente |
 
---
 
### 4.2 Infrastruttura
Stato: <mark>[Bozza]</mark>
 
> Vista infrastrutturale ad alto livello
 
- Cloud / On-prem
- Network
- Layer di sicurezza
- Storage
 
---
 
### 4.3 Architecture Decision Records (facoltativo)
Stato: <mark>[Bozza]</mark>
 
- Decisione tecnologia backend
- Pattern architetturale
