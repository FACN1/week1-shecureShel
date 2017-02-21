# week1-shecureShel

##WHY
We want to build a single-page portfolio site for team ShecureShel, to promote our services as full stack web developers.

We want to offer a way of describing our services, and then make it easy for customers to contact us if they want to hire us.

We want the site to be accessible to the visually impaired, blind users, users with old browsers, or with javascript disabled, as well as users viewing the site from any sized device.

##WHAT
#### - Navigation
  - About | Team | contact

Note: nav bar needs to be responsive for mobile, and function without javascript (as well as WITH if we get the time).

- We can use HREF links to link to the various sections of the page.

- Nav bar should use the <nav> tag for its semantic value, for screen readers.

#### About Section:
  - Header displaying our company name "ShecureShel"
  - Profile picture / logo (shell petrol logo?)
  - Strapline / slogan / one-line description.

#### Team Section
  - 4 x
    - Profile pictures.
    - Social network links (linked in, github & codewars)
    - Name.
    - Web development job description.

Design note: on full width display profiles from left - to - right.
              - as the screen shrinks, pile profiles ontop of each other to display from top - to - bottom.

#### Contact Section
  - use html form elements to create a contact form.
    form fields:
        - name  
        - email
        - message

    - submit button

Responsive design of contact page.
  - For full width viewports, lay the 'name', 'email' and 'submit' sections to the left, and then the message field to the right.
  - As the viewport narrows down. Name and Email fields and submit button should move above message field.

## Stretch goal:
  - Without using javascript - try to rearrange narrow viewport contact form so that submit buttons moves below message field, and name and email fields move above message field, for logical ordering.

#HOW
  - Semantic html for improved accessibility and search engine optimization.
  - media queries, used with a mobile-first approach to create responsve design

## Stretch goal
  - Possibly consider using noscript tag for browsers with JS switched off
