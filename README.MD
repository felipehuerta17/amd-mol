# AMD-MOL

1-D unsteady acid mine drainage code solved with the method of lines.

The momentum and species conservation PDEs are not coupled. Hence,
they are modelled as subsystems of ODEs, and an augmented system
[ODEs of Richards Equations
ODEs of Species conservation]

Is solved 

The selected form of the Richards' equation is explicit in psi (h), the
pressure head. Haverkamp (1977) states that if a fixed time-step is used,
explicit methods take 5 to 10 times more computational time to achieve the
solution than implicit methods. However, we don't know how this explicit form
will behave if variable time-steps are used.
