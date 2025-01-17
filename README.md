# Diversity & Inclusion


## Project Brief

**External User’s Goal:** The user wants to gain a basic understanding of diversity and inclusion in the workplace or educational environment. They seek straightforward information and tips presented in a clear, organised format.

**Site Owner’s Goal:** The site owner aims to create a visually appealing, easy-to-navigate webpage that introduces diversity and inclusion concepts and offers basic guidance on how to implement these practices. The focus is on clear communication through effective use of HTML and CSS, utilising Bootstrap for layout and design.

### Potential Features might Include:

- **Hero Section:** Use Bootstrap’s Jumbotron or a well-designed header section to introduce the topic with a compelling message and a simple background image or colour.
- **Information Sections:** Organise content into clear sections using Bootstrap’s grid system with headings and paragraphs that outline key principles of diversity and inclusion.
- **List of Tips:** A simple list of tips or best practices styled using Bootstrap’s list group component to help users understand how to promote diversity.
- **Resource Links:** Use Bootstrap’s button styling for links to external resources, making them easy to identify and click.


# Contents

- [Intro](#Intro)
- [Features](#Features)
- [Wireframes](#Development-Considerations)
- [Use of AI](#Use-of-AI)
- [Testing](#Testing)
- [Deployment](#Deployment)
- [Credits](#Credits)

# Introduction
The goal for this website is for new and experienced users to learn about Diversity and Inclusion, either as; a business, an organisation, a charity, or an individual.

Therefore, the site needs a homepage that can introduce the topics to a new learner/user of the topic, as well as a navigation that experienced learners/users can use to access additional or more full information.

Finally, for additional learning, the site needs to host several external resources or links to further educate on the topic.

[Back to Contents](#Contents)

# Features

> Fully responsive fixed navbar.

- Links to; Home (hero), Introduction (opener), Tips (policy implementation tips), Diversity, Inclusion, Links (external link cards to further resources)
- The fixed navbar ensures navigation is always visible and available for ease of use.
- Burger toggle collapsable navbar for mobile and tablet, and full navbar (no dropdown) for laptops and desktops.

> Hero section with inspirational quote.

- Eases users into the subject, and gives the correct emotive feel (positivity) of the subject matter.
- Fixed hero image with quote overlay, ensures the quote can always be read regardless of scroll.
- Adjusts size of hero and quote for all devices, to ensure visibility and ease to read quote.

> Introduction (What is Diversity & Inclusion?) section.

- Fully responsive, and fills whitespace throughout all devices.
- Split unordered list helps to eliminate this whitespace on larger devices.

> Information sections. (Diversity, Inclusion sections)

> Tips section.
- Fully responsive, with titles and text size matching when split into 2x2 row and columns on larger devices.

> Links section.
- Fully responsive, 1x6 column and rows for small devices, 2x3 column and rows for medium devices, finally 3x2 column and rows for larger devices.
- Links within card component allows easy editing or change of links, and for updating or changing their styling.

> Footer.

[Back to Contents](#Contents)

# Wireframes

Note, this is not an exhaustive list of all wireframe images, the full low-fidelity wireframe can be viewed via the attached pdf's at the end of this section.

![Home](https://github.com/user-attachments/assets/97f0c31a-bbff-414a-9952-ce673e798957)
![Introduction](https://github.com/user-attachments/assets/b8ac0a26-c0a5-4942-ac84-6f83ac3800ac)
![Links](https://github.com/user-attachments/assets/6c460b72-57c6-4b50-be0b-66fa53bba953)


![Introduction](https://github.com/user-attachments/assets/22e36899-21ee-413d-a386-d07544b3c1c8)
![Links](https://github.com/user-attachments/assets/dfcafd1e-f8ea-41f3-9a59-b60994eeae51)


![Introduction](https://github.com/user-attachments/assets/e9487dae-2d6c-419f-999e-ea216ee1f107)
![Links](https://github.com/user-attachments/assets/d067a331-1922-4627-8d29-d5d41484ba3c)



- [Mobile wireframe PDF](https://github.com/user-attachments/files/18398785/D.I.-.mobile.pdf)
- [Tablet wireframe PDF](https://github.com/user-attachments/files/18398786/D.I.-.tablet.pdf)
- [Laptop wireframe PDF](https://github.com/user-attachments/files/18398788/D.I.-.laptop.pdf)
- [Desktop wireframe PDF](https://github.com/user-attachments/files/18398791/D.I.-.desktop.pdf)

[Back to Contents](#Contents)

# Use of AI

I used AI at times to rapidly build css template style rules, before modifying them further with my own declarations within the style rule.

I also used AI for generating text content for the Diversity and Inclusion information sections.

The use of AI within this project allowed for a more rapid development, by allowing myself to focus on design decisions rather than content. However I found it unnecessary to use AI to create large sections of code (especially in the HTML) because I have a good understanding of HTML and CSS, and with the emmet extension auto-complete features I found that this automation already provided a significant improvement to code writing time. I feared that having AI create large sections of code would not save time, as it would generate code I might not understand, or might have significant bloat within it that would take time to modify. This fear came from earlier work in my independent learning from the course.

[Back to Contents](#Contents)

# Testing

1. HTML no errors were found when passed through the W3C Markup validator.
- One warning is shown for the use of an aria-label on a background image div tag, however this is an accepted method to provide alt text for background images.
2. CSS no errors were found when passed through the W3C CSS validator.

Whilst testing, I used Firefox for desktop and resized the viewport using development tools, and also tested the site on my mobile. However during public testing, a user noticed that Chromium browsers for desktop render the site with a horizontal scroll bar, with about 10-20 pixels off to the right of the site.

[Back to Contents](#Contents)

# Deployment

1. Clone the repository
``` git clone https://github.com/mogr20/diversity-inclusion.git ```
2. Open ```index.html``` in your web browser to view the website.

[Back to Contents](#Contents)

# Credits
AI generated text content was used for a large amount of the Diversity, and Inclusion pages.

Some AI generated code was used as a template, before being modified or added to.

Bootstrap v5.3.3 was used to rapidly create this website, using pre-built navbar and card templates, with added personal CSS to modify or override and give the site its own styling.

Google fonts; Quicksand, and Outfit.

Fontawesome was used for some icons on the site.

Repository template provided by Code Institute.

### Images

![hero-image.webp](https://github.com/user-attachments/assets/cc7d240f-f7b8-44ef-ac24-141d19b75da6)
- [Fauxels](https://www.pexels.com/@fauxels/), stock image via the pexels site.
<br> <br>

![intro-image.webp](https://github.com/user-attachments/assets/bcd5479f-63c3-438a-9c34-0af013a4ca4a)
- [Antoni Shkraba](https://www.pexels.com/@shkrabaanthony/), stock image via the pexels site.
<br> <br>

![acas-logo.webp](https://raw.githubusercontent.com/mogr20/diversity-inclusion/refs/heads/main/assets/images/acas-logo.webp)
- [ACAS](https://www.acas.org.uk/), logo from the ACAS website.
<br> <br>

![equalities-office.webp](https://raw.githubusercontent.com/mogr20/diversity-inclusion/refs/heads/main/assets/images/equalities-office.webp)
- [Gov Office Equality](https://www.gov.uk/government/organisations/office-for-equality-and-opportunity), logo from the Government Office for Equality and Opportunity.
<br> <br>

![business-disability-forum.webp](https://raw.githubusercontent.com/mogr20/diversity-inclusion/refs/heads/main/assets/images/business-disability-forum.webp)
- [Business Disablity Forum](https://businessdisabilityforum.org.uk/) logo from the Business Disability Forum.
<br> <br>

![diversity-uk.webp](https://raw.githubusercontent.com/mogr20/diversity-inclusion/refs/heads/main/assets/images/diversity-uk.webp)
- [Diversity UK](https://diversityuk.org/) logo from the Diversity UK site.
<br> <br>

![equality-and-human-rights-commission.webp](https://raw.githubusercontent.com/mogr20/diversity-inclusion/refs/heads/main/assets/images/equality-and-human-rights-commission.webp)
- [Equality and Human Rights Commission](https://www.equalityhumanrights.com/) logo from the EHRC website.
<br> <br>

![ew-group-logo.webp](https://raw.githubusercontent.com/mogr20/diversity-inclusion/refs/heads/main/assets/images/ew-group-logo.webp)
- [EW Group](https://theewgroup.com/) logo from the EW Group.
<br> <br>

[Back to Contents](#Contents)
