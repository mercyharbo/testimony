# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

![image](https://user-images.githubusercontent.com/64808015/111819463-a6f41d00-88e0-11eb-954c-c641a956c8b0.png)

### Links

- Solution URL: https://github.com/mercyharbo/testimony
- Live Site URL: http://mercyharbo.github.io/testimony/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I expand more on CSS Grid Layout by working on this challenge which I am hoping to learn more in the future, also helped me gain more confidence with CSS Grid and flexbox.

To see how you can add code snippets, see below:

```html

<div class="textimonies-grid daniel ">
      <div class="details">
        <img src="./images/image-daniel.jpg" alt="Daniel">
        <h4> Daniel Clifford <br> <span>Verified Graduate</span></h4>
      </div>
      <h3> I received a job offer mid-course, and the subjects I learned were current, if not more so,
        in the company I joined. I honestly feel I got every penny’s worth. </h3>
      <p>
        “ I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a
        transition and have heard some people who had an amazing experience here. I signed up
        for the free intro course and found it incredibly fun! I enrolled shortly thereafter.
        The next 12 weeks was the best - and most grueling - time of my life. Since completing
        the course, I’ve successfully switched careers, working as a Software Engineer at a VR startup. ”

      </p>
    </div>

```css

.container {
  display: grid;
  grid-template-columns: repeat(4, 2fr);
  grid-template-areas:
    ' daniel daniel jonat kira'
    ' jean pat pat kira';
  column-gap: 5%;
  padding: 2%;
}

### Continued development

I want to continue to learn more of CSS Grid and flexbox in future to boost my confidence and improve on my working speed as this took me less than I expected.

## Author

- Frontend Mentor - [@mercyharbo](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@codewithmercy](https://www.twitter.com/codewithmercy)
