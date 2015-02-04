### Zachary May
### CS 616, Spring 2015
### Reaction Essay \#2

When working on the TeAL experiment in class, I found myself quite confused.
This was probably to be expected: I was part of the control group, not working
with Almost TeAL. However, I wonder if the Almost TeAL approach might not be
excessive.

Even having read the initial paper [1], the quick introductory document we
received did not leave me with a good grasp on how to *use* the language.
Consider the example from [1]:

*connect(serA, nodeA)* **causes** *connected(nodeA, serA)* **if** *systemOn*
    
While the paper is explicit that the first "slot" in a **causes-if** expression
must be an action and the other two are lists of fluents, it was difficult to
extract those "type" rules from the examples in the introductory document, which
was all that was available while working on the exercises.

Similarly, it was difficult really keep track the difference between actions
and fluents since they are syntactically identical. In isolation, is  *connect(serA, nodeA)* 
an action or a fluent? Even something as simple as saying that actions should
be prepended with an exclamation point might be helpful, e.g.: *!connect(serA, nodeA)*.

More problems come up when we move to temporal constraints. After a closer re-reading of
the paper, I think I better understand their role in the language (standing alongside but
separate from the *AD* expressions), but between the paper and the introductory document,
I still do not have much of a grasp on how to use TeAL to translate real requirements!

So, in the end, I wonder if the approach of using intermediate tools like Almost TeAL
could be obviated with better training materials and possibly some syntactic changes
to clear up confusion.

### References

[1] Li, Wenbin, Jane Huffman Hayes, and Miroslaw Truszczynski. Temporal Action Language (TAL):
A Controlled Language for Consistency Checking of Natural Language Temporal Requirements. 2012.
