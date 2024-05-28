# PORTFOLIO WITH STATIC PAGE

Simple static page for portfolio.

### CONTACT SECTION

The contact section of the website incorporates a form that utilizes the free service of Formspree to avoid for configuring any backend. To achieve this, simply create an account on Formspree and set up a form. Formspree will generate a specific endpoint for the form,
which should be substituted for the action attribute within the <form> element in the corresponding HTML file:

```html
<form method="post" action="https://formspree.io/your-endpoint">
  <!-- Define the form fields here -->
</form>
```

Make sure to replace https://formspree.io/your-endpoint with the specific endpoint generated by Formspree for your form. This ensures that the form data is correctly sent to the desired destination. The destination email address is defined within the Formspree service.
