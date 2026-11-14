# Part 3 — Mathematics PDF Footprinting

## Objective

Find and document ten public mathematics PDF resources, and explain what search results reveal during passive footprinting.

## Methodology

The assignment's Google dork was used as a model for relevant public-resource searches. The ten entries below include an instructor-provided directory example, university lecture notes, and open textbook publishers. These search queries are examples; they are not asserted to be official GHDB entries or individually verified live searches. Public educational material is not inherently a security vulnerability.

## Footprinting findings

| No. | PDF resource / listing | Relevant Google dork | Username / Password (if any) | Observation |
|---|---|---|---|---|
| 1 | [Skyline University mathematics directory](https://www.skylineuniversity.ac.ae/pdf/math/) | `intitle:index.of "parent directory" mathematics pdf` | — | Instructor's directory-listing example |
| 2 | [UW–Madison free lecture notes](https://people.math.wisc.edu/~angenent/Free-Lecture-Notes/) | `site:wisc.edu mathematics "PDF" "calculus"` | None indicated | Public lecture-note collection |
| 3 | [UW–Madison Elementary Calculus](https://people.math.wisc.edu/~hkeisler/calc.html) | `site:wisc.edu "Elementary Calculus" pdf` | None indicated | Open mathematics textbook page |
| 4 | [American Institute of Mathematics open textbooks](https://textbooks.aimath.org/textbooks/approved-textbooks/) | `site:aimath.org "open textbooks" pdf` | None indicated | Curated open-textbook collection |
| 5 | [OpenStax College Algebra 2e](https://openstax.org/books/college-algebra-2e/pages/preface) | `site:openstax.org "College Algebra 2e" pdf` | None indicated | Free textbook page with PDF option |
| 6 | [OpenStax Precalculus 2e](https://openstax.org/books/precalculus-2e/pages/preface) | `site:openstax.org "Precalculus 2e" pdf` | None indicated | Free textbook page with PDF option |
| 7 | [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e/pages/1-introduction) | `site:openstax.org "Introductory Statistics 2e" pdf` | None indicated | Free textbook page with PDF option |
| 8 | [OpenStax Calculus Volume 1](https://openstax.org/subjects/math) | `site:openstax.org "Calculus Volume 1" pdf` | None indicated | Mathematics catalog, book link not individually checked |
| 9 | [OpenStax Algebra and Trigonometry 2e](https://openstax.org/subjects/math) | `site:openstax.org "Algebra and Trigonometry 2e" pdf` | None indicated | Mathematics catalog, book link not individually checked |
| 10 | [OpenStax mathematics textbook collection](https://openstax.org/subjects/math) | `site:openstax.org/subjects/math textbooks pdf` | None indicated | General catalog; overlaps with entries 5–9 |

## Screenshot evidence and live links

The repository already includes an [example GHDB screenshot](evidence/ghdb-entry.jpg) and a [webcam-interface screenshot](evidence/webcam-interface.jpg) from the earlier camera exercise. They do **not** verify these ten mathematics PDF resources. The clickable links in the findings table open the referenced resource pages; no fresh screenshots of the ten PDF pages were supplied or captured for this section. A static screenshot itself is not a clickable link, so the URLs remain separately clickable in the table.

## Reference

[Google Hacking Database (GHDB)](https://www.exploit-db.com/google-hacking-database)
