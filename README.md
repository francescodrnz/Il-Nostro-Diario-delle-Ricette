# ***Il Nostro Diario delle Ricette***
#### Mangiare bene e sano ai tempi del COVID (e non solo)

## Indice
- [Ricettario](#ricettario)
- [Documentazione](#documentazione)
  - [Inizializzazione](#inizializzazione)
  - [Inserire una ricetta](#inserire-una-ricetta)


## Ricettario
<details>
 <summary>Antipasti e Cocktails</summary>

  - [Gnocco fritto per i non-fascisti](Antipasti%20e%20Cocktails/Gnocco%20fritto%20per%20i%20non-fascisti.pdf)
  - [La Bomba](La%20Bomba.pdf)
</details>

<details>
 <summary>Primi Piatti</summary>
 
  - ['A Carbonara](Primi%20Piatti/'A%20Carbonara.pdf)
  - [Minestrone dei poveri però buono](Primi%20Piatti/Minestrone%20dei%20poveri%20però%20buono.pdf)
  - [Pasta al cavolfiore rosso](Primi%20Piatti/Pasta%20al%20cavolfiore%20rosso.pdf)
  - [Pasta all’assassina non cancerogena](Primi%20Piatti/Pasta%20all’assassina%20non%20cancerogena.pdf)
  - [Riso alla porca troia](Primi%20Piatti/Riso%20alla%20porca%20troia.pdf)
  - [Spaghetti con pomodorini freschi ai due sapori](Primi%20Piatti/Spaghetti%20con%20pomodorini%20freschi%20ai%20due%20sapori.pdf)
</details>

<details>
 <summary>Secondi</summary>
   
   - [Frico all’Ischitana](Secondi/Frico%20all’Ischitana.pdf)
   - [Peperoni Ripieni della Speranza](Secondi/Peperoni%20Ripieni%20della%20Speranza.pdf)
   - [Pollo coi peperoni](Secondi/Pollo%20coi%20peperoni.pdf)
   - [Pollo simpatico](Secondi/Pollo%20simpatico.pdf)
   - [Scaloppine all’arancia](Secondi/Scaloppine%20all’arancia.pdf)
 
</details>

<details>
 <summary>Piatti Unici</summary>
 
   - [Fagotto Ripieno Liberté](Piatti%20Unici/Fagotto%20Ripieno%20Liberté.pdf)
   - [Hamburger Autoprodotto](Piatti%20Unici/Hamburger%20Autoprodotto.pdf)
   - [Piadina](Piatti%20Unici/Piadina.pdf)
   - [Zuppa di cipolle](Piatti%20Unici/Zuppa%20di%20cipolle.pdf)
   - [Zuppa di salsicce, fagioli e birra](Piatti%20Unici/Zuppa%20di%20salsicce,%20fagioli%20e%20birra.pdf)
  
</details>

<details>
 <summary>Contorni</summary>
 
   - [Spadellata della Bandiera Indiana](Contorni/Spadellata%20della%20Bandiera%20Indiana.pdf)
   
</details>

<details>
 <summary>Dolci</summary>
 
   - [Cookies di Chicago](Dolci/Cookies%20di%20Chicago)
   - [Crema Pasticciata](Dolci/Crema%20Pasticciata)
   - [Pasticciotti Leccesi](Dolci/Pasticciotti%20Leccesi)
   - [Plumcake allo yogurt](Dolci/Plumcake%20allo%20yogurt)
   - [Torta al cioccolato di Akira](Dolci/Torta%20al%20cioccolato%20di%20Akira)
   - [Torta di carote](Dolci/Torta%20di%20carote)
   - [Tortino al cioccolato con cuore morbido](Dolci/Tortino%20al%20cioccolato%20con%20cuore%20morbido)
   
</details>
 

## Documentazione
### Inizializzazione
1. [Installa Git sul tuo pc](https://git-scm.com/downloads). Impostazioni consigliate:
    - | ![](https://i.imgur.com/2hk611Q.png) | 
      |:--:| 
      | *deseleziona “Git GUI Here”* |
    - | ![](https://i.imgur.com/7rOS7ax.png) | 
      |:--:| 
      | *se installato (consigliato), scegli Notepad++;*
        *in alternativa, scegli Notepad (preinstallato su Windows)* |
    - lascia le altre impostazioni di default
2. Apri il prompt dei comandi (start -> cerca cmd)
3. Decidi una cartella su cui salvare la repository, ad es. Documenti, ed esegui il seguente comando:

	  **cd C:\Users\\_nome-utente_\Documenti**
4. **git clone https://github.com/francescodrnz/Il-Nostro-Diario-delle-Ricette.git**

I file ora sono disponibili nella cartella selezionata, ad esempio C:\Users\\*nome-utente*\Documents\Il-Nostro-Diario-delle-Ricette, ed è possibile fare modifiche.



### Inserire una ricetta

0. _Solo la prima volta: [Crea un account su GitHub](https://github.com/signup), installa il font disponibile nella cartella utils: [Comfortaa.ttf](utils/Comfortaa.ttf)_
1.  | ![](https://i.imgur.com/9jg2qpe.png) | 
    |:--:| 
    | *Da esplora risorse, tasto destro nella cartella principale -> Git Bash Here* |
2. Esegui il comando **git pull** per sincronizzare eventuali modifiche
3. Apri il file *Template Ricette.docx* disponibile nella cartella *utils*
4. Scrivi la ricetta seguendo il template
5. File -> Salva con nome -> Sfoglia -> selezionare la cartella corretta in base al tipo di ricetta -> Salva come: scegliere PDF -> Salva
6. Esegui i seguenti comandi:
    - **git add .**
    - **git commit -m “Inserisci un messaggio che descriva le modifiche”**
    - **git push**
  
        *Solo la prima volta: chiedi a @giazaki di essere aggiunto come collaboratore*
    
        _Solo la prima volta: si aprirà una finestra per effettuare il login su GitHub, segui le istruzioni; successivamente, esegui il seguente comando (per salvare le credenziali, in modo da non fare più il login):
**git config credential.helper store**_
