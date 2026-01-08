## Reflection questions

1. What challenges did you face when refactoring your code to use Tailwind?

I used tailwind since my instructor allowed it. The challenges I faced was the weirdness  with measurements. I generally use pixels for everything; margins, padding, and font, but tailwind makes assumptions unless specified otherwise. It lead to many  things being misaligned, but a quick look at the docs was I all I needed. For the most part the transition was smooth, but I couldn't figure out why my font size was different from the tailwind one. 

2. How did using Tailwind utility classes and components simplify your styling process?

By having the styling embedded in  a element's class I only needed to look at the html. It removes the context switching between an external style sheet and html. The syntax is much shorter too allowing me add multiple style attributes inline. By having the style attributes  inside their selector their easily searchable via the keyword finder too. 

3. In what scenarios might you choose not to use Tailwind and write custom CSS instead?

The only scenario I can see myself not using tailwind is if I'm using latest css features. Or if I'm doing something with heavy styling. In tailwind since all the style attributes are inline you're repeating yourself more for a group of the same selector. Writing all those style attributes for each element will lead to an mistake. Its something you don't have to deal with using css in an external style sheet. Aside from those things, using tailwind for basic websites is fine.