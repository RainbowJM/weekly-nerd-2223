# Introduction
As part of the Minor Web Development and Design, each week we have a guest lecture.
Date: 7 June 2023

Pre CSS day by Sophie Koonin, Adam Argyle & Google Chrome team

## Pre CSS Day
### Sophie Koonin
SopSophie Koonin, a web engineering lead at Monzo, has a unique goal of reviving the quirky and humorous website styles of the 2000s. 
In a captivating showcase, she presented a website she built using modern and accessible HTML, CSS, and JavaScript, while incorporating the nostalgic aesthetics of the 2000s.

One of Sophie's key focuses is accommodating user preferences. 
She emphasized the importance of allowing users to disable animations and autoplay features. 
Sophie achieves this by utilizing media queries such as prefers-reduced-motion. To ensure a smooth experience, she leverages the HTML source attribute to load static versions of gifs and videos.

During her presentation, Sophie demonstrated how to create a 2000s WordArt effect using modern CSS techniques. 
By utilizing the CSS property background-clip: text; and applying a drop shadow to the wrapper, she achieved a simulated 3D effect reminiscent of that era.

Sophie also highlighted the evolution of web practices, specifically mentioning that audio autoplay is no longer favored. 
Instead, she advocates for audio to be "opt-in" only, allowing users to choose whether they want to engage with audio elements on a website.

Recalling a popular trend from the 2000s, Sophie shared her creation of a webring for silly and funny websites. 
To implement this, she used Google Sheets, interlinking various websites in a network reminiscent of the past.

Additionally, Sophie developed a guestbook using Mastodon, a federated social network. 
This serves as an alternative to leaving messages directly on websites, providing a more interactive and connected experience for visitors.

Through her showcase, Sophie Koonin brings together the best of both worlds, combining modern web development practices with the nostalgic charm of the 2000s web era.

### Adam Argyle
During the presentation, Adam Argyle introduced us to the concept of CSS variable fonts, which offer multiple variations of a font within a single font file. 
This innovative approach allows developers to manipulate font attributes such as weight, width, slant, and even morphing using CSS. 
With this flexibility, designers can easily customize and fine-tune typography to achieve their desired visual effects.

In addition to variable fonts, Argyle also discussed the LCH color model, which provides a more accurate representation of human-perceived color compared to the traditional RGB model. 
The LCH model stands for lightness (L), chroma (C), and hue (H), and it allows for more precise control over color variations. 
This advanced color model empowers designers to create captivating and visually appealing palettes that closely align with their intended artistic expression.

To demonstrate the practical implementation of these concepts, Adam showcased a website he created called "https://gradient.style." 
This website serves as a powerful tool for generating gradients and exploring color possibilities in the LCH color space. 
By leveraging this resource, designers can easily experiment with different color combinations and gradients, resulting in visually striking and harmonious designs.

Adam Argyle's talk provided valuable insights into the world of CSS variable fonts and the LCH color model, empowering developers and designers to push the boundaries of typography and color in their web projects.

### Debugging with DevTools
The browser devtools are indispensable tools for developers, aiding in troubleshooting various aspects of web development, such as HTML, CSS, JavaScript, and network requests. 
The dedicated devtools team at Chrome has been working diligently to ensure that the tooling not only exposes information but also presents it in a user-friendly and comprehensible manner.

One of the key offerings of DevTools is CSS authoring hints, which provide insights into inactive styles or selectors and indicate specificity, helping developers identify and resolve CSS-related issues more efficiently. 
Given the rapid evolution of CSS features, the DevTools team strives to stay up-to-date with the latest advancements. 
As a result, new features have been introduced, including color debugging and conversion, animation timing, container queries, and scroll-driven animations.

Through these advancements, DevTools continues to enhance the developer experience, empowering them to navigate and optimize their code with greater ease. 
By streamlining the debugging and development process, DevTools plays a pivotal role in ensuring a smoother and more productive web development workflow.
