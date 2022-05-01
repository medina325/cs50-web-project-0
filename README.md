# CS50' Web Programming with Python and Javascript - Project 0 - Search

## Summary
- [Description](#description)
- [Requirements](#requirements)
- [Submit Version](#submit-version-result)

## Description
Design a front-end for Google Search, Google Image Search, and Google Advanced Search.

## Requirements
Taken from the [project's page](https://cs50.harvard.edu/web/2020/projects/0/search/).
- Your website should have at least three pages: one for regular Google Search (which must be called index.html), one for Google Image Search, and one for Google Advanced Search.
    - On the Google Search page, there should be links in the upper-right of the page to go to Image Search or Advanced Search. On each of the other two pages, there should be a link in the upper-right to go back to Google Search.
- On the Google Search page, the user should be able to type in a query, click “Google Search”, and be taken to the Google search results for that page.
    - Like Google’s own, your search bar should be centered with rounded corners. The search button should also be centered, and should be beneath the search bar.
- On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page.
- On the Google Advanced Search page, the user should be able to provide input for the following four fields (taken from Google’s own advanced search options)
    - Find pages with… “all these words:”
    - Find pages with… “this exact word or phrase:”
    - Find pages with… “any of these words:”
    - Find pages with… “none of these words:”
- Like Google’s own Advanced Search page, the four options should be stacked vertically, and all of the text fields should be left aligned.
    - Consistent with Google’s own CSS, the “Advanced Search” button should be blue with white text.
    - When the “Advanced Search” button is clicked, the user should be taken to the search results page for their given query.
- Add an “I’m Feeling Lucky” button to the main Google Search page. Consistent with Google’s own behavior, clicking this link should take users directly to the first Google search result for the query, bypassing the normal results page.
    - You may encounter a redirect notice when using the “I’m Feeling Lucky” button. Not to worry! This is an expected consequence of a security feature implemented by Google.
- The CSS you write should resemble Google’s own aesthetics.

## Submit Version Result
Here are the final results for the project. The figures below aim to demonstrate how close it is to the current version of Google's user interface, but besides that, every functionality was implemented according to the requirements.

### Google Search

![google search](/examples/index.jpg)
<img alt="google search" src="/examples/index.jpg" width="50px" height="30px" >

### Google Images

![google search](/examples/images.jpg)

### Google Advanced Search
![google search](/examples/advanced_search.jpg)

