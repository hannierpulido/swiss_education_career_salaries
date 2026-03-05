# Swiss Education & Career Salaries

Two interactive visualizations of the Swiss school system and the careers it leads to.

---

## Why this project?

My daughter came home one evening with a simple question: *"Papa, what jobs can I do depending on which school I go to?"*

We are immigrants in Switzerland, and like many families who didn't grow up here, the Swiss education system is still a mistery to us. In sixth grade — around age 12 — children face one of the earliest and most consequential academic forks of their lives. They can sit the *Aufnahmeprüfung* (admission exam) for the Gymnasium, the academic track that leads directly to university. Many children opt not to take it. Those who do and pass enter the Langgymnasium; those who don't follow one of the Sekundarschule tracks — A, B, or C — each opening different doors to apprenticeships, vocational schools, and applied universities.

I didn't have a good answer for her. So I built one.

The **phylogenetic tree** maps each school track to the careers it typically leads to, drawn in the style of an evolutionary tree — branches diverging from a common root, each path lengthening with time and specialisation. It is an oversimplification, of course. Switzerland's system is very permeable: a motivated student on the Sek-B track can upgrade to an EFZ, pass the Berufsmatura, and reach a Fachhochschule. The Passerelle exam even allows FH graduates to enter university. Every branch has bridges. But as a first map for a curious ten-year-old, it does its job.

The **bubble chart** adds the economic dimension. The link between education and earnings is one of the most robustly replicated findings in economics. Oreopoulos & Petronijevic (2013) summarise decades of evidence showing that each additional year of schooling raises lifetime earnings by 8–13%. The OECD's *Education at a Glance 2023* reports that tertiary-educated adults in Switzerland earn roughly 60% more than those with only upper-secondary qualifications. Card (1999) and the broader Mincer earnings literature establish that this premium is causal, not merely correlational — education genuinely opens higher-paying doors, it does not simply sort people who would have earned more anyway. Each bubble represents a profession, sized by workforce, coloured by track, and positioned by median gross annual salary (FSO / jobs.ch 2024 data).

Together, the two charts try to answer my daughter's question honestly: here are your paths, and here is roughly where each one tends to lead — both in terms of what you will do and what you will earn.

---

## Visualizations

| Chart | Description |
|-------|-------------|
| [`tree.html`](tree.html) | Phylogenetic career tree · A3 landscape · print-ready |
| [`bubbles.html`](bubbles.html) | Salary bubble chart · ~80 professions · A3 landscape |

## Data sources

- Salaries: Swiss Federal Statistical Office (FSO) 2024, jobs.ch, Glassdoor, SalaryExpert
- Workforce estimates: FSO Labour Force Survey 2023
- Card, D. (1999). *The causal effect of education on earnings.* Handbook of Labor Economics, 3, 1801–1863.
- Oreopoulos, P. & Petronijevic, U. (2013). *Making college worth it.* Journal of Economic Perspectives, 27(1), 125–152.
- OECD (2023). *Education at a Glance 2023.* OECD Publishing, Paris.

