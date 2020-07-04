[Chunklands Documentation](../README.md) › ["Game"](../modules/_game_.md) › [Game](_game_.game.md)

# Class: Game

Default implementation for the game.

## Hierarchy

* **Game**

## Index

### Constructors

* [constructor](_game_.game.md#constructor)

### Methods

* [initialize](_game_.game.md#initialize)
* [run](_game_.game.md#run)

## Constructors

###  constructor

\+ **new Game**(`window`: Window‹›): *[Game](_game_.game.md)*

*Defined in [Game.js:12](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/Game.js#L12)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`window` | Window‹› |   |

**Returns:** *[Game](_game_.game.md)*

## Methods

###  initialize

▸ **initialize**(): *Promise‹void›*

*Defined in [Game.js:23](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/Game.js#L23)*

Initializes the game. Bake models, create shader, etc.

**Returns:** *Promise‹void›*

___

###  run

▸ **run**(): *Promise‹any›*

*Defined in [Game.js:167](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/Game.js#L167)*

Runs the game (has to be initialized before).

**Returns:** *Promise‹any›*
