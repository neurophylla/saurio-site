# saurio-site

This is a repo for my personal site.


To publish the page with Jekyll you must follow these steps:

     Open the terminal and navigate to the root folder of your Jekyll site.
     Type the command "bundle exec jekyll serve" to start a local server (in case of problems with gem use the command: "gem update --system").
     Open your browser and go to http://localhost:4000 to view your website locally.
     If satisfied with the result, stop the local server by pressing Ctrl + C in the terminal.
     Type the command "jekyll build" to build your site's static files in the _site folder.
     Upload the generated files to the _site folder on your web server or a hosting platform like GitHub Pages.

Remember to perform these steps whenever you change your site and want to publish them.




ARUBA
To publish your site on your space with Aruba, you must upload the files in the _site folder via FTP.

To do that, follow these steps:

     Access the control panel of your Aruba space using the link provided (for example, https://hosting123.aruba.it/);
     Click on the "linux hosting" section;
     Click on file manager;
     Upload all files from the _site folder to the public_html folder via your FTP client (be sure also to upload hidden files, such as .htaccess).

At this point, your site should be live and visible online at your domain address. It may take a few hours for the changes to take effect, as DNS propagation times can vary.
