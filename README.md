# Onefootball-task

## General information

The goal of this project is to build a WordPress plugin that publishes an article viewer with key bindings to navigate to the previous / next article.

The plugin is compatibile with WordPress 4.7+, it uses WP-API (http://v2.wp-api.org/) and jQuery as the JavaScript solution.

The name of the plugin is **article-viewer** and is in the `/wp-content/plugins` folder of the project.

**article-viewer.php** declare the architecture of the plugin and the shortcodes used in the homepage and the "article viewer" page.

**art_viewer.js** (in the `/article-viewer/js` folder) contains all the logic so posts data can be retrieved with WP-API.

**art_viewer.css** (in the `/article-viewer/css` folder) contains code to style buttons on the homepage and arrows on the "article viewer" page.

## How to install the project

1. Download the release version on https://github.com/vincentdelsalle/wp-onefootball/releases
2. Unzip the file downloaded inside your local development folder environnement ( ex: /xampp/htdocs/)
3. Rename this folder to `wp-onefootball`
4. In your MySQL administration tool, import the database dump `onefootball.sql` sent by email
5. Open http://localhost/wp-onefootball to view it in the browser

## The journey on the website ;)

Choose an article category on the homepage by clicking on it.

Once a category is picked, the user is redirected to the "article viewer" page and he can navigate through the articles by pressing "J" or "K" key.
