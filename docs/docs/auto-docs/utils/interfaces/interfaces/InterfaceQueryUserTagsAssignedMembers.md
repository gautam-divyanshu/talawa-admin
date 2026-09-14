[Admin Docs](/)

***

# Interface: InterfaceQueryUserTagsAssignedMembers

Defined in: [src/utils/interfaces.ts:1167](https://github.com/PalisadoesFoundation/talawa-admin/blob/main/src/utils/interfaces.ts#L1167)

Defines the structure for a query result containing user tags and their assigned members.

## Properties

### ancestorTags

> **ancestorTags**: `object`[]

Defined in: [src/utils/interfaces.ts:1171](https://github.com/PalisadoesFoundation/talawa-admin/blob/main/src/utils/interfaces.ts#L1171)

#### \_id

> **\_id**: `string`

#### name

> **name**: `string`

***

### childTags

> **childTags**: `InterfaceTagNodeData`

Defined in: [src/utils/interfaces.ts:1169](https://github.com/PalisadoesFoundation/talawa-admin/blob/main/src/utils/interfaces.ts#L1169)

***

### folder?

> `optional` **folder**: `object`

Defined in: [src/utils/interfaces.ts:1175](https://github.com/PalisadoesFoundation/talawa-admin/blob/main/src/utils/interfaces.ts#L1175)

#### \_id

> **\_id**: `string`

#### name

> **name**: `string`

#### parentFolder?

> `optional` **parentFolder**: `object`

##### parentFolder.\_id

> **\_id**: `string`

##### parentFolder.name

> **name**: `string`

##### parentFolder.parentFolder?

> `optional` **parentFolder**: `object`

##### parentFolder.parentFolder.\_id

> **\_id**: `string`

##### parentFolder.parentFolder.name

> **name**: `string`

***

### name

> **name**: `string`

Defined in: [src/utils/interfaces.ts:1168](https://github.com/PalisadoesFoundation/talawa-admin/blob/main/src/utils/interfaces.ts#L1168)

***

### usersAssignedTo

> **usersAssignedTo**: `InterfaceTagMembersData`

Defined in: [src/utils/interfaces.ts:1170](https://github.com/PalisadoesFoundation/talawa-admin/blob/main/src/utils/interfaces.ts#L1170)
