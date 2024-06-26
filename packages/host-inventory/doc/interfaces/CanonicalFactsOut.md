[@redhat-cloud-services/host-inventory-client](../README.md) / [Exports](../modules.md) / CanonicalFactsOut

# Interface: CanonicalFactsOut

**`Export`**

CanonicalFactsOut

## Table of contents

### Properties

- [bios\_uuid](CanonicalFactsOut.md#bios_uuid)
- [fqdn](CanonicalFactsOut.md#fqdn)
- [insights\_id](CanonicalFactsOut.md#insights_id)
- [ip\_addresses](CanonicalFactsOut.md#ip_addresses)
- [mac\_addresses](CanonicalFactsOut.md#mac_addresses)
- [provider\_id](CanonicalFactsOut.md#provider_id)
- [provider\_type](CanonicalFactsOut.md#provider_type)
- [satellite\_id](CanonicalFactsOut.md#satellite_id)
- [subscription\_manager\_id](CanonicalFactsOut.md#subscription_manager_id)

## Properties

### bios\_uuid

• `Optional` **bios\_uuid**: ``null`` \| `string`

A UUID of the host machine BIOS.  This field is considered to be a canonical fact.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:342](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L342)

___

### fqdn

• `Optional` **fqdn**: ``null`` \| `string`

A host’s Fully Qualified Domain Name.  This field is considered to be a canonical fact.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:354](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L354)

___

### insights\_id

• `Optional` **insights\_id**: ``null`` \| `string`

An ID defined in /etc/insights-client/machine-id. This field is considered a canonical fact.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:324](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L324)

___

### ip\_addresses

• `Optional` **ip\_addresses**: ``null`` \| `string`[]

Host’s network IP addresses.  This field is considered to be a canonical fact.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:348](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L348)

___

### mac\_addresses

• `Optional` **mac\_addresses**: ``null`` \| `string`[]

Host’s network interfaces MAC addresses.  This field is considered to be a canonical fact.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:360](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L360)

___

### provider\_id

• `Optional` **provider\_id**: ``null`` \| `string`

Host’s reference in the external source e.g. Alibaba, AWS EC2, Azure, GCP, IBM etc. This field is one of the canonical facts and does not work without provider_type.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:366](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L366)

___

### provider\_type

• `Optional` **provider\_type**: ``null`` \| `string`

Type of external source e.g. Alibaba, AWS EC2, Azure, GCP, IBM, etc. This field is one of the canonical facts and does not workout provider_id.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:372](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L372)

___

### satellite\_id

• `Optional` **satellite\_id**: ``null`` \| `string`

A Red Hat Satellite ID of a RHEL host.  This field is considered to be a canonical fact.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:336](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L336)

___

### subscription\_manager\_id

• `Optional` **subscription\_manager\_id**: ``null`` \| `string`

A Red Hat Subcription Manager ID of a RHEL host.  This field is considered to be a canonical fact.

**`Memberof`**

CanonicalFactsOut

#### Defined in

[api.ts:330](https://github.com/RedHatInsights/javascript-clients/blob/main/packages/host-inventory/api.ts#L330)
