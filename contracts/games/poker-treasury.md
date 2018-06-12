# Poker Treasury

The TREASURER is `zimmi` for this game.

```TREASURER=zimmi```

### Funding

##### Cash

PLAYER buys GG tokens from the TREASURER.

_`BIG` game_

```2018/04/20 * GG transfer
    ; timestamp: 1524268800
    zimmi:Assets   -1333.33333333 GG
    gg:Games:PTY-POKER-1-BIG    1333.33333333 GG```

_`SMALL` game_

```2018/04/20 * GG transfer
    ; timestamp: 1524268800
    zimmi:Assets   -133.33333333 GG
    gg:Games:PTY-POKER-1-SMALL    133.33333333 GG```

Official zimmi representative then saves this transaction in `~/ledger/GG/ASSETS/zimmi/1524268800.dat` and signs.

##### GG

_`BIG` game_


```2018/04/20 * GG funding
    ; timestamp: 1524268800
    PLAYER:Assets    -1333.33333333 GG
    gg:Games:GAME:PTY-POKER-1-BIG    1333.33333333 GG```

_`SMALL` game_


```2018/04/20 * GG funding
    ; timestamp: 1524268800
    PLAYER:Assets    -133.33333333 GG
    gg:Games:GAME:PTY-POKER-1-SMALL    133.33333333 GG```

PLAYER then saves this transaction in `~/ledger/GG/ASSETS/PLAYER/1524268800.dat` and signs.
