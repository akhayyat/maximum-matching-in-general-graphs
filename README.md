A matching *M* in *G* is a subset of its edges such that no two meet
the same vertex. A *maximum matching* is a matching of maximum
cardinality. That is, *M* is a maximum matching if no matching on *G*
contains more edges than *M*. A maximum matching is not necessarily
unique.

*Berge* proposed constructing a maximum matching by exhaustively
searching for augmenting paths, which *Edmonds* argues is of
exponential order. Edmonds then proposed the first polynomial time
maximum matching algorithm using the same augmenting path method. His
algorithm is O(n<sup>4</sup>). *Gabow* then proposed a ``careful
implementation'' of Edmonds algorithm that improves the algorithm time
to O(n<sup>3</sup>). *Vazirani*, *Blum*, and *Gabow* used different
techniques to achieve the best known algorithms for solving the
maximum matching problem for general non-bipartite graphs. The three
algorithms are of complexity O(m n), which gives O(n<sup>2.5</sup>)
for dense graphs.

These LaTeX/Beamer slides illustrate these algorithms. The rendered
slides are available on [Slide Share][1] and [Speaker Deck][2].

[1]: http://www.slideshare.net/akhayyat/maximum-matching-in-general-graphs
[2]: https://speakerdeck.com/akhayyat/maximum-matching-in-general-graphs
