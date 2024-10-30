Converting to CNF,

!t(!s → (p+r)) ∨ ((!s+!t) → (p+r)t)

!t(s+(p+r)) + (s+t) → (p+r)t = !t(s+p+r) + !(st) + (p+r)t  (Implications eliminated)

Applying De Morgan's Law,

!t(s+p+r) + (!s+!t) + (p+r)t

Distributing  !t,

(!ts)+(!tp)+(!tr)+!s+!t+(pt+rt)

(!ts)+(!tp)+(!tr)+!s+!t+pt+rt 

!t(s+p+r)+!s+!t+pt+rt (Distributive Law)

!t+!s+pt+rt (Absorption Law)

(!t+!s)+(pt+rt)
