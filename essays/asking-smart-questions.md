---
layout: essay
type: essay
title: Do Bad Questions Exist?
# All dates must be YYYY-MM-DD format!
date: 2018-01-25
labels:
  - Software Engineering
  - Learning
  - StackOverflow
  - Meaningful Questions
---

<img class="ui medium left square floated image" src="../images/better_question.jpg">

As a kid in elementary school, I had been constantly reminded that bad questions did not exist. Looking back, I have come to realize that it was simply a ploy to elicit higher class participation. Bad questions are definitely in the realm of existence. However, the difference between good and bad questions is not exactly black and white. Certain factors which include phrasing, persistence (attempts at finding a solution), and proper grammar can swing a reader’s interpretation of a question for better or worse.

This is especially true for the software engineering field. There are many approaches that can be taken to reach a solution from a presented problem. Because of this, it is imperative that smart and insightful questions are asked to bolster understanding. Consequently, an effective response will follow and may even spark an even more meaningful discussion. Using StackOverflow as a learning resource, we will analyze presented questions on this platform for elements that constitute good and bad questions.

<blockquote> Thread Title: I dont understand this c++ term </blockquote>
<blockquote> <i>I have seen the the last sentence at some source code.please explain me what is this. </i> </blockquote>
  
  ```
     unsigned int dataPos;
     unsigned char header[54];
     dataPos    = *(int*)&(header[0x0A]);
  ```
This is a poorly presented question. At first glance, the title is extremely vague and provides little to no context regarding the question that is about to be asked. Furthermore, there is a terse sentence which showcases a lack of effort in regards to proper grammar, capitalization, and any attempts at reaching a solution prior to asking on StackOverflow. Although a code snippet is included, I would imagine that readers are already mildly annoyed with the poster’s lack of effort to present a proper question. Why would you want to help someone who does not even want to help themselves? Surprisingly, there was no backlash from the community but there was a wide variety of proposed solutions to the question. This further emphasizes that the question presented was unclear as many responses had differing interpretations of the question.

<blockquote> Thread Title: How do I check if an array includes an object in JavaScript? </blockquote>
<blockquote> <i>What is the most concise and efficient way to find out if a JavaScript array contains an object?
  This is the only way I know to do it: </i> </blockquote>

  ```
     function contains(a, obj) {
       for (var i = 0; i < a.length; i++) {
           if (a[i] === obj) {
               return true;
           }
       }
       return false;
     }
  ```
<blockquote> <i>Is there a better and more concise way to accomplish this?
This is very closely related to Stack Overflow question *Best way to find an item in a JavaScript Array?* which addresses finding objects in an array using indexOf. </i> </blockquote>

This is a smart and insightful question. The title for this question is very specific and gives readers the appropriate context. It explicitly asks how to perform a specific task in a specific programming language. Since the question title is straight to the point, it does not waste readers’ time and it helps to filter out responses from people inexperienced with JavaScript. Furthermore, a code snippet is provided with the poster’s implementation to the presented problem which helps readers gain an even better understanding of what is being asked. The poster follows up with a concise question asking whether or not there is a better way to accomplish the task. It is also worth noting that the poster referenced another related StackOverflow question. This shows readers that the poster searched the internet looking for similar problems before concluding that a separate question had to be asked to reach a solution to his/her problem. Due to the nature of this smart question, it evoked effective responses. The responses were similar which shows that there was no misinterpretation of the question. Each response led to a follow up discussion so it is clear that readers were engaged with the poster regarding the presented question.

Since programming is such a vast field, smart questions need to be emphasized to obtain quick and meaningful answers. Using smart questions as building blocks, the quality of information available on the Internet becomes better and as a result, software developers will be able to prototype/deploy code at a faster pace.
