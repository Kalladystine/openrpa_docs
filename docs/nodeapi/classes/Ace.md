---
layout: page
title: Ace
parent: NodeJS Api
---
[@openiap/nodeapi](../README.html) / [Exports](../modules.html) / Ace

# Class: Ace

## Table of contents

### Constructors

- [constructor](Ace.html#constructor)

### Properties

- [\_id](Ace.html#_id)
- [deny](Ace.html#deny)
- [name](Ace.html#name)
- [rights](Ace.html#rights)
- [ace\_right\_bits](Ace.html#ace_right_bits)
- [full\_control](Ace.html#full_control)

### Methods

- [\_arrayBufferToBase64](Ace.html#_arraybuffertobase64)
- [\_base64ToArrayBuffer](Ace.html#_base64toarraybuffer)
- [isBitSet](Ace.html#isbitset)
- [resetfullcontrol](Ace.html#resetfullcontrol)
- [resetnone](Ace.html#resetnone)
- [setBit](Ace.html#setbit)
- [toogleBit](Ace.html#tooglebit)
- [unsetBit](Ace.html#unsetbit)

## Constructors

### constructor

• **new Ace**()

#### Defined in

[src/Ace.ts:8](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L8)

## Properties

### \_id

• **\_id**: `string`

#### Defined in

[src/Ace.ts:5](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L5)

___

### deny

• **deny**: `boolean` = `false`

#### Defined in

[src/Ace.ts:4](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L4)

___

### name

• **name**: `string`

#### Defined in

[src/Ace.ts:6](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L6)

___

### rights

• **rights**: `string` \| `number` = `65535`

#### Defined in

[src/Ace.ts:7](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L7)

___

### ace\_right\_bits

▪ `Static` **ace\_right\_bits**: `number` = `16`

#### Defined in

[src/Ace.ts:2](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L2)

___

### full\_control

▪ `Static` **full\_control**: `number` = `65535`

#### Defined in

[src/Ace.ts:3](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L3)

## Methods

### \_arrayBufferToBase64

▸ `Static` **_arrayBufferToBase64**(`arraybuffer`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `arraybuffer` | `any` |

#### Returns

`string`

#### Defined in

[src/Ace.ts:43](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L43)

___

### \_base64ToArrayBuffer

▸ `Static` **_base64ToArrayBuffer**(`base64`): `ArrayBuffer`

#### Parameters

| Name | Type |
| :------ | :------ |
| `base64` | `any` |

#### Returns

`ArrayBuffer`

#### Defined in

[src/Ace.ts:27](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L27)

___

### isBitSet

▸ `Static` **isBitSet**(`item`, `bit`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Ace`](Ace.html) |
| `bit` | `number` |

#### Returns

`boolean`

#### Defined in

[src/Ace.ts:53](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L53)

___

### resetfullcontrol

▸ `Static` **resetfullcontrol**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Ace`](Ace.html) |

#### Returns

`void`

#### Defined in

[src/Ace.ts:10](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L10)

___

### resetnone

▸ `Static` **resetnone**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Ace`](Ace.html) |

#### Returns

`void`

#### Defined in

[src/Ace.ts:20](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L20)

___

### setBit

▸ `Static` **setBit**(`item`, `bit`): `string` \| `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Ace`](Ace.html) |
| `bit` | `number` |

#### Returns

`string` \| `number`

#### Defined in

[src/Ace.ts:87](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L87)

___

### toogleBit

▸ `Static` **toogleBit**(`item`, `bit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Ace`](Ace.html) |
| `bit` | `number` |

#### Returns

`void`

#### Defined in

[src/Ace.ts:139](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L139)

___

### unsetBit

▸ `Static` **unsetBit**(`item`, `bit`): `string` \| `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Ace`](Ace.html) |
| `bit` | `number` |

#### Returns

`string` \| `number`

#### Defined in

[src/Ace.ts:114](https://github.com/openiap/nodeapi/blob/a6b5438/src/Ace.ts#L114)
