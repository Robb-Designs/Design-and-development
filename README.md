# Clipboard Landing Page

This is My take on the Frontend Mentor Clipboard challenge. ---> [Frontend Mentor's landing page design](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9)




This project was a design challenge from Frontend Mentor. The challenge was to build out their landing page and get it looking as close to the design as possible.


## Reflection: Challenges  I faced

One challenge I encountered during development involved understanding how Tailwind utilities interact with flexbox layouts.While I was styling the button, one thing I've done was adjust the padding. However, the button did not appear to change. After investigating the layout structure and looking at Tailwind's documentation, I realized that the flex container was constraining the buttons, andd I found out that is what was preventing them from expanding as expected. Once I adjusted the container height and flex properties, the padding behaved correctly.


Another challenge involved working with Tailwind's mobile-first breakpoint system. I initially approached this in the opposite direction. Desktop first, then mobile. But, when getting to Tailwind's breakpoint classes, it was confusion. After doing more searching and reading the documentation, I saw that Tailwind's utility classes encourage mobile first, then scale UP to larger screens. Realizing that, I refactored my code to have it set for mobile, then placed my breakpoint `md:` to scale up. This process for this landing page suited me very well. 


---

## Future Improvements


- Try the mobile first approach in the beginning of the project.
- Improve my semantic markup.
- Refactor repeated Tailwind styles and create components


---

## Resources

- Tailwind CSS Documentation  
- Frontend Mentor design challenge
