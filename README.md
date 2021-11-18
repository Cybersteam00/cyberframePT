
# Cyberframe (Prototype) #

An adaptive Framework with mobile-first approach for any Website. Update CSS-Variables to apply your own global color scheme and design. Finetune with your own CSS to fully customize Websites.<br/>
[uncompiled Sandbox](https://github.com/Cybersteam00/cyberframeSandbox) (build with sveltekit)<br/>
[Documentation](https://github.com/Cybersteam00/cyberframePT/wiki)

## Content ##
**Default**<br/>
Includes **Basic** and **Components**


**Basic**
- reboot (CSS reset)
- breakpoints (sm - xxl)
- basic grid columns with gaps (CSS grid)
- form-control
- button
- dropdown

**Components**
- alert
- card
- dropdown (colored)
- modal
- dialog

! Additional Components are in development<sup><small>TM</small></sup> !

**Utility**

- padding/margin
- display
- flex-grow


## Features ##
 * Cross-Browser CSS reset
 * Better readable mediatypes in HTML like sm:cols-2 md:cols-4 print:d-none etc.
 * Combined CSS-Classes for less bloated HTML (btn primary, card secondary, alert danger)
 * Some basic CSS-Variables:
   * 6 different Colors (in dark and light)
     * primary
     * secondary
     * info
     * success
     * warning
     * danger
   * 2 Colorvariations for Background and font
   * 1 ghost Color
   * border-radius
   * transform speed
   * fontsize
   * font family + weight
   * header sizes


### Why? ###
Yes, why indeed. Why develop another Framework, when we have Bootstrap, Bulma, Tailwind, daisyui, etc.?
Well, allow me to explain.

**Bootstrap, Bulma and other Component-Based Frameworks**<br/>
These Frameworks provide you with a tested prebuild css, to build a professional Website as quickly as possible. The big frameworks provide extensive documentation about their framework and how to integrate them into your website.
However such Frameworks are really really big, with all their different components and utilities. Not really a good choice for smaller Websites with only a few components. Furthermore just changing the color-scheme is difficult/tedious, because you either have to host your own version of the chosen framework or overwrite the CSS, which is time consuming.<br/>
To be fair, Bootstrap is implementing more and more CSS-Variables, to better customize everything in it. ([Bootstrap CSS-Variables](https://getbootstrap.com/docs/5.1/customize/css-variables/)) But since I have seen their monstrous amount of scss variables, I think the end result will be an equally monstrous amount off CSS-Variables. Not a thing I'm exited about.

**Tailwind and other Utility-Based Frameworks**<br/>
These kind of Frameworks provide a wide variety of atomic CSS-classes to customize your website as much as possible without increasing the size of your css-file. A good choice to keep your Filsizes small and create unique websites. As long as you use a frontend-framework like react, vue or svelte.<br/>
And yet at the same time they blur the line between HTML and CSS (separation of concern). They limit the usage of abstract/pseudo CSS usage. Using more than 5 Classes bloats your HTML (something daisyui 'fixes'). CSS-Features, like CSS-Grid, can never be fully utilized in such Frameworks because of their complex nature. I don't think Tailwind will last.

**daisyui**<br/>
DaisyUI is an extension to Tailwind to minimize the written HTML-classes and allows you to use precise names for your components. It's like bootstrap but for Tailwind.<br/>
It also has like a 100 different CSS-variables and a lot of basic CSS that will be overwritten. Good luck debugging daisyUI in your browser.


### You're wrong! Tailwind and DaisyUI will revolutionize webdesign! ###
We have to wait and see.


### Won't I lock myself into your Framework? ###
Depends. <br/>
**Basic** Package: not really. CSS Variables are not exclusive to Cyberframe. The DOM structure is similar to any other Framework, except for the grid. (Because it uses CSS-grid)<br/>
**Components** Package: More than in the **Basic** Package since the Components require a specific DOM structure. And some classnames might be different compared to the other frameworks. <br/>
**Utility** Package: If you exclusively use utilities -> yes


### Is it possible to create a Module based on Cyberframe? Like a datepicker or pictureslider? ###
Yes, it's very easy and doesn't need to be catered to Cyberframe. All you need to do is to integrate CSS-Variables into your modules-style and update the documentation.<br/>
Even the existing datepickers and picturesliders would be able to do it today.


### Can I copy your framework? ###
Yes, you can. I tried to keep the Files content small and contained for better Developer experience.


### Can I contribute to this? ###
Yes. Also please keep in mind, I never administrated such a project on github.
