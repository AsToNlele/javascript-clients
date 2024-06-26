[@redhat-cloud-services/javascript-clients-shared](../README.md) / [Exports](../modules.md) / ConfigurationParameters

# Interface: ConfigurationParameters

## Table of contents

### Properties

- [accessToken](ConfigurationParameters.md#accesstoken)
- [apiKey](ConfigurationParameters.md#apikey)
- [baseOptions](ConfigurationParameters.md#baseoptions)
- [basePath](ConfigurationParameters.md#basepath)
- [formDataCtor](ConfigurationParameters.md#formdatactor)
- [password](ConfigurationParameters.md#password)
- [username](ConfigurationParameters.md#username)

## Properties

### accessToken

• `Optional` **accessToken**: `string` \| `Promise`\<`string`\> \| (`name?`: `string`, `scopes?`: `string`[]) => `string` \| (`name?`: `string`, `scopes?`: `string`[]) => `Promise`\<`string`\>

#### Defined in

[packages/shared/configuration.ts:8](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/shared/configuration.ts#L8)

___

### apiKey

• `Optional` **apiKey**: `string` \| `Promise`\<`string`\> \| (`name`: `string`) => `string` \| (`name`: `string`) => `Promise`\<`string`\>

#### Defined in

[packages/shared/configuration.ts:5](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/shared/configuration.ts#L5)

___

### baseOptions

• `Optional` **baseOptions**: `any`

#### Defined in

[packages/shared/configuration.ts:10](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/shared/configuration.ts#L10)

___

### basePath

• `Optional` **basePath**: `string`

#### Defined in

[packages/shared/configuration.ts:9](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/shared/configuration.ts#L9)

___

### formDataCtor

• `Optional` **formDataCtor**: () => `any`

#### Type declaration

• **new formDataCtor**(): `any`

##### Returns

`any`

#### Defined in

[packages/shared/configuration.ts:11](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/shared/configuration.ts#L11)

___

### password

• `Optional` **password**: `string`

#### Defined in

[packages/shared/configuration.ts:7](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/shared/configuration.ts#L7)

___

### username

• `Optional` **username**: `string`

#### Defined in

[packages/shared/configuration.ts:6](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/shared/configuration.ts#L6)
