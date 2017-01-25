# Rafael Luque's PhD Thesis notes

Notes and resources about my PhD only interesting for my future me.

Anyway, if you want to have a look then browse to [Rafael Luque's PhD Thesis](https://luque.github.io/phd-notes/)


# Overview

Industry statistics as a whole have failed to improve much since 1.968, when software
engineering and scientific management were introduced as means for resolving the
*software crisis*. Unfortunately abandoned projects, cost/time overruns, and bloated,
buggy software still dominate the landscape.

In spite of the efforts to mitigate this situation –- like XP, agile, software craftsmanship or
DDD--- the reality is that a usual software project stack involves an increasingly larger
number of programming languages, DSLs, frameworks, systems, tools, techniques and
processes, so it is a fact that the accidental complexity in our day-to-day software
projects is increasing to unbearable levels.

As we have conceived the software development we see as natural that once a
programmer has adquired enough knowledge about a problem domain and has conceived
a mental model for this domain we must wait for days or weeks before seeing a running
prototype and maybe months before a production-quality piece of software be ready.
We argue that this is an unacceptable consequence of our failed conception about the
software development activity, but not an inherent characteristic to the nature of software
development.

Nowadays the programming we have invented requires developers to jump continuously
between very different thinking levels –--like the conceptual, the source code or the
runtime levels--- trying to tracing back and forth between a domain concept and the code
that represents it, or between a defect and the affected source code or application
behaviour.

We claim that programming should be reconsidered as a mainly learning, exploring and
modeling activity and programmers should be able to capture their applications in an
executable domain model from which to obtain running prototypes efforlessly and immediately.
In the other hand, we have constrained the developers range of experiences in a tiny
subset of their intellectual capabilities: sitting at a desk, staring at a computer screen and
typing in a keyboard.

We think this is the wrong way to understand or think about a complex system. The right
way is to model it and explore it. So we need a new kind of media to create *dynamic
models* in real time in the middle of a modeling conversation with other developers or
domain experts.

We plan to build a new breed of **dynamic and fully conceptual modeling environment** in
order to enable programmers to work through every development stage –-analysis,
specification, design, implementation, deployment, evolution, etc.--- at the conceptual
level and explore their dynamic models as a thinking and learning tool.

# Precedentes and State of the Art

Software engineers are little concerned with the representation and processing of domain
knowledge and too much concerned with the solution space considerations.
Until now the focus has been on the least tractable representation of the software
problem, the code:
  * Extremely complex.
  * Hard to reason.
  * Hard to change, adapt or reuse.

The promise of object-oriented programming, and of programming languages themselves,
has yet to be fulfilled. That promise is to make plain to computers and to other
programmers the communication of the computational intentions of a programmer or a
team of programmers.

The failure of programming languages to do this is the result of a variety of failures to
take seriously the needs of people in programming rather than the needs of the computer
and the language/compiler/framework writer. To some degree, this failure can be
attributed to our failure to take seriously the needs of the programmer.

Several initiatives have appeared in the last years trying to tackle the software
complexity by focusing the team's attention on knowledge of the domain, picking apart
the most tricky, intricate problems with models, and shaping the software around those
models.

Perhaps the most prominent initiative is this direction is the Domain-Driven Design (DDD)
approach proposed by Eric Evans in 2004. Since then the DDD principles have been
slowly spreaded and adopted by an incipient community of practitioners. In spite of these
efforts most software projects continue both ignoring the relevance of the domain
knowledge or doing a poor previous modeling work withouth getting much real benefits at
the end.

In our opinion, DDD has laid out some useful concepts and practices. However we pretend
to take the DDD phylosophy and vaues until their last consequences in a kind of “Extreme
DDD”.

# Work hypothesis and Goals

It is safe to say that we all share a feeling of unease as far as the general state of
software is concerned: development is difficult, achieving correctness is difficult, levels of
software reuse are low, feedback loops are too large, etc.

In this thesis we explore some of the root causes of this apparent failure, and argue that
we need to be bolder in interpreting the original vision of object-orientation.

An argument can be made that the contemporary mainstream understanding of objects
is but a pale shadow of the original idea. Further, it can be argued that the mainstream
understanding of objects is, in practice, antithetical to the original intent.

We have identified the following working hypothesis:

  1. Programming is a representation of thought, so programmers should be able to
focus their attention on the problem space rather than the solution space.
Our current programming languages and tools appart us far from the domain
concepts. Even using those languages relatively bening –-like “pure” object-
oriented programming languages--- it is still required too much attention and
dedicated effort to the implementation details.
  2. We must get away from pencil-and-paper thinking and create a new dynamic
  medium for thinking and learning software.

Even when working on the computer, we still think in representations that were
invented for the medium of paper. Programming languages are written languages
and they were designed for writing.

What programmers could think is determined by the language they use and some
languages or media allow you to think "better" than others (Sapir–Whorf hypothesis
or “linguistic relativity”).

To understand or build complex systems, we need powerful new representations,
and we need a powerful new medium to work with these representations.
Our screens and keyboards are pencil and paper metaphors that constrained us to
mostly simple symbolic representations. However in the new medium
representations can draws on all the modes of understanding of the human brain
like visual, aural, tactile, kinesthetic and spatial.

Besides, this new media should also be dynamic because to understand a system
it's not enough to see one static representation or a variable at a time. You should
see the system running to be able to fully understand its dynamics.

In this thesis we argue that we should revisit our traditional programming paradigms to
address these issues.

We further propose a number of research challenges:

  1. Bring programmers inmerse into the domain model and avoid any kind of
distractions by working permanently within a “pure” conceptual modeling
environment. This conceptual environment must provide an holistic view of a
software system, incluyding all necessary aspects of function (behaviour),
interaction (system integrations and user interactions) and data (structure).
  2. Build a domain-aware runtime environment –-a kind of domain-aware virtual
machine--- able to interpret any valid conceptual model. This runtime environment
will enable a very fast feedback loop based on our work-in-progress models.
  3. Experiment with new media for working with dynamic and powerful
representations to think and learn about our software systems.

# Work plan

* 1st year: State of the art systematic review and made the required adjustments to this research
plan in based of the review results.
* 2nd year: Build first prototypes for a conceptual-modeling environment and the supporting domain-
aware virtual machine to run the models.
* 3rd year: Enhance the conceptual modeling environment with capabilities to build and show
powerful and real-time representations of the dynamic models.

# Bibliography

[1] The Death of Object-Oriented Programming. Oscar Nierstrasz. Software Composition
Group, University of Bern, Switzerland.

[2] Conceptual-Model Programming: A Manifesto. David W. Embley, Stephen W. Liddle,
and Oscar Pastor.

[3] The Humane Representation of Thought. Bret Victor.
http://worrydream.com/TheHumaneRepresentationOfThought/note.html

[4] Media for Thinking the Unthinkable. Bret Victor.
http://worrydream.com/MediaForThinkingTheUnthinkable/

[5] Patterns of Software: Tales from the Software Community. Richard P. Gabriel.

[6] Object Thinking. David West.

[7] Domain-Driven Design:Tackling Complexity in the Heart of Software. Eric Evans.

[8] Implementing Domain-Driven Design. Vernon Vaughn.

[9] Domain-Driven Design Reference: Definitions and Pattern Summaries. Eric Evans.

[10] The Nature of Software Development. Ron Jeffries.

[11] The CRC Card Book. David Bellin and Susan Suchman.
