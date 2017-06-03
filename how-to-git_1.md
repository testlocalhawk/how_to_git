# How-To Version Control with Git


## Setting up git

### install git

### setting up git towards the master repository

git clone <address https>

git config --global user.email "you@example.com"

git config credential.helper store

// remove git config --global push.default matching


## Work Flow with Git

Nå er vi klare til å utvikle siden vi har en personlig kopi av repo'et

Men først kan det være lurt med litt info om hvordan ting henger sammen.


### personal work flow
- working directory, staging area, committed files

- Fix a bug
åpne icecream_maker_constants filen

fix maxScoops

git status  - viser nå at endringen ikke er lagt til staging area

legg endringen til staging area

git add icecream_maker_constants

git status  // viser nå at vi har lagt endingen til staging area

// la oss committe endringen
git commit

// commit melding skal skrives så det er lett for deg og andre å vite hva er egentlig endret her?
// fix: max number of icecream scoops limited to 10 per ice cream

git status // viser nå at vi er foran origin/master 


// adding a new file
vim IceCreamMaker.h

git status // viser at vi har en untracked file

git add IceCreamMaker.h // adds the file to the staging area

git status // viser at vi har lagt til en ny fil

// før vi committer så la oss gjøre en endring til på en unstaged fil
git mv icecream_maker_constants icecream_maker_constants.h

git status // viser oss at filen er blitt renamet og klar for å kommittes

git commit // git commit -m "add: class making icecream, renamed class containing constants"



#### Oppgave 1 a) - Make a Cheat sheet - of personal repository git commands
               b) - Tegne personal repo workflow



### origin/master repository work flow
- pulling, pushing, and merging

- Sharing your work - practical
	- first practial no merge conflicts
	- second practial merge conflicts


-- end of first git intro course






 




