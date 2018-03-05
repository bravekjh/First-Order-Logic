# First-Order-Logic
Implemented First Order Logic Solver using Python.

  In first-order logic variables refer to things in the world and, furthermore, you can quantify over them – to talk about all of them or some of them without having to name them explicitly. 
	
#FOL syntax:
• Term
• Constant symbols: Fred, Japan, Bacterium39
• Variables: x, y, a
• Function symbol applied to one or more terms: F(x),
F(F(x)), Mother-of(John)
• Sentence
• A predicate symbol applied to zero or more terms:
on(a,b), sister(Jane, Joan), sister(Mother-of(John), Jane),
its-raining()
• t1=t2
• For v a variable and Φ a sentence, then ∀v.Φ and ∃v.Φ are
sentences. • Closure under sentential operators: Æ v → ¬ ( )

#Basic FOL Semantics
Denotation of terms (naming)
• I(Fred) if Fred is constant, then given
• I(x) undefined
• I(F(term)) I(F)(I(term))
•|=I P(t1, …, tn) iff <I(t1), …, I(tn)> ∈ I(P)

brother(John, Joe)??
• I(John) = [an element of U]
• I(Joe) = [an element of U]
• I(brother) = {< < >, <…,…>, … }
• |=I brother(John, Joe) 
