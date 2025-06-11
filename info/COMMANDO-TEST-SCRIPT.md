# Nederlandse Hype Jet 6.1 Commando Test Script

## Test Overzicht

Dit document bevat een systematische test procedure voor alle Nederlandse commando's in het Hype Jet 6.1 agent systeem. Gebruik dit script om te verifiëren dat alle commando's correct functioneren.

## Pre-Test Setup

### Vereisten Check
- [ ] Nederlandse Hype Jet 6.1 systeem geladen
- [ ] Nederlandse AgentConfig beschikbaar
- [ ] Alle Nederlandse agent persona bestanden toegankelijk
- [ ] Nederlandse taken, sjablonen, en data bestanden geladen
- [ ] Nederlandse checklist bestanden beschikbaar

### Initiële Systeem Status
1. Start Nederlandse Hype Jet Orchestrator
2. Verifieer Nederlandse begroeting en rol uitleg
3. Controleer Nederlandse AgentConfig loading
4. Bevestig Nederlandse resource toegankelijkheid

## Core Navigatie Commando Tests

### Test 1: `/help` Commando
**Test Stappen:**
1. Type: `/help`
2. Selecteer optie 1 (commando lijst)
3. Verifieer Nederlandse commando lijst wordt getoond
4. Controleer genummerde rijen format
5. Test optie 2 (workflow begeleiding)
6. Test optie 3 (Hype Jet methode advies)

**Verwachte Resultaten:**
- [ ] Nederlandse help menu verschijnt
- [ ] Alle drie opties functioneren correct
- [ ] Nederlandse commando's zijn volledig en accuraat
- [ ] Format is duidelijk en leesbaar

### Test 2: `/yolo` Commando
**Test Stappen:**
1. Type: `/yolo`
2. Verifieer modus toggle bericht
3. Type: `/yolo` opnieuw
4. Controleer terug toggle naar originele modus

**Verwachte Resultaten:**
- [ ] Nederlandse status bericht toont huidige modus
- [ ] Toggle werkt in beide richtingen
- [ ] Duidelijke Nederlandse modus indicatie

### Test 3: `/core-dump` Commando
**Test Stappen:**
1. Type: `/core-dump`
2. Controleer Nederlandse systeem status rapport
3. Verifieer Nederlandse agent inventaris
4. Check Nederlandse resource status
5. Valideer Nederlandse configuratie check

**Verwachte Resultaten:**
- [ ] Volledig Nederlandse systeem rapport
- [ ] Alle Nederlandse agents getoond
- [ ] Nederlandse resource status accuraat
- [ ] Nederlandse configuratie errors (indien aanwezig) getoond

## Agent Management Commando Tests

### Test 4: `/agents` Commando
**Test Stappen:**
1. Type: `/agents`
2. Verifieer Nederlandse agent tabel format
3. Controleer alle Nederlandse agents aanwezig
4. Check Nederlandse taken count voor elke agent
5. Verifieer Nederlandse checklist taken apart getoond

**Verwachte Resultaten:**
- [ ] Nederlandse tabel met alle agents
- [ ] Sequentiële nummering correct
- [ ] Nederlandse agent namen en titels accuraat
- [ ] Nederlandse taken count klopt
- [ ] Nederlandse checklist taken apart vermeld

### Test 5: Nederlandse Agent Schakel Commando's
**Test Stappen:**
1. Type: `/marcus` (Script Schrijver)
2. Verifieer Nederlandse agent activatie
3. Check Nederlandse agent introductie
4. Type: `/sophia` (Creatief Directeur)
5. Bevestig Nederlandse agent switch
6. Test ongeldige agent: `/invalid-agent`
7. Verifieer Nederlandse error handling

**Verwachte Resultaten:**
- [ ] Nederlandse agent activatie succesvol
- [ ] Nederlandse agent introductie correct
- [ ] Nederlandse agent switch bevestiging
- [ ] Nederlandse error message voor ongeldige agent
- [ ] Nederlandse suggesties voor correcties

### Test 6: `/exit` Commando
**Test Stappen:**
1. Activeer Nederlandse agent (bijv. `/marcus`)
2. Type: `/exit`
3. Verifieer terugkeer naar Nederlandse orchestrator
4. Controleer Nederlandse orchestrator begroeting

**Verwachte Resultaten:**
- [ ] Nederlandse agent sessie beëindigd
- [ ] Nederlandse orchestrator geactiveerd
- [ ] Nederlandse context gewist
- [ ] Nederlandse orchestrator begroeting getoond

### Test 7: `/taken` Commando
**Test Stappen:**
1. Activeer verschillende Nederlandse agents
2. Type: `/taken` voor elke agent
3. Verifieer Nederlandse taken lijst voor elke agent
4. Controleer Nederlandse taak beschrijvingen

**Verwachte Resultaten:**
- [ ] Nederlandse taken lijst accuraat per agent
- [ ] Nederlandse beschrijvingen volledig
- [ ] Genummerde Nederlandse lijst format
- [ ] Nederlandse taak namen correct

### Test 8: `/party` Commando
**Test Stappen:**
1. Type: `/party`
2. Verifieer Nederlandse party mode activatie
3. Test Nederlandse multi-agent interactie
4. Controleer Nederlandse agent persoonlijkheden
5. Test `/exit` vanuit party mode

**Verwachte Resultaten:**
- [ ] Nederlandse party mode geactiveerd
- [ ] Alle Nederlandse agents aanwezig
- [ ] Nederlandse agent persoonlijkheden authentiek
- [ ] Nederlandse collaboratieve interactie mogelijk
- [ ] Nederlandse exit werkt correct

## Aanvullende Commando Tests

### Test 9: `/doc-out` Commando
**Test Stappen:**
1. Creëer of bespreek Nederlands document
2. Type: `/doc-out`
3. Verifieer volledig Nederlands document output
4. Controleer geen truncatie

**Verwachte Resultaten:**
- [ ] Volledig Nederlands document getoond
- [ ] Geen content truncatie
- [ ] Nederlandse formatting behouden

### Test 10: `/load-{agent}` Commando
**Test Stappen:**
1. Type: `/load-marcus`
2. Verifieer forceerde Nederlandse agent switch
3. Test verschillende Nederlandse agents
4. Controleer Nederlandse context reset

**Verwachte Resultaten:**
- [ ] Nederlandse agent forceerd geladen
- [ ] Nederlandse context correct gereset
- [ ] Nederlandse agent begroeting getoond

### Test 11: `/hype-jet {query}` Commando
**Test Stappen:**
1. Activeer Nederlandse agent (bijv. `/marcus`)
2. Type: `/hype-jet Wat is de Nederlandse Hype Jet methode?`
3. Verifieer Nederlandse orchestrator response
4. Controleer Nederlandse agent context behouden

**Verwachte Resultaten:**
- [ ] Nederlandse orchestrator antwoordt
- [ ] Nederlandse agent context behouden
- [ ] Nederlandse query correct verwerkt

### Test 12: `/{agent} {query}` Commando
**Test Stappen:**
1. Activeer Nederlandse agent (bijv. `/marcus`)
2. Type: `/sophia Wat denk je van dit concept?`
3. Verifieer Nederlandse cross-agent consultatie
4. Controleer Nederlandse originele agent context

**Verwachte Resultaten:**
- [ ] Nederlandse cross-agent response
- [ ] Nederlandse originele context behouden
- [ ] Nederlandse query correct doorgestuurd

## Error Handling Tests

### Test 13: Nederlandse Commando Validatie
**Test Stappen:**
1. Type ongeldig commando: `/invalid-command`
2. Type verkeerd gespelde agent: `/marcuss`
3. Type incomplete commando: `/`
4. Verifieer Nederlandse error messages

**Verwachte Resultaten:**
- [ ] Nederlandse error messages duidelijk
- [ ] Nederlandse correctie suggesties gegeven
- [ ] Nederlandse help informatie aangeboden
- [ ] Nederlandse graceful error recovery

### Test 14: Nederlandse Resource Toegankelijkheid
**Test Stappen:**
1. Test Nederlandse agent activatie met ontbrekende resources
2. Verifieer Nederlandse error handling
3. Controleer Nederlandse fallback mechanismen

**Verwachte Resultaten:**
- [ ] Nederlandse resource errors gedetecteerd
- [ ] Nederlandse error messages informatief
- [ ] Nederlandse fallback opties aangeboden

## Nederlandse Checklist Tests

### Test 15: Nederlandse Checklist Taken
**Test Stappen:**
1. Activeer Nederlandse agent met checklist mogelijkheden
2. Type: `/taken`
3. Verifieer Nederlandse checklist taken apart getoond
4. Test Nederlandse checklist uitvoering

**Verwachte Resultaten:**
- [ ] Nederlandse checklist taken apart vermeld
- [ ] Nederlandse checklist namen correct
- [ ] Nederlandse checklist uitvoering functioneel

## Test Resultaten Documentatie

### Test Completion Checklist
- [ ] Alle core navigatie commando's getest
- [ ] Alle agent management commando's getest
- [ ] Alle aanvullende commando's getest
- [ ] Nederlandse error handling getest
- [ ] Nederlandse checklist functionaliteit getest
- [ ] Nederlandse party mode getest
- [ ] Nederlandse resource toegankelijkheid getest

### Nederlandse Issues Log
| Test | Nederlandse Issue | Nederlandse Severity | Nederlandse Status |
|------|-------------------|---------------------|-------------------|
| [#] | [Nederlandse beschrijving] | [Hoog/Medium/Laag] | [Open/Opgelost] |

### Nederlandse Aanbevelingen
- [Nederlandse lijst van verbeteringen]
- [Nederlandse optimalisatie suggesties]
- [Nederlandse functionaliteit uitbreidingen]

---

**Test Datum:** [Datum]
**Test Versie:** Nederlandse Hype Jet 6.1
**Tester:** [Naam]
**Nederlandse Test Status:** [Pass/Fail/Partial]
