1. Update readme.md with video
2. validate form input - waitlist and pitch
3. on prod, companies logo is not showing - unable to fetch comapnies locally now
4. Have a spot in the admin table for counting

<!-- I really do not have much to comment -->


<!-- what am i working on today -->
- a protected route
- the ability to edit and delete a company
- 

**To-write About problems I personally faced**

1. the <Image/> not showing the images, replace instead with img
2. react hydration error
3. response type basic (there are cors) etc... basic means that the response type is from the same origin

```
next-dev.js?3515:20 Warning: validateDOMNesting(...): <tr> cannot appear as a child of <table>. Add a <tbody>, <thead> or <tfoot> to your code to match the DOM tree generated by the browser.
```

companies list
- higligh on hover and on click
- on scroll does not change navbar color
- space between the companies and sign up list
- space between the companies footer links

pitch
- highligh on hover and on click
- it is a simple form to submit companies considered global
- by default, approved is set to false
- only companies who has their approval set to true will be displayed

Sign in
- what is the sign in button for? Well, only authorized users can access the 'pending page'
- the pending page is a table with all the companies who are yet to be approved
- there is going to be a button to click them true or false
- the pending page should also display all the companies so that if they need to be edited or deleted, they can be.

Deployment
- deployment is failing on vercel
- add backend environment variables on vercel

Considering
- Is there anyway to indicate that I am currently hovering over the logo?

Bugs
- navbar background does not change in the company page 🟢

This is what I have to do today, I am excited 🍵