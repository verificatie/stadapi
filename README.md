# Stad API

Welkom bij de **Stad API**! Deze API is ontwikkeld door de Nederlandse Verificatie App in samenwerking met de OS Autoriteit. Met de Stad API kun je eenvoudig toegang krijgen tot waardevolle informatie over steden en dorpen in Nederland.

## Wat is Stad API?

De Stad API biedt ontwikkelaars de mogelijkheid om gegevens op te vragen over verschillende steden en dorpen, zoals het aantal stoplichten, gebouwen en andere relevante informatie.

## Functionaliteiten

Met de Stad API kun je de volgende gegevens opvragen:

- **Aantal stoplichten** in een specifieke stad of dorp.
- **Aantal gebouwen** en hun kenmerken.
- **Algemene informatie** over de stad of het dorp.
- **Statistieken** en andere nuttige data met betrekking tot de regio.

## API Endpoints

Hieronder vind je een overzicht van de beschikbare endpoints:

| Endpoint                             | Beschrijving                            |
|--------------------------------------|----------------------------------------|
| `/api/steden`                        | Lijst van alle steden en dorpen        |
| `/api/stad/{naam}`                  | Gegevens van een specifieke stad of dorp |
| `/api/stad/{naam}/stoplichten`      | Aantal stoplichten in de stad of dorp  |
| `/api/stad/{naam}/gebouwen`         | Informatie over gebouwen in de stad of dorp |

## Voorbeeldgebruik

### 1. Lijst van steden en dorpen

```http
GET /api/steden
