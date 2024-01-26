---
sidebar_position: 2
---

# Traccia 

### Obiettivo del Progetto

L'obiettivo di questo progetto è la creazione di un'applicazione web che permetta agli utenti di generare una bio professionale in stile LinkedIn. L'utente inserirà le proprie informazioni professionali e personali attraverso un form, e l'applicazione genererà dinamicamente una pagina che presenta queste informazioni in un formato pulito e professionale.

## Requisiti Specifici:

  -   Scrivere uno script JavaScript che prenda le informazioni inserite dall'utente e le visualizzi in una sezione separata della pagina sotto forma di bio.
  -   Implementare la validazione del form per assicurarsi che tutti i campi siano compilati prima di permettere all'utente di generare la bio.


### Struttura dei File
Il progetto dovrà essere organizzato in tre file principali:

-   `index.html`: Contiene la struttura della pagina e il form di input.
-   `style.css`: Contiene le regole di stilizzazione per la pagina.
-   `script.js`: Contiene la logica per raccogliere i dati del form e generare la bio.

## Guida alla Realizzazione del Progetto

### Strutturare il Form HTML 

-   In `index.html`, creare un form con campi di input per tutte le informazioni richieste.
-   Assicurarsi che ogni campo di input abbia un `id` unico per facilitare la raccolta dei dati con JavaScript.

Crea un file HTML contenente questo codice:
  
```html
  <html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Progetto Finale SheTech</title>
        <link rel="stylesheet" href="style.css">
    </head>

    <body>
        <div class="container">
            <h1>Professional Bio Maker 📝</h1>
            <form id="#">
                <input type="text" id="name" placeholder="Nome e Cognome" required>
                <input type="text" id="role" placeholder="Ruolo" required>
                <textarea id="#" placeholder="Competenze Tecniche" required></textarea>
                <textarea id="#" placeholder="Competenze Trasversali" required></textarea>
                <textarea id="#" placeholder="Breve Biografia" required></textarea>
                <textarea id="#" placeholder="Esperienze Lavorative" required></textarea>
                <textarea id="#" placeholder="Formazione" required></textarea>
                <input type="text" id="#" placeholder="Contatti" required>
                <button type="submit">Generate Bio</button>
            </form>
            <div id="#"></div>
        </div>
        <script src="script.js"></script>
    </body>
  </html>
```

### Stilizzare la Pagina e il Form 

-   In `style.css`, definire le regole CSS per rendere l'interfaccia utente pulita, moderna e responsive.
-   Utilizzare margini, padding, bordi e colori per migliorare l'usabilità e l'estetica del form e della bio risultante.
-   Personalizzare il font e i colori per rendere la pagina più accattivante.

In `style.css`, crea un file CSS contenente questo codice:

```css
body, html {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

.container {
    max-width: 600px;
    margin: 20px auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

h1 {
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
}

input[type="text"], textarea {
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

button {
    padding: 10px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

#bioOutput {
    margin-top: 20px;
    padding: 20px;
    background-color: #f0f0f0;
    border: 1px solid #ddd;
    border-radius: 5px;
}
```

### Implementare la Logica con JavaScript 

-   In `script.js`, aggiungere un event listener al form per intercettare il submit e prevenire il comportamento di default del browser.
-   Raccogliere i valori inseriti dall'utente, validarli, e poi generare dinamicamente la bio utilizzando questi dati.
-   Inserire la bio generata in una sezione dedicata della pagina.


### Testare il Progetto 

-   Verificare che il form raccolga correttamente i dati inseriti dall'utente.
-   Controllare che la bio venga generata correttamente e visualizzata nella pagina.

**Congratulazioni! 🎉**

E' arrivato il momento di presentare il progetto al resto del gruppo! 
