---
layout: post
title:      "Rails + Javascript Portfolio Project"
date:       2018-03-13 02:08:27 +0000
permalink:  rails_javascript_portfolio_project
---


For my Rails + Javascript portfolio project, I added a great deal of functionality to my Classic Car App from the Rails project mode section. It was a great learning experience all the way through, and having completed this section and project I now feel like a much more well rounded developer.

On to the requirements: 

1. Must render at least one index page (index resource - 'list of things') via jQuery and an Active Model Serialization JSON Backend - For this requirement, I added a profile page for each registered user of the program, and on that profile page is a "Load Cars" button that loads the index of cars that are owned by the current user via an AJAX GET request.

2. Must render at least one show page (show resource - 'one specific thing') via jQuery and an Active Model Serialization JSON Backend. - For this requirement, I put a next button on the cars show page that fetches and renders the next car via JQuery/AJAX.

3. The rails API must reveal at least one has-many relationship in the JSON that is then rendered to the page. - This requirement was also met using the current user profile page. I also added another has_many reveal to the "All Cars" page, where there is a button to load the awards for each car, which when clicked loads the awards via an AJAX GET request without refreshing the page.

4. Must use your Rails API and a form to create a resource and render the response without a page refresh. - I met this requirement with a form on the categories index page, where users can add categories to the list to choose from. Once a user adds a category, the category is immediately made visible on the page without refreshing, which was accomplished using an AJAX POST request.

5. Must translate the JSON responses into Javascript Model Objects. The Model Objects must have at least one method on the prototype. - To satisfy this requirement, I translated the category JSON responses into Javascript Model Objects, and then added a method on the prototype that makes a link to the category's show page from the category index page.

Now on to React and Redux, I am very excited to see what these next few weeks have in store!




