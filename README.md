# Semantic HTML & Accessibility Project

This project focuses on building a well-structured and accessible HTML document using semantic elements and ARIA attributes.

##  Files

- `0-index.html` – Basic semantic HTML structure
- `1-index.html` – Meta tags and SEO improvements
- `2-index.html` – Blog post layout with semantic elements
- `3-index.html` – Accessible form using ARIA roles

---

## 0. Basic Semantic Structure

**File:** `0-index.html`

- Add `<!DOCTYPE html>`
- Create `<html>`, with empty `<head>` and `<body>`
- In `<body>`:
  - `<header>` with a `<nav>` containing 3 links
  - `<main>` with an `<article>`:
    - `<h1>` title
    - `<section>` with content
  - `<footer>` with copyright

---

## 1. SEO & Meta Tags

**File:** `1-index.html`

- Copy from `0-index.html`
- In `<head>`:
  - Add `<meta charset="utf-8">`
  - Add meta tags:
    - description
    - keywords
    - author
    - viewport
  - Add `<title>`: `Semantic Html Blog Post`

---

## 2. Blog Post Layout

**File:** `2-index.html`

- Copy from `1-index.html`
- In `<header>`:
  - Add `<h1>My Blog</h1>`
  - `<nav>` with `<ul>` and 3 `<li>`: Home, About, Contact
- In `<article>`:
  - `<header>` with:
    - `<h2>` title
    - `<p>` with `<time>`
  - Three `<section>` elements:
    1. **Introduction**: `<h3>` + `<p>`
    2. **Main Content**: `<h3>`, `<p>`, `<figure>` with `<img>` and `<figcaption>`
    3. **Conclusion**: `<h3>` + `<p>`
  - `<footer>` with author and publish date

---

## 3. Accessible Form

**File:** `3-index.html`

- Copy from `2-index.html`
- In `<main>`, add a new `<section>` with a `<form>`:
  - `action="#"`, `method="POST"`, `aria-labelledby="form-title"`, `role="form"`
  - Fields:
    - Name: `<label>` + `<input>` (with `aria-required="true"`)
    - Email: `<label>` + `<input>` (with `aria-required="true"`)
  - Submit `<button>` with `aria-label`
  - `<div>` with `aria-live="polite"` and `role="alert"`

---

## Notes

- Always close all tags.
- Use semantic tags for better accessibility and SEO.
- Use ARIA attributes to enhance screen reader support.

---



