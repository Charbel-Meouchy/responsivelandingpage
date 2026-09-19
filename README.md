Stride - Responsive Landing Page

this is assignment 2 for web dev. its a landing page for stride which is a fake AI coach app i made up, it 
helps you set goals and build daily habits and it checks in with you every day
I added alot of comments espically on new stuff that we haven't used in past assingments and if something passed once i commented it and it passed again
i didn't since it practically is the same.(i only explained the same stuff once)
what i used
html: header nav main footer, lists, a table, a description list for the faq and a form with required fields
css: variables, grid, flexbox and media queries

how the layout works
i used **grid** for the whole page, every section has a grid-area name so the layout is just a map in grid-template-areas
i used **flexbox** inside each section: the navbar, the buttons, the cards, the form and the footer
i did it **mobile first** so the base css is for phones and then i added 2 media queries with min-width (600px for tablet and 1024px for desktop)
on desktop the faq and the form go side by side, thats the part where grid actually matters

colors and spacing used the exact same in the entire website for consistency
i only used 5 colors and named them by what they do not by the color: --surface --text --brand --success --danger
all the spacing comes from --sp-1 to --sp-6 (8px to 64px in rem) so i dont have random numbers everywhere
font sizes and line heights are variables too


screenshots

phone (375px)(screenshots/mobile.png)

ipad (700px)(screenshots/ipad.png)

desktop (1440px)(screenshots/desktop.png)