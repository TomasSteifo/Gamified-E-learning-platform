# Gamifierad e-lärandeplattform
En OOP-baserad applikation med fokus på quiz, badges och andra spelifierade moment för att öka motivation och engagemang i digitalt lärande.

---

## Projektidé och Kontext
Denna plattform ska låta studenter eller anställda genomföra kurser och övningar online, där olika moment är “spelifierade” för att öka motivation. Användare kan samla poäng, få badges och jämföra resultat i leaderboards. Läraren/administratören kan följa deltagarnas framsteg i realtid.

### Bakgrund och Syfte
- **Bakgrund**: E-lärande blir alltmer populärt men saknar ofta mekanismer för kontinuerlig motivation.  
- **Syfte**: Att erbjuda en innovativ inlärningsmiljö där användare motiveras genom poäng, badges och tävlingar, samtidigt som lärare kan följa upp och utvärdera progression.

### Vision och Mål
- **Vision**: “Skapa en lustfylld digital inlärningsupplevelse som ökar både kunskapsnivå och engagemang genom spelifiering.”  
- **Huvudmål**:  
  1. Interaktiv plattform med videolektioner, quiz och uppdrag.  
  2. Spelifiering genom poäng, badges och nivåer.  
  3. Tydlig rapportering för lärare att följa studenternas framsteg.  
  4. Mätbar framgång via antalet slutförda kurser, inloggningsfrekvens och användarfeedback.

---

## Key Features (Översikt av Funktioner)
- **Registrering och Inloggning**: Användare kan skapa konton eller logga in via OAuth (t.ex. Google).  
- **Kursnavigering**: Översikt av tillgängliga kurser, möjlighet att starta och genomföra.  
- **Quiz och Uppdrag**: Direkt feedback på svar för att stödja inlärning.  
- **Poäng- och Badgesystem**: Användare tjänar poäng och får badges vid uppnådda milstolpar.  
- **Leaderboards**: Rankning av toppstudenter baserat på poäng.  
- **Kursrapport (valfritt)**: Export av resultat för lärare.  
- **Notifikationssystem (valfritt)**: E-post/pushnotiser för nya uppgifter eller deadlines.

---

## Kravspecifikation (Sammanfattning)

### Funktionella Krav
- **Must**: Registrering/inloggning, kursnavigering, quiz.  
- **Should**: Poäng/badges, leaderboard.  
- **Could**: CSV-export, notifikationer.

### Icke-funktionella Krav
- **Prestanda**: Klarar minst 100 samtidiga användare.  
- **Säkerhet**: Krypterad inloggning (HTTPS), lösenordshantering.  
- **Användbarhet**: Responsivt gränssnitt.  
- **Underhållbarhet**: Modulär kod.  
- **Skalbarhet**: Möjligt att integrera nya moduler eller API:er.

---

## User Stories
1. Som **student** vill jag kunna registrera mig och logga in, så att jag får tillgång till mina kurser.  
2. Som **student** vill jag kunna göra quiz och få direkt feedback, så att jag vet vad jag behöver förbättra.  
3. Som **lärare** vill jag kunna lägga till nytt kursmaterial, så att jag kan uppdatera och förbättra kursen löpande.  
4. Som **student** vill jag ha ett poängsystem, så att jag motiveras att slutföra fler uppgifter.  
5. Som **lärare** vill jag kunna se studenternas framsteg i en dashboard, så att jag kan följa deras utveckling.

---

## Use Cases (Exempel)

### 1. Genomföra Quiz
- **Aktör**: Student  
- **Previllkor**: Studenten är inloggad och har valt en kurs med quiz.  
- **Huvudflöde**:
  1. Studenten besvarar frågorna i quizet.  
  2. Systemet ger direkt feedback och uppdaterar poäng.  
- **Postvillkor**: Studenten ser sin nya poängsumma och quizet markeras som slutfört.

### 2. Administrera Kurs
- **Aktör**: Lärare/Admin  
- **Previllkor**: Läraren är inloggad med admin-rättigheter.  
- **Huvudflöde**:
  1. Läraren skapar eller redigerar kurskapitel via administrationsgränssnitt.  
  2. Läraren laddar upp material (video, text, bilder) och kopplar quiz.  
  3. Systemet sparar ändringarna och uppdaterar kursen.  
- **Postvillkor**: Nya eller ändrade kapitel är direkt tillgängliga för studenterna.

---


