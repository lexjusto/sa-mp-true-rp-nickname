# lj_checkrpname.inc

## (RUS):
Просто кусочек кода, может практически на 99.8% отсеять игроков с никами не соответствующими RolePlay режиму (SA-MP).

Использование (пример):

```pawn
#include <lj_checkrpname.inc> // add to all includes (on top)

public OnPlayerConnect(playerid) // default SA-MP function
{
    CheckRPName(playerid); // check player name with use lj_checkrpname.inc

    return 1;
}
```

Особенности:

* Определяет и уведомляет игрока о недостающей длинне первой или второй части ника. (Перед или после "_" разделителя.)
* Определяет и уведомляет игрока о запрещенных символах в первой или второй части ника. 
* Определяет и уведомляет игрока о нескольких заглавных букв в первой или второй части ника. 
* Определяет и уведомляет игрока о недостающей первой заглавной буквы в первой или второй части ника.
* Определяет и уведомляет игрока о нескольких разделителей в нике.


(Предупреждение! Это не готовый код который вы можете использовать в любом вашем проекте, данный код иногда требует некоторых изменений именно мод ваш игровой режим!)

## (ENG):
Just a piece of code on nearly 99.8% weed out players with nicknames are not relevant to the RolePlay mode (SA-MP).

Usage (example):

```pawn
#include <lj_checkrpname.inc> // add to all includes (on top)

public OnPlayerConnect(playerid) // default SA-MP function
{
    CheckRPName(playerid); // check player name with use lj_checkrpname.inc

    return 1;
}
```

Features:

* Determines and notifies the player about missing the first length or the second part of nick. (Before or after the "_" separator.)
* Determines and notifies the player of the prohibited characters in the first or second part of nick. 
* Determines and notifies the player about a few capital letters in the first or second part of nick. 
* Determines and notifies the player about missing the first capital letter in the first or second part of nick.
* Determines and notifies the player about several separators at nick.


(Warning! This is not finished code that you can use in any of your project, this code sometimes requires some changes of your mod game mode!)
