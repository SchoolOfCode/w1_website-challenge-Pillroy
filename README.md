# Website Challenge

## Overview

For your first project on the bootcamp, we want you to make a website all about your pair partner using HTML and CSS.

The person you are making your website for is your partner, aka The Client. It is your job as a programmer to understand what the client wants from a profile site, assess what information is available and useful, design what serves the audience of users (aka the other bootcampers) best from the experience, and then create something which best solves those needs. You won't be given any guidance of what to build - you'll need to empathise with your users to see what they would find useful (or even survey and talk to them), and plan your site accordingly.

## Outcome

- a single web page created with HTML and CSS
- a profile describing your client
- a short 1-page README.md file alongside it which describes how you went about the project (your thoughts, research, plans, and justification for decisions)

## Extra

This is not only a chance for you to practice the core skills of HTML and CSS, but also a chance to invest time in thinking about how to build a website for a client, and have a user-centric approach - a key learning objective of the course. You will need to actively communicate with the client to find out everything you need in order to design and build a website which represents them to the rest of the cohort.

Although you will each have an individual repository in which to make the website, there is nothing stopping you pair programming with your partner on the project. Organise your time so that you can spend an equal amount of time on each project. For example, if you spend three hours coding together on Sunday, you would spend 1.5 hours pair programming on one site, before moving over to the other site.

This project will span the first two weeks of the bootcamp, and you will be given time in live evening sessions to work on it as well.



## Learning Summary

Below is a summary of learning thus far, broken into sections: HTML and CSS.

### HTML

HTML, or _Hypertext Markup Language_, is the language used to code the **structure** of a website. Broadly speaking, a HTML webpage is split into two sections: &lt;head&gt; and &lt;body&gt;.

#### The &lt;head&gt; tag

The &lt;head&gt; tag contains information that lays the groundwork for the webpage; information vital for web browsers to run the webpage as the developer intends. Information specified in the &lt;head&gt; tag includes, but is not limited to,:

* page <title>
* meta data, including:
    * meta description
    * keyword specifications
    * author name
* links to sister sheets, such as .css and .js files.

#### The &lt;body&gt; tag

The &lt;body&gt; tag contains the page content; i.e. what the user will see when using a webpage. Remember, only structural elements are built here (styling and interactivity are typically dealt with in the sister files). Website structure follows several best practice principles, both to maximise effectiveness of web crawlers understanding the webspage for search indexing, and to make the site as intuitive as it can be to the user. As such, webpages typically follow the following structural order:

1. &lt;header&gt; - can include brand logo, navigation links, call-to-actions (e.g. click-to-call button).
2. &lt;main&gt; - includes content befitting main prupose of the page, keeping in mind what the user(s) expect and want from the webpage.
3. &lt;footer&gt; - often includes contact information, links to legal documents, sign-up forms etc. Should include options for continued user flow.

### CSS

CSS, or _Cascading Style Sheets_, is the language used to code the **styling** of a website. Using _CSS Selectors_, as defined in HTML via _tags, classes_ or _IDs_, HTML elements are styled for a more appealing, more intuitive webpage display.

By enlarge, pretty much every element built in HTML will need to have some kind of custom styling, either to please a client or appease a web designer.

**WEBSITES NEED TO LOOK SEXY**

_CSS Selectors_ are hierarchical: when specified, _class_ styling rules are prioritised over _tag_ rules, and _ID_ styling rules are prioritised over _class_ rules. With some planning, _CSS Selectors_ can be deployed efficiently to style a website to make anybody happy.

The syntax goes as follows:

[selector] {
    [property]: [value];
}


## Website Project Summary

To get going, Gurmukh and I sent each other our CV's. We felt this was a quick way to get across our formal education/work backgrounds.We also took inspiration from what we'd chatted about on Zoom.

From his CV, I saw he played Sitar (Indian String Instrument), and took part in several live performances. I thought this was cool, and decided to make this a centre stage of the website.

Following some pictures sent by Gurmukh, I began to write the HTML, thinking about how to compartmentalise the site into coherent parts. I decided to go with a 'Mind, Body & Soul' theme, given his mind had achieved much in academia and healthcare, his soul was expressed via his musicianship, and his body, well that was a tough one to work out (as evident on the webpage).

My existing understanding of the way HTML is written, and how it can be nested, meant I mainly needed to research and learn some of the tags, flexbox, how the form element works and is written, and the javascript to pull in the current year.

My directive was to build a profile site for Gurmukh, so I wanted to encompass different qualities of his, whilst singing his praises through all the content. And I wanted to make it funny.

We reviewed each other's progress after a week, and gave each other clear 'client feedback', including what we liked, disliked, requests for changes/additions, and suggestions. This is the point I got permission to whack Gurmukh's face on an Arnie body from his hencher days.

We also used our meeting to review each other's code, from which we were able to give each other ideas for code structure and pointers to CSS properties.

Following the feedback, I needed to make the website responsive, with specific reference to the navigation menu in the header. I considered making it a dropdown on mobile, but the solutions I found used javascript (as yet, unlearned!) So, instead I solved the problem using CSS as so the menu stacks orderly on mobile.

If I was to built it again, I would look to use flexbox to position the header, as so to ensure the header section is adaptable to it's child elements (lost when using _float_).

Overall, I'm happy with the end product, and look forward to utilising javascript in future sites.

