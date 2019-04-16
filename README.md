# A (Coding Dojo) Graduation Speech?

_For the graduating classes of April/May/Whenever 2019_

- [Developing yourself](#developing-yourself)
  - [Setting up your dev environment](#setting-up-your-dev-environment)
  - [Setting up your GitHub](#setting-up-your-github)
  - [Creating your website](#creating-your-website)
    - [Building your portfolio](#building-your-portfolio)
  - [Building your identity](#building-your-identity)
  - [Becoming a better developer](#becoming-a-better-developer)
  - [Building your confidence](#building-your-confidence)
    - [Practice](#practice)
    - [Templates](#templates)
    - [Exposure](#exposure)
    - [Presentation](#presentation)
  - [Studying best practices, principles, and patterns](#studying-best-practices-principles-and-patterns)
    - [Resources](#resources)
- [Getting a job](#getting-a-job)
  - [Who to talk to](#who-to-talk-to-in-person)
  - [Where to look](#where-to-look-online)
    - [General](#general)
    - [Dev specific](#dev-specific)
    - [Startup](#startup)
  - [What to look for](#what-to-look-for-in-a-company)
  - [How to prepare for interviews](#how-to-prepare-for-interviews)
    - [Behavioral](#behavioral)
    - [Technical](#technical)
- [General resources](#general-resources)

## Developing yourself

Keep growing your potential, developing your skills, and building your confidence. (It's an exciting, life-long process.)

### Setting up your dev environment

> "A developer is only as good as her environment."

— a fake quote I made up

Ground zero is making sure you have the tools of the trade ready. An amazing toolbox is essential for an amazing crafts(wo)man. A good development environment exponentially enhances your coding capabilities.

1. Configure your command-line interface of choice, such as Terminal, [Hyper](https://hyper.is/), or [iTerm](https://www.iterm2.com/) on Mac.
1. Install git via [Xcode Command Line Tools](https://hackernoon.com/install-git-on-mac-a884f0c9d32c) (Mac only) or the [git-scm download](https://git-scm.com/downloads).
1. Download your text editor of choice, such as [VS Code](https://code.visualstudio.com/), [Atom](https://atom.io/), or a [JetBrains product](https://www.jetbrains.com/products.html) (if you have the money).
1. Configure your text editor by downloading packages ([Atom](https://atom.io/packages)) or extensions ([VS Code](https://marketplace.visualstudio.com/VSCode)).
   1. Install a linter and auto-formatter for your text editor, preferably [ESLint](https://eslint.org/) and [Prettier](https://prettier.io/). (Note: ESLint and Prettier require you to [install Node](https://nodejs.org/en/download/) and follow the set up instructions found on each site.)
   1. Install necessary language support and syntax highlighting packages, if not already enabled by default.
   1. Install auto-completion and snippet packages for the necessary languages.
   1. Install a git differentiator package.

### Setting up your GitHub

> GitHub is home to the world’s largest community of developers and their projects. Join the millions of developers already using GitHub to share their code, work together, and build amazing things.

— what GitHub says about themselves.

The coding/development community lives and thrives on GitHub. This is your new home.

1. [Join GitHub](https://github.com/join) if you haven't already.
1. Make your profile friendly. Add your name, email, bio, and location.
1. Create new repositories (repos) for your best projects.
1. Follow awesome developers.
1. Read good code, clone repos, and play with the code.
1. Star and "Watch" great repos.
1. Contribute to an open source project.
   - [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
   - [First Contributions walkthrough](https://github.com/firstcontributions/first-contributions)
1. Create your own website using GitHub pages.

### Creating your website

GitHub offers free "static" website hosting through [GitHub Pages](https://pages.github.com/). Take advantage of that! (Save some \$\$\$.) GitHub Pages can be used for websites for your portfolios, projects, documentation, etc.

1. [Create a new repository](https://github.com/new) named _yourusername_.github.io, where "_yourusername_" is your GitHub username, e.g. _jimmy_.github.io
1. Open your command-line interface application (Terminal, Hyper, iTerm).
1. Navigate to your "dev" directory (or wherever you store your development projects).
   - `cd ~/dev`
1. Copy your repo's git url and use it to clone your new (empty) repo. (Or copy this example and replace "_{yourusername}_" with your GitHub username)
   - `git clone https://github.com/{yourusername}/{yourusername}.github.io`
   - `git clone https://github.com/jimmy/jimmy.github.io`
1. Go to your newly created directory.
   - `cd {yourusername}.github.io`
   - `cd jimmy.github.io`
1. Start by creating an `index.html` file.
   - `touch index.html`
1. Open this project directory in your text editor.
   - `code .` for VS Code or `atom .` for Atom
1. Edit the HTML file and create a basic website.
1. Add the HTML file to git.
   - `git add index.html`
1. Commit to git with a simple message.
   - `git commit -m "Initial commit"`
1. Push your first commit to your repo's master branch.
   - `git push -u origin master`
1. Check out your new site! Open your browser and go to https://_yourusername_.github.io/ (but replace "_yourusername_" with your GitHub username, of course).
1. [Get a custom URL](https://help.github.com/en/articles/quick-start-setting-up-a-custom-domain) if you want!
   1. Buy a domain through [GoDaddy](https://www.godaddy.com/domains/domain-name-search) or [Google Domains](https://domains.google/#/domains-header)
   1. On GitHub, navigate to your GitHub Pages site's repository and click Settings (in the top right tabs).
   1. Add your custom domain under "Custom domain" and click Save.
   1. (Recommended) Ensure you enforce HTTPS for your site.
   1. [Configure an `ALIAS`, `ANAME`, or `A` record](https://help.github.com/en/articles/setting-up-an-apex-domain) with your DNS provider.
   1. (May or may not be necessary) Remove and then re-add your custom domain to your GitHub repo's Settings.

#### Building your portfolio

Use your website to showcase yourself and your unique identity (or "brand" in _business-speak_). Here are some ideas for what to include:

- Your name
- An introduction, "about me", or bio
- A way for people to contact you (e.g. email)
- Links to your best work and projects
  - Links to your code for each project in GitHub
- Link to your GitHub itself
- Link to your résumé
- Links to your social media (e.g. LinkedIn)

### Building your identity

> "If you don't know what you want, you end up with a lot you don't."

— quote from _Fight Club_ by Chuck Palahniuk

```js
if (!you.know(whatYouWant)) {
  return whatYouDontWant;
}
```

— a bad coding joke by me

**Learn about yourself. Discover what you want.**

Take time to think about yourself, your life, and your ideal career. Decide what would be the best fit for you personally. Learn your strengths, preferences, passions, and values. Find a career path (jobs) that you can connect with personally.

Strive for a deep engagement with your work and a meaningful connection with your team, your leadership, and your organization's priorities, goals, principles, values, mission, and vision. Seek a career that keeps your values aligned with the values of your workplace.

### Becoming a better developer

My adaptation of _10 Ways to Become a Better Developer_:

1. Read other people's code.
1. Get someone to read your code.
1. Fix bugs before writing new code.
1. Learn new technologies.
1. Keep it simple.
1. Write README's and wikis.
1. Contribute to open source.
1. Fix it; don't hack it.
1. Cover your code with tests.
1. Don't sit for hours on end.

### Building your confidence

Confidence is key to almost everything in life but doubly so for carving a new career path. This is often the biggest worry of new developers. Beginners might feel as though they'll never feel confident in their own abilities to be a great developer and create custom projects from scratch. The best way to build confidence is through _practice_.

#### Practice

Practicing code means building the types of projects that you want to be confident in being able to create. Hone your craftsmanship; focus on a few types of projects that you want to be confident with. Choose those projects carefully and build a few on your own. This will push you, but your work will only be accountable to you. (It's safe to fail and make mistakes.) Be sure to give yourself project goals that you are passionate about and genuinely interested in. This is the fuel to your motivation! Keep your goals big but realistic.

Here are some **types** of projects you may wish to practice:

- Event planner / registration app (calendar)
- Social media / forum app
- Blog website
- Online store website
- Contact form
- Login interface
- Portfolio website
- Brand website
- Band website
- Restaurant website
- Résumé / CV website
- Search, filter, sort list app (directory)
- C.R.U.D. list app (generic data interface)
- Calculator app
- Information processor app
- Data visualizer app
- Game

#### Templates

As you start on your third or fourth project of a specific type, you'll start to notice yourself repeating some steps in the process of developing that particular type of project. This is a beautiful sign that you're ready to start building templates!

A template is a starting point / launching pad for a particular type of project. It reduces time taken to get started by having all the commonly repeated steps completed for you at the beginning. The goal is to reduce repeating boilerplate code. Write the code once in a great template and write it really well. Then reuse that template for any future projects of that particular type. (Templates are a lot like a good function, where the parameters are the variable aspects expected for every project of the template's type and the returned output is the base project.)

In the process of creating a template, you'll refine your boilerplate code and make it consistent and reusable. Then, if you give it good documentation, you can share your template with the broader, open dev community. Add a well-written `README.md` with your documentation to the root of your project; then push that to a new repo so anyone can clone your template and use it for their own projects of the template's specific type.

If you've created a template for a type of project, you're certainly mastering that type of project, which should also bolster your confidence!

#### Exposure

Explore different approaches, methods, and processes for creating the types of project that you're seeking to build your confidence in and master. Find new ways of recreating your projects using different technologies, frameworks, and libraries. Try different templates and boilerplates for your projects. Compare and contrast each discovery, noting pros and cons.

#### Presentation

The process by which you share and present your projects is as important as the process by which you create the project in the first place. Great presentation and sharing requires a great degree of confidence. The more you practice presenting your work, the better your confidence will become. There is an art and a science to talking about yourself and sharing your projects and code. Use your portfolio and any areas where you write about yourself, such as bios for websites, as your training grounds. They should be constantly evolving as your skills improve and your confidence boosts.

### Studying best practices, principles, and patterns

Stay fresh. Learn about industry standards and practices. Explore developing patterns.

1. Read the documentation of new developments, such as frameworks, libraries, and tools.
   - Read the source code in the repo on GitHub.
1. Listen to someone explain good code.
1. Watch someone write good code.
1. Follow rad developers and organizations that are active in the development community. (Find out who is behind your favorite technologies and frameworks.)
1. Regularly check up on the [topics](https://github.com/topics) you care about on GitHub.
1. See what's trending on GitHub by seeing which repos have the most stars for particular topics or tags.
1. Check up on great blogs or podcasts.
1. Attend cool conferences or [meetups](https://www.meetup.com/find/events/tech/).
1. Work on projects on your own and with friends.
   1. Ask for recommendations on what to use when starting a project.
   1. Explore various ways of accomplishing your goal.
   1. Check out similar projects to see what others use and how they accomplished their goals.
   1. Check to see if there is new standard or practice for doing what you're trying to do.
   1. Have people review your code.
1. Seriously, do projects! Nothing will motivate you to learn more than giving yourself a goal that you care about.

#### Resources

- [GitHub topics](https://github.com/topics)
- [Best practices for JavaScript projects](https://github.com/elsewhencode/project-guidelines)
- [Programming Principles & Patterns](https://github.com/webpro/programming-principles)
- [Teach Yourself Computer Science](https://teachyourselfcs.com/)
- [Awesome Lists](https://github.com/sindresorhus/awesome)
- [W3Schools](https://www.w3schools.com/)
- [Google Dev Web Fundamentals](https://developers.google.com/web/fundamentals/)

## Getting a job

### Who to talk to (in person)

1. Fellow developers
   - Friends
   - Friends of friends
1. People at co-working spaces (e.g. Trailhead)
   - People who regularly work there
   - People attending public events hosted there
1. People at meetups
   - Founders/speakers
   - Fellow members

### Where to look (online)

#### General

- [Google](https://www.google.com/) ("frontend engineer boise")
- [LinkedIn](https://www.linkedin.com/jobs/)
- Reddit?

#### Dev specific

- [GitHub](https://jobs.github.com/)
- [Stack Overflow](https://stackoverflow.com/jobs)
- [More sites in a list](https://github.com/sdmg15/Best-websites-a-programmer-should-visit#jobs)

#### Startup

- [AngelList](https://angel.co/jobs/)
- [Work at a startup](https://workatastartup.com) (YCombinator)

### What to look for (in a company)

- "Work–life balance"
- Training process (new hire onboard process)
- Responsibilities and expectations (diversity, variety, focus, definition, clarity)
- Collaboration, team work, and individual work
- Typical "day in the life"
- Definition and clarity of projects
- Reactivity to the unpredictable
- Sense of urgency
- Pace and speed of work
- Growth, development, progress, evolution (both for the organization and for individuals)
- "Off-hours" expectations (spoken or unspoken)
- Unspoken "policies"
- Documentation of process and decisions
- Definition and outline of policies, workflows, methods, roles, teams, and principles
- Decision-making process
- Leadership and management styles
- Review procedures for people ("performance")
- Metrics and measurements of "success" for goals, projects, and the organization overall
- Vision, direction, and roadmap
- Big picture overview of the purpose and people of the organization and teams
- Motivations, motives, and excitement
- Culture, personality, and values
- Relationships between short-term and long-term goals
- Forward-thinking objectives focused on the future
- Autonomy and flexibility of teams and individuals
- Craftsmanship, expertise, and mastery
- Cross-team interaction / collaboration
- Working environment and "office" setup (if applicable)
- Tech stack: who chooses it, how is it chosen, and how/when it changes
- Development and deployment workflow
- Testing and quality assurance
- Coding standards and styles
- "Cleanliness" of the codebase
- Size and scope of "backlog" and bugs
- Code review process
- How mistakes are handled
- feel a deep, meaningful connection and engagement with my work, with the company, with the goals of the organization, or with the leadership in the company

### How to prepare for interviews

Try to predict what questions you'll be asked, and try to prepare your answers.

#### Behavioral

Here are general behavioral / informational questions you should try to prepare a story for:

- Why do you want to work for us?
- Why do you want to leave your current company?
- What is your biggest achievement?
- What was your biggest programming challenge?
- Where do you see yourself in 5 years?
- What excites or interests you about coding?
- What is a recent technical challenge you experienced and how did you solve it?
- Describe a stressful situation at work and how you handled it.
- How have you handled a difficult situation with a co-worker?
- How have you handled a mistake you made?
- Describe a recent accomplishment that you're proud of.
- Describe your favorite project that you've ever worked on.
- Describe a time when you took initiative to go above and beyond your base duty.

#### Technical

It's nearly impossible to outline the vast variety of technical questions you might encounter during an interview, because each interview varies per company. Here is a list of interview preparation resources instead:

- [List of websites for interview preparation](https://github.com/sdmg15/Best-websites-a-programmer-should-visit#interview-preparation)
- [InterviewThis](https://github.com/Twipped/InterviewThis) (list of developer questions to ask prospective employers)
  - [The Joel Test: 12 steps to better code](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/)
- [InterviewBit practice](https://www.interviewbit.com/practice/)
  - [Solutions to those practice problems](https://github.com/karan/Projects-Solutions)
- [LeetCode problem set: algorithms](https://leetcode.com/problemset/algorithms/)
- [Notes from a Dozen Software Interviews](http://kelukelu.me/interview/)
- [CS interview study sheet](https://github.com/kimberli/interviews)
- [Front-end Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)

And finally, for those of you who seek a job interview that doesn't involve using a whiteboard to solve CS trivia, technical puzzles, riddles, algorithms, or brainteasers, I give you a beautiful resource of a compiled list of companies that focus on discussing real world problems in interviews instead: [Hiring Without Whiteboards](https://github.com/poteto/hiring-without-whiteboards) (and its converse: [They Whiteboarded Me](http://they.whiteboarded.me/))

## General resources

- [Google](https://google.com/) (It's a great joke, but I'm also 100% serious. It's the number one resource on the list.)
- [GitHub](https://github.com/)
- [Stack Overflow](https://stackoverflow.com/)
- [Awesome Lists](https://github.com/sindresorhus/awesome)
- Slack (Find communities)
- [W3Schools](https://www.w3schools.com/)
- [CodePen](https://codepen.io/)
- [Google Dev Web Fundamentals](https://developers.google.com/web/fundamentals/)
- [Google Tools for Web Developers](https://developers.google.com/web/tools/)
