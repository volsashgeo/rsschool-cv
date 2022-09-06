# Aleksandr Volkov
## Junior Frontend Developer  
___
### Contact information:

Phone: +7 926 560 06 70  
E-mail: volsash@mail.ru  
Telegram: @volsashgeo  
Discord: volsashgeo  
___

### About Myself:

For a long time I worked in the field of geodesy, then I decided to change my occupation to frontend development. My goals are to acquire and to consolidate new knowledge.
I am purposeful and methodical in achieving my goals and confident in success.  
___

### Skills and Proficiency:

HTML5, CSS3,
JavaScript Basics,
Git, GitHub,
VS Code
___
### Code example:

Check to see if a string has the same amount of 'x's and 'o's. The method must return a boolean and be case insensitive. The string can contain any char.  
Examples input/output:  
XO("ooxx") => true  
XO("xooxx") => false  
XO("ooxXm") => true  
XO("zpzpzpp") => true // when no 'x' and 'o' is present should return true  
XO("zzoo") => false  

    function XO(str) {
        let arr = [];
        for (j = 0; j < str.length; j++) {
            arr.push(str[j]);
        }

        let countX = 0;
        for (i = 0; i < arr.length; i++) {
            if (arr[i] == 'x' || arr[i] == 'X') {
                countX += 1;
            }
        }

        let countO = 0;
        for (i = 0; i < arr.length; i++) {
            if (arr[i] == 'o' || arr[i] == 'O') {
                countO += 1;
            }
        }

        if (countX==countO || (countX==0 && countO==0)) {
            return true
        }else {
            return false
        }
    }  
___
### Education:  
Moscow State University of Geodesy and Cartography  
Geodetic faculty  
___

### Courses:  
Frontend development from "Professional" center () 
JavaScript Manual on learn.javascript.ru (in progress),  
RS Schools Course «JavaScript/Frontend. Stage 1» (in progress)  
___
### Languages:  
English - Intermediate/Upper-intermediate,  
Russian - Native



