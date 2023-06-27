# Project Bonsai

Project bonsai is a website to help people to learn more about Bonsai.

## Features

On the index page I used images and text going around the image, and then on types was used cards with animations to create some movement, furthermore on form, it is the area to subscribe and get more information. Footer we have links for our main social media.

### Screen Initial plan

Bonsai page

![Bonsai Page large screen](https://jrakau.github.io/project_bonsai/docs/testing/index.png)

![Bonsai Page small screen](https://jrakau.github.io/project_bonsai/docs/testing/index_m.png)

Types page

![Types page small screen](https://jrakau.github.io/project_bonsai/docs/testing/types.png)

![Types page small screen](https://jrakau.github.io/project_bonsai/docs/testing/types_m.png)

Contact Us

![Contact Us page large screen](https://jrakau.github.io/project_bonsai/docs/testing/contact.png)

![Contact Us page small screen](https://jrakau.github.io/project_bonsai/docs/testing/contact_m.png)

## Technologies

- HTML
  - The structure of the Website was developed using HTML as the main language.
- CSS
  - The Website was styled using custom CSS in an external file.
- Visual Studio Code
  - The website was developed using Visual Studio Code IDE
- GitHub
  - Source code is hosted on GitHub and delpoyed using Git Pages.
- Git
  - Used to commit and push code during the development opf the Website
- Font Awesome
  - Icons obtained from <https://fontawesome.com/> were used as the Social media links in the footer section.
- Tinyjpg
  - <https://tinyjpg.com/> was used to reduce the size of the images used throughout the website
- Favicon.io
  - favicon files were created at <https://favicon.io/favicon-converter/>
- balsamiq
  - wireframes were created using balsamiq from <https://balsamiq.com/wireframes/desktop/#>

## Testing

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome, Edge, Firefox, Opera, and Safari browsers.

Steps to test:

1. Open browser and navigate to [Bonsai Project](https://jrakau.github.io/project_bonsai/index.html)
2. Click on Bonsai
3. Load page

Expected:

Load a xxx.html page properly

Actual:

Load a xxx.html page properly without any issues

### Accessibility

Developer tools from Chrome was used throughout development and for final testing of the deployed website to check for any aid accessibility testing. Using diferents screen sizes and device simulator

### Pages Testing

![Home screen](https://jrakau.github.io/project_bonsai/docs/testing/index_screen.png)

![Types screen](https://jrakau.github.io/project_bonsai/docs/testing/type_screen.png)

![Types Card open screen](https://jrakau.github.io/project_bonsai/docs/testing/type_screen2.png)

![Contact Us screen](https://jrakau.github.io/project_bonsai/docs/testing/form_screen.png)

### Functional Testing

-**Navigation Links**

Testing was performed to ensure all navigation links on the respective pages, navigated to the correct pages as per design. This was done by clicking on the navigation links on each page.

| Navigation Link | Page to Load       |
| --------------- | ------------------ |
| Bonsai          | index.html         |
| Types           | types_bonsai.html  |
| Contact Us      | comtatct_form.html |

Links on all pages navigated to the correct pages as exptected.

-**Index Testing**

The form on the home page was tested to ensure it functioned as expected when correct data was input and when incorrect data was input. The following test scenarios were covered:

Steps to test:

1. Open browser and navigate to [Bonsai Project](https://jrakau.github.io/project_bonsai/index.html)
2. Click on Bonsai
3. Load page

Expected:

Load a index.html page, with a bonsai image and text around

Actual:

Load a index.html page without issues, with a bonsai image and text around

-**Types Testing**

The form on the home page was tested to ensure it functioned as expected when correct data was input and when incorrect data was input. The following test scenarios were covered:

Steps to test:

1. Open browser and navigate to [Bonsai Project](https://jrakau.github.io/project_bonsai/types_bonsai.html)
2. Or Click on types at the Navegation Menu
3. Load page
4. Mouse over the image
5. The animation should go bottom up smootie and show more information
6. Clincking on on the link More, should bring you to form for subscription

Expected:

Load a types_bonsai.html page, with a tree bonsai image, a short description and a link for More (For form subscription)

Actual:

Load a types_bonsai.html page without issues, with a tree bonsai image, a short description and a link for More (For form subscription)

-**Form Testing**

The form on the home page was tested to ensure it functioned as expected when correct data was input and when incorrect data was input. The following test scenarios were covered:

-_Scenario One - Blank Inputs_

Steps to test:

1. Open browser and navigate to [Bonsai Project](https://jrakau.github.io/project_bonsai/contact_form.html)
2. Or Click on Contact Us
3. Load page with form
4. Press Subscribe without fill the fields

Expected:

Load a contact_form.html page, with a form, and then you press subscribe without filling the field should return a message for each field

Actual:

Load a contact_form.html page with a form without issues, and then was pressed subscribe button without filling the field, Form returned the message for each field was missing

-_Scenario Two - Correct Inputs_

Steps to test:

1. Open browser and navigate to [Bonsai Project](https://jrakau.github.io/project_bonsai/contact_form.html)
2. Or Click on Contact Us
3. Load page with form
4. Press Subscribe filling the fields properly

Expected:

Load a contact_form.html page, with a form, and then you press subscribe filling the field corretly should return thank you

Actual:

Load a contact_form.html page with a form without issues, and then was pressed subscribe button filling the fields properly, and then was returned the message thank you

-**Footer Social Media Icons / Links**

Testing was performed on the Font Awesome Social Media icons in the footer to ensure that each one opened in a new tab and that each one had a hover affect of the orange branding color.

Each item opened a new tab when clicked as expected and correct hover color was present.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org)

![Index HTML Validator Results](https://jrakau.github.io/project_bonsaihttps://jrakau.github.io/project_bonsai/docs/testing/nu_html_checker_index.png)

![Types_bonsai HTML Validator Results](https://jrakau.github.io/project_bonsai/docs/testing/nu_html_checker_types.png)

![Contact_form HTML Validator Results](https://jrakau.github.io/project_bonsai/docs/testing/nu_html_checker_contact.png)

![Thank_you HTML Validator Results](https://jrakau.github.io/project_bonsai/docs/testing/nu_html_checker_thank_you.png)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org)

![CSS Validator Results](https://jrakau.github.io/project_bonsai/docs/testing/jigsaw_validator.png)

### Unfixed Bugs

Responsiveness of the website was tested on Safari MacOs and IOS, Chrome, and worked perfect in diferents resolutions.

## Deployment

### Version Control

The site was created using the Codeanywhere editor and pushed to github to the remote repository ‘project_bonsai’.

The following git commands were used throughout development to push code to the remote repo:

`git add <file>` - This command was used to add the file(s) to the staging area before they are committed.

`git commit -m “commit message”` - This command was used to commit changes to the local repository queue ready for the final step.

`git push` - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the menu on left select 'Pages'
  - From the source section drop-down menu, select the Branch: main
  - Click 'Save'
  - A live link will be displayed in a green banner when published successfully.

The live link can be found here - <https://jrakau.github.io/project_bonsai/>

### Clone the Repository Code Locally

Navigate to the GitHub Repository you want to clone to use locally:

- Click on the code drop down button
- Click on HTTPS
- Copy the repository link to the clipboard
- Open your IDE of choice (git must be installed for the next steps)
- Type git clone copied-git-url into the IDE terminal

The project will now of been cloned on your local machine for use.
