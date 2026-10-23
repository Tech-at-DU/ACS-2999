# Independent Study Plan: UX + Full Stack Web Project (7 Weeks)

**How the course works:** The student takes one idea from the first week all the way to a live, deployed site. The first half is UX work: research, structure and design. The second half is building, testing and shipping. Each week ends with one clear deliverable to show at the weekly meeting.

---

### Week 1: Define the Project *(already assigned)*
**Deliverable:**
- 5 site ideas, with pros and cons and a sample content item for each
- 3–5 personal goals for the course

**At the meeting:** Narrow the 5 ideas to 1 or 2 finalists.

---

### Week 2: UX Research and Picking the Project
**Tasks:**
- Commit to one idea.
- Find 3 similar sites. Note what each does well and what it does badly.
- Talk to 2–3 people who might use the site. A 10-minute informal interview is fine.
- Write 1–2 personas based on those conversations.
- Write 8–12 user stories, such as "As a ___, I want to ___ so that ___."
- Mark which stories are the minimum viable product (MVP) and which are "nice to have."

**Deliverable:** A short research doc with the review of similar sites, interview notes, personas, and a ranked list of user stories with the MVP marked.

---

### Week 3: Site Structure, Wireframes and a Clickable Prototype
**Tasks:**
- Draw a sitemap: every page and how the pages link to each other.
- Draw rough wireframes for the main pages, such as home, list, detail and create/edit.
- Build a clickable prototype in Figma (or a similar tool).
- Ask 3 people to complete 2–3 tasks in the prototype. Write down where they get stuck.

**Deliverable:** The sitemap, the wireframes, a link to the prototype, and a one-page summary of what testers found and what will change.

---

### Week 4: Data Model, Back End and Setup
**Tasks:**
- Use the sample content items from Week 1 to define the data model. For a blog, this might be posts, authors and tags, with their fields and how they relate.
- Pick a tech stack. Suggestion: Node/Express or Next.js, a database (Postgres, SQLite or MongoDB), and GitHub for code.
- Create the repository, the database, and the API routes for create, read, update and delete (CRUD) on the main content type.
- Deploy a basic version early to Render, Vercel or Railway. This avoids last-minute deployment surprises.

**Deliverable:** A GitHub repo with a working API (testable with Postman or curl), a data model diagram, and a live deployed URL, even if it's bare.

---

### Week 5: Front End Build
**Tasks:**
- Build the MVP pages from the Week 3 wireframes.
- Connect the pages to the API so content is read from and written to the database.
- Turn the visual design into real styles: a type scale, a color palette and reusable components.
- Make the layout work on phones.

**Deliverable:** A working MVP on the live URL. A user can complete the core user stories from start to finish.

---

### Week 6: Usability Testing, Accessibility and Iteration
**Tasks:**
- Run a second round of testing with 3 people on the real site, using the same tasks as Week 3 so the results can be compared.
- Run an accessibility check: Lighthouse or axe, keyboard navigation, color contrast, alt text.
- Fix the top 3–5 issues the testing and checks turned up.
- Optional stretch goal: user accounts and login, search, or one of the "nice to have" stories.

**Deliverable:** Test notes, before and after accessibility scores, and a list of changes with matching commits or pull requests.

---

### Week 7: Case Study and Presentation
**Tasks:**
- Write a portfolio case study covering the problem, research, design process, what testing showed, the technical build, and what the student would do next.
- Polish the README so someone else could set up and run the project.
- Reflect on the Week 1 goals: which were met, and how.

**Deliverable:** The final live site, the case study (as a page on the site or a write-up), and a 10–15 minute walkthrough at the last meeting.

---

### Notes for the Instructor
- **The main risk is scope.** Seven weeks is short for full stack work. Hold the line on the MVP at the end of Week 2, and push everything else to the Week 6 stretch goal.
- **Deploying in Week 4 is on purpose.** Hosting and environment problems tend to eat the final week if they're left until then.
- **If the student is stronger on UX than on code**, Weeks 4–5 can use a headless CMS such as Sanity or Strapi, or a backend service such as Supabase, instead of a custom API. They would still learn data modeling without as much backend work.
- **Each meeting can follow the same pattern:** demo the deliverable (10 min), go over problems (15 min), preview next week (5 min).

If you'd like, I can turn this into a shareable doc or a handout you can give the student.