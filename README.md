# Apunts_UF1_1

# Introduccío

## Tipus de software

 - De sistema (Sistema operatiu, drivers)
 - De aplicació (Suite ofimàtica, Navegador, Edició d' imatge)
 - De desenvolupament (Editors, compliadors, interprates)
 
 ## Relació Hardware-Software
 
 - Disc dur: Emmagatzema de forma parmanent els arxius executables i els arxius de dades
 - Memoria RAM: Emmagatzema de forma temporal arxius executables i els arxius de dades necessaries
 - CPU: Llegeix i executa instruccions emagatzemades en la memoria RAM
 - E/S: Entrada i sortida (Llegeix informació i li dona sortida el ordinador)

## Codi font, objecte y executable

- Codi font: Arxiu de text legible escrit en un llenguatge de programació
- Codi objecte: Arxiu binari no executable
- Codi executable: Arxiu binari executable

# Cicle de vida del Software

## Desenvolupament del Software

- Anàlisis
- Diseny
- Codificació
- Proves
- Mantaniment

## Anàlisis

- És determina i és definex les necessitats del client i especifica els requisits que deu complir el software

## Diseny

- És determina els components que poden ser desenvolupats per seperat

## Codificació

- S'ecriu el codi font de cada component

## Proves

- L'objectiu és aconseguir que el programa funcioni incorrectament i es descobreixin fallos

## Mantaniment

- És necessari realitzar canvis ocasionals
  - Correctiu: És corregeixen defectes
  - Perfectiu: És millora la funcionalitat
  - Evolotiu: S'afageix funcions noves
  - Adaptiu: S'adapta a nous entorns

# Models de desenvolupament de Software

- Models clasics
  - Model en cascada
  - Model en V
- Model de construcció de prototius
- Model evolutius o incrementals
  - Model en espiral
  - Metodologíes àgils
  
## Model en cascada

- Model de major antiguitat
- Les fases s'han de realitzar en l'ordre indicat
- El resultat de una fase es la entrada de la següent
- És un model rígit que no se adapta el canvi continuo

## Model en V

- Model jerarquic amb diferents nivells
- Els nivells superiors indican major abstracció i els inferiors indican major nivell de detall

## Prototips

- Moltes vegades els regquisits no están especificats:
 - Per no existir experencia previa
 - Per omisió o falta de concretació del usurai/client
- Es crea un prototip duran la fase de anàlisis i es prova per l' usuari/client
-Tipus de prototips
 - Prototips ràpids
  -El prototip pot estar desenvolupat utilitzant un altre llenguatje o eina
  - Finalment el protips es tira
 -Prototips evolotius
  - Esta disenyat en el mateix llenguatje i enga que del projecte
  - El prototis s'utilitza com a base
## Model en espiral

- En el model en espiral sempre s'ha de tenir la confirmació del client per poder avançar

## Metodologies agils

- Metodes de ingenieria del software basats en el desenvolupament iteratiu e incremental
- Els requisits i solucions evolocionen amb la necessitat del projecte
- El treball es realitza amb la colaboració d' equips auto-organitzats i multidisciplinaris
- Les metodologies mes conegudes són:
 - Kanban
 - Scrum
 -XP (eXtreme Programming)
 
# Llenguatge de programació

## Codi executable

- Compila o interpreta
 - Compila/interpreta del codi font es fa:
  - Anàlisis léxic
  - Anàlisis sintactic
 - Un codi font correctament escrit no significa que funcioni segons lo desitjat
 - No es realitza un alàlisis semantic
 
## Llenguatjes compilats

- Exemples
 - C
 - C++
- Ventatja:
 - Execució molt eficient
- Desventatja:
 - Es necesari compilar cada vegada que el codi font es modifiqui
 
## Llenguatje interpretat

- Exemples
 -PHP
 -Javascripts
- Ventatja
 - El codi font s'interpreta directament
- Desventatja
 - Execució menys eficient
