# Amicus Law Institute Website

[Visit Amicus](https://amicus.com.np/)

A responsive informational website for Amicus Law Institute in Nepal, built
with HTML, CSS and JavaScript. It presents courses, admissions, faculty and
contact information, with client-side interactions and enquiry forms.

## Pages and implementation

| File | Page or responsibility |
| --- | --- |
| `index.html` | Institute introduction and homepage sections |
| `about.html` | Background and institute information |
| `courses.html` | Course information |
| `admissions.html` | Admissions details and application form |
| `faculty.html` | Faculty presentation |
| `contact.html` | Contact information and enquiry form |
| `styles.css`, `script.js` | Layout, navigation, carousels and form interactions |

## Preview locally

Clone the repository and serve its root as static files. For example, with Python 3:

```sh
python -m http.server 8000
```

Open `http://localhost:8000`. There is no framework build or database migration.
The `CNAME` file records the custom-domain configuration used for static hosting.

## Forms and content

The form handlers use EmailJS. Confirm its service/template configuration and
test delivery with authorized test addresses before accepting enquiries. A
static preview alone does not verify email delivery. Review institution-approved
copy, images and contact details before deployment; some image filenames retain
their original placeholder names.

## Review checklist

Check page navigation, mobile layout, keyboard access, form errors and successful
delivery on the intended hosting domain. This repository does not contain an
automated browser test suite or a student-management backend.

Website work by Sudip Parajuli / Techwired Solutions.
