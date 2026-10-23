# Independent Study: UX + Full Stack Web Project

**Length:** 7 weeks, one meeting with your instructor each week

## What you will do

Over 7 weeks you will take one website idea from a rough concept to a live, deployed site, and then write it up as a portfolio case study.

- **Weeks 1–3: UX.** Choose an idea, research the people who would use it, and design the site.
- **Weeks 4–6: Build.** Build the back end and the front end, deploy the site, test it with real people, and improve it.
- **Week 7: Ship.** Finish the site, write the case study, and present your work.

## How each week works

1. Each week below lists **Tasks** (what you do) and **Deliverables** (what you hand in).
2. Hand in every deliverable **at least 24 hours before your meeting**. Send your instructor a link.
3. A deliverable is done only when it meets every item on its checklist.
4. Come to the meeting ready to answer the **Meeting discussion** questions for that week. You don't need to write the answers down unless the week says to.

**Every meeting follows the same format (30 minutes):**

- **10 min:** You demo or walk through your deliverables.
- **15 min:** Discussion questions, problems, and feedback.
- **5 min:** Review next week's tasks and agree on anything that changed.

## Where your work goes

- **Weeks 1–3:** Keep your documents in one shared folder, such as a Google Drive folder or a Notion page, and share it with your instructor in Week 1.
- **Week 4 onward:** Your code goes in a GitHub repository. Move your earlier documents into a `docs/` folder in that repository so all of your work is in one place.

## The scope rule

Seven weeks is not a lot of time. In Week 2 you will choose your **MVP** (minimum viable product): the smallest set of features that makes the site useful. You build the MVP first. Anything else is a **stretch goal** and waits until Week 6. If you fall behind, cut stretch goals, never the MVP.

---

## Week 1: Define the project

**Goal:** Explore several ideas before committing to one.

### Tasks

1. Come up with **5 different ideas** for a blog or another kind of content website. Examples: a recipe blog, a hiking trail guide, a band's tour and merch site, a book review site, a local events listing.
2. For each idea, write **at least 3 pros and 3 cons**. Consider:
   - Would you enjoy working on it for 7 weeks?
   - Who would use it? Can you find real people like that to talk to?
   - How hard would it be to build?
   - Would it look good in your portfolio?
3. For each idea, write **one sample content item**: a single realistic example of the main thing the site displays, with every field filled in.
   - *Example for a recipe blog:* Title: "Weeknight Chili". Author: Sam. Prep time: 20 min. Servings: 4. Ingredients: (list). Steps: (list). Photo: (description or image). Tags: dinner, spicy.
4. Write **3–5 personal goals**: what you want to be able to do, or to show, when this course is over.

### Deliverables

- [ ] **Ideas document** with all 5 ideas. Each idea has:
  - [ ] A one-sentence description
  - [ ] At least 3 pros and 3 cons
  - [ ] One sample content item with every field filled in
- [ ] **Goals list** with 3–5 goals. Each goal is specific enough to check at the end of the course.
  - *Too vague:* "Get better at coding."
  - *Specific:* "Build and deploy a site with a database on my own."
- [ ] A **shared folder** with both documents, shared with your instructor

### Meeting discussion

- Which 2 ideas are you most excited about, and why?
- For your top 2 ideas: who exactly would use the site? Can you name 2–3 real people like that you could talk to next week?
- Look at your sample content items. Which idea has the most interesting content structure (several fields and relationships, not just a title and text)?
- Which of your goals are about UX, and which are about development? Is the balance what you want?
- **Decision to make by the end of the meeting:** narrow your list to 1 or 2 finalists.

---

## Week 2: UX research and choosing your project

**Goal:** Choose one idea and learn about the people who would use it.

### Tasks

1. **Choose one idea** from your Week 1 finalists.
2. **Competitive review.** Find 3 existing sites similar to your idea. For each one, write down:
   - Its name and link
   - 2–3 things it does well
   - 2–3 things it does badly or is missing
   - One idea you will borrow, or one mistake you will avoid
3. **User interviews.** Interview 2–3 people who might use your site, for about 10 minutes each. In person, by video call, or by phone are all fine. Ask them about their habits and frustrations, not about your idea. Write short notes after each interview. Questions you can use:
   - "When was the last time you [looked for a recipe / planned a hike / etc.]? Walk me through what you did."
   - "What was frustrating about that?"
   - "What sites or apps do you use for this now? What do you like or dislike about them?"
4. **Personas.** Write 1–2 personas based on your interviews. Each persona includes: a name, a short background, their goals, their frustrations, and how they would use your site.
5. **User stories.** Write 8–12 user stories in this format:
   > As a **[type of user]**, I want to **[do something]** so that **[reason]**.
   > *Example:* As a **home cook**, I want to **filter recipes by prep time** so that **I can find something I can make on a weeknight**.
6. **Prioritize.** Rank your user stories from most to least important. Label each one **MVP** or **Stretch**. Aim for no more than 5–6 MVP stories.

### Deliverables

- [ ] **Research document** containing:
  - [ ] The name of the idea you chose and one paragraph explaining why
  - [ ] A competitive review of 3 sites, with every item from Task 2 filled in
  - [ ] Notes from 2–3 interviews, with each person's first name or initials and the date
  - [ ] 1–2 personas, with every section from Task 4 filled in
  - [ ] 8–12 user stories, ranked and labeled MVP or Stretch

### Meeting discussion

- What surprised you in your interviews? Did anything change your idea?
- Which competitor is closest to what you want to build? What will make your site different?
- Walk through your MVP stories. If you could build only 3 of them, which 3 would you keep?
- Are any MVP stories hard to build, such as user accounts, payments, or real-time features? Should they move to Stretch?
- **Decision to make by the end of the meeting:** agree on the final MVP list. This list is your scope for the rest of the course.

---

## Week 3: Site structure, wireframes, and a clickable prototype

**Goal:** Design the site and test the design with real people before you write any code.

### Tasks

1. **Sitemap.** Draw a diagram of every page on your site and how the pages link to each other. Paper, Figma, or a diagram tool such as FigJam or Whimsical are all fine.
2. **Wireframes.** Draw low-detail wireframes (boxes and labels, no colors or images yet) for every page your MVP stories need. Most sites need at least:
   - A home page
   - A list page (for example, all recipes)
   - A detail page (for example, one recipe)
   - A create/edit page (for example, an "add recipe" form)
3. **Clickable prototype.** In Figma, turn your wireframes into a prototype where clicking a button or link takes you to the right screen. Add some visual design: your color choices, fonts, and real-looking content (use your Week 1 sample content item).
4. **Prototype test.** Ask 3 people to use the prototype. Use people who are not in this course, if possible.
   - Give each person the same 2–3 tasks, based on your MVP stories. *Example:* "Find a vegetarian recipe that takes less than 30 minutes."
   - Watch them, without helping. Write down where they hesitate, click the wrong thing, or get confused.
5. **Plan your changes.** List the problems you saw and what you will change. Update the prototype for the most important ones.

### Deliverables

- [ ] **Sitemap** (image or link)
- [ ] **Wireframes** for every page the MVP needs (images or a link to Figma)
- [ ] A **link to the clickable prototype**, with view access shared with your instructor
- [ ] **Test summary** (one page) containing:
  - [ ] The 2–3 tasks you gave testers
  - [ ] What each of the 3 testers did, and where they struggled
  - [ ] The top 3 problems you found, and the change you made or plan to make for each

### Meeting discussion

- Demo the prototype. Where did testers get stuck, and why do you think that happened?
- Which changes did you make already, and which will you make during the build?
- Does every MVP story have a page or screen that supports it? Is anything missing?
- Look at your sample content item and your detail page. What data will you need to store?
- **Decision to make by the end of the meeting:** choose your tech stack for Week 4. Decide between:
  - **Custom back end:** for example, Node/Express or Next.js with a database such as Postgres, SQLite, or MongoDB. More code, more back end learning.
  - **Hosted back end or CMS:** for example, Supabase, Sanity, or Strapi. Less back end code, more time for front end and UX.

---

## Week 4: Data model, back end, and first deploy

**Goal:** Store and serve your content, and get a live URL working early.

### Tasks

1. **Data model.** Using your sample content item and your wireframes, list every type of data your site stores (for example: recipes, authors, tags). For each type, list its fields and their data types. Show how the types connect (for example: "one author has many recipes"). Draw this as a diagram.
2. **Set up the project.** Create a GitHub repository. Move your Weeks 1–3 documents into a `docs/` folder in it. Commit your work at least every time you finish a task.
3. **Build the API.** Using the stack you chose in Week 3, set up the database and build routes that create, read, update, and delete (CRUD) your main content type.
4. **Add sample data.** Put at least 5 realistic content items in the database.
5. **Deploy.** Deploy the project to a hosting service such as Render, Vercel, or Railway. The site doesn't need to look like anything yet; it only needs to be live. Deploying now means hosting problems show up this week, not in Week 7.

### Deliverables

- [ ] **Data model diagram** in `docs/`
- [ ] A **GitHub repository** shared with your instructor, with commits from this week
- [ ] A **working API** for your main content type. In your README, list each route (method and URL) and an example request, so your instructor can test it with Postman or curl.
- [ ] At least **5 sample content items** in the database
- [ ] A **live deployed URL** that loads and returns data from at least one route

### Meeting discussion

- Walk through your data model. Why did you structure it this way? What would change if you added a stretch feature later?
- Demo the API: create an item, read it, update it, and delete it.
- What was the hardest part of setup or deployment? What did you learn from it?
- Are you on schedule? If not, what will you cut or simplify so that the front end gets built next week?

---

## Week 5: Front end build

**Goal:** Build the pages from your design and connect them to real data.

### Tasks

1. **Build every MVP page** from your Week 3 prototype (after the changes you made from testing).
2. **Connect to the API.** Pages read real content from the database, and forms save to it. No fake or hard-coded data.
3. **Apply your visual design.** Set up the font sizes, the color palette, and reusable components (such as buttons, cards, and form fields) from your prototype. Use them consistently.
4. **Make it responsive.** Every page must work on a phone screen (about 375px wide) and on a desktop screen.
5. **Deploy** the updated site to your live URL.

### Deliverables

- [ ] **Every MVP page** is built and live at your deployed URL
- [ ] **Each MVP user story** can be completed from start to finish on the live site. In your README, list each story and how to do it.
- [ ] Pages show **real data** from the database
- [ ] Every page **works on a phone and on a desktop**
- [ ] Your code is **committed and pushed** to GitHub

### Meeting discussion

- Demo each MVP story on the live site, on both phone and desktop.
- Where did the built site end up different from your prototype? Why?
- What part of connecting the front end to the back end was confusing?
- What bugs or rough spots do you already know about?
- **Decision to make by the end of the meeting:** choose the 3 tasks you will give testers next week. Use the same tasks as Week 3 if they still fit.

---

## Week 6: Usability testing, accessibility, and improvements

**Goal:** Test the real site, fix the most important problems, and add a stretch feature if you have time.

### Tasks

1. **Usability test.** Ask 3 people to complete your tasks on the live site, the same way you tested the prototype in Week 3. Use new people if possible. Write down where they struggle.
2. **Accessibility check.** Before you fix anything, check your site and record the results:
   - Run Lighthouse (in Chrome DevTools) on your home page and one other page. Write down the Accessibility score for each.
   - Use the site with only a keyboard (Tab, Shift+Tab, Enter). Can you reach and use everything?
   - Check text color contrast. Lighthouse reports this.
   - Check that every image has useful alt text.
3. **Fix the top 3–5 problems** from testing and the accessibility check. Make one commit (or pull request) per fix, with a clear message.
4. **Run Lighthouse again** on the same pages and record the new scores.
5. **Optional:** If the MVP is finished and working, build one stretch feature from your Week 2 list.

### Deliverables

- [ ] **Test notes:** the tasks, what each of the 3 testers did, and the problems you found
- [ ] **Comparison with Week 3:** a short paragraph on whether testers did better or worse than with the prototype, and why
- [ ] **Accessibility results:** Lighthouse scores before and after, plus what you found in the keyboard, contrast, and alt text checks
- [ ] **Change list:** the 3–5 problems you fixed, each with a link to its commit or pull request
- [ ] The **updated site** is live at your deployed URL
- [ ] *(Optional)* A stretch feature, working on the live site

### Meeting discussion

- What did testers struggle with on the real site that they did not struggle with in the prototype, or the other way around?
- Why did you choose these 3–5 fixes over the others?
- What did you learn from using your site with only a keyboard?
- What is left to finish before the final presentation? Is anything at risk?
- **Outline your case study** with your instructor: what is the most interesting part of your story?

---

## Week 7: Case study and final presentation

**Goal:** Finish the project and present it the way you would in a job interview.

### Tasks

1. **Final fixes.** Fix any remaining bugs. Make sure the live site works and has realistic content. Do not start new features this week.
2. **README.** Update your README so another developer could set up and run your project. Include:
   - What the project is
   - The tech stack
   - How to install and run it locally
   - Environment variables (names only, never the real values)
   - The live URL
3. **Case study.** Write a portfolio case study, either as a page on your site or as a document, with these sections:
   1. **The problem:** what the site is for and who it is for
   2. **Research:** what you learned from competitors and interviews
   3. **Design:** sitemap, wireframes, and prototype, with images
   4. **Testing:** what both rounds of testing showed and what you changed
   5. **The build:** your tech stack, your data model, and one technical challenge you solved
   6. **Next steps:** what you would build or change with more time
4. **Goal reflection.** Go back to your Week 1 goals. For each one, write 2–3 sentences about whether you met it and what shows that you did.
5. **Presentation.** Prepare a 10–15 minute walkthrough of your case study and a live demo of the site.

### Deliverables

- [ ] **Final site** live at your deployed URL, with no known broken features
- [ ] **README** with every item from Task 2
- [ ] **Case study** with all 6 sections from Task 3
- [ ] **Goal reflection** covering each of your Week 1 goals
- [ ] A **10–15 minute presentation** given at the final meeting

### Meeting discussion

- Give your presentation (10–15 min).
- What are you most proud of? What would you do differently if you started over?
- Which skills from this course do you want to keep building, and what is a good next step for each?
- How will you use this project in your portfolio or job applications?
