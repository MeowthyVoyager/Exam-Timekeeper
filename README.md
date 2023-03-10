![Picture](https://preview.redd.it/w87tglqf7wla1.png?width=1920&format=png&auto=webp&v=enabled&s=b4efcb0ad240ed807e7367530f20430c7d2efd7c)  

## π’ The unexpected problem

The story starts a few weeks before the JEEMains Session 1, when I was looking for something to keep on my screen while I solved some practice questions. Instead of just solving the pyqs, I decided to build a basic static website with a countdown timer and a title. When I posted it on Reddit, it received about 70 upvotes. Over the next few months, the site had 10,000 pageviews and 40 daily users.

It was quite absurd, this was just a countdown timer, yet so many peeps used it.

Despite its simplicity, it seemed that many people found the countdown timer helpful. I received DMs on Discord and Reddit, asking me to add more examinations to the website. So, I decided to expand this project to help even more students.

<hr/>

## π― Making it work

"I initially started the project using Svelte, but quickly realized my mistake and switched to Astro within a few hours of the hackathon starting. The development process with Astro was smooth, except for the usual CSS

The project is complete as its main feature is working, but adding smaller features would be the cherry on top.

Building the project amidst board examinations was a challenging task, but also a fun and insightful experience.

<hr/>

## π» Ensuring the importance of FOSS

It was great interacting and just watching the FOSSHack community, it was a great way to step into FOSS development

<hr/>

## π Project Structure

```
/
βββ public/
βββ src/
β   βββ components/
β   β   βββugpagescomponents/
β   βββ layouts/
β   βββ pages/
β   β   βββugpages/
β   βββ styles/
βββ package.json
```

## π§ Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |


## β Future updates [TODO]
- [ ] Webscaper to get data
- [ ] Using open source database for the scrapped data
- [ ] Better Documentation 
- [ ] Add more exams
- [ ] Create your own timer feature
