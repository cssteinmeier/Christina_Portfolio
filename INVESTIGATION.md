# Investigation Report

## Issue Summary
Update the entire resume/portfolio to add three new creative projects to showcase Chrissy Steinmeier's work.

## Scope
- **In Scope:**
  - Add three new creative data science projects to the portfolio
  - Update the "Recent Work" section in index.html
  - Create compelling project descriptions with relevant skills
  - Ensure consistency with existing project format and style
  
- **Out of Scope:**
  - Modifying existing projects
  - Changing the overall layout or design
  - Adding actual project code repositories
  - Modifying contact information or bio sections

## Current State

### Existing Portfolio Structure
The portfolio is a single-page HTML website (index.html) based on the Strata template by HTML5 UP.

**Section "Recent Work" (id="two")** currently contains:
1. Movie Recommendation System (appears twice - likely a copy-paste error)
   - Skills: Neural Networks, Collaborative Filtering, Supervised Learning, Data Processing, Exploratory Data Analysis
   - Has GitHub and Medium links
   
2. Four placeholder projects with Lorem ipsum text:
   - "Ultricies lacinia interdum"
   - "Quam neque phasellus"
   - "Nunc enim commodo aliquet"
   - "Risus ornare lacinia"

### Current Project Format
Each project article follows this structure:
```html
<article class="col-6 col-12-xsmall">
    <a href="[link]" class="image fit thumb"><img src="images/[image]" alt="" /></a>
    <h3 style="font-size: 1em; margin: 0 0 0.5em 0;">[Project Name]</h3>
    <p style="font-size: 0.8em; line-height: 1.5em; margin: 0;">Skills: [skill list]</p>
    <i>
        <a href="[github]" class="icon brands fa-github" style="color:darkgrey;"></a>
        <a href="[medium]" class="icon brands fa-medium" style="color:darkgrey;"></a>
    </i>
</article>
```

## Constraints & Risks

### Constraints
1. Must maintain the existing HTML structure and styling
2. Should align with Chrissy's background as a Data Scientist focused on sustainability and environmental justice
3. Projects should be believable and relevant to her work experience at Primo Water and UC Berkeley research
4. Need to use placeholder images from the existing template

### Risks
1. Placeholder images may not perfectly match project themes
2. Made-up GitHub/Medium links will be non-functional (should use # or remove)
3. Skills should be realistic and align with her actual expertise

## Affected Files/Modules

### Primary File
- `/home/runner/work/Christina_Portfolio/Christina_Portfolio/index.html`
  - Section: `<section id="two">` (lines 42-81)
  - Need to replace placeholder projects with three new creative projects

### Supporting Files
- Images in `/home/runner/work/Christina_Portfolio/Christina_Portfolio/images/` directory
- Existing images can be reused: thumbs/01.jpg through 06.jpg, fulls/01.jpg through 06.jpg

## Evidence & Context

### Chrissy's Background
- Current: Retention Analyst at Primo Water
- Education: B.A. in Data Science, Minor in Conservation Resource Studies (UC Berkeley)
- Research: The Potts Lab Group, EcoDataLab
- Focus: Sustainability, environmental justice, customer experience
- Key skills: Machine learning, modeling, statistical analysis, data-driven solutions

### Existing Project Example
The Movie Recommendation System demonstrates the expected quality level:
- Technical skills clearly listed
- Professional presentation
- Links to GitHub and Medium
- Relevant to data science field

## Open Questions
1. Should we keep the duplicate Movie Recommendation System entry or remove one?
2. Should project links point to actual repos or use placeholder "#"?
3. What specific format should the documentor updates take?

## Recommendations
1. Create three distinct projects that align with Chrissy's background:
   - One environmental/sustainability focused project
   - One customer analytics/business intelligence project
   - One machine learning/data science project
2. Replace the four Lorem ipsum placeholder projects
3. Keep the Movie Recommendation System (remove duplicate)
4. Use existing placeholder images from the template
5. Use "#" for project links unless specific repos are provided
