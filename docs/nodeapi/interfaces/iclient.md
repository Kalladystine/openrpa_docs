---
layout: page
title: iclient
nav_exclude: true
parent: NodeJS Api
---
[@openiap/nodeapi](../README.html) / [Exports](../modules.html) / iclient

# Interface: iclient

## Implemented by

- [`client`](../classes/client.html)

## Table of contents

### Properties

- [agent](iclient.html#agent)
- [call](iclient.html#call)
- [connected](iclient.html#connected)
- [connecting](iclient.html#connecting)
- [created](iclient.html#created)
- [doping](iclient.html#doping)
- [exchanges](iclient.html#exchanges)
- [grpc](iclient.html#grpc)
- [grpcStream](iclient.html#grpcstream)
- [id](iclient.html#id)
- [jwt](iclient.html#jwt)
- [lastheartbeat](iclient.html#lastheartbeat)
- [lastheartbeatsec](iclient.html#lastheartbeatsec)
- [lastheartbeatstr](iclient.html#lastheartbeatstr)
- [protocol](iclient.html#protocol)
- [queues](iclient.html#queues)
- [remoteip](iclient.html#remoteip)
- [replies](iclient.html#replies)
- [seq](iclient.html#seq)
- [signedin](iclient.html#signedin)
- [stream](iclient.html#stream)
- [streams](iclient.html#streams)
- [url](iclient.html#url)
- [user](iclient.html#user)
- [version](iclient.html#version)
- [watches](iclient.html#watches)
- [ws](iclient.html#ws)

### Methods

- [Close](iclient.html#close)
- [Initialize](iclient.html#initialize)
- [SendWatch](iclient.html#sendwatch)
- [UnWatch](iclient.html#unwatch)
- [Watch](iclient.html#watch)
- [onConnected](iclient.html#onconnected)
- [onDisconnected](iclient.html#ondisconnected)
- [onMessage](iclient.html#onmessage)
- [ping](iclient.html#ping)
- [queuecount](iclient.html#queuecount)

## Properties

### agent

• **agent**: [`clientAgent`](../modules.html#clientagent)

#### Defined in

[src/client.ts:16](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L16)

___

### call

• **call**: `any`

#### Defined in

[src/client.ts:36](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L36)

___

### connected

• **connected**: `boolean`

#### Defined in

[src/client.ts:27](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L27)

___

### connecting

• **connecting**: `boolean`

#### Defined in

[src/client.ts:28](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L28)

___

### created

• **created**: `Date`

#### Defined in

[src/client.ts:20](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L20)

___

### doping

• **doping**: `boolean`

#### Defined in

[src/client.ts:19](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L19)

___

### exchanges

• **exchanges**: `any`[]

#### Defined in

[src/client.ts:30](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L30)

___

### grpc

• **grpc**: `FlowService`

#### Defined in

[src/client.ts:35](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L35)

___

### grpcStream

• **grpcStream**: `any`

#### Defined in

[src/client.ts:37](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L37)

___

### id

• **id**: `string`

#### Defined in

[src/client.ts:13](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L13)

___

### jwt

• **jwt**: `string`

#### Defined in

[src/client.ts:25](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L25)

___

### lastheartbeat

• **lastheartbeat**: `Date`

#### Defined in

[src/client.ts:21](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L21)

___

### lastheartbeatsec

• **lastheartbeatsec**: `string`

#### Defined in

[src/client.ts:23](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L23)

___

### lastheartbeatstr

• **lastheartbeatstr**: `string`

#### Defined in

[src/client.ts:22](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L22)

___

### protocol

• **protocol**: [`clientType`](../modules.html#clienttype)

#### Defined in

[src/client.ts:17](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L17)

___

### queues

• **queues**: `any`[]

#### Defined in

[src/client.ts:29](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L29)

___

### remoteip

• **remoteip**: `string`

#### Defined in

[src/client.ts:15](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L15)

___

### replies

• **replies**: `any`

#### Defined in

[src/client.ts:38](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L38)

___

### seq

• **seq**: `number`

#### Defined in

[src/client.ts:14](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L14)

___

### signedin

• **signedin**: `boolean`

#### Defined in

[src/client.ts:26](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L26)

___

### stream

• **stream**: `any`

#### Defined in

[src/client.ts:34](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L34)

___

### streams

• **streams**: `any`

#### Defined in

[src/client.ts:39](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L39)

___

### url

• **url**: `string`

#### Defined in

[src/client.ts:32](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L32)

___

### user

• **user**: `any`

#### Defined in

[src/client.ts:24](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L24)

___

### version

• **version**: `string`

#### Defined in

[src/client.ts:18](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L18)

___

### watches

• **watches**: [`changestream`](../classes/changestream.html)[]

#### Defined in

[src/client.ts:31](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L31)

___

### ws

• **ws**: `any`

#### Defined in

[src/client.ts:33](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L33)

## Methods

### Close

▸ **Close**(): `void`

#### Returns

`void`

#### Defined in

[src/client.ts:49](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L49)

___

### Initialize

▸ **Initialize**(`ws`, `stream`, `call`, `req`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ws` | `any` |
| `stream` | `any` |
| `call` | `any` |
| `req` | `any` |

#### Returns

`Promise`<`boolean`\>

#### Defined in

[src/client.ts:40](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L40)

___

### SendWatch

▸ **SendWatch**(`watch`, `next`, `span`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `watch` | `any` |
| `next` | `any` |
| `span` | `any` |

#### Returns

`void`

#### Defined in

[src/client.ts:48](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L48)

___

### UnWatch

▸ **UnWatch**(`id`, `jwt`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `string` |
| `jwt` | `string` |

#### Returns

`Promise`<`void`\>

#### Defined in

[src/client.ts:47](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L47)

___

### Watch

▸ **Watch**(`aggregates`, `collectionname`, `jwt`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `aggregates` | `object`[] |
| `collectionname` | `string` |
| `jwt` | `string` |

#### Returns

`Promise`<`string`\>

#### Defined in

[src/client.ts:46](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L46)

___

### onConnected

▸ **onConnected**(`client`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`client`](../classes/client.html) |

#### Returns

`void`

#### Defined in

[src/client.ts:41](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L41)

___

### onDisconnected

▸ **onDisconnected**(`client`, `error`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`client`](../classes/client.html) |
| `error` | `Error` |

#### Returns

`void`

#### Defined in

[src/client.ts:42](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L42)

___

### onMessage

▸ **onMessage**(`client`, `message`): `Promise`<[`Envelope`](../modules.html#envelope)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`client`](../classes/client.html) |
| `message` | `any` |

#### Returns

`Promise`<[`Envelope`](../modules.html#envelope)\>

#### Defined in

[src/client.ts:43](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L43)

___

### ping

▸ **ping**(`span`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `span` | `any` |

#### Returns

`void`

#### Defined in

[src/client.ts:44](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L44)

___

### queuecount

▸ **queuecount**(): `number`

#### Returns

`number`

#### Defined in

[src/client.ts:45](https://github.com/openiap/nodeapi/blob/a6b5438/src/client.ts#L45)
