# Research Review

The STRIPS, ADL and PDDL are all specification languages, they differ in syntax and the power to model system. The evolution and history of the languages are summarized as below.

In 1971, STRIPS (Stanford Research Institute Problem Solver)[1] developed by Richard Fikes and Nils Nilsson, attempting to provide a sequence of operators that can be applied to a an initial world model in order to achieve a goal world-model formula to be true by representing these world-models, in a world-model space, through a set of first-order predicates as calculus formula, the description only applies to the definition of the language and not the planner solver itself.

Later in 1978, Edwin Pednault proposed ADL as an advancement of STRIPT. ADL[2] - an action language - in some way extends STRIPS by allowing the effect of an operation to be conditional, basically allows goal (supporting disjunctions) and effects to be conditionals, in other words, supporting variables, is open-world whereas STRIPS uses the close-world assumption, the purpose of STRIPS might not suitable for modeling actions in many real world applications, ADL lies between STRIPS and _situation calculus_, it is flexible enough to represent problems but restrictive enough to allow efficient algorithms to be implemented.

Drew McDermott and his colleagues in 1998 developed PDDL[3] as an attempt to standardize the way how planning problems are represented supporting propositional logic, this language was used and developed with the International Planning Competition (IPC) in mind, giving room to improve it with each competition. Exists several standards or official version being the latest 3.1 at this moment, supporting BNF (Backus–Naur Form) syntax definition.

There is variations of PDDL, but the core of is still the same, it is the relation to having a fully expressive language to represent real world problems but restrictive enough to implement them, it is not surprising if new and better languages will be developed as this field is in constant evolution as new algorithms require it.

---

Refrences:
[1]  STRIPS: A New Approach to the Application of Theorem Proving to Problem Solving' Richard E. Fikes, Nils J. Nilsson - IJCAI, Imperial College, London, England, September 1-3, 1971. [^2]: Russell, S, and P Norvig. Artificial Intelligence: A Modern Approach Third Edition, Chapter 10: Classical Planning

[2] Micheal Gelfond, Vladimir Lifschitz (1998) "Action Languages Archived September 2, 2011, at the Wayback Machine.", Linköping Electronic Articles in Computer and Information Science, vol 3, nr 16.

[3] McDermott, Drew; Ghallab, Malik; Howe, Adele; Knoblock, Craig; Ram, Ashwin; Veloso, Manuela; Weld, Daniel; Wilkins, David (1998). "PDDL---The Planning Domain Definition Language" (PDF). Technical Report CVC TR98003/DCS TR1165. New Haven, CT: Yale Center for Computational Vision and Control. 