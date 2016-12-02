%title: zepto 0.9.6
%author: hellerve
%date: 2016-12-15

-> # Release Party
-> # Version 0.9.6

-> # i.e. We're not ready yet

---

-> # What is zepto again?

-> a Lisp - more precisely, a Scheme

~~~~ {#mycode .scheme}
(define (transpose idx elem inpt)
  "inserts an element <par>elem</par> into a collection
   <par>inpt</par> at index <par>idx</par>. Collapses
   nesting."
  (let (((before after) (split-at idx inpt)))
    (++ before elem after)))
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-> Aims to be feature-rich and pragmatic

---

-> # Core values

-> ## Naïveté
- If there is a simple way, do it that way
- If there is a trade-off between complexity and features,
  aim for less features


-> Example:
- Generic methods defined in zepto
- Just a big(?) hashmap of protocols and their implementations

---

-> # Core values

-> ## Malleability
- Make everything pluggable.
  - You want to change the syntax? Sure.
  - You want to change the backend? Go ahead.
  - None of the components in the toolchain should impact any other

-> Example:
- Frontend has a system for plugging in custom parsers
- Should return zepto data structures
- Implemented in zepto

---

-> # Core values

-> ## Friendlyness
- We make mistakes
- We admit mistakes
- We fix mistakes

-> Example:
- Change policy comprised of RFCs
- More than half of them address
  - inconveniences introduced in the early stages of zepto
  - problems with the UX

---

-> # Stop!

-> # Demo time!

                   ,
                  /(  ___________
                 |  >:===========`
                  )(
                  ""
                (here be a thumb)

---

-> # Thanks.

-> # You've been great.

-> # Any questions?