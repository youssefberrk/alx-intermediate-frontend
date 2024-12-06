﻿# Semantic HTML: Best Practices for Accessibility and SEO

## Project Overview
This project is designed to help you practice structuring a simple HTML document using semantic elements. It focuses on creating well-structured HTML with an emphasis on improving accessibility and SEO.

## Objectives
- **Understand and apply semantic HTML elements** to structure a webpage.
- **Enhance accessibility** by using ARIA roles and attributes.
- **Improve SEO** through the proper use of meta tags and semantic elements.

## Tasks Breakdown

### Task 0: Creating a Structured HTML Document Using Semantic Elements
**Objective:** Practice structuring a simple HTML document using semantic elements.

**Instructions:**
1. Create an HTML document (`0-index.html`).
2. Inside the `html` tag, create the `head` and `body` tags (empty).
3. Inside the `body` tag:
   - Add a `header` with a `nav` that contains at least three links.
   - Add a `main` section with an `article`. Inside the `article`, include:
     - An `h1` tag for the title.
     - A `section` for the content.
   - Add a `footer` with copyright information `&copy;`.
4. Ensure the structure starts with a `DOCTYPE` declaration.

**File:** `0-index.html`

---

### Task 1: Enhancing HTML Document with Meta Tags and Title for SEO and Accessibility
**Objective:** To enhance the structure of the HTML document by adding meta tags for improved SEO, accessibility, and responsiveness, while properly defining the document’s character set and title.

**Instructions:**
1. Copy the content of `0-index.html` into `1-index.html`.
2. Inside the `head` tag, add the following:
   - `<meta charset="UTF-8">` for character encoding.
   - `<meta name="description" content="A blog post about semantic HTML and accessibility practices">`
   - `<meta name="keywords" content="HTML, Semantic, Accessibility, Blog, SEO">`
   - `<meta name="author" content="Your Name">`
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
   - `<title>Semantic HTML Blog Post</title>`

**File:** `1-index.html`

---

### Task 2: Creating a Blog Post Layout Using Semantic HTML Elements
**Objective:** Apply semantic elements to create a blog post layout.

**Instructions:**
1. Copy the content of `1-index.html` into `2-index.html`.
2. Inside the `header` tag:
   - Add an `h1` tag with the text "My Blog".
   - Add a `nav` tag with a `ul` and three `li` elements for Home, About, and Contact.
3. Inside the `article` tag in the `main` tag:
   - Add a `header` with an `h2` tag titled "Understanding Semantic HTML".
   - Add a `p` tag with the text: `Published on <time datetime="2024-09-10"> September 10</time>`.
   - Inside the `section` tag, add:
     - `h3` titled "Introduction".
     - `p` explaining Semantic HTML and its benefits.
   - Add another section with `h3` and `p` content regarding main content.
   - Add a `figure` tag with an image and a caption.
   - Add a third section for the conclusion with appropriate content.
4. Add a `footer` tag with "Written by" and "Published on" information.

**File:** `2-index.html`

---

### Task 3: Enhancing Form Accessibility with ARIA Roles and Attributes
**Objective:** Implement ARIA roles to improve accessibility in a form.

**Instructions:**
1. Copy the content of `2-index.html` into `3-index.html`.
2. Inside the `main` element, add a new `section` tag.
3. Inside the section, add a `form` tag with attributes:
   - `action="#"`, `method="POST"`, `aria-labelledby="form-title"`, `role="form"`.
4. Inside the `form`, add:
   - A `div` with a `label` for "name" and an `input` tag with `type="text"`, `id="name"`, `aria-required="true"`.
   - Another `div` with a `label` for "email" and an `input` tag similar to the "name" input.
   - A `div` with a `button` tag for form submission, with `aria-label="Submit the form"`.
   - A `div` with `aria-live="polite"` and `role="alert"`.

**File:** `3-index.html`

---

### Task 4: Manual Review
**Objective:** After completing the tasks, request a manual QA review to ensure your HTML document adheres to best practices for accessibility and SEO.

**Instructions:**
- Submit your work for a manual review in the specified repository.

**File:** `4-index.html`

---

## Additional Information
- **Repository:** [alx-intermediate-frontend](https://github.com/youssefberrk/alx-intermediate-frontend)
- **Directory:** `0x00-semantic_html`
- **Deadline:** The project must be completed by Dec 8, 2024, 10:00 PM.

---

## Git Commands to Use

To clone the repository and start working:

```bash
git clone https://github.com/youssefberrk/alx-intermediate-frontend.git
cd alx-intermediate-frontend/0x00-semantic_html

