# The Developer Roadmaps Handbook

A practical, opinionated learning guide covering eight career tracks: Frontend, Backend, Android, iOS, Flutter, DevOps, Blockchain and Data Science. Every track comes with a curated list of free resources and a 30-day plan you can actually follow.

This is not a magic promise that you will become job-ready in a month. Thirty days is enough to get through the fundamentals, build something real, and find out whether you enjoy the path. That is a far better outcome than spending three months watching tutorials and never writing any code.

---

## How to use this handbook

You do not need to read this top to bottom. Here is the short version:

1. Pick one track from the table below. Only one. Resist the urge to start three at once.
2. Read the 30-day system section once so you understand the rhythm.
3. Jump to your track, follow the day-by-day plan, and use the resource lists underneath as your library.
4. Build the small project attached to each week. Watching is not learning; building is.
5. Adjust the pace using the pace dial if 30 days feels too fast or too slow for your life.

Some resources appear in more than one track (Git, Linux, Docker, how the internet works). That is deliberate. Those topics are the shared foundation of almost everything in software, and repetition across tracks is a sign they matter.

A note on links: this handbook points to third-party sites, videos and courses. Some will move, change or disappear over time. If a link is dead, search for the title and author; most of these have been mirrored or replaced.

---

## Pick your track

Not sure where to begin? Match your interest to a track.

| If you like... | Consider | Main language(s) | Typical first project |
|---|---|---|---|
| Building things people see and click | Frontend | HTML, CSS, JavaScript | A responsive personal site, then a small React app |
| Logic, databases, and how systems talk to each other | Backend | JavaScript (Node.js), SQL | A REST API with a database |
| Apps on the phone in your pocket, on the most common OS | Android | Kotlin | A tip calculator, then a networked app |
| Polished apps in the Apple ecosystem | iOS | Swift | A SwiftUI app that calls an API |
| One codebase for both phones | Flutter | Dart | A multi-screen app with state management |
| Servers, automation, keeping things running | DevOps | Go, Bash, YAML | A containerised app with a CI pipeline |
| Decentralised systems and smart contracts | Blockchain | Solidity | A simple smart contract with a web front end |
| Numbers, patterns, and predictions | Data Science | Python, SQL, R | An end-to-end ML project with a small deployment |

If you are a complete beginner and torn, Frontend and Data Science have the gentlest on-ramps. Backend is a natural second step after Frontend. DevOps is much easier after you have built and deployed at least one application.

---

## The 30-day system

### The shape of the month

Every track follows the same four-week arc, even though the topics differ:

| Week | Days | Theme | What it feels like |
|---|---|---|---|
| Week 1 | 1 to 7 | Foundations | Getting oriented, learning the vocabulary, setting up tools |
| Week 2 | 8 to 14 | Core skills | The main language or platform, lots of small exercises |
| Week 3 | 15 to 21 | Depth and tooling | The ecosystem around the core: data, networking, frameworks |
| Week 4 | 22 to 30 | Integration and shipping | Bringing it together in a real project you can show people |

### A daily rhythm that works

Whether you have one hour or four, structure each session the same way:

- **Warm-up (10 minutes).** Redo yesterday's last exercise from memory, or review your notes. Retrieval beats re-reading.
- **Learn (30 to 90 minutes).** One video, one article, or one chapter. Not five.
- **Build (30 to 120 minutes).** Apply it immediately. Type the code yourself; do not copy and paste.
- **Log (5 minutes).** Write three lines in a learning journal: what you did, what confused you, what you will do tomorrow.

### The pace dial

Life gets in the way. Pick the dial that matches your reality and be honest about it.

| Mode | Time per day | How to adapt the plan |
|---|---|---|
| Sprint | 4 hours or more | Follow the plan exactly. Add a stretch goal from the resource list each day. |
| Steady | 2 to 3 hours | Follow the plan exactly. Skip the optional resources. |
| Gentle | 1 hour | Treat the 30 days as 60. Each plan day becomes two days. |
| Weekend warrior | Weekends only | Treat each week as a month. Do two plan days per weekend day. |

If you fall behind, do not try to "catch up" by doubling your workload. Simply resume from where you left off. The plan is a guide, not a contract.

### Rules that keep you honest

1. **One resource per topic.** Pick the video or article that suits you and finish it. If it truly does not click after 20 minutes, switch to another from the list, but only once.
2. **Build something every week.** By Sunday of each week, you should have a small working thing, even if it is ugly.
3. **Never skip the log.** Five minutes of writing is the cheapest way to notice patterns in what you find hard.
4. **Ask for help after 30 minutes of being stuck.** Not 3 minutes, not 3 hours.
5. **Rest one day per week.** Your brain consolidates learning while you are away from the screen.

### Your progress tracker

Copy this into a notes file and tick things off.

```
Week 1  [ ] Day 1  [ ] Day 2  [ ] Day 3  [ ] Day 4  [ ] Day 5  [ ] Day 6  [ ] Day 7
Week 2  [ ] Day 8  [ ] Day 9  [ ] Day 10 [ ] Day 11 [ ] Day 12 [ ] Day 13 [ ] Day 14
Week 3  [ ] Day 15 [ ] Day 16 [ ] Day 17 [ ] Day 18 [ ] Day 19 [ ] Day 20 [ ] Day 21
Week 4  [ ] Day 22 [ ] Day 23 [ ] Day 24 [ ] Day 25 [ ] Day 26 [ ] Day 27 [ ] Day 28 [ ] Day 29 [ ] Day 30

Weekly build:
  Week 1: ______________________
  Week 2: ______________________
  Week 3: ______________________
  Week 4: ______________________ (capstone)
```

### Adapting the plan to your background

- **Total beginner:** Follow the plan as written and use the Gentle pace if needed.
- **Some programming experience:** Compress the first week into three days and spend the savings on the capstone.
- **Switching from another track:** Skip the shared-foundation days (internet, Git, Linux basics) and go straight to the track-specific material.
- **Working full time:** Steady or Gentle mode. Consistency matters more than intensity.

---

## Track 1: Frontend Development

**Who this is for:** Anyone who wants to build websites and web apps that people interact with directly.
**What you will be able to do after 30 days:** Build and style responsive pages, add interactivity with JavaScript, use Git and npm, and build a small React application.
**Prerequisites:** None.

### 30-day plan

| Days | Focus | What to do |
|---|---|---|
| 1 | What frontend development is | Read one "what is a frontend developer" article and watch the Mayuko overview. Set up an editor and a browser with dev tools open. |
| 2 | How the internet works | Watch the Vox video and read the MDN article. Learn what DNS, HTTP and a browser request actually are. |
| 3 to 4 | HTML fundamentals | Work through the freeCodeCamp HTML video or web.dev's Learn HTML. Cover tags, links, images, lists, forms and tables. |
| 5 | Semantic HTML and SEO basics | Read the MDN semantics glossary entry and the HTML best practices. Rewrite an earlier page with proper semantic tags. |
| 6 to 7 | First project | Build a personal profile page in pure HTML. Try one Frontend Mentor or iCodeThis challenge. |
| 8 to 9 | CSS fundamentals | Learn selectors, the box model, colours, typography. Follow web.dev's Learn CSS or Kevin Powell. |
| 10 | Flexbox | Play Flexbox Froggy, then read the CSS-Tricks flexbox guide. |
| 11 | Grid | Play CSS Grid Garden, then read the CSS-Tricks grid guide. |
| 12 | Responsive design | Read the Webflow responsive design guide. Make your profile page work on a phone. |
| 13 to 14 | CSS project | Style your profile page fully, or build a Frontend Practice challenge. Play CSS Diner for fun. |
| 15 to 17 | JavaScript basics | Variables, types, functions, loops, arrays, objects. Use the freeCodeCamp video or javascript.info. |
| 18 | DOM manipulation | Watch the DOM manipulation video. Build a to-do list with add and delete. |
| 19 | JavaScript practice | Play Elevator Saga or try a few Exercism problems. |
| 20 | Version control | Learn Git basics. Push your projects to GitHub. |
| 21 | Package managers and build tools | Understand what npm does and why build tools exist. Install a package and run a build. |
| 22 to 25 | React | Follow the React docs or a tutorial. Cover components, props, state, effects. Rebuild your to-do list in React. |
| 26 | Routing and state | Skim the React Router and Redux playlists. Add a second page to your app. |
| 27 | CSS framework | Try Tailwind with the Traversy crash course. Restyle your app with it. |
| 28 | Meta frameworks and PWAs | Read the meta-frameworks intro and try a Next.js tutorial. Learn what makes an app a PWA. |
| 29 | Accessibility and privacy | Work through web.dev's Learn Accessibility. Audit your project. |
| 30 | Capstone | Polish, deploy and write a README for your best project. |

If you prefer Vue or Angular over React, replace days 22 to 26 with the official docs and tutorials in the Vue or Angular sections below.

### Resources

#### Introduction

What is a front end developer:

- [What is a frontend developer? - frontendmasters.com](https://frontendmasters.com/guides/front-end-handbook/2018/what-is-a-FD.html)
- [Frontend web developer - Mozilla Developer docs](https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer)
- [What is frontend development - Freecodecamp](https://www.freecodecamp.org/news/front-end-developer-what-is-front-end-development-explained-in-plain-english/)

What is frontend web development:

- [Frontend Development explained - Mayuko(Youtube)](https://www.youtube.com/watch?v=qyHyFsT7Hig)
- [Frontend web development - Wikipedia](https://en.wikipedia.org/wiki/Front-end_web_development)

#### Understanding the internet

- [Computer Networking course - Kunal Kushwaha(Youtube)](https://www.youtube.com/watch?v=IPvYjXCsTg8)
- [How the Internet Travel Across Oceans? - TechVision(Youtube)](https://www.youtube.com/watch?v=yd1JhZzoS6A)
- [How does the Internet Work? - Vox(Youtube)](https://www.youtube.com/watch?v=TNQsmPf24go)
- [How does the Internet Work? - Mozilla web docs](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)
- [How Does the Internet Work? - Stanford.edu](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)
- [How Does the Internet Work? - cloudflare](https://www.cloudflare.com/en-in/learning/network-layer/how-does-the-internet-work/)
- [How Does the Internet Work? - Lesics(Youtube)](https://www.youtube.com/watch?v=x3c1ih2NJEg)
- [What is DNS? | How DNS works](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
- [Internet - CS50's understanding technology](https://www.youtube.com/watch?v=n_KghQP86Sw)

#### HTML

- [Learn HTML - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=kUMe1FH4CHE)
- [Learn HTML - Codecademy](https://www.codecademy.com/learn/learn-html)
- [Learn HTML - web.dev](https://web.dev/learn/html/)
- [HTML Tutorial - W3schools](https://www.w3schools.com/html/)
- [HTML Tutorial - TutorialsPoint](https://www.tutorialspoint.com/html/index.htm)
- [HTML course, build a website - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=pQN-pnXPaVg)
- [HTML crash course - Traversy Media(Youtube)](https://www.youtube.com/watch?v=UB1O30fR-EE)
- [HTML Tutorial, making a Website - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=PlxWf493en4)
- [Semantics - MDN Web Docs Glossary](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [Basics of SEO](https://github.com/seo/guide)
- [HTML best practices](https://github.com/hail2u/html-best-practices)

#### CSS

- [Learn CSS - web.dev](https://web.dev/learn/css/)
- [Learn CSS - codecademy](https://www.codecademy.com/learn/learn-css)
- [CSS tutorial - w3schools](https://www.w3schools.com/css/)
- [CSS zero to hero - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=1Rs2ND1ryYc)
- [Kevin Powell(Youtube)](https://www.youtube.com/kepowob)
- [Introduction to CSS - Web Dev Simplified](https://www.youtube.com/playlist?list=PLZlA0Gpn_vH9D0J0Mtp6lIiD_8046k3si)
- [The guide to responsive web design](https://webflow.com/blog/responsive-web-design)
- [Learn flexbox by gaming - Flexbox Froggy](https://flexboxfroggy.com/)
- [Learn Grid by gaming - CSS Grid Garden](https://cssgridgarden.com/)
- [Learn Hex Code by gaming - Hex Invaders](http://www.hexinvaders.com/)
- [CSS Diner](https://flukeout.github.io/)
- [A complete guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A complete guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [A complete guide to CSS from Mozilla](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

#### JavaScript

- [Learn JavaScript - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=PkZNo7MFNFg)
- [JavaScript Tutorial - Programming with Mosh(Youtube)](https://www.youtube.com/watch?v=W6NZfCO5SIk)
- [JavaScript Programming - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=jS4aFq5-91M)
- [JavaScript Tutorial - w3schools](https://www.w3schools.com/js/)
- [Learn JavaScript - Codecademy](https://www.codecademy.com/learn/introduction-to-javascript)
- [Learn DOM manipulation](https://www.youtube.com/watch?v=5fb2aPlgoys)
- [Free JS Courses for Beginners - FreeCodeCamp](https://www.freecodecamp.org/news/learn-javascript-free-js-courses-for-beginners/)
- [Exercism - free practice to master JS](https://exercism.org/)
- [30-Days-Of-JavaScript repository](https://github.com/Asabeneh/30-Days-Of-JavaScript)
- [Learn JavaScript - JavaScriptInfo](https://javascript.info/)
- [Elevator Saga Game](http://play.elevatorsaga.com/)
- [Codingame](https://www.codingame.com/start)
- [Dungeons and Developers](http://www.dungeonsanddevelopers.com/)
- [Namaste Javascript - Youtube](https://www.youtube.com/watch?v=pN6jk0uUrD8&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP)
- [Learn by reading blogs](https://nikk.hashnode.dev/series/javascript-series)
- [How JS works - Akshay Saini (playlist)](https://www.youtube.com/playlist?list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP)

#### Version control

- [Git Documentation](https://git-scm.com/docs/gittutorial)
- [Git Tutorial](https://www.youtube.com/watch?v=apGV9Kg7ics)

#### Package managers

- [What is NPM & why do we need it?](https://www.youtube.com/watch?v=P3aKRdUyr0s)
- [NPM crash course](https://www.youtube.com/watch?v=jHDhaSSKmB0)
- [Yarn package manager crash course](https://www.youtube.com/watch?v=g9_6KmiBISk)
- [Learn Package Manager](https://frontendmasters.com/guides/front-end-handbook/2018/learning/package-manager.html)
- [Javascript Package manager](https://www.freecodecamp.org/news/javascript-package-manager-npm-and-yarn/)
- [Learn Node.JS](https://www.youtube.com/watch?v=RLtyhwFtXQA)
- [Package management basics](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Package_management)

#### Build tools

- [What are build tools?](https://www.youtube.com/watch?v=V5qvWl-O-zE)
- [6 best build tools](https://www.developerdrive.com/best-build-tools-frontend-development/)
- [Learn build tools - Codecademy](https://www.codecademy.com/learn/learn-build-tools)
- [Making sense of front-end build tools - Freecodecamp](https://www.freecodecamp.org/news/making-sense-of-front-end-build-tools-3a1b3a87043b/)

#### Choosing a framework or library

- [Frameworks - Web Development](https://www.youtube.com/watch?v=W6KCPXl6Zuc)

**React**

- [React Tutorial - Freecodecamp(Youtube)](https://www.youtube.com/watch?v=bMknfKXIFA8)
- [React Tutorial - JavaScript Mastery(Youtube)](https://youtu.be/dyFVwXROzZk)
- [React Tutorial - Tapas Adhikary(Youtube)](https://www.youtube.com/playlist?list=PLIJrr73KDmRyrDnDFy-hHvQ24rRjz6e_J)
- [React Official Docs](https://react.dev/)
- [React Router Tutorial](https://www.youtube.com/playlist?list=PLC3y8-rFHvwjkxt8TOteFdT_YmzwpBlrG)
- [React Redux Tutorials](https://www.youtube.com/playlist?list=PLC3y8-rFHvwheJHvseC3I0HuYI2f46oAK)
- [30-Days-Of-React repository](https://github.com/Asabeneh/30-Days-Of-React)

**Vue**

- [Tutorial](https://www.youtube.com/watch?v=FXpIoQ_rT_c)
- [Docs](https://vuejs.org/tutorial/#step-1)

**Angular**

- [Angular Tutorial - Programming with Mosh(Youtube)](https://www.youtube.com/watch?v=k5E2AVpwsko)
- [Learn Angular - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=2OHbjep_WjQ)
- [Docs](https://angular.io/docs)

#### Meta frameworks

- [What is a meta framework](https://www.ombulabs.com/blog/javascript/what-is-a-javascript-meta-framework.html)

**Next.js**

- [Next Js Tutorial - Codevolution(Youtube)](https://www.youtube.com/watch?v=9P8mASSREYM&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH)
- [Next Js Tutorial - Traversy Media(Youtube)](https://www.youtube.com/watch?v=Y6KDk5iyrYE)
- [Docs](https://nextjs.org/docs)

**Gatsby**

- [Gatsby Tutorial - The Net Ninja(Youtube)](https://www.youtube.com/watch?v=Qms4k6y7OgI&list=PL4cUxeGkcC9hw1g77I35ZivVLe8k2nvjB)
- [Docs](https://www.gatsbyjs.com/docs/)

**Remix**

- [Remix Tutorial](https://www.youtube.com/watch?v=d_BhzHVV4aQ)
- [Docs](https://remix.run/)

#### CSS frameworks

- [Top CSS Frameworks](https://www.browserstack.com/guide/top-css-frameworks)
- [Tailwind vs MUI vs Bootstrap vs Chakra vs...](https://www.youtube.com/watch?v=CQuTF-bkOgc)

**Bootstrap:** [Tutorial](https://www.youtube.com/watch?v=-qfEOE4vtxE) and [Docs](https://getbootstrap.com/docs/5.2/getting-started/introduction/)

**Chakra UI:** [Chakra UI for beginners](https://www.chakrauiforbeginners.com/play), [Build a checkout page with Chakra UI](https://egghead.io/lessons/react-install-and-setup-chakra-ui-in-a-react-project) and [Docs](https://chakra-ui.com/getting-started)

**Tailwind CSS:** [Crash course 1 - Traversy Media](https://www.youtube.com/watch?v=UBOj6rqRUME), [Crash course 2 - Traversy Media](https://www.youtube.com/watch?v=dFgzHOX84xQ) and [Docs](https://tailwindcss.com/docs/installation)

#### Progressive Web Apps

- [PWA tutorial - The Net Ninja(Youtube)](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gTxqJBcDmoi5Q2pzDusSL7)
- [Progressive web apps - Mozilla developer docs](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
- [What are progressive web apps? - Freecodecamp](https://www.freecodecamp.org/news/what-are-progressive-web-apps/)
- [Progressive Web Apps - web.dev](https://web.dev/progressive-web-apps/)

#### Practice projects

- [frontendeval.com](https://www.frontendeval.com)
- [frontendmentor.io](https://www.frontendmentor.io/)
- [frontendpractice.com](https://www.frontendpractice.com/)
- [iCodeThis.com](https://www.icodethis.com/)

#### Level up

- [Learn Privacy](https://web.dev/learn/privacy/)
- [Learn Accessibility](https://web.dev/learn/accessibility/)

---

## Track 2: Backend Development

**Who this is for:** People who enjoy logic, data and systems, and want to build the engines behind applications.
**What you will be able to do after 30 days:** Build a REST API with Node.js and Express, connect it to a relational or NoSQL database, secure and test it, and package it in Docker.
**Prerequisites:** A little HTML and CSS helps. The plan includes a quick frontend primer.

### 30-day plan

| Days | Focus | What to do |
|---|---|---|
| 1 | What backend development is | Watch "What is Backend Development" and read the Upwork beginner's guide. |
| 2 | Frontend basics | Watch the frontend crash course, plus one HTML and one CSS video. Build one small page so you understand what your API will serve. |
| 3 to 4 | How the internet and HTTP work | Watch the Vox video and the Boot.dev HTTP course. Read the MDN HTTP overview. |
| 5 | Operating system basics | Watch Jenny's Lectures intro. Understand processes, memory and the file system. |
| 6 to 7 | Linux terminal | Follow the complete Linux course and practise the basic commands daily. |
| 8 to 10 | Node.js | Watch the Traversy crash course. Read the Node docs. Write small scripts and use modules. |
| 11 | Git | Learn the basics from the Git docs and tutorial. Put every project on GitHub. |
| 12 to 13 | Relational databases and SQL | Watch the Postgres freeCodeCamp tutorial. Design tables, run joins, write queries. |
| 14 | Node with Postgres | Follow the Node and PostgreSQL project playlist. |
| 15 to 16 | NoSQL and MongoDB | Learn what NoSQL is, watch SQL vs NoSQL, then work through MongoDB basics. |
| 17 to 19 | APIs with Express | Build a REST API following Programming with Mosh or Web Dev Simplified. |
| 20 | MVC | Restructure your API into routes, controllers and models. |
| 21 | Caching | Learn client-side caching, server-side caching, and what a CDN does. |
| 22 | Web security | Study HTTPS, use Helmet in Express, and read Node security best practices. |
| 23 to 24 | Testing | Write tests with Jest or Mocha. Test your API endpoints. Read about TDD. |
| 25 to 26 | Docker | Watch a Docker tutorial and containerise your API. |
| 27 | Web servers and deployment | Learn what a web server is and follow a deployment tutorial. |
| 28 | Microservices concepts | Watch the microservices overview. You do not need to build one yet. |
| 29 to 30 | Capstone | Finish, test, containerise and deploy your API. Write documentation. |

### Resources

#### Introduction to backend development

- [What is Backend Development](https://www.youtube.com/watch?v=cbSrsYiRamo) (recommended)
- [Introduction to Backend Development](https://dev.to/kaperskyguru/introduction-to-backend-development-506a)
- [Back-end Developer Career Path](https://boot.dev/tracks/backend)
- [How Backend works](https://www.youtube.com/watch?v=4r6WdaY3SOA)
- [Guide to Backend Development](https://www.upwork.com/resources/beginners-guide-back-end-development)

#### Basics of frontend

- [Frontend Developer crash course](https://www.youtube.com/watch?v=QA0XpGhiz5w)
- [CSS](https://www.youtube.com/watch?v=1Rs2ND1ryYc)
- [HTML](https://www.youtube.com/watch?v=kUMe1FH4CHE)
- Build a project: [frontendpractice.com](https://www.frontendpractice.com/) and [frontendmentor.io](https://www.frontendmentor.io/)

#### Understanding the internet

- [Computer Networking course - Kunal Kushwaha(Youtube)](https://www.youtube.com/watch?v=IPvYjXCsTg8)
- [How does the Internet Work? - Vox(Youtube)](https://www.youtube.com/watch?v=TNQsmPf24go) (recommended)
- [Mozilla web docs](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)
- [Stanford.edu](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)
- [Cloudflare](https://www.cloudflare.com/en-in/learning/network-layer/how-does-the-internet-work/)
- [Lesics(Youtube)](https://www.youtube.com/watch?v=x3c1ih2NJEg)
- [Internet - CS50's understanding technology](https://www.youtube.com/watch?v=n_KghQP86Sw)
- [Full HTTP Networking Course - Boot.dev](https://www.youtube.com/watch?v=2JYT5f2isg4) (recommended)
- [An overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
- [How Web Browsers work](https://web.dev/howbrowserswork/)

#### Operating system basics

- [Introduction to operating systems - Jenny's Lectures(Youtube)](https://www.youtube.com/watch?v=RozoeWzT7IM) (recommended)
- [Operating system basics - Geek's Lesson(Youtube)](https://www.youtube.com/watch?v=6-mdtMKfEYM)
- [How do operating systems work? - ClickView(Youtube)](https://www.youtube.com/watch?v=GjNp0bBrjmU)
- [What is an operating system - Techquickie(Youtube)](https://www.youtube.com/watch?v=pVzRTmdd9j0)
- [Operating system tutorial - Tutorialspoint](<https://www.tutorialspoint.com/operating_system/index.htm#:~:text=An%20Operating%20System%20(OS)%20is%20an%20interface%20between%20a%20computer,as%20disk%20drives%20and%20printers.>)
- [Operating System Tutorial - Guru99](https://www.guru99.com/os-tutorial.html)

#### Linux terminal basics

- [Complete Linux Course](https://www.youtube.com/watch?v=iwolPf6kN-k) (recommended)
- [Introduction to Linux - Full Course for Beginners By FreeCodeCamp](https://youtu.be/sWbUDq4S6Y8)
- [Linux Masterclass Course - Apoorv Goyal(YouTube)](https://www.youtube.com/playlist?list=PL2kSRH_DmWVZp_cu6MMPWkgYh7GZVFS6i)
- [Linux Tutorial](https://www.youtube.com/watch?v=cBokz0LTizk)
- [Basic Linux Commands](https://www.youtube.com/watch?v=J2zquYPJbWY) (recommended)
- [Linux Command Cheatsheet](https://www.guru99.com/linux-commands-cheat-sheet.html)

#### JavaScript with Node.js

- [Node.js Crash Course - Traversy Media(Youtube)](https://www.youtube.com/watch?v=fBNz5xF-Kx4) (recommended)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Node.js tutorial - Programming with Mosh(Youtube)](https://www.youtube.com/watch?v=TlB_eWDSMt4)
- [Node.js crash course playlist - The Net Ninja(Youtube)](https://www.youtube.com/playlist?list=PL4cUxeGkcC9jsz4LDYc6kv3ymONOKxwBU)
- [Node.js and express.js course - freecodecamp(Youtube)](https://www.youtube.com/watch?v=Oe421EPjeBE)
- [Express js Getting started](https://expressjs.com/en/starter/installing.html)

#### Version control

- [Git documentation](https://git-scm.com/docs/gittutorial)
- [Git Tutorial](https://www.youtube.com/watch?v=apGV9Kg7ics&t=1964s)

#### Relational databases and PostgreSQL

- [Learn SQL and Relational Databases - Boot.dev](https://boot.dev/learn/learn-sql)
- [What is Relational Databases](https://www.youtube.com/watch?v=OqjJjpjDRLc)
- [PostgreSQL Tutorial - freecodecamp(Youtube)](https://www.youtube.com/watch?v=qw--VYLpxG4) (recommended)
- [PostgreSQL Course - Amigoscode(Youtube)](https://www.youtube.com/playlist?list=PLwvrYc43l1MxAEOI_KwGe8l42uJxMoKeS)
- [PostgreSQL Course - DataZ(Youtube)](https://www.youtube.com/watch?v=Ir7nScz_Vs4)
- [postgresqltutorial.com](https://www.postgresqltutorial.com/)
- Project: [Nodejs and PostgreSQL Project](https://www.youtube.com/playlist?list=PLillGF-RfqbaEmlPcX5e_ejaK7Y5MydkW)

#### NoSQL databases and MongoDB

- [What is NoSQL Databases?](https://www.youtube.com/watch?v=uD3p_rZPBUQ)
- [SQL vs NoSQL](https://www.youtube.com/watch?v=Q5aTUc7c4jg)
- [MongoDB Tutorial - Amigoscode(Youtube)](https://www.youtube.com/watch?v=Www6cTUymCY) (recommended)
- [Complete MongoDB Tutorial - The Net Ninja(Youtube)](https://www.youtube.com/playlist?list=PL4cUxeGkcC9h77dJ-QJlwGlZlTd4ecZOA)
- [Complete MongoDB Tutorial - DataZ(Youtube)](https://www.youtube.com/watch?v=GFaKsrfQkAc&t=9298s)
- [Introduction & getting started with MongoDB - MongoDB University M001](https://learn.mongodb.com/learning-paths/introduction-to-mongodb)
- Project: [Build a Markdown Blog with Node.js, Express and MongoDB](https://www.youtube.com/watch?v=1NrHkjlWVhM)

#### APIs

- [REST API with Node js & Express - Programming with Mosh(Youtube)](https://www.youtube.com/watch?v=pKd0Rpw7O48)
- [Back End Development and APIs - FreeCodeCamp](https://www.freecodecamp.org/learn/back-end-development-and-apis/)
- [Learn API Servers in Go - Boot.dev](https://boot.dev/learn/learn-web-servers)
- [REST API With Node.js, Express, & MongoDB - Web Dev Simplified(Youtube)](https://www.youtube.com/watch?v=fgTGADljAeg)
- [Build a Node.js API - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=fsCjFHuMXj0)
- [JSON APIs](https://www.youtube.com/watch?v=N-4prIh7t38)
- [APIs for Beginners 2023 - How to use an API (Full Course)](https://youtu.be/WXsD0ZgxjRw)

**Caching**

- [Client Side Caching](https://youtu.be/HiBDZgTNpXY)
- [Server side Caching](https://www.starwindsoftware.com/resource-library/server-side-caching/)
- [CDN (Content Delivery Network)](https://www.cloudflare.com/en-ca/learning/cdn/what-is-a-cdn/)

**MVC**

- [MVC explained - Web Dev Simplified(Youtube)](https://www.youtube.com/watch?v=DUg2SWWK18I)
- [Express Router & MVC - The Net Ninja(Youtube)](https://www.youtube.com/watch?v=zW_tZR0Ir3Q)

**Deployment**

- [Node.js & Express, Deploying an app - Traversy Media(Youtube)](https://www.youtube.com/watch?v=_GSOnHRYSS0)
- [Full Node.js Deployment - Traversy Media(Youtube)](https://www.youtube.com/watch?v=oykl1Ih9pMg)
- [Express Tutorial, Deploying to production - Mozilla web docs](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/deployment)

#### Microservices

- [What are Microservices?](https://www.youtube.com/watch?v=j3XufmvEMiM)
- [NodeJs Microservices](https://www.youtube.com/playlist?list=PLrwNNiB6YOA0KmfliJoSuZzEN6tjSdEXc)
- [Backend Development and API projects](https://www.freecodecamp.org/learn/back-end-development-and-apis/#mongodb-and-mongoose)
- [What is a microservices architecture and its advantages?](https://www.youtube.com/watch?v=qYhRvH9tJKw)

#### Web security

- [HTTPS and Web Security](https://www.youtube.com/watch?v=kBzbKUirOFk)
- [How Hackers use DevTools](https://www.youtube.com/watch?v=5mUUBkxayQ4)
- [Secure ExpressJS application with Helmet](https://www.youtube.com/watch?v=tGMPWVl_l9Y)
- [NodeJS Security Best Practices](https://blog.sqreen.com/nodejs-security-best-practices/)

#### Testing

- [Testing a Rest API](https://www.youtube.com/watch?v=I4BZQr-5mBY)
- [Jest Tutorial](https://www.youtube.com/watch?v=8gHEv5iNRKk)
- [Testing Node.js with Mocha](https://www.youtube.com/watch?v=Bs68k6xfR3E)
- [Test Driven Development](https://www.youtube.com/watch?v=ISAjES_Gklc)
- Docs: [Mocha](https://mochajs.org/), [Chai](https://www.chaijs.com/guide/), [Jest](https://jestjs.io/docs/getting-started), [Cucumber](https://cucumber.io/docs/guides/), [Pactum](https://pactumjs.github.io/guides/api-testing.html)

#### Containerisation with Docker

- [Containers Explained](https://www.youtube.com/watch?v=0qotVMX-J5s)
- [Docker Tutorial - Kunal Kushwaha(Youtube)](https://www.youtube.com/watch?v=17Bl31rlnRM) (recommended)
- [Docker Tutorial - TechWorld With Nana(Youtube)](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [Learn Docker - Boot.dev](https://boot.dev/learn/learn-docker)
- [Learn Docker - freecodecamp(Youtube)](https://www.youtube.com/watch?v=9zUHg7xjIqQ)
- [Docs](https://docs.docker.com/)
- Project: [Build a NodeJS application with Docker](https://www.youtube.com/watch?v=PsWeSg38XFY)

#### Web servers

- [Web servers and their working - Hussein Nasser(Youtube)](https://www.youtube.com/watch?v=JhpUch6lWMw)
- [What is a web server - Mozilla web docs](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server)
- [Web Server - Tutorialspoint](https://www.tutorialspoint.com/internet_technologies/web_servers.htm)
- [What is a web server? - NGINX](https://www.nginx.com/resources/glossary/web-server/)

#### Build projects

- [4 projects with Node.js/Express](https://www.youtube.com/watch?v=qwfE7fSVaZM)
- [Project Ideas](https://gist.github.com/MWins/41c6fec2122dd47fdfaca31924647499)
- [50 Node.js/Express Project with tutorial](https://www.youtube.com/playlist?list=PL9iaMyazOxXsIl-WQV9hoVmnHYy49DuVl)

---

## Track 3: Android Development

**Who this is for:** People who want to build apps for the world's most widely used mobile operating system.
**What you will be able to do after 30 days:** Write Kotlin, design screens with layouts and RecyclerViews, navigate between activities and fragments, call web APIs with Retrofit, and structure an app with a sensible architecture.
**Prerequisites:** Some programming exposure is helpful but not required.

### 30-day plan

| Days | Focus | What to do |
|---|---|---|
| 1 | Introduction to Android | Read the introduction and set up Android Studio using the setup video. Run the default app on an emulator. |
| 2 to 4 | Kotlin basics | Watch "Kotlin In 12 Minutes" first for the big picture, then the Kotlin course or full programming course. Practise variables, functions, classes and null safety. |
| 5 to 6 | Layouts and UI | Read the layouts and resources lesson. Build three simple screens with different layouts. |
| 7 | Week 1 build | A single-screen app such as a unit converter. |
| 8 | Event-based programming | Read the Android UI events docs. Handle clicks and input. |
| 9 to 10 | Views | Text and scroll views, buttons and clickable images. |
| 11 | RecyclerView | Display a scrolling list of items. This one concept powers a huge share of real apps. |
| 12 to 13 | Activities and intents | Understand the activity lifecycle. Start one activity from another and pass data. |
| 14 | Implicit intents | Open a web page, dial a number, or share text using implicit intents. Week 2 build: a tip calculator. |
| 15 to 16 | Networking basics | Watch the networking and API video and read the slides. |
| 17 to 18 | Retrofit | Fetch JSON from a public API and show it in a RecyclerView. |
| 19 to 20 | Fragments | Watch both fragment videos. Rebuild one screen using fragments. |
| 21 | Consolidation | Refactor your Week 3 app. Fix what feels messy. |
| 22 to 23 | Application architecture | Read Android's app architecture guide and watch the accompanying video. Separate UI, data and logic. |
| 24 to 29 | Practice project | Choose one of the practice projects (Yelp clone, tip calculator, My Maps) and build it end to end. |
| 30 | Ship and reflect | Clean up, test on a real device if possible, write a README with screenshots. |

### Resources

#### Introduction

- [Introduction To Android](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/unit-1-get-started/lesson-1-build-your-first-app/1-0-c-introduction-to-android/1-0-c-introduction-to-android.html)
- [Android Studio Setup](https://youtu.be/4M0hNugPJV8)
- [Notes-Slides](https://piazza.com/class_profile/get_resource/ktlu0ly5db84bb/kubkxvhvj8g66m)

#### Introduction to Kotlin

- [Notes-Slides](https://piazza.com/class_profile/get_resource/ktlu0ly5db84bb/kubl00rkflpx8)
- [Introduction To Kotlin](https://youtu.be/X1RVYt2QKQE)
- [Kotlin In 12 Minutes](https://youtu.be/iYrgWO2oibY)
- [Kotlin Course](https://developer.android.com/courses/pathways/android-basics-kotlin-one)
- [Kotlin Programming Full Course](https://youtu.be/EExSSotojVI)

#### Layouts and UI

- [Notes-Slides](https://piazza.com/class_profile/get_resource/ktlu0ly5db84bb/kubrwffwj8459a)
- [Layouts And UI](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/unit-1-get-started/lesson-1-build-your-first-app/1-2-c-layouts-and-resources-for-the-ui/1-2-c-layouts-and-resources-for-the-ui.html)
- [Layouts, UI & Responding To User Input](https://youtu.be/o1SZJNYJ7vg)

#### Event-based programming

- [Developer Docs](https://developer.android.com/guide/topics/ui/ui-events)
- [Event Handlers](https://youtu.be/LV_5lOvYAn8)

#### Views

- [Notes-Slides](https://piazza.com/class_profile/get_resource/ktlu0ly5db84bb/kuz3vxzyo744i8)
- [Recycler View](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/unit-2-user-experience/lesson-4-user-interaction/4-5-c-recyclerview/4-5-c-recyclerview.html)
- [Text And Scroll Views](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/unit-1-get-started/lesson-1-build-your-first-app/1-3-c-text-and-scrolling-views/1-3-c-text-and-scrolling-views.html)
- [Button And Clickable Images](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/unit-2-user-experience/lesson-4-user-interaction/4-1-c-buttons-and-clickable-images/4-1-c-buttons-and-clickable-images.html)

#### Activities and intents

- [Notes-Slides](https://piazza.com/class_profile/get_resource/ktlu0ly5db84bb/kuz3w4v5gpn4zh)
- [Implicit Intent](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/unit-1-get-started/lesson-2-activities-and-intents/2-3-c-implicit-intents/2-3-c-implicit-intents.html)
- [Intents And Starting Activities](https://youtu.be/1xj9G2FvLeE)
- [Activities And Intent](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/unit-1-get-started/lesson-2-activities-and-intents/2-1-c-activities-and-intents/2-1-c-activities-and-intents.html)
- [Activities Lifecycle And State](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts-v2/unit-1-get-started/lesson-2-activities-and-intents/2-2-c-activity-lifecycle-and-state/2-2-c-activity-lifecycle-and-state.html)

#### Networking and APIs

- [Notes-Slides](https://piazza.com/class_profile/get_resource/ktlu0ly5db84bb/kvj97fdgts92ju)
- [Networking And APIs](https://youtu.be/k2N3EoZI3eU)
- [Retrofit](https://square.github.io/retrofit/)

#### Fragments

- [Fragments Lecture](https://youtu.be/JuBpWzEoDw4)
- [Fragments Implementation](https://youtu.be/Btli00YA1eI)

#### Application architecture

- [Article on App Architecture](https://developer.android.com/topic/architecture)
- [Android's Guide To App Architecture](https://youtu.be/4L3-DW-z7iI)

#### Practice projects

- [Yelp Clone](https://www.youtube.com/playlist?list=PL7NYbSE8uaBBPVU8RPRKuah_hUFQWCMLR)
- [Tip Calculator Application](https://www.youtube.com/playlist?list=PL7NYbSE8uaBCMVBVg6cskGzdYguj3CUP-)
- [My Maps Application](https://www.youtube.com/playlist?list=PL7NYbSE8uaBCSkZum6Z88RvjiXrTBpjT2)

---

## Track 4: iOS Development

**Who this is for:** People drawn to the Apple ecosystem and to well-crafted native apps.
**What you will be able to do after 30 days:** Write Swift, build screens in SwiftUI, navigate between views, call an API and decode JSON, persist data, and structure an app using MVVM.
**Prerequisites:** A Mac with Xcode installed. iOS development requires Apple hardware for building and running apps.

### 30-day plan

| Days | Focus | What to do |
|---|---|---|
| 1 | Introduction and setup | Start Apple's intro tutorial and follow the Xcode setup video. |
| 2 to 5 | Swift fundamentals | Read the Swift Book's basics chapter alongside the Swift course. Optionals, structs, classes, closures and protocols matter most. |
| 6 to 10 | SwiftUI | Work through Apple's SwiftUI tutorials and the first days of 100 Days of SwiftUI. SwiftUI is the recommended starting point. |
| 11 | Week 2 build | A simple habit tracker or notes screen. |
| 12 to 13 | Navigation | SwiftUI navigation first. Look at UIKit navigation only for awareness. |
| 14 to 16 | Networking and JSON | Consume a REST API, learn JSONDecoder, and try a POST call. Use QuickType.io to generate models. |
| 17 to 19 | Persistence | Core Data basics first. Read about Realm or Firebase if you want a cloud option. |
| 20 | Dependency managers | Add a package with Swift Package Manager. Read about CocoaPods for older projects. |
| 21 to 23 | Concurrency | Basic concepts, then async and await. |
| 24 to 26 | Architecture and patterns | MVVM in SwiftUI, then SOLID principles and design patterns. |
| 27 | Tools | Learn Xcode shortcuts and try SourceTree, Diawi and the app icon generator. |
| 28 to 30 | Capstone | Build a Liquid Coder or Kavsoft-style project, or a small app of your own that calls an API and stores data. |

If you want to learn UIKit as well (many existing codebases still use it), treat it as a follow-up after this 30-day sprint.

### Resources

#### Introduction

- [Introduction to iOS](https://developer.apple.com/tutorials/app-dev-training)
- [Xcode Setup](https://www.youtube.com/watch?v=vKPCvAPW9Ns)

#### Introduction to Swift

- [Swift Book](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)
- [Swift Course](https://www.youtube.com/watch?v=FcsY1YPBwzQ)

#### iOS development courses

SwiftUI (recommended first):

- [Introduction to SwiftUI](https://developer.apple.com/tutorials/swiftui)
- [100 Days Of SwiftUI](https://www.hackingwithswift.com/100/swiftui)
- [Hacking with SwiftUI](https://www.hackingwithswift.com/books/ios-swiftui)

UIKit:

- [100 Days Of Swift](https://www.hackingwithswift.com/100)
- [Hacking with Swift](https://www.hackingwithswift.com/read)

#### View navigation

- [SwiftUI Navigation](https://www.kodeco.com/5824937-swiftui-tutorial-navigation)
- [UIKit Navigation](https://www.youtube.com/watch?v=LbAd2FIlnos)

#### Networking

- [Networking in SwiftUI](https://medium.com/@nutanbhogendrasharma/consume-rest-api-in-swiftui-ios-mobile-app-b3c5d6ecf401)
- [Networking in UIKit](https://www.freecodecamp.org/news/how-to-make-your-first-api-call-in-swift/)
- [Post API Call](https://www.youtube.com/watch?v=o3Rkg6WmZoY)
- [Advanced Networking](https://malcolmkmd.medium.com/writing-network-layer-in-swift-protocol-oriented-approach-4fa40ef1f908)

#### JSON parsing

- [JSON Decoder](https://www.avanderlee.com/swift/json-parsing-decoding/)
- [JSON Serialization](https://www.hackingwithswift.com/example-code/system/how-to-parse-json-using-jsonserialization)

#### Databases

- [Core Data Basics](https://medium.com/@ankurvekariya/core-data-crud-with-swift-4-2-for-beginners-40efe4e7d1cc)
- [Core Data](https://youtube.com/playlist?list=PLMRqhzcHGw1aDYKmCuqXQ_IqpWpJlpoJ3)
- [Realm](https://www.kodeco.com/32960966-realm-with-swiftui-tutorial-getting-started)
- [Firebase](https://www.kodeco.com/11609977-getting-started-with-cloud-firestore-and-swiftui)
- [Firebase Project](https://youtube.com/playlist?list=PL0dzCUj1L5JEN2aWYFCpqfTBeVHcGZjGw)

#### Dependency managers

- [Swift Package Manager](https://cocoacasts.com/xcode-fundamentals-how-to-add-a-swift-package-to-a-project)
- [Cocoapods](https://codewithchris.com/cocoapods/)

#### Concurrency

- [Basic Concepts](https://betterprogramming.pub/concurrency-in-ios-and-swift-guide-50443ce5b0f5)
- [Concurrency in Depth](https://www.freecodecamp.org/news/ios-concurrency/)
- [Async/Await](https://www.avanderlee.com/swift/async-await/)

#### Architectures and design patterns

- [MVVM Architecture in UIKit](https://www.youtube.com/watch?v=iI0LabCYZJo)
- [MVVM Architecture in SwiftUI](https://azamsharp.medium.com/mvvm-in-swiftui-8a2e9cc2964a)
- [MVP Architecture in UIKit](https://www.youtube.com/watch?v=SFqIP5jYn_4)
- [VIPER Architecture in UIKit](https://www.youtube.com/watch?v=hFLdbWEE3_Y)
- [SOLID Principles](https://betterprogramming.pub/swift-s-o-l-i-d-21203ba3a226)
- [Design Patterns](https://aglowiditsolutions.com/blog/top-swift-design-patterns/)

#### Most useful tools

- [Xcode Tools & Tricks](https://www.youtube.com/watch?v=ZAqnJQn7xp4): the most essential Xcode tools for iOS development.
- [SourceTree](https://www.sourcetreeapp.com): a free Git client with a visual representation of your repositories.
- [QuickType.io](https://app.quicktype.io): converts JSON data into Swift models.
- [Diawi](https://www.diawi.com): deploy and test your app directly on devices.
- [App icon Generator](https://appicon.co): generates app icons for different devices.
- [Device Shots](https://deviceshots.com): design device mockups with screenshots of your app or website.
- [Transporter](https://apps.apple.com/us/app/transporter/id1450874784?mt=12): upload your iOS apps to App Store Connect quickly.

#### Practice projects

- [Liquid Coder](https://liquidcoder.com/courses): SwiftUI projects for beginners.
- [Kavsoft](https://www.youtube.com/c/Kavsoft/videos): complex and beautiful UI in SwiftUI.
- [Spotify Clone](https://youtube.com/playlist?list=PL5PR3UyfTWve9ZC7Yws0x6EGjBO2FGr0o): a step-by-step Spotify clone in UIKit.

#### Most useful links

- [Apple Developer Videos](https://developer.apple.com/videos/topics/): best saved for later, because it assumes some iOS knowledge.
- [Advanced SwiftUI Animation](https://swiftui-lab.com): detailed animation knowledge that the documentation does not cover.

---

## Track 5: Flutter Development

**Who this is for:** People who want one codebase that runs on both Android and iOS.
**What you will be able to do after 30 days:** Write Dart, build multi-screen apps with widgets, manage state, apply Material and Cupertino design, and debug with DevTools.
**Prerequisites:** None, though any prior programming helps with the OOP section.

### 30-day plan

| Days | Focus | What to do |
|---|---|---|
| 1 | Cross-platform introduction and setup | Read the cross-platform overview and set up your environment using the Flutter setup guide. Run the starter app. |
| 2 to 4 | Dart basics | Variables, built-in types, functions, operators and control flow. Use the official Dart docs and language tour. |
| 5 to 6 | Object-oriented programming | Understand OOP, constructors and inheritance. Work through the OOP playlist. |
| 7 | Week 1 build | A small Dart command-line program using classes. |
| 8 to 9 | Advanced Dart | Extension methods, async programming, futures with async and await, and generics. |
| 10 to 13 | Widgets | Intro to widgets, widget overview, stateless versus stateful. Explore the widget catalog and build several small screens. |
| 14 | Week 2 build | A counter app extended with a list and a form. |
| 15 to 18 | State management | Read the state management options page, then try Riverpod or Bloc. Use the tutorial playlist. |
| 19 to 21 | Design systems and navigation | Material and Cupertino widgets, then routing with go_router. |
| 22 to 23 | Debugging | Learn Flutter debugging and Dart DevTools. |
| 24 to 25 | Essentials | Working with assets, images and keys. |
| 26 | Complete course | Watch a chunk of the beginners course for anything you missed. |
| 27 to 30 | Capstone | A multi-screen app with state management, navigation and at least one API call or local data source. |

### Resources

#### Introduction

- [Introduction to Cross-Platform App Development](https://kotlinlang.org/docs/cross-platform-mobile-development.html#the-most-popular-cross-platform-solutions)
- [Setting up your Development Environment](https://rohitlogs.com/from-zero-to-flutter-setting-up-your-development-environment-and-first-app)

#### Introduction to Dart

- [Official Dart Documentation](https://dart.dev/overview)
- [Getting started with Dart](https://rohitlogs.com/diving-into-dart-the-foundation-of-flutter-1#heading-creating-your-first-dart-project)
- [Introduction to Dart](https://www.javatpoint.com/flutter-dart-programming)

#### Basics of programming with Dart

- [Variables](https://dart.dev/guides/language/language-tour#variables)
- [Built-in types](https://dart.dev/guides/language/coming-from/js-to-dart#built-in-types)
- [Functions](https://www.geeksforgeeks.org/dart-programming-functions/)
- [Operators](https://www.geeksforgeeks.org/operators-in-dart/)
- [Control flow statements](https://dart.dev/guides/language/language-tour#control-flow-statements)

#### Object-oriented programming

- [Understanding Object Oriented Programming](https://rohitlogs.com/discover-the-magic-of-object-oriented-programming-a-beginners-guide-to-oop-mastery)
- [Constructors in Dart](https://www.freecodecamp.org/news/constructors-in-dart/)
- [Playlist to learn Object Oriented Programming](https://www.youtube.com/playlist?list=PL9gnSGHSqcno1G3XjUbwzXHL8_EttOuKk)

#### Advanced concepts of Dart

- [Extension Methods](https://dart.dev/guides/language/extension-methods)
- [Asynchronous Programming](https://medium.flutterdevs.com/exploring-asynchronous-programming-in-dart-flutter-25f341af32f)
- [Future, Async and Await](https://dart.dev/codelabs/async-await)
- [Generics](https://dart.academy/generics-in-dart-and-flutter/)

#### Widgets

- [Intro to Widgets](https://docs.flutter.dev/development/ui/widgets-intro)
- [Widget Overview](https://www.youtube.com/watch?v=FU2Eeizo95o)
- [Explore the wide range of widgets available in Flutter](https://docs.flutter.dev/development/ui/widgets) (just explore and have fun for now)
- [Stateless Widgets](https://api.flutter.dev/flutter/widgets/StatelessWidget-class.html)
- [Stateful Widgets](https://api.flutter.dev/flutter/widgets/StatefulWidget-class.html)
- [Tutorial on Stateful widgets](https://www.youtube.com/watch?v=p5dkB3Mrxdo)
- [Inherited Widgets](https://api.flutter.dev/flutter/widgets/InheritedWidget-class.html)
- [Stateless VS Stateful Widgets](https://www.geeksforgeeks.org/flutter-stateful-vs-stateless-widgets/)
- [Flutter Widget Binding](https://api.flutter.dev/flutter/widgets/WidgetsFlutterBinding-class.html)

#### State management

- [Flutter State Management Techniques](https://docs.flutter.dev/data-and-backend/state-mgmt/options)
- [Flutter Riverpod 2.0](https://codewithandrea.com/articles/flutter-state-management-riverpod/)
- [Flutter Bloc Architecture](https://bloclibrary.dev/#/?id=documentation)
- [Flutter State Management Tutorials](https://www.youtube.com/playlist?list=PL6yRaaP0WPkUf-ff1OX99DVSL1cynLHxO)

#### Design systems and navigation

- [Material Design System Guidelines By Google](https://m2.material.io/design/guidelines-overview)
- [Material Component Widgets in Flutter](https://docs.flutter.dev/development/ui/widgets/material#Buttons)
- [Cupertino Widgets in Flutter](https://docs.flutter.dev/development/ui/widgets/cupertino)
- [Cupertino Design System for iOS Style](https://blog.logrocket.com/flutter-cupertino-tutorial-build-ios-apps-native/)
- [Flutter Navigation and Routing - go_router](https://medium.com/@antonio.tioypedro1234/flutter-go-router-the-essential-guide-349ef39ec5b3)

#### Debugging

- [Official Flutter Debugging](https://docs.flutter.dev/testing/debugging)
- [Dart DevTools](https://docs.flutter.dev/development/tools/devtools/overview)

#### Flutter essentials

- [Working with assets](https://docs.flutter.dev/development/ui/assets-and-images)
- [Tutorial for Working with assets](https://www.youtube.com/watch?v=Hxh6nNHSUjo)
- [Keys - Why, How and Where?](https://youtu.be/kn0EOS-ZiIc)

#### Complete course

- [Flutter Course for Beginners](https://www.youtube.com/watch?v=VPvVD8t02U8)

---

## Track 6: DevOps

**Who this is for:** People who like automation, infrastructure and making systems reliable.
**What you will be able to do after 30 days:** Write small programs in Go, work confidently in a Linux terminal, script in shell, build and run Docker containers, understand Kubernetes, Terraform, CI/CD and monitoring at a working level, and deploy something to a cloud provider.
**Prerequisites:** Comfort with the command line helps. If you have never deployed an application, consider doing the Backend track first.

A candid note: DevOps is the widest track in this handbook. Thirty days gives you a guided tour, not mastery. The goal is to touch every major tool once, so you know what each one is for and which ones to go deeper on.

### 30-day plan

| Days | Focus | What to do |
|---|---|---|
| 1 to 3 | Go language | Learn the basics from the Go tour, one video course, and the Codecademy or W3Schools reference. Write a few small programs. |
| 4 to 6 | Linux terminal | Follow one complete Linux course. Practise navigation, permissions, processes, pipes and package management daily. |
| 7 | Operating system basics | Watch one OS overview and skim the OS notes. |
| 8 | Networking and YAML | Skim the computer networks course and learn YAML syntax. It appears in almost every DevOps tool. |
| 9 | Server management | Linux for server management and the Ubuntu server guide. |
| 10 to 11 | Shell scripting | Write scripts that automate repetitive tasks. Follow one shell scripting course. |
| 12 to 14 | Containers and Docker | Understand containers, then Docker. Containerise a small app. |
| 15 | Configuration management | Compare Chef, Puppet and Ansible, then run a first Ansible playbook. |
| 16 to 18 | Kubernetes | Learn pods, deployments and services. Use a hands-on lab such as KubeCampus. |
| 19 to 20 | Infrastructure provisioning | Learn Terraform basics and provision a small resource. |
| 21 | Service mesh | Read what a service mesh is and skim Istio. Awareness level only. |
| 22 to 23 | CI/CD | Understand the concepts, then build a GitHub Actions pipeline. Look at Jenkins for comparison. |
| 24 to 25 | Monitoring | Prometheus and Grafana for infrastructure, then a look at application monitoring (New Relic, Jaeger). |
| 26 | Log management | Elastic and the ELK stack overview. |
| 27 to 28 | Cloud providers | Pick one provider and complete its fundamentals material. |
| 29 to 30 | Capstone | Containerise an app, write a CI pipeline that builds and pushes it, and deploy it somewhere. |

### Resources

#### Go

- [Learn Go - Codecademy](https://www.codecademy.com/learn/learn-go)
- [Getting started - Go](https://go.dev/learn/)
- [Go tutorial - Tutorials point](https://www.tutorialspoint.com/go/index.htm)
- [Go tutorial - W3schools](https://www.w3schools.com/go/)
- [Learn Go Programming - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=YS4e4q9oBaU)
- [Golang tutorial - TechWorld With Nana(Youtube)](https://www.youtube.com/watch?v=yyUHQIec83I)
- [Complete Golang tutorial - Hitesh Choudhary(Youtube)](https://www.youtube.com/playlist?list=PLRAV69dS1uWQGDQoBYMZWKjzuhCaOnBpa)
- [Go programming - GoLang Course with Bonus Project](https://youtu.be/un6ZyFkqFKo)

#### Linux terminal basics

- [Complete Linux Course](https://www.youtube.com/watch?v=iwolPf6kN-k&feature=youtu.be)
- [Introduction to Linux - Full Course for Beginners By FreeCodeCamp](https://youtu.be/sWbUDq4S6Y8)
- [Basic Linux Commands](https://www.youtube.com/watch?v=J2zquYPJbWY)
- [Linux Tutorial](https://www.youtube.com/watch?v=cBokz0LTizk)
- [Linux Command Cheatsheet](https://www.guru99.com/linux-commands-cheat-sheet.html)
- [Linux Masterclass Course - Apoorv Goyal(YouTube)](https://www.youtube.com/playlist?list=PL2kSRH_DmWVZp_cu6MMPWkgYh7GZVFS6i)
- [Bogdan Stashchuk - Linux for beginners playlist](https://www.youtube.com/playlist?list=PLWkguCWKqN9OrwsklvLC8FB87TbaOQGqY)
- [Linux Command Line for Beginners](https://ubuntu.com/tutorials/command-line-for-beginners)
- [Linux Complete Hands-On Tutorial](https://linuxjourney.com/)

#### Operating system basics

- [Introduction to operating systems - Jenny's Lectures(Youtube)](https://www.youtube.com/watch?v=RozoeWzT7IM)
- [Operating system basics - Geek's Lesson(Youtube)](https://www.youtube.com/watch?v=6-mdtMKfEYM)
- [How do operating systems work? - ClickView(Youtube)](https://www.youtube.com/watch?v=GjNp0bBrjmU)
- [What is an operating system - Techquickie(Youtube)](https://www.youtube.com/watch?v=pVzRTmdd9j0)
- [Operating system tutorial - Tutorialspoint](<https://www.tutorialspoint.com/operating_system/index.htm#:~:text=An%20Operating%20System%20(OS)%20is%20an%20interface%20between%20a%20computer,as%20disk%20drives%20and%20printers.>)
- [Operating System - Neso Academy](https://youtube.com/playlist?list=PLBlnK6fEyqRiVhbXDGLXDk_OQAeuVcp2O)
- [Operating System Notes](https://github.com/Aniruddha-Tapas/Operating-Systems-Notes)

#### Other prerequisites

- [Complete Computer Networks Course](https://www.youtube.com/watch?v=IPvYjXCsTg8&list=PL9gnSGHSqcnoqBXdMwUTRod4Gi3eac2Ak&index=4)
- [Complete YAML Course](https://www.youtube.com/watch?v=IA90BTozdow)
- [YAML Docs](https://yaml.org/spec/1.2.2/)
- [DevOps Prerequisites Course - Getting started with DevOps](https://www.youtube.com/watch?v=Wvf0mBNGjXY&t=237s)

#### Server management

- [Linux For Server Management](https://www.youtube.com/watch?v=HsDIz0zKwjs)
- [Ubuntu Server Guide](https://ubuntu.com/server/docs)
- [Linux System Administration Basics](https://www.linode.com/docs/guides/linux-system-administration-basics/)

#### Shell scripting

- [Shell Scripting for DevOps + Hands on projects](https://www.youtube.com/watch?v=zsajhz2_50g&list=PLdpzxOOAlwvIZ7u-gtpX_bozrspUbTQ1S)
- [Shell Scripting Tutorial for Beginners](https://www.youtube.com/watch?v=cQepf9fY6cE&list=PLS1QulWo1RIYmaxcEqw5JhK3b-6rgdWO_)
- [Shell Scripting Tutorial | Shell Scripting Crash Course](https://www.youtube.com/watch?v=GtovwKDemnI&t=1658s)

#### Containers

- [Containers Explained](https://www.youtube.com/watch?v=0qotVMX-J5s)
- [Docker Tutorial - Kunal Kushwaha(Youtube)](https://www.youtube.com/watch?v=17Bl31rlnRM)
- [Docker Tutorial - TechWorld with Nana(Youtube)](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [Learn Docker - freecodecamp(Youtube)](https://www.youtube.com/watch?v=9zUHg7xjIqQ)
- [Docker Docs](https://docs.docker.com/)
- [Complete Docker Course - From BEGINNER to PRO! - DevOps Directive](https://www.youtube.com/watch?v=RqTEHSBrYFw&t=3615s)
- [Build a NodeJS Application With Docker](https://www.youtube.com/watch?v=PsWeSg38XFY&feature=youtu.be)

#### Configuration management

- [Chef Vs Puppet Vs Ansible](https://www.youtube.com/watch?v=_TVNCTK808I)
- [What is Ansible](https://www.youtube.com/watch?v=wgQ3rHFTM4E)
- [Chef, Puppet, Ansible Course](https://www.youtube.com/watch?v=O1s16cYzC10)
- [Ansible Docs](https://docs.ansible.com/ansible/latest/index.html)
- [Getting started with Ansible(Youtube)](https://www.youtube.com/playlist?list=PLT98CRl2KxKEUHie1m24-wkyHpEsa4Y70)
- [Ansible Tutorial for Beginners: Ultimate Playbook & Examples - Spacelift](https://spacelift.io/blog/ansible-tutorial)

#### Container orchestration (Kubernetes)

- [Kubernetes Tutorial - Kunal Kushwaha(Youtube)](https://www.youtube.com/watch?v=KVBON1lA9N8)
- [Learn Kubernetes - Civo Academy](http://civo.io/kunal)
- [Kubernetes 101 for beginners by Saiyam Pathak](https://www.youtube.com/watch?v=PN3VqbZqmD8&t=7206s)
- [Kubernetes - Tutorialspoint](https://www.tutorialspoint.com/kubernetes/index.htm)
- [Learn Kubernetes in Under 3 Hours - FreeCodeCamp](https://www.freecodecamp.org/news/learn-kubernetes-in-under-3-hours-a-detailed-guide-to-orchestrating-containers-114ff420e882/)
- [Kubernetes Tutorial - TechWorld with Nana(Youtube)](https://www.youtube.com/watch?v=X48VuDVv0do)
- [Complete Kubernetes Course - Hitesh Choudhary(Youtube)](https://www.youtube.com/watch?v=7XDeI5fyj3w)
- [Kubernetes in 5 minutes - VMware(Youtube)](https://www.youtube.com/watch?v=PH-2FfFD2PU)
- [Learn Kubernetes with hands-on labs - KubeCampus](https://kubecampus.io/)

#### Infrastructure provisioning

- [Terraform Tutorials - Hashicorp](https://learn.hashicorp.com/terraform)
- [Terraform Tutorial - TechWorld with Nana(Youtube)](https://www.youtube.com/watch?v=l5k1ai_GBDE)
- [Terraform Course - FreeCodeCamp(Youtube)](https://www.youtube.com/watch?v=SLB_c_ayRMo)
- [Complete Terraform Course - DevOps Directive(Youtube)](https://www.youtube.com/watch?v=7xngnjfIlK4)
- [What is Terraform - Hashicorp](https://www.terraform.io/intro)

#### Service mesh

- [What Is A Service Mesh](https://www.youtube.com/watch?v=vh1YtWjfcyk)
- Istio: [Istio Service Mesh Explained - IBM Technology](https://www.youtube.com/watch?v=6zDrLvpfCK4), [Istio & Service Mesh - TechWorld with Nana](https://www.youtube.com/watch?v=16fgzklcF7Y), [Docs](https://istio.io/latest/docs/setup/getting-started/)
- Consul: [Introduction](https://www.youtube.com/watch?v=UHLr8UsHuDA), [Docs](https://www.consul.io/docs)

#### CI/CD

- [What Is CI/CD](https://www.youtube.com/watch?v=62N8UiWUdQo&list=PL9gnSGHSqcnoqBXdMwUTRod4Gi3eac2Ak&index=21)
- [Github Actions](https://www.youtube.com/watch?v=R8_veQiYBjI)
- Jenkins: [Jenkins Tutorial - TechWorld with Nana](https://www.youtube.com/watch?v=7KCS70sCoK0), [Jenkins Tutorial - Tutorialspoint](https://www.tutorialspoint.com/jenkins/index.htm), [Docs](https://www.jenkins.io/doc/tutorials/)

#### Infrastructure monitoring

- [Prometheus and Grafana Tutorial - The Digital Life(Youtube)](https://www.youtube.com/watch?v=9TJx7QTrTyo)
- [How Prometheus Monitoring works - TechWorld with Nana(Youtube)](https://www.youtube.com/watch?v=h4Sl21AKiDg)
- [Prometheus Docs](https://prometheus.io/docs/introduction/overview/)
- [Grafana Docs](https://grafana.com/docs/grafana/latest/getting-started/get-started-grafana-prometheus/)

#### Application monitoring

- New Relic: [New Relic - Amazon Web Services](https://www.youtube.com/watch?v=aU6A-45c7Vs), [New Relic](https://www.youtube.com/c/NewRelicInc), [Ingesting OpenTelemetry data with New Relic One](https://www.youtube.com/watch?v=YHyopdCfxsQ)
- Jaeger: [Getting Started with Jaeger - CNCF](https://www.youtube.com/watch?v=aMZoUIG-mgY), [Jaeger Intro - CNCF](https://www.youtube.com/watch?v=UNqilb9_zwY), [Docs](https://www.jaegertracing.io/docs/1.36/getting-started/)

#### Log management

- Elastic: [What is Elasticsearch? - IBM Technology](https://www.youtube.com/watch?v=ZP0NmfyfsoM), [Elastic.co Webinar](https://www.elastic.co/observability/log-monitoring), [OpenDev 10.2017 - Microsoft Azure](https://www.youtube.com/watch?v=tOqWX9JWEYc)
- ELK: [Log Management With ELK - cprime](https://www.cprime.com/resources/blog/log-management-elk-and-why-you-should-care/), [What is ELK stack - sematext](https://sematext.com/guides/elk-stack/), [What is ELK? - Tech Primer](https://www.youtube.com/watch?v=4X0WLg05ASw), [Log Management at Scale with ELK - Logz.io](https://www.youtube.com/watch?v=MuPhf6uL-kE)

#### Cloud providers

- [Civo](https://www.civo.com/docs)
- [AWS](https://docs.aws.amazon.com/)
- [Google Cloud Provider](https://cloud.google.com/docs)
- [Azure](https://docs.microsoft.com/en-us/azure/?product=popular)
- [Getting started with Civo - Youtube](https://www.youtube.com/watch?v=mHtCkmshfks)
- [AWS Certified Cloud Practitioner Certification Course - Youtube](https://www.youtube.com/watch?v=SOTamWNgDKc)
- [Google Cloud Platform Full Course - Youtube](https://www.youtube.com/watch?v=pTm0iI3_pIQ)
- [Google Cloud Certified Associate Cloud Engineer Course - Youtube](https://www.youtube.com/watch?v=jpno8FSqpc8)
- [Microsoft Certified Azure Fundamentals Certification Course - Youtube](https://www.youtube.com/watch?v=NKEFWyqJ5XA)

#### Project ideas and books

- [11 Projects With Go](https://www.youtube.com/watch?v=jFfo23yIWac)
- [DevOps Project](https://www.youtube.com/playlist?list=PLxzKY3wu0_FJdJd3IKdiM4Om1hGo2Hsdt)
- [20 Real Time DevOps Projects](https://youtube.com/playlist?list=PLkWRCY_kK0Gh1NTvgHUE0naF4-mOURp7e)
- [Collection of some DevOps books](https://github.com/rohitg00/DevOps_Books)

---

## Track 7: Blockchain

**Who this is for:** People curious about decentralised systems, smart contracts and how trust can be built into software.
**What you will be able to do after 30 days:** Explain how blockchains work, write and deploy a simple Solidity smart contract, use a framework like Hardhat, and connect a contract to a web front end.
**Prerequisites:** Basic JavaScript is very helpful, since most tooling and front ends use it.

A word of caution: smart contracts handle real money and cannot easily be changed once deployed. Use test networks while learning and treat security as a first-class topic from the start.

### 30-day plan

| Days | Focus | What to do |
|---|---|---|
| 1 to 2 | What is Web3 and blockchain | Read the Web3 introduction, blockchain and distributed ledger articles, and crypto basics. |
| 3 to 4 | Core concepts | Web1 vs Web2 vs Web3, smart contracts, wallets, block explorers, layer 1 vs layer 2, oracles, NFTs, DAOs and dapps. |
| 5 | Choose a blockchain | Ethereum is the most documented and is the best place to start. Solana is the main alternative. |
| 6 to 8 | Ethereum concepts | Accounts, transactions, consensus (proof of work, proof of stake), the EVM and gas. |
| 9 | Nodes and providers | Learn what a node is and try a provider like Alchemy, Infura or QuickNode. |
| 10 | Layer 2 | Skim Polygon and the Lightning Network to see why scaling solutions exist. |
| 11 to 17 | Solidity | Use Remix IDE for instant feedback. Work through a Solidity tutorial and complete CryptoZombies. |
| 18 to 20 | Frameworks | Install MetaMask, then set up Hardhat (or Foundry). Write, compile, test and deploy to a local network. |
| 21 to 23 | Connecting to a front end | Learn Ethers.js or Web3.js. Read and write to a deployed contract from a web page. |
| 24 to 25 | Decentralised storage | Store a file on IPFS and understand where Arweave and Filecoin fit. |
| 26 to 27 | Mid-level tools | OpenZeppelin contracts, Chainlink, The Graph and WalletConnect. |
| 28 to 30 | Capstone | Build and deploy to a testnet: a small dapp such as a voting contract with a simple front end. |

### Resources

#### Introduction

- [What is Web3](https://www.freecodecamp.org/news/what-is-web3/)

#### Blockchain fundamentals

- [What is Blockchain](https://www.geeksforgeeks.org/blockchain-technology-introduction)
- [Distributed Ledger](https://www.geeksforgeeks.org/what-is-blockchain-distributed-ledger)
- [Crypto Basics](https://www.oswego.edu/cts/basics-about-cryptocurrency)
- [Difference between Web1, Web2, Web3](https://www.simplilearn.com/what-is-web-1-0-web-2-0-and-web-3-0-with-their-difference-article)
- [Smart Contracts](https://ethereum.org/en/developers/docs/smart-contracts/)
- [Crypto wallet](https://www.businessinsider.com/personal-finance/crypto-wallet)
- [Block Explorers](https://www.gemini.com/cryptopedia/what-is-a-block-explorer-btc-bch-eth-ltc)
- [Blockchain Layer 1 vs. Layer 2 Scaling Solutions](https://www.gemini.com/cryptopedia/blockchain-layer-2-network-layer-1-network)
- [Oracles](https://chain.link/education/blockchain-oracles)
- [What Are NFTs](https://www.forbes.com/advisor/investing/cryptocurrency/nft-non-fungible-token/)
- [What Is A DAO](https://www.forbes.com/sites/cathyhackl/2021/06/01/what-are-daos-and-why-you-should-pay-attention/?sh=343b04067305)
- [Intro To DApps](https://ethereum.org/en/developers/docs/dapps/)
- [EVM and Non-EVM Chains](https://ethereum.org/en/developers/docs/dapps/)
- [Overview of technologies included in Web3](https://remote3.co/blog-post/complete-web3-developer-roadmap-2022)
- [Road to Web3](https://www.web3.university/tracks/road-to-web3)
- [One of the best Web3 Roadmaps](https://vitto.cc/web3-and-solidity-smart-contracts-development-roadmap/)

Additional resources:

- [Metaschool: Free courses](https://metaschool.so/courses)
- [Lumos Academy: Learning Platform](https://academy.lumoslabs.co/courses)
- [DeFi Infrastructure(Youtube)](https://www.youtube.com/playlist?list=PLE1Vu6ctbqa61FqJmPDnoPzDqrnyILHRm)

#### Choose a blockchain

- [Ethereum](https://ethereum.org/)
- [Solana](https://solana.com/)

#### Ethereum concepts

- [Accounts](https://ethereum.org/en/developers/docs/accounts/)
- [Transactions](https://ethereum.org/en/developers/docs/transactions)
- Consensus: [Proof Of Work](https://www.investopedia.com/terms/p/proof-work.asp), [Proof Of Stake](https://www.investopedia.com/terms/p/proof-stake-pos.asp), [Proof Of History](https://medium.com/solana-labs/proof-of-history-a-clock-for-blockchain-cf47a61a9274)
- [Ethereum Virtual Machine](https://ethereum.org/en/developers/docs/evm/)
- [Gas](https://ethereum.org/en/developers/docs/gas/)
- Advanced concepts (optional): [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/), [Blockchain Trilemma](https://www.gemini.com/cryptopedia/blockchain-trilemma-decentralization-scalability-definition), [Ethereum Trilemma](https://ethereum.org/en/upgrades/vision), [Endgame](https://vitalik.ca/general/2021/12/06/endgame.html)
- [Nodes And Clients](https://ethereum.org/en/developers/docs/nodes-and-clients/)
- [Networks, Nodes as a Service](https://ethereum.org/en/developers/docs/networks): [Alchemy](https://www.alchemy.com/), [Infura](https://infura.io/), [Quicknode](https://www.quicknode.com/)

#### Layer 2 solutions

- [Polygon](https://wiki.polygon.technology/)
- [Lightning Network](http://lightning.network/docs/)

#### Choose a language

- [Solidity](https://docs.soliditylang.org/)
- [Vyper](https://vyper.readthedocs.io/en/stable/)
- [Rust (Solana)](https://docs.solana.com/developing/on-chain-programs/developing-rust)

#### Solidity

- [Remix IDE](https://remix-project.org/)
- [Solidity With Javascript 31 hours Course](https://youtu.be/gyMwXuJrbJQ)
- [Solidity With Javascript 10 hours Course](https://youtu.be/cGQHXmCS94M)
- [Solidity Tutorial](https://youtu.be/3g2WT2jms_k)
- [Solidity Docs](https://docs.soliditylang.org/en/v0.8.16/)
- [Solidity Cheatsheet](https://intellipaat.com/mediaFiles/2019/03/Solidity-Cheat-Sheet.jpg)
- [CryptoZombies](https://cryptozombies.io/)

#### Frameworks and tooling

- [Metamask](https://docs.metamask.io/guide/)
- [VS Code Solidity Extension](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity)
- [Truffle](https://trufflesuite.com/)
- [Hardhat](https://hardhat.org/docs)
- [Foundry](https://getfoundry.sh/)
- [Web3.py](https://web3py.readthedocs.io/)

#### Connect your dapp to a front end

- [Web3.js](https://web3js.readthedocs.io/en/v1.7.5/)
- [Ethers.js](https://docs.ethers.io/v5/)
- Decentralised storage: [IPFS](https://docs.ipfs.tech/install/), [Arweave](https://docs.arweave.org/info/), [Filecoin](https://docs.filecoin.io/)

#### Mid-level tools

- Testing: [Waffle](https://ethereum-waffle.readthedocs.io/en/latest/), [Ganache](https://trufflesuite.com/docs/ganache/)
- [Open Zeppelin](https://docs.openzeppelin.com/)
- [Wallet Connect](https://docs.walletconnect.com/2.0/)
- [Chain Link](https://docs.chain.link/)
- [Ceramic Network](https://developers.ceramic.network/learn/welcome/)
- [The Graph](https://thegraph.com/docs/en/)
- [Scaffold-Ethereum](https://docs.scaffoldeth.io/scaffold-eth/)
- [Alchemy Dapp Store](https://www.alchemy.com/dapps)
- SDKs: [Third Web](https://portal.thirdweb.com/), [Moralis](https://docs.moralis.io/moralis-dapp/getting-started)

#### Project ideas

Articles:

- [The Complete Guide to Full Stack Web3 Development](https://dev.to/edge-and-node/the-complete-guide-to-full-stack-web3-development-4g74)
- [The Complete Guide to Full Stack Ethereum and EVM Development](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13)
- [Blocktrain.info](https://www.blocktrain.info/project)
- [Buildspace - Modern Web3 projects](https://buildspace.so/builds)
- [Build these Apps & EARN](https://www.pointer.gg/tutorials)
- [80+ Web3 Dapps](https://www.theinsaneapp.com/2022/05/best-web3-projects.html)

Videos:

- [Moralis Web3 (Youtube)](https://www.youtube.com/c/MoralisWeb3)
- [Alchemy (Youtube)](https://www.youtube.com/c/AlchemyPlatform)
- [Dapp University (Youtube)](https://www.youtube.com/channel/UCY0xL8V6NzzFcwzHCgB8orQ)
- [Patrick Collins (Youtube)](https://www.youtube.com/c/patrickcollins)
- [EatTheBlocks (Youtube)](https://www.youtube.com/@EatTheBlocks) and [DeFi Tutorial](https://youtu.be/z9FgWvUai28)
- [Austin Griffith](https://www.youtube.com/channel/UC_HI2i2peo1A-STdG22GFsA)
- [Nader Dabit](https://www.youtube.com/user/boyindasouth)
- [Harkirat Singh (Youtube)](https://www.youtube.com/playlist?list=PLVKLWop9wWA82pZoyylZD2VF2c7MR8_5I)
- [Daulat Hussain (Youtube)](https://www.youtube.com/@daulathussain/featured)

---

## Track 8: Data Science

**Who this is for:** People who enjoy finding patterns in data and telling stories with numbers.
**What you will be able to do after 30 days:** Write Python and SQL for data work, clean and explore datasets with Pandas and NumPy, visualise results, train basic machine learning models, and put one behind a simple web endpoint.
**Prerequisites:** School-level maths. The plan covers the rest.

### 30-day plan

| Days | Focus | What to do |
|---|---|---|
| 1 | What is data science | Read one overview article (IBM, AWS or Simplilearn) to see the shape of the field. |
| 2 to 5 | Python | Use one beginner course, such as CS50P or the Programming with Mosh video. Cover data types, loops, functions, lists, dictionaries and files. |
| 6 to 7 | SQL | Learn SELECT, WHERE, GROUP BY and JOIN. Practise on a real dataset. |
| 8 to 9 | Pandas | Follow Corey Schafer's Pandas series and Kaggle's Pandas course. |
| 10 | NumPy and SciPy | Arrays, vectorised operations and basic SciPy. |
| 11 to 13 | Maths, probability and statistics | Descriptive statistics, distributions, probability rules and hypothesis testing. StatQuest is excellent for intuition. |
| 14 to 15 | Data cleaning | Missing values, duplicates, types, outliers. Complete the Kaggle data cleaning course. |
| 16 to 17 | Data visualisation | Matplotlib fundamentals and Kaggle's data visualisation course. |
| 18 | Exploratory data analysis | Do a full EDA on one dataset from start to finish. |
| 19 to 23 | Machine learning | Andrew Ng's course or a beginner series. Train regression, classification and clustering models. Learn train/test splits and evaluation metrics. |
| 24 to 25 | BI tools | Pick either Power BI or Tableau. Build one dashboard. |
| 26 | Web scraping and APIs | Scrape a small site with Beautiful Soup and pull data from an API. |
| 27 | Model deployment | Wrap a trained model in a small Flask app. Read about cloud deployment. |
| 28 to 30 | Capstone | An end-to-end project: choose a dataset, clean it, explore it, model it, present results, and deploy or publish. |

R is a strong choice for statistics and visualisation. If you are curious, spend a side session on the R resources below, but Python is the safer default for a first 30 days.

### Resources

#### What is data science

- [What is data science? - ibm.com](https://www.ibm.com/topics/data-science)
- [What is data science? - aws.amazon.com](https://aws.amazon.com/what-is/data-science/)
- [What is data science? - simplilearn.com](https://www.simplilearn.com/tutorials/data-science-tutorial/what-is-data-science)

#### Programming languages

R (a good tool for visualisation and statistical analysis):

- [R programming tutorial - freeCodeCamp](https://youtu.be/_V8eKsto3Ug)
- [R For Data Science Full Course - Simplilearn](https://youtu.be/iROHLA_TXQM)
- [R programming language Introduction - GeeksForGeeks](https://www.geeksforgeeks.org/r-programming-language-introduction/)
- [R programming Tutorial - W3schools](https://www.w3schools.com/r/)
- [R for Data Science - Hadley Wickham](https://r4ds.had.co.nz/)

Python:

- [Python Tutorial for Beginners - TechWorld with Nana](https://youtu.be/t8pPdKYpowI)
- [Python Full Course for Beginners - Programming with Mosh](https://youtu.be/_uQrJ0TkZlc)
- [Harvard CS50's Introduction to Programming with Python - freeCodeCamp](https://youtu.be/nLRL_NcnK-4)
- [Python for Beginners - freeCodeCamp](https://youtu.be/eWRfhZUzrAc)
- [Python programming language - W3Schools](https://www.w3schools.com/python/python_intro.asp)
- [Python programming language - GeeksForGeeks](https://www.geeksforgeeks.org/python-programming-language/)

SQL:

- [SQL Tutorial - Full Course - freeCodeCamp](https://youtu.be/HXV3zeQKqGY)
- [SQL Tutorial for Beginners - Programming With Mosh](https://youtu.be/7S_tz1z_5bA)
- [SQL for Data Analysis - W3schools](https://www.w3schools.com/sql/)
- [SQL for Data Analysis - javatpoint](https://www.javatpoint.com/sql-tutorial)

#### Frameworks

Pandas:

- [Pandas Tutorials - Corey Schafer](https://youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS)
- [Best practices with pandas - Data School](https://youtube.com/playlist?list=PL5-da3qGB5IBITZj_dYSFqnd_15JgqwA6)
- [Pandas - Kaggle](https://www.kaggle.com/learn/pandas)
- [Pandas documentation](https://pandas.pydata.org/pandas-docs/version/0.15/tutorials.html)

NumPy:

- [Python NumPy Tutorial for Beginners - freeCodeCamp](https://youtu.be/QUT1VHiLmmI)
- [Numpy Full Course - Simplilearn](https://youtu.be/j31ah5Qa4QI)
- [Numpy Tutorial For Beginners - Kaggle](https://www.kaggle.com/code/legendadnan/numpy-tutorial-for-beginners-data-science/notebook)
- [Python Numpy - cs231n](https://cs231n.github.io/python-numpy-tutorial/)
- [Python Numpy documentation](https://numpy.org/doc/1.18/user/quickstart.html)

SciPy:

- [Python Scipy - Mr. P Solver](https://youtu.be/jmX4FOUEfgU)
- [SciPy - cs231n](https://cs231n.github.io/python-numpy-tutorial/#scipy)

#### Mathematics for data science

- [Mathematics and statistics for data science - codebasics](https://www.youtube.com/playlist?list=PLeo1K3hjS3uuKaU2nBDwr6zrSOTzNCs0l)
- [Maths for data science masterclass - Udemy](https://www.udemy.com/share/107qEq/)
- [Maths for data science - GeeksForGeeks](https://www.geeksforgeeks.org/maths-for-data-science/)

#### Probability

- [Probability and statistics - Khan Academy](https://www.khanacademy.org/math/statistics-probability/probability-library)
- [Probability for Data Science - Stanley H. Chan](https://probability4datascience.com/ch02.html)
- [Introduction to Probability - Joseph K. Blitzstein, Jessica Hwang](https://drive.google.com/file/d/15Y0oFNHQRls1qvQNvO3DFLJVhIZvUjTD/view?usp=sharing)

#### Statistics

- [Statistics for data science - Great Learning](https://youtu.be/Vfo5le26IhY)
- [Statistics: A full university course - freeCodeCamp](https://youtu.be/xxpc-HPKN28)
- [Statistics fundamentals - StatQuest with Josh Starmer](https://youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9)
- [Statistics for data science - CampusX](https://youtu.be/DUT4WEUngt0)
- [Intro to Descriptive Statistics - Udacity](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
- [Fundamentals Of Statistics For Data Scientists - Towards Data Science](https://towardsdatascience.com/fundamentals-of-statistics-for-data-scientists-and-data-analysts-69d93a05aae7)

#### Data manipulation

Data cleaning:

- [Data cleaning - Alex The Analyst](https://youtu.be/bDhvCp3_lYw)
- [Cleaning Data in Python - DataCamp](https://app.datacamp.com/learn/courses/cleaning-data-in-python)
- [Data cleaning course - Kaggle](https://www.kaggle.com/learn/data-cleaning)
- [Data cleaning and some analysis - Kaggle notebook](https://www.kaggle.com/ashishg21/data-cleaning-and-some-analysis-shoe-prices)

Data visualisation:

- [Data Visualization full playlist - Corey Schafer](https://www.youtube.com/watch?v=UO98lJQ3QGI&list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_)
- [Data Visualization tutorial series - sentdex](https://www.youtube.com/watch?v=q7Bo_J8x_dw&list=PLQVvvaa0QuDfefDfXb9Yf0la1fPDKluPF)
- [Data Visualization python - Intellipaat](https://www.youtube.com/live/_YWwU-gJI5U?feature=share)
- [Introduction to Data Visualization with Matplotlib - DataCamp](https://app.datacamp.com/learn/courses/introduction-to-data-visualization-with-matplotlib?fbclid=IwAR1OrJSdZ2LVD_c1o3d-_1I7Nhq8OZ3pzTu4010E_XWEmMc0KYsTosz8CIU)
- [Data Visualization - Kaggle](https://www.kaggle.com/learn/data-visualization)

#### Exploratory data analysis

- [EDA and Feature Engineering - Krish Naik](https://youtu.be/fHFOANOHwh8)
- [EDA in Python - Simplilearn](https://youtu.be/MoM6mighOJM)
- [Exploratory Data Analysis in Python - DataCamp](https://learn.datacamp.com/courses/exploratory-data-analysis-in-python)
- [EDA for Machine Learning - Coursera](https://www.coursera.org/learn/ibm-exploratory-data-analysis-for-machine-learning)

#### Machine learning

- [ML for beginners - freeCodeCamp](https://youtu.be/NWONeJKn6kc)
- [ML full course playlist - Andrew Ng](https://youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU)
- [ML full playlist - Kunal Kushwaha](https://youtube.com/playlist?list=PLyzHIYrZBplo3K0dNUqppd2ynnoZPD6N1)
- [ML full course video - Simplilearn](https://www.youtube.com/live/lTzHlU3OrXs?feature=share)
- [ML full playlist - Kimia Lab](https://youtube.com/playlist?list=PL4upCU5bnihwCX93Gv6AQnKmVMwx4AZoT)
- [Machine learning - GeeksForGeeks](https://www.geeksforgeeks.org/machine-learning/)
- [Intro to Machine Learning - Udacity](https://www.udacity.com/course/intro-to-machine-learning--ud120)
- [Machine Learning with Python - Coursera (IBM)](https://www.coursera.org/learn/machine-learning-with-python)

#### Power BI

- [Power BI training - Microsoft](https://powerbi.microsoft.com/en-us/learning/)
- [Power BI full course tutorial - Learnit Training](https://youtu.be/e6QD8lP-m6E)
- [Power BI complete course - Coursera](https://www.coursera.org/learn/data-driven-decisions-with-power-bi)
- [Power BI tools and functionalities - GeeksForGeeks](https://www.geeksforgeeks.org/power-bi-tools-and-functionalities/)

#### Tableau

- [Tableau data visualisation tutorial - DataCamp](https://www.datacamp.com/tutorial/data-visualisation-tableau)
- [Tableau training - Salesforce](https://www.tableau.com/learn/training)
- [Introduction to Tableau - DataCamp](https://learn.datacamp.com/courses/introduction-to-tableau)
- [Tableau full course - Simplilearn](https://youtu.be/HM81vShSlWY)
- [What is Tableau and its importance - GeeksForGeeks](https://www.geeksforgeeks.org/what-is-tableau-and-its-importance-in-data-visualization/)

#### Web scraping and APIs

- [Web Scraping in Python - DataCamp](https://learn.datacamp.com/courses/web-scraping-with-python)
- [Build a Web Scraper with Python - Real Python](https://realpython.com/beautiful-soup-web-scraper-python/)
- [Web Scraping with Python - freeCodeCamp](https://youtu.be/XVv6mJpFOb0)

#### Model deployment

- [Deploying a deep learning model using Flask - Towards Data Science](https://towardsdatascience.com/deploying-a-deep-learning-model-using-flask-3ec166ef59fb)
- [Flask: creating a first simple application - GeeksForGeeks](https://www.geeksforgeeks.org/flask-creating-first-simple-application/)
- [How to Deploy a Machine Learning Model to Google Cloud - Daniel Bourke](https://www.youtube.com/watch?v=fw6NMQrYc6w)
- [GCP tutorial - GeeksForGeeks](https://www.geeksforgeeks.org/what-is-google-cloud-platform-gcp/)
- [Deploy Models with TensorFlow Serving and Flask - Coursera](https://www.coursera.org/projects/deploy-models-tensorflow-serving-flask)

#### Sample project ideas

- [End to end Project](https://www.youtube.com/playlist?list=PLatl6hdtJ0RnbkReSAuel6PeCPO155FpG)
- [Machine Learning Projects](https://www.youtube.com/watch?v=fiz1ORTBGpY&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6)
- [End To End ML Project With Docker, Github Actions And Deployment](https://www.youtube.com/watch?v=MJ1vWb1rGwM)
- [Real-World Python Machine Learning Tutorial w/ Scikit Learn](https://youtu.be/M9Itm95JzL0)

---

## Skills that show up in every track

Regardless of the path you choose, these topics keep coming back. If you invest in them early, every track gets easier.

| Skill | Why it matters | Where it appears in this handbook |
|---|---|---|
| How the internet works | Every application talks over a network | Frontend, Backend, DevOps |
| Linux terminal | Servers, tools and build systems live here | Backend, DevOps |
| Git and GitHub | Your history, your portfolio, your safety net | Frontend, Backend, and every project |
| Operating system basics | Explains processes, memory and files | Backend, DevOps |
| Docker and containers | Consistent environments from laptop to production | Backend, DevOps, Data Science deployment |
| APIs and JSON | The glue between almost all modern software | Frontend, Backend, Android, iOS, Flutter, Data Science |
| Databases and SQL | Nearly every real application stores data | Backend, iOS, Data Science |
| Testing | Confidence that your changes did not break things | Backend, DevOps |

If you are unsure where to spend your first week, spend it on internet basics, the terminal, and Git. They are never wasted.

---

## When you get stuck

Everyone gets stuck. What separates people who finish is how they respond.

1. **Read the error message slowly.** Out loud if it helps. Most error messages say exactly what is wrong.
2. **Shrink the problem.** Delete code until the error disappears, then add it back a line at a time.
3. **Explain it to a rubber duck.** Describing the problem in plain language often reveals the answer.
4. **Search with intent.** Paste the exact error text, add the language or framework name, and read the top few results before trying anything.
5. **Take a walk.** Fifteen minutes away from the screen solves more bugs than another hour of staring.
6. **Ask well.** When you post a question, include what you expected, what actually happened, the smallest code that reproduces it, and what you have already tried.
7. **Come back tomorrow.** Sleep does real work on hard problems.

If you are stuck on the same concept for two days, it usually means a prerequisite is missing. Step back one topic and try again.

---

## Final note

Learning to build software is mostly a matter of showing up, building small things, and being kind to yourself when progress feels slow. You do not need to be a genius, and you do not need to have started earlier. You need a plan, a few good resources, and the patience to keep going. This handbook gives you the first two. The third is up to you.

Good luck, and enjoy the month.
