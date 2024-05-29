
# Class: InteractionAffordance

TOOD

URI: [td:InteractionAffordance](https://www.w3.org/2019/wot/td#InteractionAffordance)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[PropertyAffordance],[MultiLanguage],[Form]<forms%200..*-++[InteractionAffordance&#124;name:string],[DataSchema]<uriVariables%200..*-++[InteractionAffordance],[MultiLanguage]<descriptionInLanguage%200..1-%20[InteractionAffordance],[MultiLanguage]<titleInLanguage%200..1-%20[InteractionAffordance],[MultiLanguage]<description%200..1-%20[InteractionAffordance],[MultiLanguage]<title%200..1-%20[InteractionAffordance],[MultiLanguage]<descriptions%200..*-++[InteractionAffordance],[MultiLanguage]<titles%200..*-++[InteractionAffordance],[InteractionAffordance]^-[PropertyAffordance],[InteractionAffordance]^-[EventAffordance],[InteractionAffordance]^-[ActionAffordance],[Form],[EventAffordance],[DataSchema],[ActionAffordance])](https://yuml.me/diagram/nofunky;dir:TB/class/[PropertyAffordance],[MultiLanguage],[Form]<forms%200..*-++[InteractionAffordance&#124;name:string],[DataSchema]<uriVariables%200..*-++[InteractionAffordance],[MultiLanguage]<descriptionInLanguage%200..1-%20[InteractionAffordance],[MultiLanguage]<titleInLanguage%200..1-%20[InteractionAffordance],[MultiLanguage]<description%200..1-%20[InteractionAffordance],[MultiLanguage]<title%200..1-%20[InteractionAffordance],[MultiLanguage]<descriptions%200..*-++[InteractionAffordance],[MultiLanguage]<titles%200..*-++[InteractionAffordance],[InteractionAffordance]^-[PropertyAffordance],[InteractionAffordance]^-[EventAffordance],[InteractionAffordance]^-[ActionAffordance],[Form],[EventAffordance],[DataSchema],[ActionAffordance])

## Children

 * [ActionAffordance](ActionAffordance.md) - An Interaction Affordance that allows to invoke a function of the Thing, which manipulates state (e.g., toggling a lamp on or off) or triggers a process on the Thing (e.g., dim a lamp over time).
 * [EventAffordance](EventAffordance.md) - An Interaction Affordance that describes an event source, which asynchronously pushes event data to Consumers (e.g., overhearing alerts).
 * [PropertyAffordance](PropertyAffordance.md) - An Interaction Affordance that exposes state of the Thing. This state can be retrieved (read) and/or updated.

## Referenced by Class


## Attributes


### Own

 * [titles](titles.md)  <sub>0..\*</sub>
     * Range: [MultiLanguage](MultiLanguage.md)
 * [descriptions](descriptions.md)  <sub>0..\*</sub>
     * Description: TODO, check, according to the description a description should not contain a lang tag.
     * Range: [MultiLanguage](MultiLanguage.md)
 * [title](title.md)  <sub>0..1</sub>
     * Description: Provides a human-readable title (e.g., display a text for UI representation) based on a default language.
     * Range: [MultiLanguage](MultiLanguage.md)
 * [description](description.md)  <sub>0..1</sub>
     * Range: [MultiLanguage](MultiLanguage.md)
 * [titleInLanguage](titleInLanguage.md)  <sub>0..1</sub>
     * Description: title of the TD element (Thing, interaction affordance, security scheme or data scheme) with language tag. By convention, a language tag must be added to the object of descriptionInLanguage. Otherwise use description.
     * Range: [MultiLanguage](MultiLanguage.md)
 * [descriptionInLanguage](descriptionInLanguage.md)  <sub>0..1</sub>
     * Description: description of the TD element (Thing, interaction affordance, security scheme or data scheme) with language tag. By convention, a language tag must be added to the object of descriptionInLanguage. Otherwise use description.
     * Range: [MultiLanguage](MultiLanguage.md)
 * [➞name](interactionAffordance__name.md)  <sub>1..1</sub>
     * Description: Indexing property to store entity names when serializing them in a JSON-LD @index container.
     * Range: [String](types/String.md)
 * [➞uriVariables](interactionAffordance__uriVariables.md)  <sub>0..\*</sub>
     * Description: Define URI template variables according to RFC6570 as collection based on schema specifications. The individual variables DataSchema cannot be an ObjectSchema or an ArraySchema. TODO: range is not obvious from the ontology.
     * Range: [DataSchema](DataSchema.md)
 * [➞forms](interactionAffordance__forms.md)  <sub>0..\*</sub>
     * Description: Set of form hypermedia controls that describe how an operation can be performed.
     * Range: [Form](Form.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Mappings:** | | td:InteractionAffordance |