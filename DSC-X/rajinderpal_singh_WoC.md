# Developer – Winter of Code (WoC) 2020
---
##### **Rajinderpal Singh**
## DSC-X : <a href="https://sairish2001.github.io/omgframestesting.github.io/" target="_blank">OMG-Frames</a>

OMG-Frames aims to Generate Badges for the events that happens for across the Student Clubs, or any other events.My work is to create a Frontend for the entire project mainly Dashboard.
>**Apart from my work, I added new features which I thought to be in for better user experience.**

**I am <a href="https://github.com/sairish2001/" target="_blank">*Rajinderpal Singh*</a>, an undergraduate student from <a href="http://www.gndu.ac.in/" target="_blank">*Guru Nanak Dev University,Amritsar*</a>, as part of Winter of Code.** This project was mentored by <a href="https://github.com/xprilion/" target="_blank">Anubhav Singh</a>

## Contributions
Contributions are outlined as follows:

 * 20 <a href="https://github.com/dsc-x/omg-frames/commits/develop" target="_blank">commits</a> (approx.) are made into the develop branch of iWasAt.events

* Total of 3 Pull Requests made and got merged in develop branch.

    * First Pull Request
 ![First Pull Request](https://i.imgur.com/QR3CiKv.png)<a href="https://github.com/dsc-x/omg-frames/pull/5" target="_blank"> #PR-6</a>

    * Second Pull Request ![Second Pull Request](https://i.imgur.com/EaHvExN.png) <a href="https://github.com/dsc-x/omg-frames/pull/8" target="_blank">#PR-8</a>

    * Total ![Total](https://i.imgur.com/LAaiWWz.png)

* Created 2 Issues in API Repository.
    * Fogot Password? API wanted <a href="https://github.com/dsc-x/omg-frames-api/issues/14" target="_blank"> {#14}</a>
    * Delete Frame API <a href="https://github.com/dsc-x/omg-frames-api/issues/11" target="_blank"> {#11}</a>

* Closed 2 Issues, by working on it.
    * Dashboard UI<a href="https://github.com/dsc-x/omg-frames/issues/3" target="_blank"> {#3}</a>
    * Performance issue in `gallery.html` page <a href="https://github.com/dsc-x/omg-frames/issues/9" target="_blank"> {#9}</a>
* Created 3 issues in omg-frames Repository
    * Implement update frame API <a href="https://github.com/dsc-x/omg-frames/issues/11" target="_blank"> {#11}</a>
    * Design a Favicon <a href="https://github.com/dsc-x/omg-frames/issues/12" target="_blank"> {#12}</a>
    * Make Share button Working <a href="https://github.com/dsc-x/omg-frames/issues/13" target="_blank">{ #13}</a>
* 10 (approx.) New Features

## New Features
* Created Frontend
    * <a href="https://getbootstrap.com/" target="_blank">Bootstrap framework</a> for responsive website 
    * <a href="https://github.com/dsc-x/omg-frames/blob/develop/index.html" target="_blank">index.html</a>, <a href="https://github.com/dsc-x/omg-frames/blob/develop/dashboard.html" target="_blank">dashboard.html</a>, <a href="https://github.com/dsc-x/omg-frames/blob/develop/gallery.html" target="_blank">gallery.html</a> , <a href="https://github.com/dsc-x/omg-frames/blob/develop/forgotpassword.html" target="_blank">forgotpassword.html</a>, <a href="https://github.com/dsc-x/omg-frames/blob/develop/reset.html" target="_blank">reset.html</a> 
    * CSS files for each page <a href="https://github.com/dsc-x/omg-frames/tree/develop/css" target="_blank">{css/}</a>
    
    * JS files (<a href="https://github.com/dsc-x/omg-frames/blob/develop/js/main.js" target="_blank">main.js</a>, <a href="https://github.com/dsc-x/omg-frames/blob/develop/js/imageedit.js" target="_blank">imagedit.js</a>, <a href="https://github.com/dsc-x/omg-frames/blob/develop/js/loginsignup.js" target="_blank">loginsignup.js</a>), the `main.js` contains all the required functions, the `imageedit.js` contains implementation of crop feature into dashboard, and `loginsignup.js` contains all functions which has link with Backend in someway, along with all functions for AJAX request. <a href="https://github.com/dsc-x/omg-frames/tree/develop/js" target="_blank"> {js/}</a>
* Functionality added<a href="https://sairish2001.github.io/omgframestesting.github.io/" target="_blank">{ see working }</a>
    * Crop feature <a href="https://foliotek.github.io/Croppie/" target="_blank">(Croppie.js)</a>. Now user can crop it's Picture after selecting.

    * <a href="https://github.com/dsc-x/omg-frames/blob/develop/js/croppie.js" target="_blank">Customized Croppie.js</a> for showing instant result on canvas (oninput/onchange)
    
    * **Generate Strong Password** (12 characters long, includes alphabets, numbers, special characters), it generates a strong password and insert automatically into password field <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/main.js#L197" target="_blank">{ function generatepassword() }</a>
    ![generatepassword](https://i.imgur.com/8ruldPM.png)
    
    * Fullscreen mode, now user can experience fullscreen feature.<a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/main.js#L224" target="_blank">{ function enablefullscreen() }</a>

    * User can see it’s Account information by clicking on My Account button in navbar (email, name, organization,role).
    
    * Colored custom popups for displaying response message after fetching from API request, just call `alertpopup(message,'open',colorofpopup);`.Red(`#dc3545`) on error, Green(`#28a745`) on success.<a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/main.js#L186" target="_blank">{ function alertpopup() }</a>
    ![popups](https://i.imgur.com/9qBVSu7.png)

    * `loader()` function, to show/hide loading animation, just call `loader(‘show’)` or `loader(‘hide’)`<a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/main.js#L88" target="_blank">{ function loader() }</a>
    
    * Light/Dark  Mode (index.html, dashboard.html, gallery.html), set mode in any page, will be applied to all pages automatically.
    ![lightdark](https://i.imgur.com/gwKAX24.jpg)
    
    * Show/Hide Password.<a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/main.js#L210" target="_blank">{ function showpassword() }</a> in Login/SignUp form.
    
    * Form validation <a href="https://jqueryvalidation.org/" target="_blank">(jQuery form validation)</a> with custom error messages and color 
    
    * <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/loginsignup.js#L190" target="_blank">Download or Delete</a> Saved frames by hovering on fetched frames in gallery.html.
    ![gallerypage](https://i.imgur.com/j8Bm0R1.jpg)

    * Customized Bootstrap’s buttons, input field’s classes according to wireframe design.

    * Changed SVG logo to PNG (by making it’s background transparent) <a href="https://github.com/dsc-x/omg-frames/blob/develop/images/logo.png" target="_blank">{logo.png}</a>                                                         
    * Changed Black color to white of logo for dark mode.<a href="https://github.com/dsc-x/omg-frames/blob/develop/images/logodark.png" target="_blank">{logodark.png}</a>
    
    * As per requirement, user cannot use dashboard or visit gallery **without logging in**.
    
    * Created other required functions for proper working of project <a href="https://github.com/dsc-x/omg-frames/tree/develop/js" target="_blank">{ js/ }</a>
        * `createordestroybutton()` for creating and destroying **Login/Logout button**.
        
        * `dashboardandgallerybutton()` for creating/destroying **View Dashboard and Gallery button** if Logged in and **Get Started button** if not Logged in.
        
        * Other functions for toggle closing/opening of Content.<a href="https://github.com/dsc-x/omg-frames/blob/develop/js/main.js" target="_blank">{ main.js }</a>
        
        * Many More

    * Implemented All available API’s <a href="https://github.com/dsc-x/omg-frames/blob/develop/js/loginsignup.js" target="_blank">{ loginsignup.js }</a>
        * <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/loginsignup.js#L117" target="_blank">Login</a>
        * <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/loginsignup.js#L68" target="_blank">SignUp</a>
        * <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/loginsignup.js#L246" target="_blank">Save Frame</a>
        * <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/loginsignup.js#L219" target="_blank">Get Frame</a>
        * <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/loginsignup.js#L162" target="_blank">Delete Frame</a>
        * <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/loginsignup.js#L280" target="_blank">Send-reset-email</a>
        * <a href="https://github.com/dsc-x/omg-frames/blob/6c1e9c40dfcd8e21980094d9291784da1c7b6612/js/loginsignup.js#L309" target="_blank">Update-password</a>

## Future Scope
Here is a list for future developers. 
* Use <a href="http://fabricjs.com/" target="_blank">`frabric.js`</a> for live editing on  canvas.
* Make frames fully customized so that user can change Event Text(Attendee, Speaker,etc.) , and can also change logo.
* Other editing features like Brightness, Contrast,etc. along with filters(for filters I suggest <a href="https://una.im/CSSgram/" target="_blank">CSSgram</a>).

* Drag,Transform, contents inside canvas.

* Enable user to download the frame in different Resolutions

Feel free to come up with new ideas yourself.

## Acknowledgments
I would like to express my gratitude to [Anubhav Singh](https://github.com/xprilion) for his patient guidance and thanks for going through all my PR's.
I would also like to thank [Awantika Nigam](https://github.com/awantika10) and [Arnab Sen](https://github.com/arnabsen1729),they are the main source of configuring bugs regarding new Pull Request. It has been a great experience working at OMG-Frames!.


WoC with DSC-X was a warm and unforgettable experience for me. Everytime I talk of Open Source, OMG-Frames will be remembered fondly.