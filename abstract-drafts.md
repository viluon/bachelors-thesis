# Abstract drafts

Here are a few ideas for the abstract.

---

> Lazy evaluation is a potentially powerful implementation strategy for
> non-strict languages, freeing the programmer to focus on what a program means
> rather than on how it is computed. Laziness naturally accommodates
> user-defined control flow and evaluates only the required subset of a given
> program in a demand-driven manner. However, delayed evaluation makes
> complexity analysis challenging and can lead to hard-to-predict memory
> behaviour. To better understand the trade-offs laziness offers and how it is
> used in practical scenarios, we design a dynamic tracing plugin for the
> Glasgow Haskell Compiler, implement a proof of concept, and demonstrate its
> ability to record crucial information about the use of laziness in simple
> Haskell programs.

---

> Lazy evaluation is at once convenient, efficient, and bloated. Its natural
> support for infinite data structures and user-defined control flow, as well
> as the possibility of avoiding unnecessary computation, make it a compelling
> evaluation strategy. Its memory overhead does not. An ideal compiler would
> only introduce call-by-need in places where it is absolutely necessary to
> implement non-strict semantics. While the Glasgow Haskell Compiler is
> state-of-the-art, little is known about the pitfalls of its static strictness
> analyser. Understanding how is laziness used in practice requires dynamic
> analysis. We design and implement a compiler plugin suitable for
> laziness-oriented dynamic tracing, laying the groundwork for a future study.

---

> Haskell is a unique language in its successful implementation of non-strict
> semantics. However, the unarguable convenience and abstraction capabilities
> of non-strictness are hampered by the runtime overhead and hard-to-predict
> behaviour of call-by-need, which begs the question -- is laziness worth it?
> Untangling this problem demands an understanding of the use of laziness in
> the wild, which is the motivation of this work. We develop a plugin for the
> Glasgow Haskell Compiler designed to capture real-world usage data to fill in
> the gaps in static analysis.

---

