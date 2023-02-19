# ***Il Nostro Diario delle Ricette***
#### Mangiare bene e sano ai tempi del COVID (e non solo)

## Table of Contents
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

## Documentazione
### Inizializzazione
1. [Crea un account su GitHub](https://github.com/signup)
2. [Installa Git sul tuo pc](https://git-scm.com/downloads). Impostazioni consigliate:
    - | ![](https://i.imgur.com/2hk611Q.png) | 
      |:--:| 
      | *deseleziona “Git GUI Here”* |
    - | ![](https://i.imgur.com/7rOS7ax.png) | 
      |:--:| 
      | *se installato (consigliato), scegliere Notepad++;*
        *in alternativa, scegliere Notepad (preinstallato su Windows)* |
    - lasciare le altre impostazioni di default
  3.	Aprire il prompt dei comandi: start -> cercare cmd
4.	Scegliere una cartella su cui si salverà la repository, ad es. Documenti, ed eseguire il seguente comando:

	  **cd C:\Users\\_nome-utente_\Documenti**
5.	**git clone https://github.com/francescodrnz/Il-Nostro-Diario-delle-Ricette.git**

I file ora sono disponibili nella cartella selezionata, ad esempio C:\Users\\*nome-utente*\Documents\Il-Nostro-Diario-delle-Ricette, ed è possibile fare modifiche.

### Inserire una ricetta
*Solo la prima volta: installare il font disponibile nella cartella utils: Comfortaa.ttf*
1.	| ![](https://i.imgur.com/9jg2qpe.png) | 
    |:--:| 
    | *Da esplora risorse, tasto destro nella cartella principale -> Git Bash Here* |
2.	Eseguire il comando **git pull** per sincronizzare eventuali modifiche
3.	Aprire il file *Template Ricette.docx* disponibile nella cartella *utils*
4.	Scrivere la ricetta seguendo il template
5.	File -> Salva con nome -> Sfoglia -> selezionare la cartella corretta in base al tipo di ricetta -> Salva come: scegliere PDF -> Salva
6.	Eseguire i seguenti comandi:
    - **git add .**
    -	**git commit -m “Inserire un messaggio che descriva le modifiche”**
    -	**git push**
  
        *Solo la prima volta: chiedere a @giazaki di essere aggiunto come collaboratore*
    
        _Solo la prima volta: si aprirà una finestra per effettuare il login su GitHub, seguire le istruzioni; successivamente, eseguire il seguente comando (per salvare le credenziali, in modo da non fare più il login):
**git config credential.helper store**_
