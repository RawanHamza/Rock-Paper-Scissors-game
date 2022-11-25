#Introduction 

Rock,Paper,Scissors is a game developed using HTML, CSS and JavaScript. 
The game is responsive.

#Code

Generating and getting the computer random choioces by this code:
```
function getComputerChoice(){

    const choices = ['r','p','s'];
    const randomNumber=Math.floor(Math.random() * 3) ;
    return choices[randomNumber];
    
}
```
Change the html paragraph results according to the current result:
PS: "it's a draw" is changing for each case.
``` 
result_p.innerHTML = `${convertToWord(userChoice)} ${smallUserWord} equals ${convertToWord(computerChoice)} ${smallCompWord} It's a Draw! `;
```
