# PasswordGenerator
Responsive Portfolio
Installation:
    You can check the running project at:  
    https://aysenunlu.github.io/ResponsivePortfolio/

Usage:
   - When you run the application, you're welcomed with an About Me page:

     ![About me page](assets/images/a1.png)

     The page is responsive. The paragraph wraps around the image at breakpoints-large(992px) 

     ![About me page](assets/images/a2.png)
     and medium(768px) 

     ![About me page](assets/images/a3.png)
     
     and at breakpoints-sm(576px) the paragraphs listed below the image

     ![About me page](assets/images/a4.png)

   - When you click the portfolio page, you see matrix of images. The images are    
     placeholders for links to your projects in the future.  

     ![Portfolio Page ](assets/images/b1.png)

     You'll see 2x3 matrix for images. 
     If you make the screen smaller, at the large and medium breakpoints , the image matrix will be 3x2. 

     ![Portfolio Page ](assets/images/b2.png)
     
     If you make it smallest, at the small and xsmall(0px), the image matrix will be 5x1. 
     
     ![Portfolio Page ](assets/images/b3.png)

     The images and page is responsive.

   - When you click the Contact page, you see name and email text fields and a text 
     area to write your message and a submit button to send it.  

     ![Contact Page ](assets/images/c1.png)
     
     ![Contact Page ](assets/images/c4.png)

   - The footer is fixed to the bottom and does not run up with the length of the content.   

   - At breakpoints small and xsmall, navigation bar changes, the horizontal list menu 
    is displayed under the name logo

How:

First, I used Bootstrap CSS Framework to recreate my portfolio. Responsiveness is achieved through bootstrap. Media queries used to change the navigation bar for small and xsmall screens. Following pages are created:

index.html: Includes a short biography.

portfolio.html: Contains image placeholders to link to projects in the future

contact.html: The user enters his name and email, sends a message

Using Bootstrap, my portfolio site is created with the following items:


A navbar : Bootstrap navbar is used. To change the layout for navigation bar for small and x-small screens media queries are used 

A responsive layout: Layout is responsive through bootstrap.

Responsive images: Images are responsive as well

I used Bootstrap's grid system for my "about me" page. Which lines are going to be shown depends on the screen size, so text will wrap around the image with large and medium screen sizes.

Grid System is used for "portfolio page" as well with subrows so images and headings repositioned without breaking.

For Contact page bootstrap's label,text field, text area and buttons are used so it's responsive

On small and larger screens, I have margins on left and right sides of the screen. 

On xs screen, content takes up entire screen.

I used a sticky footer which resides on the bottom of the page.

Credits: 

I'm forever grateful for the Bootstrap Documentation which can be accessed by the link:
https://getbootstrap.com/docs/4.3/getting-started/introduction/

I'm also greatful for our instructor Omar Patel and TA's Tyler Bray and Matthew Calimbas for their feedback and recommendations.

Licence:

Anybody is welcomed to copy code snippets and test it out.

Limitations:

On the contact page, submit button does not work since no javascript code is added.