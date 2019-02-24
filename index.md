## Using GitHub Pages to host your first website

More often then not, when someone starts to learn the basics of web design it is normally by starting with HTML, CSS and Javascript. Sooner or later, after a little bit/ a lot of practice you may find yourself designing and creating all of these different sites that you want to show off to the world. But how do you actually get these from your text editor onto the actual internet.

There are a number of ways to get your first web page online each with varying degrees of difficulty.

For many budding web designers one of the first steps is to find somewhere to safely store all of your work, with the most popular option being GitHub.

If you have already started using GitHub your already one step towards hosting your first web page online, and if not it’s a simple as signing up for a new account.


   [GitHub](https://github.com/)

### Github Pages
One of the many services GitHub provides on its free accounts is something called GitHub pages. GitHub pages allows you to turn one GitHub repository into a real-life website and it is surprisingly simple to do so by following the below steps.

1. Create a GitHub repository named ‘username.github.io’ ensuring your username is spelt exactly as it is on your account. For example, my GitHub username is ‘ScottDenton’ so my repository will be as shown below. Note it is case sensitive.

![Repository name]('./images/repo_name.png')

2. Within your repository create an ‘index.html’ file. This will be your main home page for your site. You may have other .html files within your site but no matter how it is set up within your repository GitHub will always show the first index.html file it finds as your home page.

3. Once all your files are complete, commit and push all your changes up to the master branch of your repository and go to https://username.github.io where username is your GitHub account name. Using my account as an example the name of the site will be https://scottdenton.github.io.

4. Once your site is live you can update/change anything you want by simply altering the files in your repository and pushing them back to the master branch. It is generally pretty quick to update but can on occasion take upwards of five minutes.

### Custom URL's
If you find that you don’t like having to use your GitHub username as your sites URL there is also the option of changing it to a custom URL.
  - Find a domain through a DNS provider/host such as GoDaddy.
  - Before configuring/finalizing the purchase of your custom domain you must add your custom domain to your GitHub pages site through the settings. Go to your repo, into settings and enter your custom domain and click save.
  - Then finalize your domain purchase and GitHub’s magic should do the rest for you.



  ### Dont like CSS ?
  If you don’t quite feel that your experienced enough to work with html and css or simply dont like it...don’t worry, because Jekyll can help you with that.

  Jekyll is a project that initially originated on GitHub, run entirely by a team of volunteers. It is completely open source, meaning anyone can fork their repository and use the code any way they wish.

Jekyll is designed to allow users the ability to create their own static webpages without any pre existing knowledge of html or CSS. You can simply type everything in markdown and let Jekyll do all the hard work converting it into the correct html and CSS format.

Jekyll is ideal for blogging as it allows the user to easily add new posts to their site by simply updating a markdown file without the need for a server to save everything to, as it is all be stored on your GitHub repository.

To download Jekyll and create a new site it only requires 4 simple steps.

If you are afraid that your site will look boring and the same as everyone else, do not fear because GitHub and Jekyll have you covered.

Once you’ve added all of your posts and information to your page and pushed it back to your GitHub repository you can then move on to picking a pre-built theme.

Simply go into your repositories settings and scroll down to the Theme Chooser and click Choose a theme. This will present you with multiple options to choose from, including giving you the ability to preview each theme in your browser.

But remember this will only work if you have used Jekyll to create your site and won’t work if you have created the files from scratch yourself.

### Project pages
Once you have created your initial username.github.io site that’s when the fun really begins. That is thanks to the unlimited amount of project sites that GitHub provides you with your free site.

Project sites allow you to create as many different static pages as you want. The URL for these sites is simply the name of your repository appended to your username.github.io URL.

For example, I created a repository with the name ‘github-pages-test’ giving me the URL of https://scottdenton.github.io/github-pages-test/

The process for creating a new project page is even simpler than creating your initial site page.

1. Choose if you want to use one of the pre built Jekyll themes I mentioned above or start from scratch.

2. Create a new repository, go into the settings and scroll down to the GitHub Pages section and click choose a theme.

3. Pick a theme.

4. Once you have selected a theme, the readme.md file will open for you to edit.
This is where you add all of your information that you want to be in your page.

5. Commit your changes at the bottom of the page and go to http://username.github.io/repository (remembering that the username might not be case sensitive in the URL but the repository name IS case sensitive)
