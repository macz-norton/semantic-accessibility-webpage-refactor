# Webpage Refactor: Semantic HTML & Accessibility

![Last Commit](https://img.shields.io/github/last-commit/macz-norton/semantic-accessibility-webpage-refactor)

## Description

This respository highlights the changes to an existing marketing agency webpage that improve the webpage's semantic HTML, accessibility, and search engine optimization (SEO).

I followed this series of high-level steps to refactor the code:

Index.html
1. Replaced non-descriptive elements with semantic HTML5 elements, including 'nav', 'header', 'main', 'section', 'footer', etc.
2. Updated webpage title to be more descriptive.
3. Added alt elements to describe images.
4. Fixed broken anchor links.
5. Added additional spacing to the file for improved code readability.

Style.css
1. Consolidated repetitive class styling
2. Updated colors and sizing for consistency and clarity.
3. Added comments to describe more complex styling / classes

Assets/Images
1. As mentioned, added alt elements to each image (in the index.html file)
2. Compressed image sizes for improved image load time.

## Installation

This project requires no installations. 

## Usage

The updated, deployed website uses semantic HTML and follows accessibility standards: https://macz-norton.github.io/semantic-accessibility-webpage-refactor/

![ Horiseon Social Services, Inc. webpage](https://user-images.githubusercontent.com/71162422/95649950-6670b780-0a95-11eb-850e-e02dd5689437.png)

## Tests

To test the accessibility of the site:
1. **Keyboard accessibility**
    * You can use the tab / enter keys to use the navigation anchor links in the header. 
    * You can use the up and down arrows to move up or down the webpage.
2. **Visuals**
    * The background colors for elements with text meet contrast standard for those with impaired vision. Try this out: [ChromeLens](https://chrome.google.com/webstore/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd?hl=en)
    * The webpage is compatible with a screenreader. Try this out: [Chrome Vox](https://chrome.google.com/webstore/detail/chromevox-classic-extensi/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en)
    * Images include alt text that are compatible with a screenreader.
3. **Hearing:** This website does not include any audio elements (i.e. video, sounds).

## Credits

Guidance on semantic HTML and accessibility guidelines:
* [HTML: A good basis for accessibility, MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
* [HTML Semantic Elements, w3schools](https://www.w3schools.com/html/html5_semantic_elements.asp)


Guidance on using Git and GitHub:
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [Git Started with GitHub](https://www.udemy.com/course/git-started-with-github/)

## License

Licensed under the [MIT](LICENSE.txt) license.