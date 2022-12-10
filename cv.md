# Yury Savitski
**+375 29 727 7138** | telegram: **@yur1k_sav** | **yura.abc@gmail.com**

### Goal
***
To obtain a position as an Front-End developer in a growth oriented company,
where I am able to use my skills to contribute to the overall operation of the team.

### Profile
***
* Detail-oriented
* Quick learner
* Desire to follow procedures
* Excellent verbal and written communication skills
* Strong problem solving capability

### Professional experience
***
* Belarussian State University, Minsk, System Administrator
* National Intellectual Property Center, Minsk, Chief Specialist of the Automation
* Republican Centre of Real Estate Accounting, Minks, Specialist of Information Technology

### Education
***
* Master of Science: Belarusian National Technical University, 2009
* Bachelor of Science: Automation Engineer, Belarusian National Technical University 2008

### Proffesional Skills/Certifications
***
* Certified in CCNA Exploration (Cisco Certified Network Association);
* BUSINESS  ANALYST (High Technology Park);
* Basic knowledge of programming languages(HTML, CSS, JS, SQL);

### Code example
***
```
//Convert text - each sentence starts with an upper case letter.
const sentenceCaseButton = document.getElementById("sentence-case");
sentenceCaseButton.addEventListener("click", function () {
    let myText = document.querySelector("textarea").value.toLowerCase();
    let textArray = myText.split(". ");
    function capitalizeFirstElement(str) {
        return str.charAt(0).toUpperCase() + str.slice(1);
    };
    let sentenceTextArray = textArray.map(capitalizeFirstElement);
    let sentenceCase = sentenceTextArray.join(". ");
    document.querySelector("textarea").value = sentenceCase;
});
```
