[Chunklands Documentation](../README.md) › ["noise"](_noise_.md)

# Module: "noise"

## Index

### Functions

* [perlin2](_noise_.md#perlin2)
* [perlin3](_noise_.md#perlin3)
* [prng2](_noise_.md#prng2)
* [prng3](_noise_.md#prng3)
* [seed](_noise_.md#seed)
* [simplex2](_noise_.md#simplex2)
* [simplex3](_noise_.md#simplex3)

## Functions

###  perlin2

▸ **perlin2**(`x`: number, `y`: number): *number*

*Defined in [noise.js:271](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/noise.js#L271)*

2D perlin noise.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`x` | number | The x-value |
`y` | number | The y-value  |

**Returns:** *number*

___

###  perlin3

▸ **perlin3**(`x`: number, `y`: number, `z`: number): *number*

*Defined in [noise.js:302](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/noise.js#L302)*

3D perlin noise.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`x` | number | The x-value |
`y` | number | The y-value |
`z` | number | The z-value  |

**Returns:** *number*

___

###  prng2

▸ **prng2**(`x`: number, `y`: number, `valueOffset`: number, `valueMult`: number): *number*

*Defined in [noise.js:348](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/noise.js#L348)*

2D pseudo random number generator.

**Parameters:**

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`x` | number | - | The x-value |
`y` | number | - | The y-value |
`valueOffset` | number | PRNG_OFF | Value offset |
`valueMult` | number | PRNG_MUL | Value multiplicator |

**Returns:** *number*

Normalized value [0; 1]

___

###  prng3

▸ **prng3**(`x`: number, `y`: number, `z`: number, `seedOff`: number, `seedMul`: number): *number*

*Defined in [noise.js:362](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/noise.js#L362)*

3D pseudo random number generator.

**Parameters:**

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`x` | number | - | The x-value |
`y` | number | - | The y-value |
`z` | number | - | The z-value |
`seedOff` | number | PRNG_OFF | - |
`seedMul` | number | PRNG_MUL | - |

**Returns:** *number*

Normalized value [0; 1]

___

###  seed

▸ **seed**(`seed`: number): *void*

*Defined in [noise.js:57](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/noise.js#L57)*

Initializes permutations.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`seed` | number | Any seed value  |

**Returns:** *void*

___

###  simplex2

▸ **simplex2**(`xin`: number, `yin`: number): *number*

*Defined in [noise.js:104](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/noise.js#L104)*

2D simplex noise.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`xin` | number | The x-value |
`yin` | number | The y-value  |

**Returns:** *number*

___

###  simplex3

▸ **simplex3**(`xin`: number, `yin`: number, `zin`: number): *number*

*Defined in [noise.js:168](https://github.com/20hoibe/chunklands/blob/38f14fe/src/game/noise.js#L168)*

3D simplex noise.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`xin` | number | The x-value |
`yin` | number | The y-value |
`zin` | number | The z-value  |

**Returns:** *number*
