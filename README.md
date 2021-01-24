//user
let userName = 'Hugo';

//greeting
userName ? console.log(`Hello, ${userName}`) : console.log('Hello!');

//question
let userQuestion = 'Am I pretty?';
console.log(userQuestion);

//pc answer for the question
let randomNumber = Math.floor(Math.random()*8)

//
let eightBall = '';

if(randomNumber === 1) {
  eightBall = 'Yes, you are!';
} else if (randomNumber === 2) {
  eightBall = 'Yes, you are222!';
} else if (randomNumber === 3) {
  eightBall = 'Yes, you are333!';
} else if (randomNumber === 4) {
  eightBall = 'Yes, you are444!';
} else if (randomNumber === 5) {
  eightBall = 'Yes, you are555!';
} else if  (randomNumber === 5){
  eightBall = 'Yes, you are666!';
} else if (randomNumber === 6) {
  eightBall = 'Yes, you are!777';
} else {
  eightBall = 'Yes, you are888!';
};



/* THE SAME, WITH SWITCH
switch (randomNumber) {
  case 1:
    eightBall = 'It is certain';
    break;
  case 2:
    eightBall = 'It is decidedly so';
    break;
  case 3:
    eightBall = 'Reply hazy try again';
    break;
  case 4:
    eightBall = 'Cannot predict now';
    break;
  case 5:
    eightBall = 'Do not count on it';
    break;
  case 6:
    eightBall = 'My sources say no';
    break;
  case 7:
    eightBall = 'Outlook not so good';
    break;
  default:
    eightBall = 'Signs point to yes';
    break;
};
*/


console.log(eightBall);
