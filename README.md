# Radiology Outpatient Order Board App

This is Brian Lipscombe's third Milestone Project at [Code Institute](https://codeinstitute.net). It was built using HTML5, CSS3, JavaScript, Python+Flask, MongoDB Gitpod, and deployed on the hosting platform Heroku. It is designed with Code Institute's Assessment Handbook Project Idea 0 in mind - Bring your own idea to life, based on providing value to users to address a specific real or imagined need.

It is intended to provide organization and management support for outpatient diagnostic imaging orders scheduled within the radiology department of a hospital.

The app can be found [here.]()

## User Experience (UX)

* User Stories

    1. Visitor Goals

    - Start the quiz
    - Agree to the rules of the quiz
    - See how much time to answer is available
    - Read the questions without being overly rushed
    - Answer the questions in time correctly, but if incorrect, see which answers are correct
    - Receive a score at the end
    - Decide whether to take the quiz over or not

    2. Owner Goals
        
    - Make the game visually appealing
    - Ensure the questions are somewhat challenging
    - Provide multiple-choice answers that are somewhat enjoyable to read
    - Offer a bit of cryptocurrency facts and insight

* Design

    1. Color Scheme

        The main colors used are tones of orange and yellow to play off the golden color of Bitcoin, the most widely accepted cryptocurrency in the world often referred to as "digital gold." Black is used to provide a strong contrast to the bright "golden" hues. Other colors included are green and red to resemble the market candlestick colors (green for upward or bullish momentum, and red for downward or bearish momentum).  

    2. Imagery

        The background image is a rendering downloaded for free from VectorStock [here](https://www.vectorstock.com/royalty-free-vector/cpu-chip-with-bright-connections-green-vector-22525088) then further designed with additional layers using Adobe Photshop Elements Photo Editor. The cryptocurrency logos were obtained for free at designmodo [here.](https://designmodo.com/free-crypto-icons/) It is intended to appear as a magnified digital cryptocurrency networking circuit.

    3. Typography

        The fonts are basic and easy to read. The buttons at the beginning and end of the quiz are labeled with text that correspond with market terminology i.e. instead of "start" the word "invest" is used, and instead of "play again" and "quit" the words "bullish" and "bearish" are used to promote a positive or negative (but fun) feeling in the user to either play again or quit.

* Wireframe

    View the developer's Balsamiq mock-up [here.](https://slack-files.com/T0L30B202-F02PX40H0MD-a42692bf00)

## Features

* Responsive on all device sizes.
* Interactive elements: Buttons, answer options, scoring system.

## Technologies Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)

* [CSS3](https://en.wikipedia.org/wiki/CSS)

* [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

* [Font Awesome](https://fontawesome.com/)

* [Google fonts](https://fonts.google.com/)

* [Github](https://github.com/)

* [Gitpod](https://www.gitpod.io/)

* [Git](https://en.wikipedia.org/wiki/Git)

* [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)

* [Balsamiq](https://balsamiq.com/)

## Testing

1. Manual Testing
    * Buttons

        - If INVEST button is clicked, the rules are shown;
        - If the CASH OUT button is clicked, hide the info box, show the INVEST button;
        - If the I'M IN button is clicked, hide the info box, show the quiz box;
        - If NEXT button is clicked, hide current question, show next question. After the last question show the result box;
        - If the BULLISH button is clicked, hide the result box, show the initial quiz box.
        - If the BEARISH button is clicked, hide the result box, show the INVEST button.

    * Quiz Box

        - Quiz box timer text "Time:" changing to "Time Off" when the 20s are passed;
        - Quiz box timer second counter start at 30 seconds and counts down to 0;
        - Quiz box time line elongates from the left to the right and is synchronised with the counter;
        - If the correct answer is selected the green chart up icon appears and the option box background color changes to green;
        - If the incorrect answer is selected the red chart down icon appears and the option box background color changes pink;
        - Correct answers shows automatically once time is expired;

    * Result Box Text

        - Any combination of correct or incorrect answers "END OF LINE!" text appears indicating completion;
        - If the user scored less than 1 correct asnwer "YOU HAVE BEEN FORCEFULLY LIQUIDATED!!!" text appears;
        - If the user scored more than 1 correct answers "Buy low and sell high, not the other way around!" text appears;
        - If the user scored more than 5 correct answer "PARABOLIC ACTION TO THE MOON!!!" text appears;
        - All functions are confirmed to work
    
    * Responsiveness

        - This project is confirmed to be responsive on all standard screen sizes using the devtools device toolbar

    * Browser Validation

        - This project is confirmed to work with different browsers: Chrome and Internet Explorer

2. Automated Testing

    * Code Testing 

        - This project has been tested using different browsers and different mobile devices such as iphone, Android, and laptops, as well as on a desktop computer.

    * Lighthouse Auditing

        - This project scores 100 for Accessibility and Best Practices for mobile devices, and 100 for Accessibility, Best Practices, and Performance for desktop devices

All pages were tested on multiple resolutions for proper responsiveness.

All files and pages were validated by direct input with no syntax errors using:

* [Nu Html Checker](https://validator.w3.org/#validate_by_input)
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
* [JSHint](https://jshint.com/)

## Known Bugs

* When viewing in certain small device dimensions in Chrome Dev Tools, the "Rules" section does not fit perfectly with a blank strip seen below the background image after scrollig up.  

## Deployment

### GitHub

This project was deployed to the developer's respository page:
https://github.com/BrianLipscombe/cryptocurrency-quiz-game

## Credits

* Code

    Code used as a starting template was borrowed from Youtube video "Create a Quiz App with Timer using HTML CSS & JavaScript | Quiz Web App using JavaScript" parts 1 & 2 on the Youtube channel CodingNepal found [here.](https://www.youtube.com/watch?v=pQr4O1OITJo&t=1324s) as well as from the Github repository [here](https://github.com/HeleJ/quiz-game-about-Estonia) which also gives credit to the same YouTube videos.
    Code for icons from [Font Awesome](https://fontawesome.com/).

    All other code was written by the developer.

## Acknowledgements

* Guidance and Moral Support

    Caleb Mbakwe: My mentor Caleb for helping me and for providing professional feedback even though time and scheduling has been an enormous challenge for me.

    Youtube: For providing a platform with a wealth of information to absorb. Some of which helped me get the code for this project off the ground.

    Code Institute on Slack: Hele_5P. Without stumbling upon this fellow student's Slack post for her MS2 project review request, I might have never found the inspiration for this project.

    My family for being patient and understanding when most of my time is absorbed by work and school. 

This site was developed for educational purposes.