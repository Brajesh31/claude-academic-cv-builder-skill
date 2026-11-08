# Academic CV Builder Skill

A structured skill for creating and revising academic curriculum vitae for research, teaching, faculty, postdoctoral, and related academic opportunities. It helps organize a complete scholarly record while keeping every claim accurate, traceable, and appropriate to the target position.

## What This Skill Helps With

- Select a section order that fits the target role and discipline.
- Present education, academic appointments, and research experience.
- Organize publications by type and status.
- Format conference talks, posters, and invited presentations.
- Document grants, fellowships, awards, and funding roles.
- Present teaching, course development, mentoring, and supervision.
- Record academic service, memberships, and honors.
- Identify missing information and inconsistent dates.
- Review the final CV against application instructions.

## When to Use It

Use this skill when preparing or updating an academic CV for faculty, postdoctoral, research scientist, lecturer, doctoral, or similar academic opportunities. It is also useful when converting an academic record into a consistent CV.

An academic CV is not simply a longer industry resume. It records scholarly activity in a way that allows a committee to understand the applicant's research, teaching, service, and trajectory.

## Installation

~~~bash
git clone https://github.com/Brajesh31/claude-academic-cv-builder-skill.git ~/.claude/skills/academic-cv-builder
~~~

## Usage

Invoke:

~~~text
/academic-cv-builder
~~~

Supply the target position, application requirements, academic discipline, career stage, and the applicant's verified record. Do not fabricate degrees, publications, funding, appointments, awards, teaching evaluations, or collaborators.

## Recommended Academic CV Structure

1. Contact information and professional links.
2. Education and thesis or dissertation details.
3. Academic appointments and research experience.
4. Publications, grouped by type and status.
5. Presentations, talks, and posters.
6. Grants, fellowships, and funding.
7. Teaching experience and course development.
8. Mentoring and supervision.
9. Academic, professional, and institutional service.
10. Professional memberships.
11. Honors and awards.
12. References, where requested or customary.

The correct order depends on the role. Research-intensive positions often prioritize publications, grants, and research experience. Teaching-focused positions may put teaching and course development earlier. Administrative roles may emphasize leadership and service.

## Publication Handling

Preserve author order and distinguish peer-reviewed publications, books, chapters, proceedings, technical reports, preprints, accepted work, work under review, and work in preparation. Include DOI information when verified. Do not imply submitted or in-progress work is already published.

Use one citation style consistently within a category. Follow the target discipline's norms and institution instructions where explicit.

## Role-Specific Emphasis

| Target role | Evidence to prioritize |
|---|---|
| Tenure-track faculty | Research trajectory, publications, independent funding, teaching, mentoring |
| Postdoctoral role | Doctoral/postdoctoral research, publications, methods, collaboration, future potential |
| Lecturer or teaching faculty | Teaching record, course design, pedagogy, mentoring, teaching recognition |
| Research scientist | Research outputs, technical methods, grants, collaboration, relevant experience |

## Included Resources

- [Academic CV intake template](resources/academic-cv-intake-template.md)
- [Publication record template](resources/publication-record-template.md)
- [Final review checklist](resources/final-review-checklist.md)

## Quality Checklist

- All dates, titles, affiliations, and role descriptions are accurate.
- Education and appointments are consistently ordered.
- Publication status and author order are preserved.
- Grants distinguish PI, Co-PI, Co-I, and other roles.
- Teaching and mentoring responsibilities are clear.
- Awards and memberships are verifiable.
- Section order reflects the target role.
- Formatting is consistent and readable.
- The final version follows application instructions.
- No unsupported claims or inflated responsibilities are included.

## Limitations

Academic CV conventions vary by discipline, country, institution, and career stage. Use the target institution's instructions as the final authority. Page-length ranges are rough context, not mandatory limits.

## Repository Structure

~~~text
claude-academic-cv-builder-skill/
├── SKILL.md
├── README.md
├── LICENSE
└── resources/
    ├── academic-cv-intake-template.md
    ├── publication-record-template.md
    └── final-review-checklist.md
~~~

## License

Released under the MIT License. Copyright (c) 2026 Brajesh Kumar. See the root `LICENSE` file for the complete terms.
