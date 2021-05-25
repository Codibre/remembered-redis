fluent-iterable - v0.1.0

# fluent-iterable - v0.1.0

## Table of contents

### Classes

- [RememberedRedis](classes/rememberedredis.md)

### Interfaces

- [RememberedRedisConfig](interfaces/rememberedredisconfig.md)

### Type aliases

- [Action](README.md#action)
- [LogError](README.md#logerror)
- [TryTo](README.md#tryto)

### Variables

- [DEFAULT\_ACQUIRE\_TIMEOUT](README.md#default_acquire_timeout)
- [DEFAULT\_LOCK\_TIMEOUT](README.md#default_lock_timeout)
- [DEFAULT\_REFRESH\_INTERVAL](README.md#default_refresh_interval)
- [DEFAULT\_RETRY\_INTERVAL](README.md#default_retry_interval)

## Type aliases

### Action

Ƭ **Action**: () => *PromiseLike*<void\>

#### Type declaration:

▸ (): *PromiseLike*<void\>

**Returns:** *PromiseLike*<void\>

___

### LogError

Ƭ **LogError**: (`message`: *string*) => *any*

#### Type declaration:

▸ (`message`: *string*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`message` | *string* |

**Returns:** *any*

___

### TryTo

Ƭ **TryTo**: (`action`: [*Action*](README.md#action)) => *PromiseLike*<void\>

#### Type declaration:

▸ (`action`: [*Action*](README.md#action)): *PromiseLike*<void\>

#### Parameters:

Name | Type |
:------ | :------ |
`action` | [*Action*](README.md#action) |

**Returns:** *PromiseLike*<void\>

## Variables

### DEFAULT\_ACQUIRE\_TIMEOUT

• `Const` **DEFAULT\_ACQUIRE\_TIMEOUT**: *60000*= 60000

___

### DEFAULT\_LOCK\_TIMEOUT

• `Const` **DEFAULT\_LOCK\_TIMEOUT**: *10000*= 10000

___

### DEFAULT\_REFRESH\_INTERVAL

• `Const` **DEFAULT\_REFRESH\_INTERVAL**: *8000*= 8000

___

### DEFAULT\_RETRY\_INTERVAL

• `Const` **DEFAULT\_RETRY\_INTERVAL**: *100*= 100