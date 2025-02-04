Post Type Archive Mapping
===================

[![Build Status](https://travis-ci.org/ronalfy/post-type-archive-mapping.svg?branch=master)](https://travis-ci.org/ronalfy/post-type-archive-mapping)

Map a page to the archive of your post types.

Features
----------------------

<ul>
<li>Select a Private or Public page to use as your post type archive page.</li>
<li>View the archive and you will see the page content instead of the archive content.</li>
<li>Use page templates on your pages for flexibility.</li>
</ul>

## Note

Your post types need to have `has_archive` set to true.

Installation
---------------------
Go to Settings->Reading. At the bottom you will see a place to map your post types.

DEVS
---------------------

1. Clone the repo to any location you choose.
2. Run ```npm install``` inside the folder.
3. Run ```npm run dev``` inside the folder.
4. Set up a symlink to your WordPress installation using the folder as the base.
5. Run ```npm run start``` to make changes and then ```npm run prod``` when you're done.

1. To edit the block, they are in ```/blocks/load.js``` and ```/blocks/edit.js```.
2. The REST API is created and passed in ```/blocks.init.php```.
3. The attributes and output are in ```/blocks/class-post-type-select-posts.php```.

Credit
-------------
Chris Logan for coming up with the idea.