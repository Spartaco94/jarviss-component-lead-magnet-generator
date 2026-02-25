```markdown
# Lead Magnet Generator - Jarviss AI Component

## Descrizione
Componente modulare per generazione automatica di PDF lead magnet per nicchie specifiche.

## Utilizzo

```javascript
import LeadMagnetGenerator from './lead_magnet_generator.js';

const config = {
    title: "10 Strategie Marketing Ristoranti",
    targetNiche: "ristorazione",
    sections: [
        {
            heading: "Introduzione",
            content: "...",
            key_takeaway: "..."
        }
    ],
    cta: "Scarica la guida completa",
    hook: "Scopri le strategie per aumentare i ricavi"
};

const generator = new LeadMagnetGenerator(config);
const pdfResult = generator.generatePDF();
```

## Metodi
- `generatePDF()`: Genera PDF basato sulla configurazione
- `validate(config)`: Convalida la configurazione del lead magnet

## Requisiti
- Node.js
- PDF Generation Library
```