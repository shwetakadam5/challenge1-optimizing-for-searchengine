# Refactoring an existing site to improve web accessibility.

## Description

- An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a      website using assistive technologies like video captions, screen readers, and braille keyboards. 
- Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google.
- It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.
- Refactoring the code so that the existing website has better web accessibilty and also the code base fulfils the acceptance criteria to ensure that we have cleaner functional code base. 

## Table of Contents 

- [Installation](#installation)
- [User Story](#user-story)
- [Usage](#usage)
- [Tests](#tests)
- [Acceptance Criteria](#acceptance-criteria)
- [License](#license)


## Installation

Follow these instructions to create your project and deploy it to GitHub Pages:

1. Create a new repository on your GitHub account and clone it to your computer.

2. When you're ready to deploy, use the git add, git commit, and git push commands to save and push your code to your GitHub repository.

3. Navigate to your GitHub repository in the browser and then select the Settings tab on the right side of the page.

4. On the Settings page, select Pages on the left side of the page. On the GitHub Pages screen, choose main in the dropdown under Branch. Click the Save button.

5. Navigate to <your-github-username.github.io/your-repository-name> and you will find that your new webpage has gone live! For example, if your GitHub username is "lernantino" and the project is "css-demo-site", then your URL would be <lernantino.github.io/css-demo-site>.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Usage
Once the website is live, the following webpage should be displayed to the user where all the navigation links should navigate to necessary sections and provide accessibility texts for the various tools.

![alt text](assets/images/Screenshot_22-2-2024_32252_shwetakadam5.github.io.jpeg)

## Tests

**Test 1** : Click on all the links on the navigation and check if redirected to the appropriate content.
- Click on the link Search Engine Optimization : User will be navigated to the details of search engine optimization on the webpage.
- Click on the link Online Reputation Management : User will be navigated to the details of online reputation management on the webpage.
- Click on the link Social Media Marketing : User will be navigated to the details of Social Media Marketing on the webpage.

**Test 2** : Hovering on the navigation links will display appropriate text.
- Hover on the link Search Engine Optimization : Hover text will display "Click to visit Search Engine Optimization"
- Hover on the link Online Reputation Management : Hover text will display "Click to visit Online Reputation Management"
- Hover on the link Social Media Marketing : Hover text will display "Click to visit Social Media Marketing"

**Test 3** :
- Hover on the images : Hover text will display the title of the respective image.

**Test 4** : 
- Check if appropriate alt text is displayed if the image fails to load for some reason.

**Test 5**: 
- Check appropriate headers are displayed for every section.

**Test 6** : 
- Check the title of the webpage upon loading.

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## License

MIT