# Elizaveta Chizh

## Contacts for communication:

- _Location:_ Minsk, Belarus
- _Phone:_ +375444640092
- _E-mail:_ elizavetka.chizh@gmail.com
- _Skype:_ live:.cid.c9877aac54d1f26c
- [LinkedIn](https://vk.com/away.php?to=https://www.linkedin.com/i..)
- [Git](https://github.com/elizavetachizh)

## About me:

I'm 20 years old and I'm a student of the last year of the university. I begginner Java Script (JS) Developer and Software Engineer.\
More than a year ago I’ve become passionate about programming. I took various online courses and studied by myself. My objective as a JS Developer is to apply my skills in IT craftsmanship and IT implementation, and to utilize my knowledge in web configuration and troubleshooting to fulfill the company's vision and mission.\
I'll want to bring success to the company by designing specific IT solutions that will address technical issues usually encountered in a JS environment.\
I am a team player, who is able to learn quickly and learn something new, open to adapt changes and a great problem solver.

## Skills:

- HTML5
- CSS
- basic knowledge bootstrap
- Cross-browser and adaptive site layout
- OOP
- JS(ES6+,Fundamentals,Functional Programming, Asynchronous JavaScript,DOM)
- basic knowledge React
- theoretical knowledge PHP
- Knowledge of http/https protocols
- Knowledge of tcp/ip networks
- Git/GitHub
- MySQL
- Mathematical knowledge and understanding of algorithms

## Code example:

```
function isValid(str) {
    let arr = [];
    const brackets = {
        "}": "{",
        ")": "(",
        "]": "[",
    };
    for (let i = 0; i < str.length; i++) {
        const current = str[i];
        if (isClosedBrackets(current)) {
            if (brackets[current] != arr.pop()) {
                return false;
            }
        } else {
    arr.push(current);
    }
}
    return arr.length === 0;
}

function isClosedBrackets(char) {
    return ["}", ")", "]"].indexOf(char) > -1;
}
console.log(isValid("{([])}"));
```
