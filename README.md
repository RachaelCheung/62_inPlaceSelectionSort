# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by three times. The number of elements tripled,
so the number of comparisons needed would triple respectively. 
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by three times. In the constructor, the reigning champ
algorithm is invoked once for each element in the input, so if 
the number of elements triples, the invocations would triple respectively as well.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by three times. As noted in the previous question, the 
number of invocations will triple, so the time required for the sort would triple respectively. 
[Justify, in about 2 sentences.]
