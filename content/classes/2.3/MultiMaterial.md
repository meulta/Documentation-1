---
ID_PAGE: 25215
PG_TITLE: MultiMaterial
PG_VERSION: 2.1
TAGS:
    - Material
---
## Description

class [MultiMaterial](/classes/2.3/MultiMaterial) extends [Material](/classes/2.3/Material)



## Constructor

##  new [MultiMaterial](/classes/2.3/MultiMaterial)(name, scene)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | name | string |   
 | scene | [Scene](/classes/2.3/Scene) |   [Scene](/classes/2.3/Scene) which contain the [MultiMaterial](/classes/2.3/MultiMaterial)
## Members

### subMaterials : [Material](/classes/2.3/Material)[]



## Methods

### getSubMaterial(index) &rarr; [Material](/classes/2.3/Material)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | index | any |   Index of the submaterial

### isReady(mesh) &rarr; boolean



#### Parameters
 | Name | Type | Description
---|---|---|---
optional | mesh | [AbstractMesh](/classes/2.3/AbstractMesh) |   The mesh with the multi material

### clone(name, cloneChildren) &rarr; [MultiMaterial](/classes/2.3/MultiMaterial)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | name | string |   
optional | cloneChildren | boolean | 
### serialize() &rarr; any

