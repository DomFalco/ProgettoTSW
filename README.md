# ProgettoTSW - E-commerce Pharmatex

[![GitHub repo](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/DomFalco/ProgettoTSW)
[![Java](https://img.shields.io/badge/Java-8-orange)](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
[![Maven](https://img.shields.io/badge/Maven-3.8+-green)](https://maven.apache.org/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)](https://www.mysql.com/)
[![Tomcat](https://img.shields.io/badge/Tomcat-10.0-yellow)](https://tomcat.apache.org/)

## 📋 Descrizione
ProgettoTSW è un'applicazione e-commerce sviluppata per l'esame di **Tecnologia Software per il Web** del secondo anno del Corso di Laurea in Informatica - Classe 3 Resto 2 presso l'**Università degli Studi di Salerno**.

Il sito simula la commercializzazione online delle componenti dell'angolo notte, offrendo ai visitatori la possibilità di navigare il catalogo, aggiungere prodotti al carrello e completare l'acquisto. È inoltre presente un'area amministratore con funzionalità di riepilogo e gestione.

## ✨ Caratteristiche principali
- **Catalogo prodotti**: visualizzazione dei prodotti con filtri e ricerca
- **Carrello**: aggiunta, modifica e rimozione di articoli
- **Checkout**: procedura di acquisto simulata
- **Area utente**: registrazione e login
- **Area amministratore**: riepilogo ordini, gestione prodotti e utenti
- **Database MySQL**: persistenza dei dati (prodotti, utenti, ordini)

## 🛠️ Tecnologie utilizzate
| Tecnologia | Versione |
|------------|----------|
| Java | 8 |
| Servlet API | 5.0 |
| JSP / JSTL | 2.0 |
| MySQL Connector | 8.0.18 |
| Tomcat JDBC | 10.0.17 |
| JUnit | 5 |
| Maven | 3.8+ |
| Tomcat | 10.0 |

## 📦 Prerequisiti
- **JDK 8** o superiore
- **Apache Maven** 3.8+
- **MySQL** 8.0+
- **Apache Tomcat** 10.0 (o 9.0 con Jakarta EE 9+)

## 🚀 Installazione

### 1. Clonare il repository
Aprire il terminale ed eseguire i seguenti comandi:
`git clone https://github.com/DomFalco/ProgettoTSW.git`
`cd ProgettoTSW`

### 2. Configurare il database
Importare il file `Pharmatex.sql` nel proprio server MySQL:
`mysql -u root -p < Pharmatex.sql`
Modificare le credenziali del database nel file di configurazione (es. `src/main/resources/db.properties` o `context.xml`).

### 3. Compilare il progetto
Eseguire il comando Maven:
`mvn clean package`

### 4. Deploy su Tomcat
Copiare il file `target/Progetto.war` nella directory `webapps` di Tomcat.
Avviare Tomcat e accedere all'applicazione all'indirizzo:
`http://localhost:8080/Progetto`

## 📁 Struttura del progetto
ProgettoTSW/
├── src/
│   └── main/
│       ├── java/
│       │   ├── Controller/   # Servlet e logica di controllo
│       │   └── Model/        # Classi model e accesso ai dati
│       ├── webapp/
│       │   ├── ParteCSS/     # Fogli di stile
│       │   ├── ParteHTML/    # Pagine JSP e HTML
│       │   ├── WEB-INF/      # File di configurazione
│       │   └── immagini/     # Risorse grafiche
├── pom.xml                   # Configurazione Maven
├── Pharmatex.sql             # Script di creazione database
└── Documentazione Sito.pdf   # Documentazione del progetto


## 📄 Documentazione
La documentazione completa, l'artefatto software e un video dimostrativo sono disponibili al seguente link:
📥 [Scarica da Mega](https://mega.nz/file/JuIWiTgD#1EgLvhyrvOPhCbgeXhNqee0kiWVkw4OzoHqLtK0P2M0)

## 👥 Autori
- **Francesco Alfonso Barlotti** - Matricola: 0512110169
- **Domenico Falco** - Matricola: 0512112500
- **Giuseppe Napolitano** - Matricola: 0512111999

## 📝 Licenza
Progetto realizzato a scopo accademico per l'Università degli Studi di Salerno. Nessuna licenza specifica applicata.
