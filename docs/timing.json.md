The schema defines the following types:

## UseType 

*no description yet*

`"add_to_mash"`<br/>`"add_to_boil"`<br/>`"add_to_fermentation"`<br/>`"add_to_package"`
## TimingType 

The timing object fully describes the timing of an addition with options for basis on time, gravity, or pH at any process step.

**TimingType** is an object with these properties:

|Name|Required|Type|Description|
|--|--|--|--|
| **time** |  | [TimeType](measureable_units.json.md#timetype)|  |
| **duration** |  | [TimeType](measureable_units.json.md#timetype)|  |
| **continuous** |  | boolean|  |
| **specific_gravity** |  | [GravityType](measureable_units.json.md#gravitytype)|  |
| **pH** |  | [AcidityType](measureable_units.json.md#aciditytype)|  |
| **step** |  | integer|  |
| **use** |  | [UseType](#usetype)|  |

