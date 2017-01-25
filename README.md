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
  - Extremely complex.
  - Hard to reason about.ESCUELA
  - Hard to change, adapt or reuse.

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

