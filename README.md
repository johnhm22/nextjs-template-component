## NextJS template.js  
A very short coding exercise to practise the use of template.js from [NextJS v14](https://nextjs.org/docs/app/api-reference/file-conventions/template)  

As the NextJS documents state:  
"A template file is similar to a layout in that it wraps each child layout or page. Unlike layouts that persist across routes and maintain state, templates create a new instance for each of their children on navigation."  

This exercise shows how the use of template.js (tsx in this case as TypeScript is being used) allows for the transition of text when navigating between different links in a header. 

Without the template, the fact that the page is stored in the cache means the text transition effect is not seen unless the page is reloaded. By using template.tsx the transition effect occurs each time the user navigates to the page.  

The page itself is not reloaded, but rather the template.tsx component which wraps the pages.


Ref.
Hamed Bahram  
https://www.youtube.com/watch?v=jVU3JD6qOBo


