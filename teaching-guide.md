# Classmates - Teacher's Guide

This is a hands-on coding project. Upon completion of the assignment, the student will have a working telephone application and personal phone number that can be shared to provide connectivity with their friends/families/fellow classmates.

## Prerequisites

Student should have a basic grasp of reading. The intended age range is 6-14 years. (Grownups are also very much welcome 💪)

Student will need an Internet connection and a web browser. We will be creating a free trial with Twilio. Using this [free trial promo code]() will double the amount of free credit.

Previous programming experience is **not** required for the student nor the instructor.

## Learning Objectives

After watching this video, the student will be able to:

* Explain that coding can provide solutions to real world problems
* Identify a tag and what characters make up the tag
* Recall how to close a tag in a markup language
* Identify common errors found in strict markup languages
* Recall how to nest a tag in a markup language
* Construct a telephone application that uses Text to Speech
* Create a telephone application that connects caller's to a Conference call

## Solutions

The video reveals the correct answers, but in case you want access to the various coding prompts:

*8:35* - [Say code](classmates-twiml#dial-a-conference) (Make sure you have an open and closing tag, along with the proper casing!)

*11:00* - Replace the initial saying with `Connecting to classmates` within the `<Say>` tag.

```xml
<Say>Connecting to Classmates</Say>
```

*12:08* - Nest a `<Conference>` tag within the `<Dial>` tag.

```xml
<Dial><Conference></Conference></Dial>
```

Next we add the conference name.

```xml
<Dial><Conference>Classmates</Conference></Dial>
```

[Final solution](classmates-twiml#dial-a-conference)

## Discussion Prompts

### What other solutions can you think of that have been created to solve problems? How do they help?

Suggestion: Discuss Amazon.com and Grocery Store pickup for very relatable solutions they are seeing during the pandemic. Also consider Google Classroom / Seesaw. Discuss future feeling ideas: self driving cars/robots etc.

### What made the coding parts challenging? How do you think you could get better at it?

Suggestion: If programming is new to them and probably has stricter rules than they will be accustomed to. Practice, practice, practice.

### What do you want to build with code?

Suggestion: Anything is possible! Please share the responses with us! We are always looking for inspiration [@craigsdennis](https://twitter.com/craigsdennis)