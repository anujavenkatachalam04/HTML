# About
This repository contains the .html and .css files to create a basic student website containing 5 webpages - Home, Academics, Personal, Resume and Contact.

This was created for a weekly assignment for the course - Application Development - I as part of the IIT Madras BSc Degree Programme in Programming and Data Science.

The HTML & CSS specifications were provided as part of the assignment (see Instructions below).

# Instructions

This assignment requires the creation of a five-page HTML-only website using specific instructions. The submission must follow HTML5 standards and use only allowed tags.

Each page must have:

- **Header** (`div`): Contains links to the other four pages.
- **Main Section** (`div`): Page-specific content.
- **Footer** (`div`): Includes your name, batch, ©, and year.

---

HTML Page Details

| Page     | File Name       | Header Links                     | Footer                       |
|----------|------------------|----------------------------------|-------------------------------|
| Home     | `index.html`     | Academics, Personal, Contact, Resume | Name, Batch, Copyright, Year       |
| Academics| `academics.html` | Home, Personal, Contact, Resume     | Name, Batch, Copyright, Year       |
| Personal | `personal.html`  | Home, Academics, Contact, Resume   | Name, Batch, Copyright, Year       |
| Contact  | `contact.html`   | Home, Academics, Personal, Resume | Name, Batch, Copyright, Year       |
| Resume   | `resume.html`    | Home, Academics, Personal, Contact| Name, Batch, Copyright, Year       |

---

Allowed Tag Usage Per Page

| Page     | div | h1 | h5 | a  | p | table | tr | th | td | br | img | address |
|----------|-----|----|----|----|---|--------|----|----|----|----|-----|---------|
| Home     | 3   | 1  | 1  | 4  | 3 | 0      | 0  | 0  | 0  | 0  | 0   | 0       |
| Academics| 3   | 1  | 1  | 4  | 0 | 1      | 7  | 2  | 12 | 0  | 0   | 0       |
| Personal | 3   | 1  | 1  | 5  | 0 | 0      | 0  | 0  | 0  | 2  | 2   | 0       |
| Contact  | 3   | 1  | 1  | 4  | 0 | 0      | 0  | 0  | 0  | 5  | 0   | 1       |
| Resume   | 3   | 1  | 1  | 5  | 0 | 0      | 0  | 0  | 0  | 0  | 0   | 0       |

---

Page-Specific Requirements

### 1. **Home Page (`index.html`)**
- Heading: `Student data`
- Content: Name, roll number, and self-introduction (max 50 words)
- Use 3 paragraphs

### 2. **Academics Page (`academics.html`)**
- Heading: `Mark sheet`
- Display a table with marks (keep structure and count of headers/rows same as example)

### 3. **Personal Page (`personal.html`)**
- Show two images (`250x250` pixels)
- External link: [IITM Online Degree](http://www.onlinedegree.iitm.ac.in)
- Use `<br>` for formatting

### 4. **Contact Page (`contact.html`)**
- Heading: `Contact Us`
- Include address and email using `<address>` tag
- Use `<br>` for formatting

### 5. **Resume Page (`resume.html`)**
- Provide a link: `"download resume"` which opens your CV

