Video opgave:

Fra 3.50 Object oriented programming:
*Decoupling
Spaghetti code er hård til at arbejde med, derfor decoupling hjælper med at "straighte tingene ud". Hvad definerer object?

*Single Responsibility Principle - giver forskellige funktioner til objekter
& Separation og Concerns

*Encapsulation - hver af de lille stk har sin egen meaning og skal være brugbare i alle andre projekter. Skal være universelle.

Fra 5.20 from Backend enrolling to Frontend

Fra 6.30 OOCSS (Object Oriented CSS) - man skal definere objects/moduls, identify once, apply in different context (eksempel fra FB). At identificere patterns som genkender sig.

Fra 8.57 SMACSS (Scalable Modular Architecture og CSS) - organise your code.
Fem basics of SMACSS (base, layout, module, state, theme).

Fra 20.50 BEM - læsbart kode. Strength of overwriting, specific/double selectors, ID blows everything! Man skal ikke bruge den.

Fra 22.06 same as BEM - Specitifity, DU SKAL ALDRIG BRUGE ID til styling, kun til JavaScript, arbejd med BEM til CSS og class.

Fra 24.20 CSS reading from the last piece not first
Selvom koden er langt nogle gange når man bruger BEM, er den stadig bedre fordi man har styr på tingene og det blander sig ikke sammen med andre ting.

For eksempel:

hellere brug:

.unordered-list-in-the-body__list-item-reversed{

}
end
body h1 .tag{
    
}