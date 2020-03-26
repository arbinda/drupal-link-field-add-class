# drupal-link-field-add-class
Display different classes based on text on url. e.g. if it has doc or docx add "document" class, if it has youtube.com add "youtube" class

- Make of copy of filed.html.twig from your base theme, In my case I used the field.html.twig from bootstrap 3 theme.
- Rename fiield.html.twig to field--node--field-fieldname.html.twig so that anywhere that field is used this twig template is   used.
