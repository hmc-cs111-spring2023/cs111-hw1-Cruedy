# Language

_What is the name of the language? Link the name to its webpage
(if appropriate)._
_The name of the language I chose is VHDL_
_https://en.wikipedia.org/wiki/VHDL_
_I couldn't find it's website, so I linked the wikipedia page to it._

# Domain

_Describe the language's domain in five words._
_hardware, circuits, gates, Verilog adjacent_

# Computational model

_We don't yet have a great definition of the term "computational model".
For now, try to come up with the clearest, most concise explanation of
what happens when a program in your DSL runs._
_When a program in VHDL runs, it models how digital systems behave._

# DSL-ness

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_
_This language is not at all general because it's purely used for hardware design, so it is purely domain-specific._

# Internal or external?

_Is the language implemented as an internal or external DSL?
Justify your answer._
_VHDL is an internal DSL because it uses its own language to translate it into hardware._

# Host language

_What language(s) was (were) used to implement the DSL?_
_VHDL is its own host langauge. Verilog is also a host language for VHDL._

# Benefits

_Identify one potential benefit of the DSL: how is a programmer's life made
easier by the existence of this language?_
_VHDL allows users to describe logic circuits using text, so it makes it easier to describe an visualize a circuit._

# Drawbacks

_Identify one potential drawback of the DSL: what does a programmer
lose by using this DSL instead of a general-purpose language?_
_VHDL is very specific in its purpose, so a programmers can't use VHDL for anything outside of circuit design._