[@remembered/redis - v0.7.0](../README.md) / AlternativePersistence

# Interface: AlternativePersistence

## Table of contents

### Methods

- [get](AlternativePersistence.md#get)
- [save](AlternativePersistence.md#save)

## Methods

### get

▸ **get**(`key`): `Promise`<`string` \| `Buffer`\>

Get the content for the informed key

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | the key for the content |

#### Returns

`Promise`<`string` \| `Buffer`\>

___

### save

▸ **save**(`key`, `content`, `ttl`): `Promise`<`void`\>

Saves the informed content

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | the key for the content |
| `content` | `string` \| `Buffer` | the content to be saved |
| `ttl` | `number` | the ttl redis will maintain the reference for this key, in seconds |

#### Returns

`Promise`<`void`\>