# soutient.github.io
My package on hackage.haskell.org:
https://hackage.haskell.org/package/TrivialMonadWithUnitType

$\color{#58A6FF}{My package on \text{ hackage.haskell.org}$

```yaml
● Did you know: What is a monad? The best explanation I've heard is something like this: "In 1940, Turing was puzzled by the 
                cracking of the Nazi Enigma cipher. He cleverly guessed the cipher error. A letter of the Latin alphabet used
                in the encoding - cannot be itself when pressed. This property in Haskell is designated as the famous "return"
                in the monad, that is, the encoding must be without "return" to itself! The Germans implemented "return".
                Turing understood this, and the decoding method was based on successive elimination of letter by letter."
                Now let's get back to the answer to the question. A monad is what Turing used long before monads were officially
                invented, without knowing anything about them! Appreciate his talent! Nowadays, this topic is controversial, 
                probably because of the "ban on hacking".
                But I have never heard a simpler and more precise explanation of the essence of monads.
```

```diff
● Semantics Lesson: A good teacher can't tell "and things didn't go as planned", provided their students are well-motivated, of course. Here's a real-life example from my experience as a "Haskell
              formal methods engineer" when I explained this to team members: Spatial Thinking. 1) Take a pencil or pen in your left hand. 2) Point to the left end of the pencil with the index
              finger of your right hand. 3) Say out loud: "Here are the rules." 4) Then point to the right end of the pencil and say out loud: "And here are the exceptions to the rules.
              Exceptions are always the opposite of the rules." 5) Then point to the left end of the pencil and say out loud: "But exceptions only prove the rules." 6) Consider: Why is there only
              one pencil,yet the statements it represents are logically opposed, yet related? Now you will understand what Haskell code is. Let's return to the pencil. Imagine the left end of a
              pencil is the English letter "A" (a) and the right end is the letter "B" (b). This means you can write all the pencil statements in their proper order. a="Rules" b="Exceptions to the
              rules." Written down, it looks like this: a -> b -> a. The meaning of the structure is clear and preserved in the entry!
              This will even become clear to teenagers, won't it?
```
```yaml
● Research project: Ring‑like structures, operations and equations without explicit quantifiers:
              An algebraic theory is specified by a signature — a set of operation symbols with fixed arities, such
              as a constant Oₚ, a constant 1ₚ, a unary operation —, and two binary operations + and − acting on
              a single carrier. Terms are built inductively from variables and these operations; every application
              of an operation to existing terms yields a new term. The axioms of the theory are equations t₁ = t₂
              between such terms, with no explicit quantifiers; uni-quantification over the variables is understood.
```
