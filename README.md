# Math and CS Department at Mount St. Mary's University
### Emmitsburg, MD

A repository for departmental information that students can contribute to. Pages are researched, created, and maintained by students in Dr. Lamprecht's Software Development class, beginning in Spring 2025.

## Pages Included

* [Coad Hubs](#coad-hubs)
* [Women in Computing Group](#women-in-computing)
* [Mount Programming Club](#mount-programming-club)
* [Cyber Defense Club](#cyber-defense-club-readme) 
* [Students of Color in STEM club](#students-of-color-in-stem)
* [Data Science Club](#data-science-club-page)
* [Women in STEM Club](#women-in-stem)
* [SmallTalks](#smalltalks)
* [Invited Talks](#invited-talks-page))
* [Faculty](#faculty)
* [Computer Science major](#computer-science-major) 
* [Cybersecurity major](#cybersecurity-major) 
* [Data Science major](#data-major)
* [Mathematics major](#mathematics-major)
* [Double majors](#data-major)
* [Minors](#minors)
* [Internships](#internships) 
* [On-Campus Jobs](#oncampus-jobs)
* [Graduate Schools](#graduate-schools)
* [What’s Nu? newsletter](#whats-nu?)

## Directions for Updates

Each of the following should be completed through seperate pull requests.

### README.md Updates

For each page, use a triple pound sign to create a subsection with the title of the page being added. Then use standard paragraphs and lists as apporpriate to document where page information was gathered from (include formal citations), how/why information was included or excluded from the page, and details on the formatting and styling choices for the display of information. Creators/editors of the page and the documentaion should be listed at the end of the write-up using the @ character with GitHub usernames.

Once your subsection is written, edit the appropriate item in the list of included pages to be an anchor link to the new subsection. Note that subsection titles must be unique, simple, and descriptive.

Other styling options for the READEME documentation can be found here: [GitHub Docs: Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Individual Pages Updates

Each of the pages listed above should be researched via the faculty and students of the Math and CS Department, or from the Mount's [Course Catalog](https://catalog.msmary.edu/index.php). The page must use the CSS files included in the repository so that the style matches the welcome.html page. Filenames must follow camel notation.

### Welcome Page Updates

When new pages are added to the repository, the welcome.html page must be updated with a link to the new file.

## Page Documentations

### Welcome Page

The index.html page is the landing page for this departmental website. Information was gathered from the Mount's Course Catalog, the [School of Science, Mathematics & Technology](https://msmary.edu/academics/schools-divisions/school-of-science-mathematics-and-technology/index.html) webpage, and department faculty discussions. Also referenced is the [Visit Emmitsburg](https://visitemmitsburg.com) site.


### Data Science Club

The Data Science Club page provides an overview of the club at Mount St. Mary's University, offering students opportunities to enhance their data science skills, participate in competitions, and prepare for careers in the field.

 **Information Sources**
- Information was primarily gathered from the Mount St. Mary's University website, specifically the [Data Science Major page](https://catalog.msmary.edu/preview_program.php?catoid=18&poid=1680&returnto=775) and the [Course Catalog](https://catalog.msmary.edu/index.php).
- Faculty details were confirmed through direct communication with Dr. Jonathan McCurdy, Dr. Daniel Salinas Duron, and Dr. Nadun Kulasekera Mudiyanselage.

- Additional resources and club activities (e.g., Kaggle competitions) were based on common practices in data science clubs and verified with student and faculty overview.

**Data Science HTML Page Content**
- **Header:** Includes the club name, university name, and logo for branding consistency.
- **Navigation:** Links to the home page and external Mount St. Mary's resources for easy access.
- **Main Content:**
  - **Purpose:** illustrates the club's focus on key projects, skill-building, and career preparation through data science.
  - **About Section:** Lists key activities like Kaggle competitions, mathematical skill development, and interview preparation. Excluded overly technical details to keep it accessible to new students.
  - **Activities:** Details a shift from Kaggle competitions to interview preparation and small project development, enhancing problem-solving and technical skills.
  - **Faculty Leaders:** Provides names, titles, and contact emails for the club advisors. Note: The HTML contains a typo ("Facuality" instead of "Faculty") and an email error (Dr. Salinas Duron’s email is listed as Dr. McCurdy’s).
  - **Participation:** Describes who typically joins (primarily Data Science majors/minors, open to Math majors with experience) and how to get involved.
  - **Join Now:** Explains how to join via email to faculty or by attending meetings, with invitations sent to Data Science students.
  - **Meeting Times:** Specifies Wednesday meetings from 5:00 PM to 6:00 PM, with email notifications sent as needed.
  - **Resources:** Organized into a three-column layout (Data, Python, R) with links to external tools, chosen for their relevance to data science education.
  - **Additional Considerations:** Recommends foundational knowledge (e.g., Data 200) and programming experience for full engagement.
- **Footer:** Includes a copyright notice for 2025. 

**Design Choices**
- The page follows the department’s official CSS to maintain a consistent style.
- The page uses the repository’s `style.css` for consistency with the welcome page, ensuring uniform fonts, colors, and layout overall clubs web page designs.
- A tri-column layout was chosen for the "Faculty Leaders" and "Resources" sections to optimize readability and space usage as part of general campus web page layout.
- Horizontal rules (`<hr>`) and captions emphasize section breaks and key messages, inspired by the welcome page’s structure.
- External links open in new tabs (`target="_blank"`) to keep users on the site while exploring resources.
- The sidebar navigation (`rightsideNav`) is collapsible via `sidebar.js`, improving mobile responsiveness and enhancing user experience.
- A floating "Top" button (`id="topBtn"`) linked to `floatingTopButton.js` improves navigation.
- Meta tags provide SEO details (authors, description, keywords) in the HTML head.

**Club Purpose:**
- Encourages learning and collaboration in data science through hands-on projects.
- Prepares students for future employment with a strong resume.
- Focuses on projects and concepts that align with job requirements and necessities.

**Web Page Section**

**Leadership:** 
- Lists faculty advisors (Dr. McCurdy, Dr. Salinas Duron, Dr. Nadun). Note: Student leaders are not yet included in the HTML.

**How to Join:**
- Instructions on how new students can participate via email or attending meetings.

**Resources:** 
- Links to useful materials like datasets (e.g., Kaggle), Python tools, and R tools.
  


**References**
- Mount St. Mary's University [Data Science Major page](https://catalog.msmary.edu/preview_program.php?catoid=18&poid=1680&returnto=775)
- Mount St. Mary's University [Course Catalog](https://catalog.msmary.edu/index.php)
- Verified information through direct communication with Dr. Jonathan McCurdy, Dr. Daniel Salinas Duron, and Dr. Nadun Kulasekera Mudiyanselage.


_**Editors**_
<!-- Creating a table  NA-->
| Contributor | Role |
|-------------|------|
| [@EthanLane](https://github.com/EthanLane) | Web Page Development & Initial Content |
| [@NabilAlimi](https://github.com/NabilAlimi) | Content Research & Formatting |


### CSS Files

Version 1 of the website includes one stylesheet. Styles are defined and used on the welcome page for left and right side menus, header, main content area, citation caption, and scrolling top button. Other styles are defined for potential use on subpages for blog entries, calendar displays, two- and three-column sections, drop down menus, and special button menu items.

## Usage

Students in the Software Development class are required to participate in this project as part of their classwork. Other GitHub users not in the class may also contribute, but may be rejected. See the [GitHub Docs: Contributing to a project](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) for more guidance on contributing to a project on GitHub.
