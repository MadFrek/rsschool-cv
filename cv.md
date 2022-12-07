# **Vasiliy Andreev**
![](src/img/avatar_180x180.jpg)

## **Contacts**

* **Location**: [Kazan, Russia](https://www.google.ru/maps/place/%D0%9A%D0%B0%D0%B7%D0%B0%D0%BD%D1%8C,+%D0%A0%D0%B5%D1%81%D0%BF.+%D0%A2%D0%B0%D1%82%D0%B0%D1%80%D1%81%D1%82%D0%B0%D0%BD/@55.795569,48.7931208,10z/data=!3m1!4b1!4m5!3m4!1s0x415ead2b7caccd99:0x7fcb77b9b5ad8c65!8m2!3d55.7878944!4d49.1233294)
* **Phone**: +79991620876
* **Email**: andreevasian95@gmail.com
* **Github**: MqsterOfStrange
* **Telegram**: [Vasiliy Andreev](https://t.me/MadFreck)
* **Discord**: Vasiliy (@MqsterOfStrange)

## **About Me**
I am not devoid of logic and want to contribute to society, so I decided to become a programmer. I have never worked in IT. This year I entered school 21, passed all the qualification tests, but left it for personal reasons. I know a little C and Python, I can work with git and bash, I can read English texts, I don’t know the real level of knowledge A2 or B1. And I know it's not enough. Therefore, I decided to learn more on this course in order to develop further and, perhaps, find my place.

## **Skills**
* **HTML**
* **CSS**
* **C** (*basic*)
* **Python** (*basic*)
* **Git**

## **Code Examples**
Hello World on JS from codewars.

```helloWorld = function() {
  var str = "Hello World!";
  console.log( str );
}

const { assert } = require('chai');
describe("Tests", () => {
  it("test", () => {
    assert.isFunction(helloWorld, "function helloWorld is not defined")
    helloWorld();
  });
});
```

Bagles game on Python. It's my own work.

```import random

NUM_DIGITS = 3
MAX_GUESSES = 10

def main():
    Preview()
    SecretNum = GetSecretNum()
    
    numGuesses = 1
    while numGuesses <= MAX_GUESSES:
        guess = ''
        while len(guess) != NUM_DIGITS or not guess.isdecimal():
            print('Guess #{}: '.format(numGuesses))
            guess = input('> ')
            if len(guess) != NUM_DIGITS or not guess.isdecimal():
                print('''Error: Your number have wrong format.
        The number must be in {} length and decimal.
        Try again.'''.format(NUM_DIGITS))

        if guess == SecretNum:
            break

        for i in range(NUM_DIGITS):
            if SecretNum[i] == guess[i]:
                print('Fermi')
        
        for i in range(NUM_DIGITS):
            for j in range(NUM_DIGITS):
                if SecretNum[i] == guess[j] and i != j:
                    print('Pico')
            
        numGuesses += 1
    
    again = ''
    if guess == SecretNum:
        print('You are win')
    else:
        print('You are lost')

    while True:
        again = input('Do you wanna play again? Y/N\n> ')
        if again == 'Y' or again == 'y':
            main()
        elif again == 'N' or again == 'n':
            print("Goodbye, thank you for playing this game")
            break

def Preview():
    print('''Bagles, a deductive logic game.
    I am thinking of a {}-digit number with no repeated digits.
    Try to guess what it is. Here are some clues:
    When I say: That means:
        Pico One digit is correct but in the wrong position.
        Fermi One digit is correct and in the right position
        Bagels No digit is correct.'''.format(NUM_DIGITS))


def GetSecretNum():
    numbers = list('0123456789')
    random.shuffle(numbers)
    numbers = numbers[0:3]
    return ''.join(numbers)

Preview()
main()
```

## **Experience**
As i said i don't have any experience, Except training projects. And I didn't pushed my cods to git.

## **Education**
* **School**: Secondary general education Tatar-Russian lyceum №23.
* **Stepik** course:\
![](src/img/sertificate.png)

## **English**
I was learning English at school, from different games and from other players.