
# Type: add node to subset


Places a node inside a subset, by annotating that node

URI: [ocl:AddNodeToSubset](http://w3id.org/oclAddNodeToSubset)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[NodeChange],[AddToSubset],[AddNodeToSubset&#124;about(i):string%20%3F;old_value(i):string%20%3F;new_value(i):string%20%3F]uses%20-.->[AddToSubset],[NodeChange]^-[AddNodeToSubset],[Activity])

## Parents

 *  is_a: [NodeChange](NodeChange.md) - A simple change where the change is about a node

## Uses Mixins

 *  mixin: [AddToSubset](AddToSubset.md) - placing an element inside a subset

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

## Other properties

|  |  |  |
| --- | --- | --- |
| **Aliases:** | | add term to slim |
| **See also:** | | http://wiki.geneontology.org/index.php/Adding_a_Term_to_a_GO_Subset_(Slim) |
