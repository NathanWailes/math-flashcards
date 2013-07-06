#Teach Yourself Mathematical Groups

##Preface
Who is this book intended for?||People working on their own, or with limited access to other kinds of help.||

What is pure mathematics about?||Proving things.||

##Proof

###Main Ideas

When is arguing from particular cases sufficient to prove something?||When you examine every possible case.||

Suppose you know that "If P then Q", and you also know that P is false.  What do you know about Q?||Nothing||

Prove that the sum of two consecutive whole numbers is odd

Prove that if a and b are even, then a + b is even.

What is a proof by contradiction?

Prove that if a^2 is an even number, then a is an even number.||This is an example of a proof that benefits from an indirect approach (in this case, proof by contradiction). Suppose a is an odd number. Then a can be written in the form a = 2n + 1, where n is a whole number. Then a^2 = (2n+1)^2, that is a^2 = 4n^2 + 4n + 1 = 2(2n^2 + 2n) + 1, so a^2 is 1 more than a multiple of 2, and therefore odd. But you are given that a^2 is an even number, so you have arrived at a contradiction. Therefore the supposition that a is an odd number is untenable. Therefore a is an even number.||

Prove that [$$]\sqrt{2}[/$$] is irrational.

Prove that there is no greatest prime number.

Prove that the product mn of two numbers m and n is even if, and only if, at least one of m and n is even.

What does it mean to say that two statements are "equivalent"?

What does it mean to say that "P is a sufficient condition for Q"?

What does it mean to say that "P is a necessary condition for Q"?

What does it mean to say that something is "a necessary and sufficient condition for" something else?

How do you prove results which involve "if, and only if"?

How do you prove that two statements are equivalent?

What is denary notation?

Prove that a necessary and sufficient condition for a number N expressed in denary notation to be divisible by 3 is that the sum of the digits of N is divisible by 3.

What do you need to be careful of when reading mathematicians' use of the word "if"?||They sometimes use the word "if" when they mean "if and only if".

How do you prove a statement false?

What's a counterexample?

###Exercises
1. Prove that the product of two odd numbers is odd.
2. Use proof by contradiction to show that it is not possible to find positive whole numbers m and n such that [$$]m^{2} - n^{2} = 6[/$$].

3. Prove that a number plus its square is always even.

4. Fig 1.2 shows four playing cards. Two are face up, and two are face down. Each card has either a chequered pattern or a striped pattern on its reverse side. Which cards would you need to turn over in order to determine whether the statement "Each card with a striped pattern on its reverse side is a diamond", is true?

5. Return to the proof in Example 1.2.2 that [$$]\sqrt{2}[/$$] is irrational. Where does this proof break down if you replace 2 by 4?

6.Prove that the statement 'if x < 1 then [$$]x^{2}[/$$] < 1' concerning real numbers, is false.

7. Prove that if [$$]\sqrt{a + b} = \sqrt{a} + \sqrt{b}[/$$], then a = 0 or b = 0.

8. Prove that the product pq of two integers p and q is odd if, and only if, p and q are both odd.

9. Prove that a necessary and sufficient condition for an integer N expressed in denary notation to be divisible by 9 is that 9 divides the sum of the digits of N.

##Sets

###Main Ideas

###Exercises

1. Which of the following sets is well defined?(1) The set of prime numbers.<np>(2) People in the world whose birthday is on 1 April.<np>(3) [$$]A = \{x=\mathbb{Z} : x\:is\:the\:digit\:in\:the\:1000th\: place\:in\:the\:decimal\:expansion\:of\:\pi\}[/$$]

2. Mark each of the following statements true or false.<np>(1)[$$]0\in \mathbb{Q}[/$$]<np>[$$]0\in \mathbb{Z}^{*}[/$$]<np>(3) A set may have just one element.

3. List the members of the set [$$]P = \{x \in \mathbb{Z} : |x| < 3 \}[/$$]. Does [$$]-3 \in P[/$$] ?

4. Explain why [$$]\mathbb{Z} \subseteq \mathbb{Q}[/$$].

5. The notation [$$]2 \mathbb{Z}[/$$] is used to mean the set [$$]\{ 2x : x \in \mathbb{Z} \}[/$$]. Decide whether [$$]2 \mathbb{Z} \subseteq \mathbb{Z}[/$$] or [$$]\mathbb{Z} \subseteq 2 \mathbb{Z}[/$$] or neither or both is true.

6. A, B, and C are any sets. Prove that the statements [$$]A \cup B = B[/$$] and [$$]A \cap B = A[/$$] are equivalent.

7. A, B, and C are any sets. Prove that [$$]A \cap \left (B \cup C \right ) = \left (A \cap B \right ) \cup \left (A \cap C \right )[/$$].

8. Mark each of the following statements true or false for general sets A and B.<np>(1). [$$]\varnothing \subseteq A[/$$]<np>(2). [$$]A \subseteq \left (A \cap B \right )[/$$]<np>(3). [$$]A \subseteq \left (A \cup B \right )[/$$]<np>(4). [$$]A \subseteq A[/$$]<np>(5). [$$]A \in A[/$$]<np>(6). A is a proper subset of A.<np>(7). [$$]\left (A /cup B \right ) \subseteq \left ( A \cap B \right )[/$$]

9. Let [$$]A = \left { x \in \mathbb{R} : |x| < 3 \right }[/$$] and [$$]B = \left { x \in \mathbb{R} : | x - 1 | < 2 \right }[/$$]. Prove that [$$]B \subseteq A[/$$].

10. Let A be a set with n elements. Prove that A has [$$]2^{n}[/$$] subsets.

##Binary Operations

###Main Ideas

###Exercises

1. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{Z}, \times \right )[/$$]

2. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np>[$$]\left ( \mathbb{N}, \lozenge \right )[/$$], where [$$]a \lozenge b = a^{b}[/$$]

3. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{R}, \div \right )[/$$]

4. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{Z}, \lozenge \right )[/$$]

5. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{Z}, \circ \right )[/$$], where [$$]a \circ b = a[/$$] for all [$$]a, b \in \mathbb{Z}[/$$]

6. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \left {1, 3, 7, 9 \right }, \circ \right )[/$$] where [$$]a \circ b[/$$] is the remainder when [$$]a \times b[/$$] is divided by 10

7. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{R}, \circ \right )[/$$], where [$$]a \circ b = 0[/$$] for all [$$]a, b \in \mathbb{R}[/$$]

8. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{C}, \circ \right )[/$$], where [$$]a \circ b = | a - b |[/$$]

9. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{M}, \times \right )[/$$], where [$$]\mathbb{M}[/$$] is the set of matrices, and [$$]\times[/$$] is multiplication of matrices

10. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{M}, \circ \right )[/$$], where [$$]\mathbb{M}[/$$] is the set of [$$]2 \times 2[/$$] matrices and [$$]A \circ B[/$$] is given by [$$]A \circ B = det(A - B)[/$$]

11. Which of the given operations are binary operations on the given set? For each operation which is not a binary operation, give one reasons why it is not a binary operation:<np><np>[$$]\left ( \mathbb{R}, \lozenge \right )[/$$], where [$$]a \lozenge b = a^{b}[/$$]

##Integers

###Main Ideas

###Exercises

1. Find a counterexample to show that the result in Theorem 2 is not true if m and n are not relatively prime.

2. Find a counterexample to show that the result in Theorem 3 is not true if m and n are relatively primne.

3-1. Which of the following statements are true and which are false?<np>(1) [$$]7  \equiv 9 (mod\;2)[/$$]

3-2. Which of the following statements are true and which are false?(1) [$$]3  \equiv -5 (mod\;4)[/$$]

3-3. Which of the following statements are true and which are false?<np>(1) [$$]5  \not\equiv -13 (mod\;3)[/$$]

4-1. Carry out the following calculation:<np>[$$]2 + 2 \;in\; \mathbb{Z}_{3}[/$$]

4-2. Carry out the following calculation:<np>[$$]3 + 5 \;in\; \mathbb{Z}_{8}[/$$]

4-3. Carry out the following calculation:<np>[$$]7 \times 9 \;in\; \mathbb{Z}_{10}[/$$]

4-4. Carry out the following calculation:<np>[$$]6 \times 2 \;in\; \mathbb{Z}_{12}[/$$]

5. Solve the equation [$$]x^{2} \equiv 3 (mod\;11)[/$$].

6. Let a and b be any two positive integers, and let h be their highest common factor and l be their least common multiple. Prove that ab = hl.<np><np>Hint: Observe that if [$$]a = p^{r_{1}}_{1} ... p^{r_{n}}_{n}[/$$] and [$$]b = p^{s_{1}}_{1} ... p^{s_{n}}_{n}[/$$] then [$$]h = p^{\alpha_{1}}_{1} ... p^{\alpha_{n}}_{n}[/$$] and [$$]l = p^{\beta_{1}}_{1} ... p^{\beta_{n}}_{n}[/$$] where [$$]\alpha = min \left { r_{i}, s_{i} \right }, i = 1, ..., n[/$$] and [$$]\beta_{i} = max { r_{i}, s_{i} \right }, i = 1, ..., n[/$$].

##Groups

###Main Ideas

###Exercises

1. Write out a table showing the set {1, 5, 7, 11} under the operation of multiplication modulo 12. Is it the table of a group?

2. The notation [$$]\mathbb{R} - \left { 0, 1 \right }[/$$] means the set [$$]\mathbb{R}[/$$] without the numbers 0 and 1. Consider the set of functions [$$]\left { I, F, G, H, K, L \right }[/$$] defined on the set [$$]\mathbb{R} - \left { 0, 1\right }[/$$] defined by [$$]I(x) = x, F(x) = 1 / (1-x), G(x) = (x-1) / x, H(x) = 1-x, K(x) = x/(x-1)[/$$] and [$$]L(x) = 1/x[/$$]. Construct a table to show that composition of functions is a binary operation on this set, and that the set [$$]\left { I, F, G, H, K, L \right }[/$$] together with the operation of composition is a group. (Assume that composition of functions is associative; this is actually proved in Chapter 10, Theorem 32.)

3. Show that the set [$$]\mathbb{R} - \left {-1\right }[/$$], together with the operation [$$]\circ[/$$], given by [$$]x \circ y = x + y + xy[/$$], is a group. Which is the identity element for the group? Find an expression for [$$]x^{-1}[/$$] in terms of x. (Note: the notation [$$]\mathbb{R} - \left {-1\right }[/$$] means the set [$$]\mathbb{R}[/$$] with the number -1 deleted.

4. Let R be a rectangle which is not a square. Follow the working of Example 5.2.2, and define a set of symmetries for R. Draw up a group table for these symmetries. This group is called the Vierergruppe, the four-group, and denoted by V.

5. Write out a table for the set [$$]\left {1, 3, 7, 9\right }[/$$] under the operation multiplication modulo 10.

6. Write out a table for the set [$$]\left {1, 2, 4, 8\right }[/$$] under the operation multiplication modulo 15. Show that the table has the same structure as the table in question 5, with the elements re-named.

7. Let G be a group, and let a be an element of G. Prove that if [$$]a^{2} = a[/$$], then [$$]a = e[/$$].

8. Let G be a group. Prove that if [$$]a^{2} = e[/$$] for all [$$]a \in G[/$$], then G is abelian.

9-1. Is the following a group? Give reasons for your answer.<np>(1) The set of all odd integers under addition.

9-2. Is the following a group? Give reasons for your answer.<np>(2) The set of all integers of the form [$$]2^{m}5^{n} \left ( m, n \in \mathbb{Z} \right )[/$$], under multiplication.

9-3. Is the following a group? Give reasons for your answer.<np>(3) The set of all [$$]2 \times 2[/$$] matrices of the form [$$]\begin{pmatrix} a & b\\ 0 & 0 \end{pmatrix}[/$$], where [$$]a, b \in \mathbb{R}[/$$], under matrix multiplication.

9-4. Is the following a group? Give reasons for your answer.<np>(4) The set of all [$$]2 \times 2[/$$] matrices of the form [$$]\begin{pmatrix} a & 0\\ b & c \end{pmatrix}[/$$], where [$$]a, b \in \mathbb{R}, a \neq 0, c \neq 0[/$$], and [$$]b \in \mathbb{Q}[/$$] under matrix multiplication.

10. Show that the matrices [$$]\begin{Bmatrix} \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}, \begin{pmatrix} -1 & 0 \\ 0 & 1 \end{pmatrix}, \begin{pmatrix} 1 & 0 \\ 0 & -1 \end{pmatrix}, \begin{pmatrix} -1 & 0 \\ 0 & -1 \end{pmatrix} \end{Bmatrix}[/$$] form a group under matrix multiplication.

11-1. Prove the index rules for all [$$]s, t \in \mathbb{Z}[/$$]:<np>(1) [$$]x^{s}x^{t} = x^{s + t}[/$$]

11-2. Prove the index rules for all [$$]s, t \in \mathbb{Z}[/$$]:<np>(2) [$$]\left (x^{s}\right )^{t} = x^{st}[/$$]

11-3. Prove the index rules for all [$$]s, t \in \mathbb{Z}[/$$]:<np>(3) [$$]x^{-s} = \left (x^{s} \right )^{-1} = \left ( x^{-1} \right ) ^{s}[/$$]

12-1. Mark the following statement true or false.<np>(1) Every element of a group has an inverse.

12-2. Mark the following statement true or false.<np>(2) It is possible for an element of a group to be its own inverse.

12-3. Mark the following statement true or false.<np>(3) It is not possible for a group to be infinite.

12-4. Mark the following statement true or false.<np>(4) It is not possible for a group to consist of a single element.

12-5. Mark the following statement true or false.<np>(5) No element of a group has order 1.

12-6. Mark the following statement true or false.<np>(6) If the order of an element x is n and [$$]x^{N} = e[/$$], then N divides n.

12-7. Mark the following statement true or false.<np>(7) All groups are abelian.

13. Prove the following generalization of Theorem 19. Let x be an element of a group G, and let the order of x be n. If h is the highest common factor of n and s, then x^{s} has order \frac{n}{h}.

##Subgroups

###Main Ideas

###Exercises

1. Find all the subgroups of the group shown in Fig. 5.1. Which of the subgroups is a proper subgroup?

2. Let G be an abelian group. Prove that the set of elements of order 2, together with the identity element, that is [$$]H = \left {a \in G : a^{2} = e \right }[/$$], is a subgroup of G.

3. Let G be an abelian group, and let [$$]H = \left {a \in G : a^{3} = e \right }[/$$]. Prove that H is a subgroup of G.

4. Let G be an abelian group. Prove that the set of elements of finite order, [$$]H = \left {a \in G : a^{n} = e, some n \right }[/$$] is a subgroup of G.

5-1. Mark the following statement true or false:<np>(1) The group in Example 5.5.2 has six subgroups.

5-2. Mark the following statement true or false:<np>(2) A non-abelian group can have a proper abelian group.

5-3. Mark the following statement true or false:<np>(3) An infinite group cannot have a finite subgroup.

5-4. Mark the following statement true or false:<np>(4) An infinite proper subgroup of an infinite group must be abelian.

5-5. Mark the following statement true or false:<np>(5) All groups have proper subgroups.||False. The null set cannot have a proper subgroup.||

6. Let A and B be subgroups of a group G. Prove that [$$]A \cap B[/$$] is a subgroup of G. Is [$$]A \cup B[/$$] a subgroup? Justify your answer.

7. Let H be a subgroup of a group G, and let [$$]a \in H[/$$]. Prove that [$$]\left \langle a \right \rangle \subseteq H[/$$].

8. Let H be a subset of a group G. Prove that H is a subgroup of G if, and only if, H is non-empty and [$$]xy^{-1} \in H[/$$] for all [$$]x,y \in H[/$$]. (This is an alternative to Theorem 21; a more compact criterion for a subgroup.)

9. Let G be a group, and let g be a fixed element of G. Prove that [$$]H = \left { x \in G : gx = xg \right }[/$$] is a subgroup of G.

10. Let G be a group with a subgroup K, and let H be a subgroup of K. Prove that H is a subgroup of G.



##Cyclic groups

###Main Ideas

###Exercises

1. Prove that the group [$$]\left ( \left {2, 4, 6, 8 \right }, \times mod 10 \right )[/$$], in Fig. 5.1, is cyclic.

2. Find four proper subgroups of a cyclic group of order 12.

3. Which elements of the cyclic group [$$]\mathbb{Z_{6}}[/$$] are generators?

4-1. Mark the following statement true or false:<np>(1) Every cyclic group has a generator.

4-2. Mark the following statement true or false:<np>(2) Every member of every cyclic group is a generator.

4-3. Mark the following statement true or false:<np>(3) A cyclic group can have more than one generator.

4-4. Mark the following statement true or false:<np>(4) A cyclic group can have a non-cyclic subgroup.

4-5. Mark the following statement true or false:<np>(5) Every cyclic group is abelian.

4-6. Mark the following statement true or false:<np>(6) [$$]\left ( \mathbb{Z}, +\right )[/$$] is not cyclic.

4-7. Mark the following statement true or false:<np>(7) [$$]\left ( \mathbb{C^{*}}, \times \right )[/$$] is cyclic.

5. Prove that [$$]\left ( \mathbb{R}, \times \right )[/$$] is not a cyclic group.

6-1. Is the following group cyclic? Give reasons.<np><np> (1) The group {1, 5, 7, 11}, under multiplication mod 12.

6-2. Is the following group cyclic? Give reasons.<np><np> (2) The additive group [$$]\mathbb{Q}[/$$] of rational numbers.

6-3. Is the following group cyclic? Give reasons.<np><np> (3) The circle group [$$]T = \left { z \in \mathbb{C} : |z| = 1 \right }[/$$] under multiplication of complex numbers.

6-4. Is the following group cyclic? Give reasons.<np><np> (4) [$$]\mathbb{Z} \left [i \right ] = \left {a + bi : a, b \in \mathbb{Z} \right }[/$$]



##Products of groups

###Main Ideas

###Exercises

1-1. Mark the following statement true or false:<np>(1) The set [$$]A \times B[/$$] always has a finite number of elements.

1-2. Mark the following statement true or false:<np>(2) The set [$$]\mathbb{Z}_{m} \times \mathbb{Z}_{n}[/$$] has mn elements.

1-3. Mark the following statement true or false:<np>(3) If the group G has m elements, and the group H has n elements, then [$$]G \times H[/$$] has mn elements.

1-4. Mark the following statement true or false:<np>(4) You cannot form the direct product [$$]G \times H[/$$] if G is infinite.

2. Write a definition for the set [$$]A \times B \times C[/$$]. Use your definition to write out the elements of [$$]\mathbb{Z}_{2} \times \mathbb{Z}_{2} \times \mathbb{Z}_{2}[/$$].

3. Prove that [$$]\mathbb{Z} \times \mathbb{Z} \subseteq \mathbb{Q} \times \mathbb{Q}[/$$].

4. You can interpret the set [$$]\mathbb{R} \times \mathbb{R}[/$$] as all the points on an infinite sheet of paper. How would you interpret [$$]\mathbb{Z} \times \mathbb{Z}[/$$]?

5. Write out a group table for [$$]\mathbb{Z}_{2} \times \mathbb{Z}_{2}[/$$].

6. Prove that if G and H are abelian, then G \times H is also abelian.

7. Prove that if G is not abelian, then G \times H is not abelian.

8. Write out a group table for [$$]\mathbb{Z}_{2} \times \mathbb{Z}_{3}[/$$]. Is it the same group as [$$]\mathbb{Z}_{3} \times \mathbb{Z}_{2}[/$$]?

9. Show that (1, 1) is a generator for [$$]\mathbb{Z}_{3} \times \mathbb{Z}_{2}[/$$]. Are there any other generators?

10. Prove that if [$$](x,y) \in G \times H[/$$] has order n in [$$]G \times H[/$$], then the order of [$$]x \in G[/$$] divides n, and the order of [$$]h \in H[/$$] divides n.



##Functions

###Main Ideas

###Exercises

1. Prove that [$$]f : \mathbb{R} \rightarrow \mathbb{R}[/$$] defined by f(x) = sin (x) is neither an injection nor a surjection

2. Give an example of a function [$$]f : \mathbb{R} \rightarrow \mathbb{R}[/$$] which is an injection, but not a surjection.

3. Give an example of a function [$$]f : \mathbb{R} \rightarrow \mathbb{R}[/$$] which is a surjection, but not an injection.

4-1. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(1) f(x) = x^{2}

4-2. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(2) f(x) = x^{3}

4-3. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(3) f(x) = \frac{1}{x}

4-4. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(4) f(x) = cos(x)

4-5. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(5) f(x) = tan(x)

4-6. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(6) f(x) = e^{x}

4-7. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(7) f(x) = |x|

4-8. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(8) f(x) = int(x) (int(x) is the largest integer \leq x.)

4-9. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(9) f(x) = \sqrt{x}

4-10. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(10) f(x) = x + 1

4-11. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(11) f(x) = sin^{-1}(x)

4-12. In the following example the domain is \mathbb{R} and the codomain is \mathbb{R}. Decide whether the statement is the definition of a function. If it is a function, decide whether it is injective, and whether it is surjective. Be able to justify your answer.<np><np>(12) f(x) is the smallest real number greater than x.

5.

6.

7.

8.

9.

10.

11.



##Composition of functions

###Main Ideas

###Exercises

1.

2.

3.

4.



##Isomorphisms

###Main Ideas

###Exercises

1.

2.

3.

4.

5.

6.

7.

8.

9.

10.

11.

12.

13.

14.

15.

16.

17.

18.

19.

20.

21.

22.



##Permutations

###Main Ideas

###Exercises

1.

2.

3.

4.

5.

6.

7.

8.

9.

10.

11.

12.

13.

14.

15.



##Dihedral groups

###Main Ideas

###Exercises

1.

2.

3.

4.

5.

6.



##Cosets

###Main Ideas

###Exercises

1.

2.

3.

4.

5.

6.

7.

8.

9.

10.

11.



##Groups of orders up to 8

###Main Ideas

###Exercises

1.

##Equivalence relations

###Main Ideas

###Exercises

1.

2.

3.

4.

5.

6.

7.

8.

9.

10.

11.



##Quotient groups

###Main Ideas

###Exercises

1.

2.

3.

4.

5.

6.

7.

8.

9.



##Homomorphisms

###Main Ideas

###Exercises

1.

2.

3.

4.

5.

6.



##The first isomorphism theorem

###Main Ideas

###Exercises

1.

2.

3.

4.

5.