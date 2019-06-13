# README

This README would normally document whatever steps are necessary to get the
application up and running.



1.
Create a new Rails app named portfolio.

2.
After you create the new app, switch to its folder. In the terminal, type:

cd portfolio
3.
Install the gems specified in the Gemfile.

4.
Generate a controller named Pages.

Make a welcome page
5.
In the Pages controller, make an action named welcome.

6.
In the routes file, set the welcome action as the root route.

7.
Set up the layout file (app/views/layouts/application.html.erb). The layout file lets you build a base view that contains all the common elements of your site, such as CSS files, the header, and the footer. The <%= yield %> defines the portion of the layout that child templates can fill in.

In the <head> below the <title>, add CSS for the Roboto web font. Follow the instructions here. Choose the styles Thin 100, Light 300, Medium 500, and Bold 700.

Add CSS for Bootstrap. Follow the instructions here. Use the latest compiled and minified CSS, and not the optional theme.

Make sure both CSS URLs start with https.

8.
Create a view named app/views/pages/welcome.html.erb and style it in app/assets/stylesheets/pages.css.scss.

Add a header section with a navigation menu and your name.

Add a main section with a tagline summarizing what you do and a ‘View my Work’ button. Add styles to pages.css.scss that targets the main section and sets the background to your own image.

Add a footer with links to your GitHub, LinkedIn, Twitter, and a copyright. Flaticon has free social icons here.

To use images, first upload your images to a hosting service like Dropbox. Then link to the images in your HTML and CSS.

9.
Start a Rails server to preview the app in the browser. In the terminal, type:

rails s -p 4001
This command starts a Rails server listening on port 4001. View the result by running the local server and going to http://localhost:4001.

10.
Put your app under version control with Git. Then push it up to GitHub. Check out the instructions here.

11.
Deploy your app to Heroku. Check out the instructions here.

Make a portfolio page
12.
Take screenshots of the apps you’ve built in this course. Upload them to an image hosting service. Check out how to do this using Dropbox.

13.
Make a new controller action and a new route for the portfolio page.

14.
Create a view for the portfolio page and style it:

The portfolio page has the same header and footer as the welcome page. Instead of writing the same code twice, refactor the header and footer from the welcome page and place them into application.html.erb so that they are available by all pages in the app.

Add a main section. In this section, use jQuery and the Unslider library to add a slideshow to top of the portfolio page. Follow the code examples in the Unslider docs to add the slideshow. Choose three screenshots of apps you’ve built and use these images in the slideshow.

Save your JavaScript code to app/assets/javascripts/, and then include it the page as shown here.

Add a supporting section. In this section create a grid of items for the apps you’ve built.

-For each item, include the screenshot of the app, a title and description, and a link to the live app on Heroku.

15.
In the header, use the link_to helper to generate links to the welcome page and portfolio page.

16.
In the welcome page, use link_to to generate a link to the portfolio page.

17.
Run the local web server to view the app at http://localhost:4001.

18.
Commit the changes using Git, and push up to GitHub.

19.
Deploy your app to Heroku.

Link to your blog
20.
A blog is a good way to share your expertise and interests with others. It helps promote your portfolio as well as increase your online presence.

In the header, use link_to to generate a link to your blog.

If you don’t have a blog, Medium is a great blog-publishing platform to distribute your content and get discovered.

21.
Run the local server to view the result at http://localhost:4001.

22.
Commit the changes using Git, and push up to GitHub.

23.
Deploy your app to Heroku.

Make an about page
24.
Make a new controller action and a new route for the about page.

25.
Create a view for the about page and style it:

Add a picture of yourself.

Write a description of yourself. Describe your background, your goals, and your technical skills.

26.
In the header, use link_to to generate a link to the about page.

27.
Run the local server to view the result at http://localhost:4001.

28.
Commit the changes using Git, and push up to GitHub.

29.
Deploy your app to Heroku.

Make a contact page
30.
Make a new controller action and a new route for the contact page.

31.
Create a view for the contact page and style it. Add links to places people can contact you online. A few options are:

email
Facebook
GitHub
Google+
LinkedIn
Twitter
Flaticon has free social icons here.

32.
In the header, use link_to to generate a link to the contact page.

33.
Run the local server to view the result at http://localhost:4001.

34.
Commit the changes using Git, and push up to GitHub.

35.
Deploy your app to Heroku.

Map a custom domain
36.
So far you’ve been using a herokuapp.com domain (eg https://portfolio-rails-2633.herokuapp.com/) to access your app. Let’s map a custom domain to your app (eg http://wwww.yourname.com). Check out the instructions here.
