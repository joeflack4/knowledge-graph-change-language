
# Type: node text definition change




URI: [ocl:NodeTextDefinitionChange](http://w3id.org/oclNodeTextDefinitionChange)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[TextDefinitionReplacement],[RemoveTextDefinition],[NodeTextDefinitionChange&#124;about(i):string%20%3F;old_value(i):string%20%3F;new_value(i):string%20%3F]^-[TextDefinitionReplacement],[NodeTextDefinitionChange]^-[RemoveTextDefinition],[NodeTextDefinitionChange]^-[NewTextDefinition],[NodeChange]^-[NodeTextDefinitionChange],[NodeChange],[NewTextDefinition],[Activity])

## Parents

 *  is_a: [NodeChange](NodeChange.md) - A simple change where the change is about a node

## Children

 * [NewTextDefinition](NewTextDefinition.md) - A node change where a de-novo text definition is created
 * [RemoveTextDefinition](RemoveTextDefinition.md) - A node change where a text definition is deleted
 * [TextDefinitionReplacement](TextDefinitionReplacement.md) - A node change where a text definition is modified

## Referenced by class


## Attributes


### Inherited from node change:

 * [new value](new_value.md)  <sub>OPT</sub>
    * Description: The value of a property held in the old instance of the ontology
    * range: [String](types/String.md)
 * [node change➞about](node_change_about.md)  <sub>OPT</sub>
    * range: [String](types/String.md)
 * [old value](old_value.md)  <sub>OPT</sub>
    * Description: The value of a property held in the old instance of the ontology
    * range: [String](types/String.md)
 * [was generated by](was_generated_by.md)  <sub>OPT</sub>
    * range: [Activity](Activity.md)