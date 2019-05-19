Getting Started with Netlify
==========

This site supports JAMstack Cincinnati's May 2019 meetup on _Getting Started with Netlify_. This meetup represents the first in a multi-step series on getting comfortable working with the JAMstack.

Prerequisites
----------

Before we dig in, make sure you have the prerequisites covered:

1. A basic understanding of [Git](https://git-scm.com/).
2. A [GitHub account](https://github.com/).
3. Basic knowledge of HTML and CSS.
4. [Yarn](https://yarnpkg.com/en/docs/install) is not 100% necessary, but can make working with the project in development (on your machine) a little easier.

Setup
----------

First, [fork the repository](https://help.github.com/en/articles/fork-a-repo) on GitHub into your own user's space.

Then clone the repository to your local filesystem (make sure to replace `[YOUR_USERNAME]`):

    $ git clone git@github.com:[YOUR_USERNAME]/1905-getting-started-with-netlify.git

If you are going to use Yarn to run the local server, you can first install the dependencies:

    $ yarn install

Running the Project Locally
----------

This project uses [http-server](https://yarnpkg.com/en/package/http-server) to run your `www` directory as a web server. You don't have to do this, though. The project is also configured so that you can open the HTML files directly in the browser.

If you want to run the server, make sure the JS packages are installed first (`yarn install`) and then you can start up the dev server:

    $ yarn run dev

After doing this, you should be able to navigate to `http://localhost:8000` in your browser and see the home page of the project.
