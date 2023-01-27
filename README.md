- 👋 Hi, I’m @Pcharlesme
- 👀 I’m interested in Gig, Job , Fulltime role and Freelance 

<!---
Pcharlesme/Pcharlesme is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
![](https://komarev.com/ghpvc/?username=Pcharlesme)


String[][] strs = new String[6][2];
PFont font;

void setup() {
  size(1920, 1080);
  font = createFont("HelveticaNeue-48.vlw", 48);
  textFont(font);
  frameRate(30);
  textAlign(CENTER);
  textSize(40);
  background(255);
  fill(0);

  strs[0][0] = "Hey there!";
  strs[0][1] = "My name is Mason Slover.";

  strs[1][0] = "I'm a Mathematics & Computer Science Major";
  strs[1][1] = "at Fordham University at Lincoln Center in New York City.";

  strs[2][0] = "I've been teaching myself how to code for 6 years!";
  strs[2][1] = "I am fluent in Java, C++, Python, Swift, JavaScript, and HTML & CSS.";

  strs[3][0] = "I've created apps, websites, and art using what I've learned.";
  strs[3][1] = "You can even find the Processing source code for this below!";

  strs[5][0] = "Feel free to reach out to say hi!";
  strs[5][1] = "phone: (512) 739-2405 | email: masonslover@gmail.com";
}

int i = 0;
boolean delete = false;
int s = 0;
int offset = 50;
int mainFontSize = 60;
int secondaryFontSize = 40;


void draw() {
  background(255);

  if (s < strs.length) {
    if ((strs[s][0].length() >= i || strs[s][1].length() >= i) && !delete) {
      if (strs[s][0].length() >= i) {
        textSize(mainFontSize);
        text(strs[s][0].substring(0, i), width/2, height/2 - offset);
      } else {
        textSize(mainFontSize);
        text(strs[s][0], width/2, height/2 - offset);
      }
      if (strs[s][1].length() >= i) {
        textSize(secondaryFontSize);
        text(strs[s][1].substring(0, i), width/2, height/2 + offset);
      } else {
        textSize(secondaryFontSize);
        text(strs[s][1], width/2, height/2 + offset);
      }
      i++;
    } else {
      if (!delete) {
        delay(1500);
      }
      delete = true;
    }


    if (delete) {

      if (i > 0) {
        if (i < strs[s][0].length()) {
          textSize(mainFontSize);
          text(strs[s][0].substring(0, i - 1), width/2, height/2 - offset);
        } else {
          textSize(mainFontSize);
          text(strs[s][0], width/2, height/2 - offset);
        }
        if (i < strs[s][1].length()) {
          textSize(secondaryFontSize);
          text(strs[s][1].substring(0, i - 1), width/2, height/2 + offset);
        } else {
          textSize(secondaryFontSize);
          text(strs[s][1], width/2, height/2 + offset);
        }
        i--;
      } else {
        delete = false;
        s++;
      }
    }
    //print(i + " ");
    //s++;
  }
}

<a href="https://api.whatsapp.com/send?phone=2348108244286&text=Hello%20Pcharles,%20I%20got%20your%20contact%20from%20your%20Github%20profile" alt="Connect on Whatsapp"> 
    <img src="https://img.shields.io/badge/WHATSAPP-%2325D366.svg?&style=for-the-badge&logo=whatsapp&logoColor=white" /> 
</a>

<a href="https://www.twitter.com/@EmmanuelPcharl1" alt="Follow Me on Twitter"> 
    <img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/emmanuelpcharles/" alt="Follow Me on Twitter"> 
    <img src="https://img.shields.io/badge/Link-%231DA1F2.svg?&style=for-the-badge&logo=Limked&logoColor=white" />
</a>

<a href="https://www.instagram.com/pcharles_01" alt="Follow Me on Instagram"> 
    <img src="https://img.shields.io/badge/instagram-%23D14831.svg?&style=for-the-badge&logo=instagram&logoColor=white" />    
</a>

</a>&nbsp;
<a href="mailto: opeyemicharlese@gmail.com">
  <img src="https://img.shields.io/badge/email me-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" />
</a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/emmanuelpcharles" alt="messsage on linkedln"> 
    <img src="https://img.shields.io/badge/linkedln-%231DA1F2.svg?&style=for-the-badge&logo=telegram&logoColor=blue" />
</a>                                                                                                                    

## 🚀 Skills

<img src="https://img.shields.io/badge/javascript-%23F7DF1E.svg?&style=for-the-badge&logo=javascript&logoColor=white" /> <img src="https://img.shields.io/badge/kotlin-%FA26A0.svg?&style=for-the-badge&logo=kotlin&logoColor=white" /> <img src="https://img.shields.io/badge/flutter-%231DA1F2.svg?&style=for-the-badge&logo=flutter&logoColor=white" /> <img src="https://img.shields.io/badge/firebase-%231DA1F2.svg?&style=for-the-badge&logo=firebase&logoColor=yellow" />  <img src="https://img.shields.io/badge/figma-%23D14836.svg?&style=for-the-badge&logo=figma&logoColor=white" /> 

<br>

