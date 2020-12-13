# Welcome to my Maths Blog

### Kolmogorov–Arnold representation theorem
##### 29-04-2020
From [Wikipedia page](https://en.wikipedia.org/wiki/Kolmogorov%E2%80%93Arnold_representation_theorem) :

>_The Kolmogorov–Arnold representation theorem (or superposition theorem) states that every multivariate continuous function can be represented as a superposition of continuous functions of one variable. It solved a more constrained, yet more general form of Hilbert's thirteenth problem._
>
>_The works of Andrey Kolmogorov and Vladimir Arnold established that if f is a multivariate continuous function, then f can be written as a finite composition of continuous functions of a single variable and the binary operation of addition. More specifically,_
>
>![Kolmogorov–Arnold representation formula](https://wikimedia.org/api/rest_v1/media/math/render/svg/7fb7e8cc17b243a4346ff1b710ccde6ec47540ea)
>
>_In a sense, they showed that the only true multivariate function is the sum, since every other function can be written using univariate functions and summing._

Professor Guiseppe Carleo mentioned in a [talk](https://youtu.be/90OZoet_1CU?t=639) that this can be said to be the first use of the concept behind neural networks, i.e. functions applied to linear combination of results of functions can be a very compact way of expressing any multivariate functon. 


### Monster group and the Moon shine Conjecture
#### 23-08-2020
[link to the quantamagazine article](https://www.quantamagazine.org/mathematicians-chase-moonshine-string-theory-connections-20150312/)
The above article quotes Shamit Kachru, a string theorist at Stanford University, 
> “Any time you hear about a striking result in number theory, there’s a high chance that it’s really a statement about modular forms.”

### Resolution of conflict
#### 05-09-2020
Read the answer by Bill Thurston. Also, the article that referred to the MathOverfow question.
https://mathoverflow.net/questions/43690/whats-a-mathematician-to-do 
https://www.quantamagazine.org/emily-riehl-conducts-the-mathematical-orchestra-from-the-middle-20200902/

### ALgebraic Structures : a CS analogy
#### 13-12-2020
https://www.cs.yale.edu/homes/aspnes/pinewiki/AlgebraicStructures.html
The various standard algebras are _abstractions that allow us to reason_ about lots of different situations at the same time. _From the perspective of computer science, they are like base classes high up in an object-oriented type hierarchy_, that provide minimal features common to all the classes that inherit from them without specifying the details. So for example in a monoid, where the single operation is associative and there is an identity e that satisfies the equations ae = a and ea = a, we can prove that there can't be a second identity e', since if ae' = a for all a we have ee' = e (from ea = a) and ee' = e' (from ae' = a), giving e = e'. This tells use that we can't extend ℤ by adding a second copy of 0 or the set of n×n matrices by adding a second copy of I; but we didn't need to know anything specific about either structure to know this. 
