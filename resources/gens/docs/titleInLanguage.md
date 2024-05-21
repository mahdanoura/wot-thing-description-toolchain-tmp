

# Slot: titleInLanguage


_title of the TD element (Thing, interaction affordance, security scheme or data scheme) with language tag. By convention, a language tag must be added to the object of descriptionInLanguage. Otherwise use description._



URI: [td:titleInLanguage](https://www.w3.org/2019/wot/td#titleInLanguage)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [DataSchema](DataSchema.md) | Metadata that describes the data format used |  no  |
| [Thing](Thing.md) | An abstraction of a physical or a virtual entity whose metadata and interface... |  no  |
| [InteractionAffordance](InteractionAffordance.md) | TOOD |  no  |
| [EventAffordance](EventAffordance.md) | An Interaction Affordance that describes an event source, which asynchronousl... |  no  |
| [ActionAffordance](ActionAffordance.md) | An Interaction Affordance that allows to invoke a function of the Thing, whic... |  no  |
| [PropertyAffordance](PropertyAffordance.md) | An Interaction Affordance that exposes state of the Thing |  no  |







## Properties

* Range: [MultiLanguage](MultiLanguage.md)





## Identifier and Mapping Information







### Schema Source


* from schema: td




## LinkML Source

<details>
```yaml
name: titleInLanguage
description: title of the TD element (Thing, interaction affordance, security scheme
  or data scheme) with language tag. By convention, a language tag must be added to
  the object of descriptionInLanguage. Otherwise use description.
from_schema: td
rank: 1000
alias: titleInLanguage
domain_of:
- DataSchema
- InteractionAffordance
- Thing
range: MultiLanguage

```
</details>