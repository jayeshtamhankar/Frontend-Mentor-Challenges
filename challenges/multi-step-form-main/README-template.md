# Frontend Mentor - Multi-step form solution

This is a solution to the [Multi-step form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/multistep-form-YVAnSdqQBJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- Complete each step of the sequence
- Go back to a previous step to update their selections
- See a summary of their selections on the final step and confirm their order
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- Receive form validation messages if:
  - A field has been missed
  - The email address is not formatted correctly
  - A step is submitted, but no selection has been made

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**

  <div class="container">

    <!-- Sidebar start -->

    <div class="stages">
      <div class="stage one">
        <div class="icon">
          <span class="stage-icon">1</span>
        </div>
        <div class="body">
          <span class="stage-step">Step 1</span>
          <br>
          <span class="stage-title">Your info</span>
        </div>
      </div>
      <div class="stage two">
        <div class="icon">
          <span class="stage-icon">2</span>
        </div>
        <div class="body">
          <span class="stage-step">Step 2</span>
          <br>
          <span class="stage-title">Select plan</span>
        </div>
      </div>
      <div class="stage three">
        <div class="icon">
          <span class="stage-icon">3</span>
        </div>
        <div class="body">
          <span class="stage-step">Step 3</span>
          <br>
          <span class="stage-title">Add-ons</span>
        </div>
      </div>
      <div class="stage four">
        <div class="icon">
          <span class="stage-icon">4</span>
        </div>
        <div class="body">
          <span class="stage-step">Step 4</span>
          <br>
          <span class="stage-title">Summary</span>
        </div>
      </div>
    </div>

    <!-- Sidebar end -->

    <div class="input-form">
      <!-- Step 1 start -->
      <div class="stage-form one-active">
        <div class="stage-form-head">
          <h1>Personal info</h1>
          <p>Please provide your name, email address, and phone number.</p>
        </div>
        <div class="stage-form-body">
          <span>
            <label for="">Name</label>
            <input type="text" name="" id="" placeholder="e.g. Stephen King">
          </span>
          <span>
            <label for="">Email Address</label>
            <input type="text" name="" id="" placeholder="e.g. stephenking@lorem.com">
          </span>
          <span>
            <label for="">Phone Number</label>
            <input type="text" name="" id="" placeholder="e.g. +1 234 567 890">
          </span>
        </div>
      </div>
      <!-- Step 1 end -->

      <!-- Step 2 start -->
      <div class="stage-form two-">
        <div class="stage-form-head">
          <span>
            <h1>Select your plan</h1>
          </span>
          <span>
            <p>You have the option of monthly or yearly billing.</p>
          </span>
        </div>
        <div class="stage-form-body">
          <div class="card">
            <span>
              <img src="./assets/images/icon-arcade.svg" alt="">
            </span>
            <span>
              <h3>Arcade</h3>
              <p>$9/mo</p>
              <p>2 monts free</p>
            </span>
          </div>
          <div class="card">
            <span>
              <img src="./assets/images/icon-advanced.svg" alt="">
            </span>
            <span>
              <h3>Advanced</h3>
              <p>$12/mo</p>
              <p>2 monts free</p>
            </span>
          </div>
          <div class="card">
            <span>
              <img src="./assets/images/icon-pro.svg" alt="">
            </span>
            <span>
              <h3>Pro</h3>
              <p>$15/mo</p>
              <p>2 monts free</p>
            </span>
          </div>
          <div class="btn">
            <span>Monthly</span>
            <input type="checkbox">
            <span class="slider"></span>
            <span>Yearly</span>
          </div>
        </div>
      </div>
      <!-- Step 2 end -->

      <!-- Step 3 start -->
      <div class="stage-form three-">
        <div class="stage-form-head">
          <span>
            <h1>Pick add-ons</h1>
          </span>
          <span>
            <p>Add-ons help enhance your gaming experience.</p>
          </span>
        </div>
        <div class="stage-form-body">
          <div>
            <input type="checkbox">
            Online service
            Access to multiplayer games
            +$1/mo
          </div>
          <div>
            <input type="checkbox">
            Larger storage
            Extra 1TB of cloud save
            +$2/mo
          </div>
          <div>
            <input type="checkbox">
            Customizable Profile
            Custom theme on your profile
            +$2/mo
          </div>
        </div>
      </div>
      <!-- Step 3 end -->

      <!-- Step 4 start -->
      <div class="stage-form four-">
        <div class="stage-form-head">
          <span>
            <h1>Finishing up</h1>
          </span>
          <span>
            <p>Double-check everything looks OK before confirming.</p>
          </span>
        </div>
        <div class="stage-form-body">
          <h3>Arcade (yearly) </h3>
          <p>Change</p>

          <p>$9/mo</p>


          Online service $9/mo
          Larger storage $9/mo

          Total (per month) $9/mo
        </div>
      </div>
      <!-- Step 4 end -->

      <!-- Step 5 start -->
      <div class="stage-form five-">
        <img src="./assets/images/icon-thank-you.svg" alt="">

        Thank you!

        Thanks for confirming your subscription! We hope you have fun 
        using our platform. If you ever need support, please feel free 
        to email us at support@loremgaming.com.
      </div>
      <!-- Step 5 end -->
      
      <div class="btn-section">
        <div class="btn-back">Go Back</div>
        <div class="btn-next">Next Step</div>
        <div class="btn-confirm">Confirm</div>
      </div>
    </div>
  </div>
