# A universe driven by a racing interaction
What if there were a fourth type of interaction in the universe? Along with repulsion, attraction, neutral let's assume a racing interaction&mdash;an interaction is the behavior between two entities. While the 3 fundamental interactions, repulsion, attraction and neutral (indifference) are intuitive, the fourth, racing, requires an introduction: racing, or chase interaction, describes the behavior between two entities where one entity runs away from a second that chases it. Indifference between two entities indicates the total absence of interactions, i.e., pair of entities that exhibit indifference simply are not aware of each other existence.

## Definitions
The file universe.htm includes javascript code that simulates an N particles universe defined by behavior and strength matrices.
- Given a universe populated by 5 entities, *U* = {a,b,c,d,e}, let's define a 5x5 behavior matrix **B** where the element *b<sub>ij</sub>* indicates the interaction between the *i<sup>th</sup>* entity and the *j<sup>th</sup>* entity; *b<sub>ij</sub>* can assume the value: +1 if attraction, -1 if repulsion, 0 if neutral and -2, +2 if racing. *b<sub>ij</sub>* = *b<sub>ji</sub>* for all interaction except racing where *b<sub>ij</sub>* = -*b<sub>ji</sub>*
- The magnitude of an interaction between any two entities is proportional to the inverse of the square of their distance.

## Thoughts
What about *U* = {a,b,c,d}?
How about assigning the pure imaginary *i* to the racing interaction in the behavior matrix? This would allow for coefficents in the behavior matrix, i.e., coalesce the strength matrix in the behavior matrix. 
What about *-i*?
Racing could be modelled in one of two ways: given entities a and b, a will always be chased by b (or viceversa), or a and b flip flop chase giving rise to jitter. Vibration? Uncertainty?

## Implications
