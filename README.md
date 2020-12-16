# UVA Hydroinformatics Group Website

This is the website of the hydroinformatics research group at the University of Virginia.

This website is powered by Jekyll and some Bootstrap and Bootwatch. It was forked from the <a herf="http://www.allanlab.org/"> Allen Lab at Leiden University</a> website, which provides a license that allows for modification for your own purposes.

To build this webpage on OSX, follow these steps.

1. Install Jekyll. https://jekyllrb.com/docs/installation/

2. Clone repository.

3. In a terminal, type the following command to update bundler (first time only)

bundle update

4. Change to the website's root directory

cd {INSERT DIRECTORY}/group_website

4. In a terminal, type the following command to serve the site

bundle exec jekyll serve

4. This generates the <underscore>site folder. Go to http://localhost:4000 to see the site

5. Edit files in the <underscore>data, <underscore>includes, <underscore>layouts, and <underscore>pages folders to edit the content and look of the site. Do not directly edit files in the <underscore>site folder.

6. After making changes, to files in these folders, simple refresh the website to see the changes.

7. To deploy the site, first stop serving the website and then build the website using the following commands.

ctrl-c (stops serving)

bundle exec jekyll build

8. Copy the contents of the <underscore>site folder to the website hosting the site.


Copyright Jon Goodall 2020. Code released under the MIT License.
