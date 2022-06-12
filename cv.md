# Aleksandra Sopiyeva

## Contacts:

- Location: Minsk, Belarus
- Phone: +375297676603
- Email: sashasopiyeva@gmail.com
- GitHub: AleksandraSopiyeva


## Summary 
I don't have big programming expirience yet, but I'm very interested in Web Development. I want to develop in this direction. I think that my ability to learn will help me in this. I have a lot experience communicating with people, which helped me became more stress-resistant and also taught me how to work in a team.


## Skills:
- HTML5,CSS3
- JavaScript Basics
- Git
- VS Code
- Adobe Photoshop,Illustrator


## Code Example
Guessing game
javascript
    var answer = parseInt(Math.random() * 100);

    var playerNumber = 1;

    while(true) {

    var userAnswer = prompt("Угадайте число от 1 до 100. \nХодит игрок" + playerNumber + "\nДля выхода нажмите q " );

    if(userAnswer == "q")
    break;

    userAnswer = parseInt(userAnswer);

        if(userAnswer == answer){
            alert("Поздравляю, победил игрок" + playerNumber);
            break;
        } else if(userAnswer > answer){
            alert("Вы ввели слишком большое число");
        } else if(userAnswer < answer){
            alert("Вы ввели слишком маленькое число");
        }
       
        if(playerNumber == 1)
            playerNumber = 2;
        else
            playerNumber = 1

    }
    alert("Правильны ответ: " + answer);


## Education
- University: 
  - Minsk State Linguistic University

## Courses
- Web-design and computer graphics
- JS/FE Pre-Schol 2022Q2 


## Languages
- English (B2)
- German (B1)
- Russian (native