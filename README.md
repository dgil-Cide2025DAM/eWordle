## eWordle<a href="https://github.com/mczhuang/eWordle"> <img src="https://github.githubassets.com/images/modules/site/icons/footer/github-mark.svg" width="3%"></a>

An extended version of [Wordle](http://nytimes.com/games/wordle) (Mini Project of EBU4201) with full-featured helper.

### How to Play

+ Endevina la paraula de Wordle en intents només un més que la longitud de la paraula que has seleccionat.
+ Cada intent ha de ser una paraula vàlida amb la longitud que has seleccionat.
+ Per cada lletra que confirmis inserir, es mostrarà:
+ Verd si està a la paraula i en la posició correcta.
+ Groc si està a la paraula però en la posició incorrecta.
+ Gris si no està a la paraula en cap posició.

### Complie & Run


```shell
cd ./src
javac eWordle.java && java eWordle
```
### Preferences

+ #### Word Source or Difficulty

    > There are 6 word sources offered: CET-4, CET-6, TOEFL, GRE, Oxford Dictionary, and All.

+ #### Word Length

    > There are 4 options about the word length you later guess available: 5, 6, 7, and 8.

+ #### Wordle Word or Hashtag

    > Enter the word to be guessed or leave empty to guess a random word.
    >
    > To compete with others in a cloned environment, share your hashtag shown after game starts.
  

### Helper Guide (Launch via square "?" icon in game) 

Replace *s with known letters. Optionally add **all** filling letters inside "()" and omitted letters inside "[]".

```
G*ES*           --> Places marked * are unknown.
*****(ESS*)[AB] --> Places marked * are unknown but contain at least 1E2S and no A or B.
G*E**(SU)       --> Places marked * ONLY contain 1S1U (None Matched, Occurrence matter).
```


 
