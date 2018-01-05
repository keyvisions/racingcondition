# A universe driven by a racing interaction
What if there were a fourth type of interaction in the universe? Along with repulsion, attraction, neutral let's assume a racing interaction&mdash;an interaction is the behavior between two entities. While the 3 basic interactions, repulsion, attraction and neurtal (indifference) are intuitive, the fourth, racing, requires an introduction: racing, or chase interaction, describes the behavior between two entities where one entity runs away from a second that chases it. Indifference between two entities indicates total absences of interactions, i.e., pair of entities that exhibit indifference simply are not aware of each other existence.

## Experimental setup
The file universe.htm includes the javascript code to simulate an N particles universe defined by behavior and strength matrices.
- Given a universe composed of 5 entities, (A B C D E), let's define a 5x5 behavior matrix (**B**) where the element *bij* indicates the interaction between *ith* entity with the *jth* entity: +1 attraction, -1 repulsion, 0 neutral and (-2, +2) racing. *bij* = *bji* for all interaction except racing where *bij* = -*bji*
- The magnitude of an interaction between any two entities is proportional to the inverse of the square of their distance.

## Questions?
Why 5 and not 4 entities? Why not more?
