# SwitchDesk: How to Switch Careers Into IT Without a Technical Background

An interactive landing page that works like a friendly IT service desk for career switchers. Visitors raise a ticket, get triaged into an IT lane, translate their old job into IT skills and work through a ninety day ticket board.

Built with plain HTML, CSS and JavaScript. No frameworks, no build step, no dependencies.

## What is inside

The page has a sticky header, a hero section with an animated ticket that you can move from Open to Resolved, a three question triage quiz that recommends an IT lane, a skill translator for six common backgrounds, an expandable role map, a ninety day ticket board with saved progress, a resources section and a full footer.

## Interactive features

Triage quiz: answer three questions and get a lane with a relevant link.
Skill translator: tap a background such as Teacher, Banker or Nurse to see how it reads in IT language.
Role map: tap a card to expand it.
Ninety day board: tick tasks and watch the progress bar fill. Progress is stored in the browser with localStorage.

## Resource links

Courses and bootcamp:
- Data Analytics Bootcamp in Hyderabad: https://www.justacademy.co/job-bootcamp-detail/hyderabad/data-analytics-bootcamp-in-hyderabad-online-live-training-with-real-world-projects
- Microsoft Power BI Training in Hyderabad: https://www.justacademy.co/course-detail/hyderabad/microsoft-power-bi-training-in-hyderabad
- Tableau Training in Hyderabad: https://www.justacademy.co/course-detail/hyderabad/tableau-training-in-hyderabad

Blogs:
- How to Switch Careers Into IT Without a Technical Background: https://www.justacademy.co/blog-detail/how-to-switch-careers-into-it-without-a-technical-background
- What Recruiters Expect From Freshers Entering the IT Industry: https://www.justacademy.co/blog-detail/what-recruiters-expect-from-freshers-entering-it-industry
- Online vs Classroom Training, Which Learning Method Works Better: https://www.justacademy.co/blog-detail/online-vs-classroom-training-which-learning-method-works-better
- Top IT Certifications That Help Freshers Get Jobs: https://www.justacademy.co/blog-detail/top-it-certifications-that-help-freshers-get-jobs

## Run it locally

Download or clone the repository and open `index.html` in any modern browser.

## Deploy on GitHub Pages

1. Push `index.html` and `README.md` to the root of your repository.
2. Open Settings, then Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. Your page goes live at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/` within a minute or two.

## Design notes

The look is a playful service desk: cream paper with a dotted grid, thick ink outlines, hard offset shadows and ticket style cards. The palette uses ink navy, mint teal, amber, coral and soft indigo. The layout is fully responsive, respects reduced motion settings and works without any external fonts or scripts.

## Customise

All colours are CSS variables at the top of the stylesheet. Quiz questions, results, the skill translator jobs, role cards and board tasks are plain arrays inside the script block at the bottom of `index.html`.

## License

Free to use and adapt for your own learning and content projects.
