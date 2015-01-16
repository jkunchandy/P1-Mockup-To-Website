# P1-Mockup-To-Website
1st of 6 projects for completion of FrontEnd Web Developer Nanodegree (Udacity.com)


Instructor Notes

Bootstrap can be found at the following path: css/bootstrap.min.css. Please use the exact path. Tests will fail if you will use a different path for bootstrap files.

Mug image can be found at images/mug.png

Font family is Verdana, sans-serif;

Font color for the main title and text is #666666, for subtitle - #F07C17

The border around the box under the image should be solid 1px and its color should be#CCCCCC.

You will have to find the font sizes, line spacing, margins/padding on your own.

HTML/CSS Style Guide: http://goo.gl/0EVzNy

Do not try to load non-local files (like fonts, from another server) in our page. This can cause the "dubious: no message left" - also there is another cause of that error we just discovered: if your line-height is a large value like 200%.

The text for the page:

Bacon ipsum dolor sit amet shoulder drumstick spare ribs shank, magna in sirloin. Turducken dolore tempor irure tenderloin pork belly shankle. Excepteur in strip steak pork chop voluptate tongue, hamburger nostrud kevin enim nulla ut cow incididunt. Do pancetta swine hamburger incididunt in excepteur irure pig labore est venison dolor ex adipisicing. Labore capicola veniam, commodo corned beef ut non rump swine pork chop exercitation ball tip ham deserunt.

Ad tri-tip short loin anim beef ribs eu ball tip velit deserunt frankfurter sunt nisi filet mignon. Pork loin quis ham hock mollit cupidatat. Id ground round chuck jerky meatball laborum frankfurter short loin in biltong t-bone doner ea irure. Culpa ex ut id. Nostrud t-bone bresaola pariatur qui tri-tip pork chop, ribeye irure velit pork et in dolore.

Bacon in sunt dolor fatback excepteur turkey chuck velit proident frankfurter quis. Nisi shank sirloin sed tenderloin. Magna short ribs kielbasa biltong minim. In esse t- bone est tail kielbasa dolor ullamco tongue mollit sint sirloin chuck venison anim. Short ribs dolore adipisicing, bresaola venison cupidatat short loin turducken biltong leberkas andouille elit ad in occaecat. Ground round pariatur cupidatat ham hock magna tempor ea jowl duis.

Hint to Achieve Udaciousness:

(Thanks to student Phil Duby)

To achieve a pixel-perfect matchup, we recommend our students to overlay the mockup-image on top of their HTML and set the image to be transparent.

Here is how you set up the mock image to overlay it over your HTML code:

In your HTML:

Add this code to the end of your HTML file, after you end your container div:

    </div> <--/End Container Div-->
    <div class="mockup-overlay">
      <img src="images/page-mock.png">
    </div>
In your CSS, add this rule:

    .mockup-overlay {
       top: 0;
       position: absolute;
       z-index: -1;
       opacity: .4;
    }
Load up your browser and resize your browser to 1024 pixels in width. In Chrome Dev Tools, resizing the browser will have Chrome notify you the current width of the browser.

You should develop everything locally on your machine first and once you get a close match, you can then copy and paste your code into the auto-evaluator. Make sure to delete the image overlay code or else the auto-evaluator will not evaluate your project.

Please note that even if your local version looks like a pixel-perfect match to your eye, it may not necessarily be pixel-perfect to the auto-evaluator. You may need to make small adjustments to achieve 0% mismatch.
