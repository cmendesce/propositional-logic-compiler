# Propositional Logic Compiler

[![CircleCI](https://circleci.com/gh/cmendesce/propositional-logic-tools.svg?style=svg)](https://circleci.com/gh/cmendesce/propositional-logic-compiler) [![Heroku](https://heroku-badge.herokuapp.com/?app=logic-compiler)](https://pl-tools.herokuapp.com/)

This is a small application for compiler expressions written in propositional logic syntax. 

It can compile expressions like these

```
(~P)
((A^B)->(AV~B))
((A^B)->(AVB))
(A->(BVC))->(AVB)V(AVC)
(((~(P^Q))^P)->(~Q))
```
Check the spec folder to see all tests and expressions.



## License
Code is under the [MIT Licence](LICENSE).

--
Special thanks to [Mario Diniz](https://github.com/mariohd)
