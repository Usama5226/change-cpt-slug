**Change Custom Post Type Slug Without Losing Existing Posts**

This code snippet allows you to change the slug of a custom post type (CPT) in WordPress without losing existing posts or causing 404 errors. When changing a CPT slug, WordPress typically loses the connection to old posts, but this snippet helps ensure all post permalinks are preserved and redirected to the new slug properly.

**Features**
* Seamlessly update custom post type slugs.
* Automatically handles permalinks for existing posts.
* No need to manually set up redirects or worry about 404 errors.

**Usage**
* Copy the code snippet to your theme’s functions.php file or a custom plugin.
* Replace the ```old_cpt_slug``` and ```new_cpt_slug``` in the snippet according to your custom post type.
* Save and refresh permalinks in the WordPress admin (Settings > Permalinks) to apply changes

