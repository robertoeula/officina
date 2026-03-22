# Officina

### Contents

- [About the project](#about-the-project)
- [Behind the design](#behind-the-design)
- [Questions & Feedback / Contribution](#questions--feedback--contribution)
- [License](#license)
<br />
<br />

<a href="./images/logo.jpg"><img src="./images/logo.jpg" width="100%" /></a>

## About the project

WHO: My name is Roberto and I define myself as a designer, whatever this work could mean to the reader. <br />
WHAT: Officina is a personal research project, a digital space documenting the analog time I spend reading and learning about everything behind design practice, from philosophy and design history to contemporary challenges for design as a profession or hobby. Its name is inspired by my working space ("Officina" means "workshop" or "garage" in Italian), but the idea was fueled, for not immediately understandable reasons, by reading *What Design Can't Do* by Silvio Lorusso. Inside Officina, the reader can find inputs regarding projects, books, exhibitions or talks, and my ideas or conclusions. <br />
WHERE: Officina will always be consultable from this repository or from the links in my social accounts. <br />
WHEN: The website was created in January 2026 and it has been updated periodically ever since. <br />
WHY: There are many reasons for this digital space. Mainly, I want to experiment with coding and AI and, at the same time, share my point of view about relevant topics for designers and creative people. <br />
PS: I would like to mention that I try to keep all my written words AI-free, since it is exactly the time I put (inefficiently) into writing that represents the purpose of this project. The texts on the website are written in my mother tongue: Italian.

### Project structure

*css/style.css*     - Main stylesheet <br />
*fonts/*            - Typography used in the website <br />
*images/*           - Images used in the website <br />
*banco.html*        - Page with texts and publications <br />
*index.html*        - Homepage <br />
*info.html*         - Information about me and the project <br />

## Behind the design

Officina is a personal website made with **Figma** and **ChatGPT**.

### Figma

[Figma project file](https://www.figma.com/design/QqO4yjAiyHMJTzyarqYoFv/Personal-projects?node-id=0-1&t=0N4SGpm9e4wGI0Ez-1)

Immediately after the first prompt asking for information about building a website, I realised I couldn't properly understand future AI inputs regarding layout and spacing for Officina without personally understanding how the website would look. <br />
My intention was to keep everything as simple as possible to give full attention to the content. Once the layout and some details were defined, I used Figma to go back and forth with VS Code. Many adjustments and decisions were made directly by looking at CSS and Live Server, but I am confident that I kept the design intention very close to the original Figma file.

### Prompts

I think it is important to share some of the prompts I used to make my process clearer and replicable. I used as my only AI tool the one and only ChatGPT in its free version (GPT-5.3). <br />

At the beginning, I asked some general questions to better understand what was necessary before even starting to ask for the code. <br />

> <br /> *I would like to start programming a website together, but first of all I would like to know about platforms or portals where I could publish the site, or the programs I should use to paste the code and review it. I would like to understand what ecosystem I should work within. I have a Windows laptop.* <br /><br />

I gave ChatGPT some references of simple and personal websites and we created the GitHub repository and the project files.<br />

> <br /> *I would like to start with a homepage and some separate pages, but I like the approach of the website [...] where the elements are not in a bar at the top but arranged vertically on the left and open windows on the right. However, this might create problems on mobile, so it would be necessary to maintain two versions. To start, I would say to create a homepage, a page with information about me and about the site itself with contacts at the bottom, and a project page titled Banco where I will gather my texts and publications directly on the site. In order: homepage (which will open by clicking on the site title “Officina”), Banco where I will publish the things I write, and then Informazioni; these three elements arranged vertically as in the site [...] rather than only in the top bar.* <br /><br />

I later wrote short practical prompts about the workflow between VS Code and GitHub and I started refining typography and spacing in style.css.<br />

> <br /> *The name “box 1” does not satisfy me very much. I would like something analogous related to the working-class and workshop environment but suitable as an analogy for being a container of reflections on topics I care about and books I have read. In addition, I would like you to resize the texts of the sidebar to 16px, set the body text on the various pages to 20px and the titles to 32px. I would like the sidebar buttons to be 60px high and positioned 120px from the left edge, raising their container to 271px from the bottom edge. I would make the background color CCCCCC and introduce the text “My name” at the top left as a kind of signature with size 16 and color 666666, spaced 60px from the top edge and 120px from the left edge. Thank you.* <br /><br />

<br /> *[index.html] This is index.html: From what we discussed before, I notice some errors such as the word “Officina” not being clickable and the non-uniform spacing between the three pages (Officina, Banco and Informazioni).* <br /><br />

Some prompts may differ from the originals in syntax and punctuation. The length and meaning of the texts remain unchanged.

## Questions & Feedback / Contribution

Open an issue or contact me:

Blah blah blah

Officina is a personal project but always open to contributions and suggestions. In particular, I am always looking for:

Related references and readings connected to the topics discussed;
...

## License
Officina is licensed under the **MIT License**. For more details, please see the LICENSE file in the project repository.
