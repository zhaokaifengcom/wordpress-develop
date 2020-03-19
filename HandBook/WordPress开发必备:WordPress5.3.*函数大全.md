# WordPress5.3.*函数大全[WordPress开发必备]

## 说明

WordPress 在 WordPress 开发者资源网 (WordPress Developer Resources) 中将 WordPress 定义的函数分开写在了几十页中，不利于直接对文本进行搜索以迅速找到相关函数。于是，我把这些函数都整合在了这一篇文章里，本文包含 WordPress 在其开发者资源网公布的 WordPress 5.3.* 的全部函数，一共 1470 个。大家在查找的时候，可以直接使用浏览器的查找功能对这个页面的文本内容进行搜索查找。通常，每个函数的下面都会有对其功能的简要描述、该函数在 WordPress 程序中的位置以及该函数被哪些函数依赖和该函数依赖于哪些函数。

搜索出函数名称后，可以在 WordPress 开发者资源网 (https://developer.wordpress.org/) 中搜索相应的函数名称来查找更详细的信息。

本文中的函数对应于 WordPress 5.3.* 版主程序，此前及此后的版本中一些常用函数的变化通常不会太大，也可以参考本文列出的函数。

## 正文

※1※

```
absint()
```

Function: Convert a value to non-negative integer.
Source: wp-includes/functions.php:4519
Used by 120 functions | Uses 0 functions

※2※

```
activate_plugin()
```

Function: Attempts activation of plugin in a “sandbox” and redirects on success.
Source: wp-admin/includes/plugin.php:618
Used by 1 function | Uses 19 functions

※3※

```
activate_plugins()
```

Function: Activate multiple plugins.
Source: wp-admin/includes/plugin.php:844
Used by 0 functions | Uses 5 functions

※4※

```
activate_sitewide_plugin()
```

Function: Deprecated functionality for activating a network-only plugin.
Source: wp-admin/includes/ms-deprecated.php:57
Used by 0 functions | Uses 1 function

※5※

```
addslashes_gpc()
```

Function: Adds slashes to escape strings.
Source: wp-includes/formatting.php:2715
Used by 1 function | Uses 1 function

※6※

```
addslashes_strings_only()
```

Function: Adds slashes only if the provided value is a string.
Source: wp-includes/formatting.php:5459
Used by 0 functions | Uses 0 functions

※7※

```
add_action()
```

Function: Hooks a function on to a specific action.
Source: wp-includes/plugin.php:403
Used by 73 functions | Uses 1 function

※8※

```
add_blog_option()
```

Function: Add a new option for a given blog id.
Source: wp-includes/ms-blogs.php:394
Used by 0 functions | Uses 4 functions

※9※

```
add_clean_index()
```

Function: Adds an index to a specified table.
Source: wp-admin/includes/upgrade.php:2360
Used by 0 functions | Uses 2 functions

※10※

```
add_comments_page()
```

Function: Add submenu page to the Comments main menu.
Source: wp-admin/includes/plugin.php:1701
Used by 0 functions | Uses 1 function

※11※

```
add_comment_meta()
```

Function: Add meta data field to a comment.
Source: wp-includes/comment.php:456
Used by 3 functions | Uses 1 function

※12※

```
add_contextual_help()
```

Function: Add contextual help text for a page.
Source: wp-admin/includes/deprecated.php:988
Used by 0 functions | Uses 3 functions

※13※

```
add_cssclass()
```

Function:
Source: wp-admin/includes/menu.php:194
Used by 1 function | Uses 0 functions

※14※

```
add_custom_background()
```

Function: Add callbacks for background image display.
Source: wp-includes/deprecated.php:3024
Used by 0 functions | Uses 2 functions

※15※

```
add_custom_image_header()
```

Function: Add callbacks for image header display.
Source: wp-includes/deprecated.php:2988
Used by 0 functions | Uses 2 functions

※16※

```
add_dashboard_page()
```

Function: Add submenu page to the Dashboard main menu.
Source: wp-admin/includes/plugin.php:1581
Used by 0 functions | Uses 1 function

※17※

```
add_editor_style()
```

Function: Add callback for custom TinyMCE editor stylesheets.
Source: wp-includes/theme.php:1939
Used by 0 functions | Uses 2 functions

※18※

```
add_existing_user_to_blog()
```

Function: Add a user to a blog based on details from maybe_add_existing_user_to_blog().
Source: wp-includes/ms-functions.php:2119
Used by 1 function | Uses 4 functions

※19※

```
add_feed()
```

Function: Add a new feed type like /atom1/.
Source: wp-includes/rewrite.php:247
Used by 0 functions | Uses 2 functions

※20※

```
add_filter()
```

Function: Hook a function or method to a specific filter action.
Source: wp-includes/plugin.php:108
Used by 93 functions | Uses 0 functions

※21※

```
add_image_size()
```

Function: Register a new image size.
Source: wp-includes/media.php:285
Used by 2 functions | Uses 1 function

※22※

```
add_link()
```

Function: Add a link to using values provided in $_POST.
Source: wp-admin/includes/bookmark.php:16
Used by 0 functions | Uses 1 function

※23※

```
add_links_page()
```

Function: Add submenu page to the Links main menu.
Source: wp-admin/includes/plugin.php:1653
Used by 0 functions | Uses 1 function

※24※

```
add_magic_quotes()
```

Function: Walks the array while sanitizing the contents.
Source: wp-includes/functions.php:1197
Used by 4 functions | Uses 1 function

※25※

```
add_management_page()
```

Function: Add submenu page to the Tools main menu.
Source: wp-admin/includes/plugin.php:1456
Used by 0 functions | Uses 1 function

※26※

```
add_media_page()
```

Function: Add submenu page to the Media main menu.
Source: wp-admin/includes/plugin.php:1629
Used by 0 functions | Uses 1 function

※27※

```
add_menu_classes()
```

Function:
Source: wp-admin/includes/menu.php:203
Used by 0 functions | Uses 3 functions

※28※

```
add_menu_page()
```

Function: Add a top-level menu page.
Source: wp-admin/includes/plugin.php:1273
Used by 2 functions | Uses 6 functions

※29※

```
add_meta()
```

Function: Add post meta data defined in $_POST superglobal for post with given ID.
Source: wp-admin/includes/post.php:896
Used by 3 functions | Uses 5 functions

※30※

```
add_metadata()
```

Function: Add metadata for the specified object.
Source: wp-includes/meta.php:30
Used by 7 functions | Uses 16 functions

※31※

```
add_meta_box()
```

Function: Adds a meta box to one or more screens.
Source: wp-admin/includes/template.php:1018
Used by 7 functions | Uses 3 functions

※32※

```
add_network_option()
```

Function: Add a new network option.
Source: wp-includes/option.php:1350
Used by 2 functions | Uses 15 functions

※33※

```
add_new_user_to_blog()
```

Function: Adds a newly created user to the appropriate blog
Source: wp-includes/ms-functions.php:2152
Used by 0 functions | Uses 5 functions

※34※

```
add_object_page()
```

Function: Add a top-level menu page in the ‘objects’ section.
Source: wp-admin/includes/deprecated.php:1429
Used by 0 functions | Uses 2 functions

※35※

```
add_option()
```

Function: Add a new option.
Source: wp-includes/option.php:459
Used by 5 functions | Uses 17 functions

※36※

```
add_options_page()
```

Function: Add submenu page to the Settings main menu.
Source: wp-admin/includes/plugin.php:1480
Used by 0 functions | Uses 1 function

※37※

```
add_option_update_handler()
```

Function: Register a setting and its sanitization callback
Source: wp-admin/includes/deprecated.php:167
Used by 0 functions | Uses 2 functions

※38※

```
add_option_whitelist()
```

Function: Adds an array of options to the options whitelist.
Source: wp-admin/includes/plugin.php:2126
Used by 1 function | Uses 0 functions

※39※

```
add_pages_page()
```

Function: Add submenu page to the Pages main menu.
Source: wp-admin/includes/plugin.php:1677
Used by 0 functions | Uses 1 function

※40※

```
add_permastruct()
```

Function: Add permalink structure.
Source: wp-includes/rewrite.php:203
Used by 2 functions | Uses 1 function

※41※

```
add_ping()
```

Function: Add a URL to those already pinged.
Source: wp-includes/post.php:4672
Used by 1 function | Uses 5 functions

※42※

```
add_plugins_page()
```

Function: Add submenu page to the Plugins main menu.
Source: wp-admin/includes/plugin.php:1528
Used by 0 functions | Uses 1 function

※43※

```
add_posts_page()
```

Function: Add submenu page to the Posts main menu.
Source: wp-admin/includes/plugin.php:1605
Used by 0 functions | Uses 1 function

※44※

```
add_post_meta()
```

Function: Adds a meta field to the given post.
Source: wp-includes/post.php:2061
Used by 16 functions | Uses 2 functions

※45※

```
add_post_type_support()
```

Function: Registers support of certain features for a post type.
Source: wp-includes/post.php:1842
Used by 2 functions | Uses 0 functions

※46※

```
add_query_arg()
```

Function: Retrieves a modified URL query string.
Source: wp-includes/functions.php:1059
Used by 141 functions | Uses 4 functions

※47※

```
add_rewrite_endpoint()
```

Function: Add an endpoint, like /trackback/.
Source: wp-includes/rewrite.php:314
Used by 0 functions | Uses 1 function

※48※

```
add_rewrite_rule()
```

Function: Adds a rewrite rule that transforms a URL structure to a set of query vars.
Source: wp-includes/rewrite.php:137
Used by 2 functions | Uses 1 function

※49※

```
add_rewrite_tag()
```

Function: Add a new rewrite tag (like %postname%).
Source: wp-includes/rewrite.php:159
Used by 2 functions | Uses 2 functions

※50※

```
add_role()
```

Function: Add role, if it does not exist.
Source: wp-includes/capabilities.php:815
Used by 1 function | Uses 2 functions

※51※

```
add_screen_option()
```

Function: Register and configure an admin screen option
Source: wp-admin/includes/screen.php:203
Used by 0 functions | Uses 1 function

※52※

```
add_settings_error()
```

Function: Register a settings error to be displayed to the user
Source: wp-admin/includes/template.php:1721
Used by 3 functions | Uses 0 functions

※53※

```
add_settings_field()
```

Function: Add a new field to a section of a settings page.
Source: wp-admin/includes/template.php:1578
Used by 0 functions | Uses 2 functions

※54※

```
add_settings_section()
```

Function: Add a new section to a settings page.
Source: wp-admin/includes/template.php:1507
Used by 0 functions | Uses 2 functions

※55※

```
add_shortcode()
```

Function: Adds a new shortcode.
Source: wp-includes/shortcodes.php:63
Used by 2 functions | Uses 2 functions

※56※

```
add_site_meta()
```

Function: Adds metadata to a site.
Source: wp-includes/ms-site.php:1048
Used by 0 functions | Uses 1 function

※57※

```
add_site_option()
```

Function: Add a new option for the current network.
Source: wp-includes/option.php:1168
Used by 3 functions | Uses 1 function

※58※

```
add_submenu_page()
```

Function: Add a submenu page.
Source: wp-admin/includes/plugin.php:1345
Used by 13 functions | Uses 6 functions

※59※

```
add_term_meta()
```

Function: Adds metadata to a term.
Source: wp-includes/taxonomy.php:1217
Used by 1 function | Uses 4 functions

※60※

```
add_theme_page()
```

Function: Add submenu page to the Appearance main menu.
Source: wp-admin/includes/plugin.php:1504
Used by 2 functions | Uses 1 function

※61※

```
add_theme_support()
```

Function: Registers theme support for a given feature.
Source: wp-includes/theme.php:2384
Used by 9 functions | Uses 7 functions

※62※

```
add_thickbox()
```

Function: Enqueues the default ThickBox js and css.
Source: wp-includes/general-template.php:4506
Used by 1 function | Uses 4 functions

※63※

```
add_user()
```

Function: Creates a new user from the “Users” form using $_POST information.
Source: wp-admin/includes/user.php:16
Used by 0 functions | Uses 1 function

※64※

```
add_users_page()
```

Function: Add submenu page to the Users/Profile main menu.
Source: wp-admin/includes/plugin.php:1552
Used by 0 functions | Uses 2 functions

※65※

```
add_user_meta()
```

Function: Adds meta data to a user.
Source: wp-includes/user.php:792
Used by 1 function | Uses 1 function

※66※

```
add_user_to_blog()
```

Function: Adds a user to a blog.
Source: wp-includes/ms-functions.php:158
Used by 5 functions | Uses 15 functions

※67※

```
add_utility_page()
```

Function: Add a top-level menu page in the ‘utility’ section.
Source: wp-admin/includes/deprecated.php:1462
Used by 0 functions | Uses 2 functions

※68※

```
adjacent_image_link()
```

Function: Displays next or previous image link that has the same post parent.
Source: wp-includes/media.php:2953
Used by 2 functions | Uses 5 functions

※69※

```
adjacent_posts_rel_link()
```

Function: Displays the relational links for the posts adjacent to the current post.
Source: wp-includes/link-template.php:1947
Used by 1 function | Uses 1 function

※70※

```
adjacent_posts_rel_link_wp_head()
```

Function: Displays relational links for the posts adjacent to the current post for single post pages.
Source: wp-includes/link-template.php:1962
Used by 0 functions | Uses 3 functions

※71※

```
adjacent_post_link()
```

Function: Displays the adjacent post link.
Source: wp-includes/link-template.php:2211
Used by 0 functions | Uses 1 function

※72※

```
admin_color_scheme_picker()
```

Function: Display the default admin color scheme picker (Used in user-edit.php)
Source: wp-admin/includes/misc.php:891
Used by 0 functions | Uses 8 functions

※73※

```
admin_created_user_email()
```

Function:
Source: wp-admin/includes/user.php:571
Used by 0 functions | Uses 6 functions

※74※

```
admin_created_user_subject()
```

Function:
Source: wp-admin/user-new.php:35
Used by 0 functions | Uses 0 functions

※75※

```
admin_url()
```

Function: Retrieves the URL to the admin area for the current site.
Source: wp-includes/link-template.php:3279
Used by 106 functions | Uses 1 function

※76※

```
allowed_http_request_hosts()
```

Function: Whitelists allowed redirect hosts for safe HTTP requests as well.
Source: wp-includes/http.php:608
Used by 0 functions | Uses 1 function

※77※

```
allowed_tags()
```

Function: Display all of the allowed tags in HTML format with attributes.
Source: wp-includes/general-template.php:2303
Used by 0 functions | Uses 0 functions

※78※

```
allow_subdirectory_install()
```

Function: Allow subdirectory installation.
Source: wp-admin/includes/network.php:53
Used by 2 functions | Uses 3 functions

※79※

```
allow_subdomain_install()
```

Function: Allow subdomain installation
Source: wp-admin/includes/network.php:35
Used by 2 functions | Uses 1 function

※80※

```
antispambot()
```

Function: Converts email addresses characters to HTML entities to block spam bots.
Source: wp-includes/formatting.php:2788
Used by 0 functions | Uses 1 function

※81※

```
apache_mod_loaded()
```

Function: Does the specified module exist in the Apache config?
Source: wp-includes/functions.php:4943
Used by 2 functions | Uses 0 functions

※82※

```
apply_filters()
```

Function: Call the functions added to a filter hook.
Source: wp-includes/plugin.php:181
Used by 1124 functions | Uses 1 function

※83※

```
apply_filters_deprecated()
```

Function: Fires functions attached to a deprecated filter hook.
Source: wp-includes/plugin.php:626
Used by 6 functions | Uses 3 functions

※84※

```
apply_filters_ref_array()
```

Function: Execute functions hooked on a specific filter hook, specifying arguments in an array.
Source: wp-includes/plugin.php:228
Used by 12 functions | Uses 1 function

※85※

```
array_replace_recursive()
```

Function: PHP-agnostic version of {@link array_replace_recursive()}.
Source: wp-includes/compat.php:472
Used by 0 functions | Uses 0 functions

※86※

```
atom_enclosure()
```

Function: Display the atom enclosure for the current post.
Source: wp-includes/feed.php:509
Used by 0 functions | Uses 7 functions

※87※

```
atom_site_icon()
```

Function: Displays Site Icon in atom feeds.
Source: wp-includes/feed.php:587
Used by 0 functions | Uses 2 functions

※88※

```
attachment_id3_data_meta_box()
```

Function: Display fields for ID3 data
Source: wp-admin/includes/meta-boxes.php:1370
Used by 0 functions | Uses 3 functions

※89※

```
attachment_submitbox_metadata()
```

Function: Displays non-editable attachment metadata in the publish meta box.
Source: wp-admin/includes/media.php:3230
Used by 0 functions | Uses 15 functions

※90※

```
attachment_submit_meta_box()
```

Function: Display attachment submit form fields.
Source: wp-admin/includes/meta-boxes.php:368
Used by 0 functions | Uses 9 functions

※91※

```
attachment_url_to_postid()
```

Function: Tries to convert an attachment URL into a post ID.
Source: wp-includes/media.php:4239
Used by 2 functions | Uses 5 functions

※92※

```
attribute_escape()
```

Function: Escaping for HTML attributes.
Source: wp-includes/deprecated.php:2093
Used by 0 functions | Uses 2 functions

※93※

```
author_can()
```

Function: Whether the author of the supplied post has a specific capability.
Source: wp-includes/capabilities.php:726
Used by 0 functions | Uses 2 functions

※94※

```
auth_redirect()
```

Function: Checks if a user is logged in, if not it redirects them to the login page.
Source: wp-includes/pluggable.php:1019
Used by 1 function | Uses 14 functions

※95※

```
automatic_feed_links()
```

Function: Enable/disable automatic general feed link outputting.
Source: wp-includes/deprecated.php:2394
Used by 0 functions | Uses 3 functions

※96※

```
avoid_blog_page_permalink_collision()
```

Function: Avoids a collision between a site slug and a permalink slug.
Source: wp-admin/includes/ms.php:724
Used by 0 functions | Uses 3 functions

※97※

```
background_color()
```

Function: Display background color value.
Source: wp-includes/theme.php:1631
Used by 0 functions | Uses 1 function

※98※

```
background_image()
```

Function: Display background image path.
Source: wp-includes/theme.php:1611
Used by 0 functions | Uses 1 function

※99※

```
backslashit()
```

Function: Adds backslashes before letters and before a number at the start of a string.
Source: wp-includes/formatting.php:2664
Used by 0 functions | Uses 0 functions

※100※

```
balanceTags()
```

Function: Balances tags if forced to, or if the ‘use_balanceTags’ option is set to true.
Source: wp-includes/formatting.php:2432
Used by 0 functions | Uses 2 functions

※101※

```
before_last_bar()
```

Function: Remove last item on a pipe-delimited string.
Source: wp-includes/l10n.php:201
Used by 4 functions | Uses 0 functions

※102※

```
block_version()
```

Function: Returns the current version of the block format that the content string is using.
Source: wp-includes/blocks.php:356
Used by 1 function | Uses 1 function

※103※

```
bloginfo()
```

Function: Displays information about the current site.
Source: wp-includes/general-template.php:652
Used by 7 functions | Uses 1 function

※104※

```
bloginfo_rss()
```

Function: Display RSS container for the bloginfo function.
Source: wp-includes/feed.php:54
Used by 1 function | Uses 3 functions

※105※

```
body_class()
```

Function: Displays the class names for the body element.
Source: wp-includes/post-template.php:589
Used by 0 functions | Uses 1 function

※106※

```
bool_from_yn()
```

Function: Whether input is yes or no.
Source: wp-includes/functions.php:1494
Used by 0 functions | Uses 0 functions

※107※

```
build_query()
```

Function: Build URL query based on an associative and, or indexed array.
Source: wp-includes/functions.php:965
Used by 1 function | Uses 1 function

※108※

```
bulk_edit_posts()
```

Function: Process the post data for the bulk editing of posts.
Source: wp-admin/includes/post.php:450
Used by 0 functions | Uses 22 functions

※109※

```
cache_javascript_headers()
```

Function: Set the headers for caching for 10 days with JavaScript content type.
Source: wp-includes/functions.php:1462
Used by 0 functions | Uses 1 function

※110※

```
cache_users()
```

Function: Retrieve info for user lists to prevent multiple queries by get_userdata()
Source: wp-includes/pluggable.php:122
Used by 2 functions | Uses 4 functions

※111※

```
calendar_week_mod()
```

Function: Get number of days since the start of the week.
Source: wp-includes/general-template.php:2037
Used by 1 function | Uses 0 functions

※112※

```
cancel_comment_reply_link()
```

Function: Display HTML content for cancel comment reply link.
Source: wp-includes/comment-template.php:1871
Used by 1 function | Uses 1 function

※113※

```
can_edit_network()
```

Function: Whether or not we can edit this network from this page.
Source: wp-admin/includes/ms.php:815
Used by 1 function | Uses 3 functions

※114※

```
capital_P_dangit()
```

Function: Forever eliminate “Wordpress” from the planet (or at least the little bit we can influence).
Source: wp-includes/formatting.php:5323
Used by 1 function | Uses 2 functions

※115※

```
category_description()
```

Function: Retrieve category description.
Source: wp-includes/category-template.php:275
Used by 0 functions | Uses 1 function

※116※

```
category_exists()
```

Function: Check whether a category exists.
Source: wp-admin/includes/taxonomy.php:24
Used by 2 functions | Uses 1 function

※117※

```
cat_is_ancestor_of()
```

Function: Check if a category is an ancestor of another category.
Source: wp-includes/category.php:235
Used by 0 functions | Uses 1 function

※118※

```
checked()
```

Function: Outputs the html checked attribute.
Source: wp-includes/general-template.php:4646
Used by 30 functions | Uses 1 function

※119※

```
check_admin_referer()
```

Function: Ensures intent by verifying that a user was referred from another admin page with the correct security nonce.
Source: wp-includes/pluggable.php:1108
Used by 12 functions | Uses 8 functions

※120※

```
check_ajax_referer()
```

Function: Verifies the Ajax request to prevent processing requests external of the blog.
Source: wp-includes/pluggable.php:1152
Used by 79 functions | Uses 7 functions

※121※

```
check_and_publish_future_post()
```

Function: Publish future post and make sure post ID has future post status.
Source: wp-includes/post.php:4254
Used by 0 functions | Uses 4 functions

※122※

```
check_column()
```

Function: Check column matches criteria.
Source: wp-admin/install-helper.php:168
Used by 0 functions | Uses 1 function

※123※

```
check_comment()
```

Function: Check whether a comment passes internal checks to be allowed to add.
Source: wp-includes/comment.php:39
Used by 1 function | Uses 8 functions

※124※

```
check_comment_flood_db()
```

Function: Hooks WP’s native database-based comment-flood check.
Source: wp-includes/comment.php:840
Used by 0 functions | Uses 1 function

※125※

```
check_import_new_users()
```

Function: Checks if the current user has permissions to import new users.
Source: wp-admin/includes/ms.php:623
Used by 0 functions | Uses 1 function

※126※

```
check_password_reset_key()
```

Function: Retrieves a user row based on password reset key and login
Source: wp-includes/user.php:2359
Used by 0 functions | Uses 7 functions

※127※

```
check_theme_switched()
```

Function: Checks if a theme has been changed and runs ‘after_switch_theme’ hook on the next WP load.
Source: wp-includes/theme.php:2938
Used by 0 functions | Uses 7 functions

※128※

```
check_upload_mimes()
```

Function: Check an array of MIME types against a whitelist.
Source: wp-includes/ms-functions.php:1809
Used by 0 functions | Uses 1 function

※129※

```
check_upload_size()
```

Function: Determine if uploaded file exceeds space quota.
Source: wp-admin/includes/ms.php:18
Used by 0 functions | Uses 6 functions

※130※

```
choose_primary_blog()
```

Function: Handles the display of choosing a user’s primary site.
Source: wp-admin/includes/ms.php:758
Used by 0 functions | Uses 8 functions

※131※

```
clean_attachment_cache()
```

Function: Will clean the attachment in the cache.
Source: wp-includes/post.php:6679
Used by 1 function | Uses 4 functions

※132※

```
clean_blog_cache()
```

Function: Clean the blog cache
Source: wp-includes/ms-site.php:971
Used by 7 functions | Uses 8 functions

※133※

```
clean_bookmark_cache()
```

Function: Deletes the bookmark cache.
Source: wp-includes/bookmark.php:458
Used by 4 functions | Uses 2 functions

※134※

```
clean_category_cache()
```

Function: Remove the category cache data based on ID.
Source: wp-includes/category.php:334
Used by 0 functions | Uses 1 function

※135※

```
clean_comment_cache()
```

Function: Removes a comment from the object cache.
Source: wp-includes/comment.php:3013
Used by 7 functions | Uses 4 functions

※136※

```
clean_network_cache()
```

Function: Removes a network from the object cache.
Source: wp-includes/ms-network.php:78
Used by 1 function | Uses 4 functions

※137※

```
clean_object_term_cache()
```

Function: Removes the taxonomy relationship to terms from the cache.
Source: wp-includes/taxonomy.php:3184
Used by 4 functions | Uses 4 functions

※138※

```
clean_page_cache()
```

Function: Will clean the page in the cache.
Source: wp-includes/deprecated.php:3115
Used by 0 functions | Uses 2 functions

※139※

```
clean_post_cache()
```

Function: Will clean the post in the cache.
Source: wp-includes/post.php:6551
Used by 14 functions | Uses 7 functions

※140※

```
clean_pre()
```

Function: Accepts matches array from preg_replace_callback in wpautop() or a string.
Source: wp-includes/deprecated.php:2961
Used by 0 functions | Uses 1 function

※141※

```
clean_site_details_cache()
```

Function: Cleans the site details cache for a site.
Source: wp-includes/ms-blogs.php:320
Used by 0 functions | Uses 2 functions

※142※

```
clean_taxonomy_cache()
```

Function: Clean the caches for a taxonomy.
Source: wp-includes/taxonomy.php:3289
Used by 1 function | Uses 5 functions

※143※

```
clean_term_cache()
```

Function: Will remove all of the term ids from the cache.
Source: wp-includes/taxonomy.php:3228
Used by 6 functions | Uses 6 functions

※144※

```
clean_url()
```

Function: Checks and cleans a URL.
Source: wp-includes/deprecated.php:2037
Used by 0 functions | Uses 2 functions

※145※

```
clean_user_cache()
```

Function: Clean all user caches
Source: wp-includes/user.php:1360
Used by 10 functions | Uses 4 functions

※146※

```
clear_global_post_cache()
```

Function: Deprecated functionality to clear the global post cache.
Source: wp-includes/ms-deprecated.php:143
Used by 0 functions | Uses 1 function

※147※

```
codepress_footer_js()
```

Function: Adds JavaScript required to make CodePress work on the theme/plugin editors.
Source: wp-admin/includes/deprecated.php:206
Used by 0 functions | Uses 1 function

※148※

```
codepress_get_lang()
```

Function: Determines the language to use for CodePress syntax highlighting.
Source: wp-admin/includes/deprecated.php:196
Used by 0 functions | Uses 1 function

※149※

```
comments_link()
```

Function: Display the link to the current post comments.
Source: wp-includes/comment-template.php:828
Used by 2 functions | Uses 3 functions

※150※

```
comments_link_feed()
```

Function: Outputs the link to the comments for the current post in an xml safe way
Source: wp-includes/feed.php:255
Used by 0 functions | Uses 4 functions

※151※

```
comments_number()
```

Function: Display the language string for the number of comments the current post has.
Source: wp-includes/comment-template.php:878
Used by 1 function | Uses 2 functions

※152※

```
comments_open()
```

Function: Determines whether the current post is open for comments.
Source: wp-includes/comment-template.php:1214
Used by 11 functions | Uses 3 functions

※153※

```
comments_popup_link()
```

Function: Displays the link to the comments for the current post ID.
Source: wp-includes/comment-template.php:1527
Used by 0 functions | Uses 17 functions

※154※

```
comments_popup_script()
```

Function: Display the JS popup script to show a comment.
Source: wp-includes/deprecated.php:3744
Used by 0 functions | Uses 1 function

※155※

```
comments_rss()
```

Function: Return link to the post RSS feed.
Source: wp-includes/deprecated.php:1174
Used by 0 functions | Uses 3 functions

※156※

```
comments_rss_link()
```

Function: Print RSS comment feed link.
Source: wp-includes/deprecated.php:1119
Used by 0 functions | Uses 2 functions

※157※

```
comments_template()
```

Function: Load the comment template specified in $file.
Source: wp-includes/comment-template.php:1321
Used by 0 functions | Uses 15 functions

※158※

```
comment_author()
```

Function: Displays the author of the current comment.
Source: wp-includes/comment-template.php:60
Used by 1 function | Uses 4 functions

※159※

```
comment_author_email()
```

Function: Display the email of the author of the current global $comment.
Source: wp-includes/comment-template.php:117
Used by 0 functions | Uses 4 functions

※160※

```
comment_author_email_link()
```

Function: Display the html email link to the author of the current comment.
Source: wp-includes/comment-template.php:151
Used by 0 functions | Uses 1 function

※161※

```
comment_author_IP()
```

Function: Display the IP address of the author of the current comment.
Source: wp-includes/comment-template.php:292
Used by 0 functions | Uses 2 functions

※162※

```
comment_author_link()
```

Function: Display the html link to the url of the author of the current comment.
Source: wp-includes/comment-template.php:253
Used by 2 functions | Uses 1 function

※163※

```
comment_author_rss()
```

Function: Display the current comment author in the feed.
Source: wp-includes/feed.php:342
Used by 0 functions | Uses 1 function

※164※

```
comment_author_url()
```

Function: Display the url of the author of the current comment.
Source: wp-includes/comment-template.php:338
Used by 0 functions | Uses 4 functions

※165※

```
comment_author_url_link()
```

Function: Displays the HTML link of the url of the author of the current comment.
Source: wp-includes/comment-template.php:414
Used by 0 functions | Uses 1 function

※166※

```
comment_class()
```

Function: Generates semantic classes for each comment element.
Source: wp-includes/comment-template.php:432
Used by 4 functions | Uses 1 function

※167※

```
comment_date()
```

Function: Display the comment date of the current comment.
Source: wp-includes/comment-template.php:579
Used by 0 functions | Uses 1 function

※168※

```
comment_excerpt()
```

Function: Display the excerpt of the current comment.
Source: wp-includes/comment-template.php:635
Used by 1 function | Uses 4 functions

※169※

```
comment_exists()
```

Function: Determine if a comment exists based on author and date.
Source: wp-admin/includes/comment.php:27
Used by 0 functions | Uses 2 functions

※170※

```
comment_footer_die()
```

Function: Display error message at bottom of comments.
Source: wp-admin/includes/comment.php:209
Used by 0 functions | Uses 0 functions

※171※

```
comment_form()
```

Function: Outputs a complete commenting form for use within a template.
Source: wp-includes/comment-template.php:2252
Used by 0 functions | Uses 41 functions

※172※

```
comment_form_title()
```

Function: Display text based on comment reply status.
Source: wp-includes/comment-template.php:1935
Used by 1 function | Uses 4 functions

※173※

```
comment_guid()
```

Function: Display the feed GUID for the current comment.
Source: wp-includes/feed.php:274
Used by 0 functions | Uses 2 functions

※174※

```
comment_ID()
```

Function: Display the comment id of the current comment.
Source: wp-includes/comment-template.php:678
Used by 3 functions | Uses 1 function

※175※

```
comment_id_fields()
```

Function: Output hidden input HTML for replying to comments.
Source: wp-includes/comment-template.php:1911
Used by 0 functions | Uses 1 function

※176※

```
comment_link()
```

Function: Display the link to the comments.
Source: wp-includes/feed.php:304
Used by 0 functions | Uses 4 functions

※177※

```
comment_reply_link()
```

Function: Displays the HTML content for reply to comment link.
Source: wp-includes/comment-template.php:1740
Used by 2 functions | Uses 1 function

※178※

```
comment_text()
```

Function: Display the text of the current comment.
Source: wp-includes/comment-template.php:988
Used by 3 functions | Uses 4 functions

※179※

```
comment_text_rss()
```

Function: Display the current comment content for use in the feeds.
Source: wp-includes/feed.php:351
Used by 0 functions | Uses 3 functions

※180※

```
comment_time()
```

Function: Display the comment time of the current comment.
Source: wp-includes/comment-template.php:1048
Used by 1 function | Uses 1 function

※181※

```
comment_type()
```

Function: Display the comment type of the current comment.
Source: wp-includes/comment-template.php:1090
Used by 0 functions | Uses 3 functions

※182※

```
compression_test()
```

Function: Test support for compressing JavaScript from PHP
Source: wp-admin/includes/template.php:2262
Used by 0 functions | Uses 2 functions

※183※

```
confirm_another_blog_signup()
```

Function: Confirm a new site signup.
Source: wp-signup.php:500
Used by 1 function | Uses 9 functions

※184※

```
confirm_blog_signup()
```

Function: New site signup confirmation
Source: wp-signup.php:821
Used by 1 function | Uses 4 functions

※185※

```
confirm_delete_users()
```

Function:
Source: wp-admin/includes/ms.php:851
Used by 0 functions | Uses 17 functions

※186※

```
confirm_user_signup()
```

Function: New user signup confirmation
Source: wp-signup.php:664
Used by 1 function | Uses 4 functions

※187※

```
content_url()
```

Function: Retrieves the URL to the content directory.
Source: wp-includes/link-template.php:3351
Used by 3 functions | Uses 3 functions

※188※

```
convert_chars()
```

Function: Converts lone & characters into `&` (a.k.a. `&`)
Source: wp-includes/formatting.php:2360
Used by 5 functions | Uses 1 function

※189※

```
convert_invalid_entities()
```

Function: Converts invalid Unicode references range to valid range.
Source: wp-includes/formatting.php:2380
Used by 0 functions | Uses 0 functions

※190※

```
convert_smilies()
```

Function: Convert text equivalent of smilies to images.
Source: wp-includes/formatting.php:3324
Used by 0 functions | Uses 1 function

※191※

```
convert_to_screen()
```

Function: Convert a screen string to a screen object
Source: wp-admin/includes/template.php:2462
Used by 12 functions | Uses 3 functions

※192※

```
copy_dir()
```

Function: Copies a directory from one location to another via the WordPress Filesystem Abstraction.
Source: wp-admin/includes/file.php:1699
Used by 3 functions | Uses 5 functions

※193※

```
core_update_footer()
```

Function:
Source: wp-admin/includes/update.php:210
Used by 0 functions | Uses 5 functions

※194※

```
core_upgrade_preamble()
```

Function: Display upgrade WordPress for downloading latest or upgrading automatically form.
Source: wp-admin/update-core.php:218
Used by 0 functions | Uses 9 functions

※195※

```
count_many_users_posts()
```

Function: Number of posts written by a list of users.
Source: wp-includes/user.php:403
Used by 1 function | Uses 2 functions

※196※

```
count_users()
```

Function: Count number of users who have each of the user roles.
Source: wp-includes/user.php:870
Used by 3 functions | Uses 14 functions

※197※

```
count_user_posts()
```

Function: Number of posts user has written.
Source: wp-includes/user.php:369
Used by 3 functions | Uses 4 functions

※198※

```
create_empty_blog()
```

Function: Create an empty blog.
Source: wp-includes/ms-deprecated.php:396
Used by 0 functions | Uses 7 functions

※199※

```
create_initial_post_types()
```

Function: Creates the initial post types when ‘init’ action is fired.
Source: wp-includes/post.php:20
Used by 0 functions | Uses 6 functions

※200※

```
create_initial_rest_routes()
```

Function: Registers default REST API routes.
Source: wp-includes/rest-api.php:193
Used by 0 functions | Uses 17 functions

※201※

```
create_initial_taxonomies()
```

Function: Creates the initial taxonomies.
Source: wp-includes/taxonomy.php:24
Used by 0 functions | Uses 9 functions

※202※

```
create_user()
```

Function: An alias of wp_create_user().
Source: wp-includes/deprecated.php:1191
Used by 0 functions | Uses 2 functions

※203※

```
current_action()
```

Function: Retrieve the name of the current action.
Source: wp-includes/plugin.php:335
Used by 2 functions | Uses 1 function

※204※

```
current_datetime()
```

Function: Retrieves the current time as an object with the timezone from settings.
Source: wp-includes/functions.php:94
Used by 1 function | Uses 1 function

※205※

```
current_filter()
```

Function: Retrieve the name of the current filter or action.
Source: wp-includes/plugin.php:323
Used by 14 functions | Uses 0 functions

※206※

```
current_theme_info()
```

Function: Retrieves information on the current active theme.
Source: wp-admin/includes/deprecated.php:1053
Used by 0 functions | Uses 2 functions

※207※

```
current_theme_supports()
```

Function: Checks a theme’s support for a given feature.
Source: wp-includes/theme.php:2819
Used by 71 functions | Uses 3 functions

※208※

```
current_time()
```

Function: Retrieve the current time based on specified type.
Source: wp-includes/functions.php:71
Used by 33 functions | Uses 2 functions

※209※

```
current_user_can()
```

Function: Returns whether the current user has the specified capability.
Source: wp-includes/capabilities.php:651
Used by 408 functions | Uses 1 function

※210※

```
current_user_can_for_blog()
```

Function: Returns whether the current user has the specified capability for a given site.
Source: wp-includes/capabilities.php:683
Used by 0 functions | Uses 4 functions

※211※

```
customize_themes_print_templates()
```

Function: Print JS templates for the theme-browsing UI in the Customizer.
Source: wp-admin/includes/theme.php:701
Used by 0 functions | Uses 3 functions

※212※

```
dashboard_browser_nag_class()
```

Function:
Source: wp-admin/includes/dashboard.php:1619
Used by 0 functions | Uses 1 function

※213※

```
dashboard_php_nag_class()
```

Function: Adds an additional class to the PHP nag if the current version is insecure.
Source: wp-admin/includes/dashboard.php:1737
Used by 0 functions | Uses 1 function

※214※

```
date_i18n()
```

Function: Retrieves the date in localized format, based on a sum of Unix timestamp and timezone offset in seconds.
Source: wp-includes/functions.php:165
Used by 16 functions | Uses 5 functions

※215※

```
dbDelta()
```

Function: Modifies the database based on specified SQL statements.
Source: wp-admin/includes/upgrade.php:2547
Used by 4 functions | Uses 10 functions

※216※

```
deactivate_plugins()
```

Function: Deactivate a single plugin or multiple plugins.
Source: wp-admin/includes/plugin.php:734
Used by 2 functions | Uses 13 functions

※217※

```
deactivate_sitewide_plugin()
```

Function: Deprecated functionality for deactivating a network-only plugin.
Source: wp-admin/includes/ms-deprecated.php:68
Used by 0 functions | Uses 1 function

※218※

```
dead_db()
```

Function: Load custom DB error or display WordPress DB error.
Source: wp-includes/functions.php:4491
Used by 4 functions | Uses 4 functions

※219※

```
debug_fclose()
```

Function: Close the debugging file handle.
Source: wp-includes/deprecated.php:2874
Used by 0 functions | Uses 1 function

※220※

```
debug_fopen()
```

Function: Open the file handle for debugging.
Source: wp-includes/deprecated.php:2840
Used by 0 functions | Uses 1 function

※221※

```
debug_fwrite()
```

Function: Write contents to the file used for debugging.
Source: wp-includes/deprecated.php:2857
Used by 0 functions | Uses 1 function

※222※

```
default_password_nag()
```

Function:
Source: wp-admin/includes/user.php:510
Used by 0 functions | Uses 4 functions

※223※

```
default_password_nag_edit_user()
```

Function:
Source: wp-admin/includes/user.php:490
Used by 0 functions | Uses 4 functions

※224※

```
default_password_nag_handler()
```

Function:
Source: wp-admin/includes/user.php:470
Used by 0 functions | Uses 4 functions

※225※

```
default_topic_count_scale()
```

Function: Default topic count scaling for tag links.
Source: wp-includes/category-template.php:752
Used by 0 functions | Uses 0 functions

※226※

```
default_topic_count_text()
```

Function: Old callback for tag link tooltips.
Source: wp-includes/deprecated.php:3407
Used by 0 functions | Uses 0 functions

※227※

```
delete_all_user_settings()
```

Function: Delete the user settings of the current user.
Source: wp-includes/option.php:1126
Used by 0 functions | Uses 2 functions

※228※

```
delete_blog_option()
```

Function: Removes option by name for a given blog id. Prevents removal of protected WordPress options.
Source: wp-includes/ms-blogs.php:421
Used by 0 functions | Uses 4 functions

※229※

```
delete_comment_meta()
```

Function: Remove metadata matching criteria from a comment.
Source: wp-includes/comment.php:475
Used by 5 functions | Uses 1 function

※230※

```
delete_expired_transients()
```

Function: Deletes all expired transients.
Source: wp-includes/option.php:860
Used by 2 functions | Uses 7 functions

※231※

```
delete_get_calendar_cache()
```

Function: Purge the cached results of get_calendar.
Source: wp-includes/general-template.php:2287
Used by 0 functions | Uses 1 function

※232※

```
delete_meta()
```

Function: Delete post meta data by meta ID.
Source: wp-admin/includes/post.php:939
Used by 2 functions | Uses 1 function

※233※

```
delete_metadata()
```

Function: Delete metadata for the specified object.
Source: wp-includes/meta.php:330
Used by 13 functions | Uses 16 functions

※234※

```
delete_metadata_by_mid()
```

Function: Delete meta data by meta ID
Source: wp-includes/meta.php:779
Used by 11 functions | Uses 12 functions

※235※

```
delete_network_option()
```

Function: Removes a network option by name.
Source: wp-includes/option.php:1471
Used by 2 functions | Uses 11 functions

※236※

```
delete_option()
```

Function: Removes option by name. Prevents removal of protected WordPress options.
Source: wp-includes/option.php:558
Used by 23 functions | Uses 12 functions

※237※

```
delete_plugins()
```

Function: Remove directory and files of a plugin for a list of plugins.
Source: wp-admin/includes/plugin.php:879
Used by 1 function | Uses 15 functions

※238※

```
delete_post_meta()
```

Function: Deletes a post meta field for the given post ID.
Source: wp-includes/post.php:2086
Used by 22 functions | Uses 2 functions

※239※

```
delete_post_meta_by_key()
```

Function: Deletes everything from post meta matching the given meta key.
Source: wp-includes/post.php:2150
Used by 0 functions | Uses 1 function

※240※

```
delete_post_thumbnail()
```

Function: Removes the thumbnail (featured image) from the given post.
Source: wp-includes/post.php:6919
Used by 5 functions | Uses 2 functions

※241※

```
delete_site_meta()
```

Function: Removes metadata matching criteria from a site.
Source: wp-includes/ms-site.php:1067
Used by 0 functions | Uses 1 function

※242※

```
delete_site_meta_by_key()
```

Function: Deletes everything from site meta matching meta key.
Source: wp-includes/ms-site.php:1117
Used by 0 functions | Uses 1 function

※243※

```
delete_site_option()
```

Function: Removes a option by name for the current network.
Source: wp-includes/option.php:1183
Used by 4 functions | Uses 1 function

※244※

```
delete_site_transient()
```

Function: Delete a site transient.
Source: wp-includes/option.php:1690
Used by 7 functions | Uses 6 functions

※245※

```
delete_term_meta()
```

Function: Removes metadata matching criteria from a term.
Source: wp-includes/taxonomy.php:1235
Used by 0 functions | Uses 1 function

※246※

```
delete_theme()
```

Function: Remove a theme
Source: wp-admin/includes/theme.php:21
Used by 1 function | Uses 11 functions

※247※

```
delete_transient()
```

Function: Delete a transient.
Source: wp-includes/option.php:629
Used by 8 functions | Uses 6 functions

※248※

```
delete_usermeta()
```

Function: Remove user meta data.
Source: wp-includes/deprecated.php:2220
Used by 1 function | Uses 7 functions

※249※

```
delete_users_add_js()
```

Function:
Source: wp-admin/includes/user.php:531
Used by 0 functions | Uses 0 functions

※250※

```
delete_user_meta()
```

Function: Remove metadata matching criteria from a user.
Source: wp-includes/user.php:811
Used by 4 functions | Uses 1 function

※251※

```
delete_user_option()
```

Function: Delete user option with global blog capability.
Source: wp-includes/user.php:553
Used by 1 function | Uses 2 functions

※252※

```
delete_user_setting()
```

Function: Delete user interface settings.
Source: wp-includes/option.php:1014
Used by 2 functions | Uses 2 functions

※253※

```
deslash()
```

Function: Filters for content to remove unnecessary slashes.
Source: wp-admin/includes/upgrade.php:2510
Used by 0 functions | Uses 0 functions

※254※

```
determine_locale()
```

Function: Determine the current locale desired for the request.
Source: wp-includes/l10n.php:121
Used by 10 functions | Uses 8 functions

※255※

```
did_action()
```

Function: Retrieve the number of times an action is fired.
Source: wp-includes/plugin.php:493
Used by 36 functions | Uses 0 functions

※256※

```
disabled()
```

Function: Outputs the html disabled attribute.
Source: wp-includes/general-template.php:4678
Used by 6 functions | Uses 1 function

※257※

```
discover_pingback_server_uri()
```

Function: Finds a pingback server URI based on the given URL.
Source: wp-includes/comment.php:2568
Used by 1 function | Uses 7 functions

※258※

```
dismissed_updates()
```

Function: Display dismissed updates.
Source: wp-admin/update-core.php:179
Used by 1 function | Uses 4 functions

※259※

```
dismiss_core_update()
```

Function:
Source: wp-admin/includes/update.php:162
Used by 1 function | Uses 2 functions

※260※

```
display_header()
```

Function: Display installation header.
Source: wp-admin/install.php:58
Used by 0 functions | Uses 6 functions

※261※

```
display_header_text()
```

Function: Whether to display the header text.
Source: wp-includes/theme.php:1047
Used by 2 functions | Uses 3 functions

※262※

```
display_plugins_table()
```

Function: Display plugin content based on plugin list.
Source: wp-admin/includes/plugin-install.php:390
Used by 1 function | Uses 4 functions

※263※

```
display_setup_form()
```

Function: Display installer setup form.
Source: wp-admin/install.php:91
Used by 0 functions | Uses 16 functions

※264※

```
display_space_usage()
```

Function: Displays the amount of disk space used by the current site. Not used in core.
Source: wp-admin/includes/ms.php:246
Used by 0 functions | Uses 4 functions

※265※

```
display_theme()
```

Function: Prints a theme on the Install Themes pages.
Source: wp-admin/includes/theme-install.php:201
Used by 0 functions | Uses 4 functions

※266※

```
display_themes()
```

Function: Display theme content based on theme list.
Source: wp-admin/includes/theme-install.php:218
Used by 0 functions | Uses 3 functions

※267※

```
documentation_link()
```

Function: Unused Admin function.
Source: wp-admin/includes/deprecated.php:33
Used by 0 functions | Uses 1 function

※268※

```
doing_action()
```

Function: Retrieve the name of an action currently being processed.
Source: wp-includes/plugin.php:379
Used by 2 functions | Uses 1 function

※269※

```
doing_filter()
```

Function: Retrieve the name of a filter currently being processed.
Source: wp-includes/plugin.php:360
Used by 2 functions | Uses 0 functions

※270※

```
dolly_css()
```

Function:
Source: wp-content/plugins/hello.php:63
Used by 0 functions | Uses 0 functions

※271※

```
domain_exists()
```

Function: Checks whether a site name is already taken.
Source: wp-includes/ms-functions.php:1487
Used by 4 functions | Uses 4 functions

※272※

```
download_url()
```

Function: Downloads a URL to a local temporary file using the WordPress HTTP API.
Source: wp-admin/includes/file.php:997
Used by 2 functions | Uses 16 functions

※273※

```
do_accordion_sections()
```

Function: Meta Box Accordion Template Function.
Source: wp-admin/includes/template.php:1425
Used by 0 functions | Uses 8 functions

※274※

```
do_action()
```

Function: Execute functions hooked on a specific action hook.
Source: wp-includes/plugin.php:444
Used by 372 functions | Uses 1 function

※275※

```
do_action_deprecated()
```

Function: Fires functions attached to a deprecated action hook.
Source: wp-includes/plugin.php:653
Used by 4 functions | Uses 3 functions

※276※

```
do_action_ref_array()
```

Function: Calls the callback functions that have been added to an action hook, specifying arguments in an array.
Source: wp-includes/plugin.php:517
Used by 29 functions | Uses 1 function

※277※

```
do_activate_header()
```

Function: Adds an action hook specific to this page.
Source: wp-activate.php:88
Used by 0 functions | Uses 2 functions

※278※

```
do_all_pings()
```

Function: Perform all pingbacks, enclosures, trackbacks, and send to pingback services.
Source: wp-includes/comment.php:2652
Used by 0 functions | Uses 7 functions

※279※

```
do_blocks()
```

Function: Parses dynamic blocks out of `post_content` and re-renders them.
Source: wp-includes/blocks.php:308
Used by 0 functions | Uses 7 functions

※280※

```
do_block_editor_incompatible_meta_box()
```

Function: Function that renders a “fake” meta box with an information message, shown on the block editor, when an incompatible meta box is found.
Source: wp-admin/includes/template.php:1122
Used by 0 functions | Uses 12 functions

※281※

```
do_core_upgrade()
```

Function: Upgrade WordPress core display.
Source: wp-admin/update-core.php:555
Used by 0 functions | Uses 11 functions

※282※

```
do_dismiss_core_update()
```

Function:
Source: wp-admin/update-core.php:657
Used by 0 functions | Uses 4 functions

※283※

```
do_enclose()
```

Function: Check content for video and audio links to add as enclosures.
Source: wp-includes/functions.php:811
Used by 1 function | Uses 13 functions

※284※

```
do_feed()
```

Function: Load the feed template from the use of an action hook.
Source: wp-includes/functions.php:1510
Used by 0 functions | Uses 7 functions

※285※

```
do_feed_atom()
```

Function: Load either Atom comment feed or Atom posts feed.
Source: wp-includes/functions.php:1589
Used by 0 functions | Uses 1 function

※286※

```
do_feed_rdf()
```

Function: Load the RDF RSS 0.91 Feed template.
Source: wp-includes/functions.php:1548
Used by 0 functions | Uses 1 function

※287※

```
do_feed_rss()
```

Function: Load the RSS 1.0 Feed Template.
Source: wp-includes/functions.php:1559
Used by 0 functions | Uses 1 function

※288※

```
do_feed_rss2()
```

Function: Load either the RSS2 comment feed or the RSS2 posts feed.
Source: wp-includes/functions.php:1572
Used by 0 functions | Uses 1 function

※289※

```
do_meta_boxes()
```

Function: Meta-Box template function.
Source: wp-admin/includes/template.php:1232
Used by 2 functions | Uses 9 functions

※290※

```
do_robots()
```

Function: Displays the default robots.txt file content.
Source: wp-includes/functions.php:1604
Used by 0 functions | Uses 6 functions

※291※

```
do_settings_fields()
```

Function: Print out the settings fields for a particular settings section.
Source: wp-admin/includes/template.php:1667
Used by 1 function | Uses 1 function

※292※

```
do_settings_sections()
```

Function: Prints out all settings sections added to a particular settings page
Source: wp-admin/includes/template.php:1628
Used by 0 functions | Uses 1 function

※293※

```
do_shortcode()
```

Function: Search content for shortcodes and filter shortcodes through their hooks.
Source: wp-includes/shortcodes.php:177
Used by 5 functions | Uses 3 functions

※294※

```
do_shortcodes_in_html_tags()
```

Function: Search only inside HTML elements for shortcodes and process them.
Source: wp-includes/shortcodes.php:355
Used by 2 functions | Uses 4 functions

※295※

```
do_shortcode_tag()
```

Function: Regular Expression callable for do_shortcode() for calling shortcode hook.
Source: wp-includes/shortcodes.php:287
Used by 1 function | Uses 6 functions

※296※

```
do_signup_header()
```

Function: Prints signup_header via wp_head
Source: wp-signup.php:22
Used by 0 functions | Uses 2 functions

※297※

```
do_trackbacks()
```

Function: Perform trackbacks.
Source: wp-includes/comment.php:2717
Used by 1 function | Uses 12 functions

※298※

```
do_undismiss_core_update()
```

Function: Undismiss a core update.
Source: wp-admin/update-core.php:674
Used by 0 functions | Uses 4 functions

※299※

```
dropdown_categories()
```

Function: Legacy function used to generate the categories checklist control.
Source: wp-admin/includes/deprecated.php:82
Used by 0 functions | Uses 2 functions

※300※

```
dropdown_cats()
```

Function: Deprecated method for generating a drop-down of categories.
Source: wp-includes/deprecated.php:677
Used by 0 functions | Uses 4 functions

※301※

```
dropdown_link_categories()
```

Function: Legacy function used to generate a link categories checklist control.
Source: wp-admin/includes/deprecated.php:97
Used by 0 functions | Uses 2 functions

※302※

```
drop_index()
```

Function: Drops a specified index from a table.
Source: wp-admin/includes/upgrade.php:2337
Used by 1 function | Uses 3 functions

※303※

```
dynamic_sidebar()
```

Function: Display dynamic sidebar.
Source: wp-includes/widgets.php:669
Used by 2 functions | Uses 9 functions

※304※

```
edit_bookmark_link()
```

Function: Displays the edit bookmark link anchor content.
Source: wp-includes/link-template.php:1585
Used by 0 functions | Uses 7 functions

※305※

```
edit_comment()
```

Function: Update a comment with values provided in $_POST.
Source: wp-admin/includes/comment.php:50
Used by 1 function | Uses 4 functions

※306※

```
edit_comment_link()
```

Function: Displays the edit comment link with formatting.
Source: wp-includes/link-template.php:1522
Used by 3 functions | Uses 7 functions

※307※

```
edit_form_image_editor()
```

Function: Displays the image and editor in the post editor
Source: wp-admin/includes/media.php:3052
Used by 0 functions | Uses 23 functions

※308※

```
edit_link()
```

Function: Updates or inserts a link using values provided in $_POST.
Source: wp-admin/includes/bookmark.php:28
Used by 1 function | Uses 7 functions

※309※

```
edit_post()
```

Function: Update an existing post with values provided in $_POST.
Source: wp-admin/includes/post.php:229
Used by 6 functions | Uses 40 functions

※310※

```
edit_post_link()
```

Function: Displays the edit post link for post.
Source: wp-includes/link-template.php:1410
Used by 0 functions | Uses 7 functions

※311※

```
edit_tag_link()
```

Function: Displays or retrieves the edit link for a tag with formatting.
Source: wp-includes/link-template.php:967
Used by 0 functions | Uses 3 functions

※312※

```
edit_term_link()
```

Function: Displays or retrieves the edit term link with formatting.
Source: wp-includes/link-template.php:1047
Used by 1 function | Uses 7 functions

※313※

```
edit_user()
```

Function: Edit user settings based on contents of $_POST
Source: wp-admin/includes/user.php:30
Used by 2 functions | Uses 30 functions

※314※

```
email_exists()
```

Function: Determines whether the given email exists.
Source: wp-includes/user.php:1428
Used by 6 functions | Uses 1 function

※315※

```
endElement()
```

Function: XML callback function that is called at the end of a XML tag.
Source: wp-admin/link-parse-opml.php:71
Used by 0 functions | Uses 0 functions

※316※

```
enqueue_block_styles_assets()
```

Function: Function responsible for enqueuing the styles required for block styles functionality on the editor and on the frontend.
Source: wp-includes/script-loader.php:2898
Used by 0 functions | Uses 3 functions

※317※

```
enqueue_comment_hotkeys_js()
```

Function:
Source: wp-admin/includes/comment.php:198
Used by 0 functions | Uses 2 functions

※318※

```
enqueue_editor_block_styles_assets()
```

Function: Function responsible for enqueuing the assets required for block styles functionality on the editor.
Source: wp-includes/script-loader.php:2918
Used by 0 functions | Uses 5 functions

※319※

```
enqueue_embed_scripts()
```

Function: Enqueue embed iframe default CSS and JS & fire do_action(‘enqueue_embed_scripts’)
Source: wp-includes/embed.php:986
Used by 0 functions | Uses 3 functions

※320※

```
ent2ncr()
```

Function: Converts named entities into numbered entities.
Source: wp-includes/formatting.php:3895
Used by 0 functions | Uses 2 functions

※321※

```
esc_attr()
```

Function: Escaping for HTML attributes.
Source: wp-includes/formatting.php:4465
Used by 272 functions | Uses 4 functions

※322※

```
esc_attr_e()
```

Function: Display translated text that has been escaped for safe use in an attribute.
Source: wp-includes/l10n.php:313
Used by 48 functions | Uses 2 functions

※323※

```
esc_attr_x()
```

Function: Translate string with gettext context, and escapes it for safe use in an attribute.
Source: wp-includes/l10n.php:377
Used by 5 functions | Uses 2 functions

※324※

```
esc_attr__()
```

Function: Retrieve the translation of $text and escapes it for safe use in an attribute.
Source: wp-includes/l10n.php:270
Used by 23 functions | Uses 2 functions

※325※

```
esc_html()
```

Function: Escaping for HTML blocks.
Source: wp-includes/formatting.php:4440
Used by 161 functions | Uses 4 functions

※326※

```
esc_html_e()
```

Function: Display translated text that has been escaped for safe use in HTML output.
Source: wp-includes/l10n.php:326
Used by 16 functions | Uses 2 functions

※327※

```
esc_html_x()
```

Function: Translate string with gettext context, and escapes it for safe use in HTML output.
Source: wp-includes/l10n.php:392
Used by 0 functions | Uses 2 functions

※328※

```
esc_html__()
```

Function: Retrieve the translation of $text and escapes it for safe use in HTML output.
Source: wp-includes/l10n.php:287
Used by 3 functions | Uses 2 functions

※329※

```
esc_js()
```

Function: Escape single quotes, htmlspecialchar ” &, and fix line endings.
Source: wp-includes/formatting.php:4412
Used by 18 functions | Uses 4 functions

※330※

```
esc_sql()
```

Function: Escapes data for use in a MySQL query.
Source: wp-includes/formatting.php:4254
Used by 9 functions | Uses 1 function

※331※

```
esc_textarea()
```

Function: Escaping for textarea values.
Source: wp-includes/formatting.php:4490
Used by 9 functions | Uses 3 functions

※332※

```
esc_url()
```

Function: Checks and cleans a URL.
Source: wp-includes/formatting.php:4274
Used by 269 functions | Uses 8 functions

※333※

```
esc_url_raw()
```

Function: Performs esc_url() for database usage.
Source: wp-includes/formatting.php:4380
Used by 43 functions | Uses 1 function

※334※

```
excerpt_remove_blocks()
```

Function: Parses blocks out of a content string, and renders those appropriate for the excerpt.
Source: wp-includes/blocks.php:127
Used by 1 function | Uses 5 functions

※335※

```
export_add_js()
```

Function: Display JavaScript on the page.
Source: wp-admin/export.php:25
Used by 0 functions | Uses 0 functions

※336※

```
export_date_options()
```

Function: Create the date options fields for exporting a given post type.
Source: wp-admin/export.php:137
Used by 0 functions | Uses 4 functions

※337※

```
export_wp()
```

Function: Generates the WXR export file for download.
Source: wp-admin/includes/export.php:56
Used by 0 functions | Uses 50 functions

※338※

```
extract_from_markers()
```

Function: Extracts strings from between the BEGIN and END markers in the .htaccess file.
Source: wp-admin/includes/misc.php:67
Used by 0 functions | Uses 0 functions

※339※

```
favorite_actions()
```

Function: Favorite actions were deprecated in version 3.2. Use the admin bar instead.
Source: wp-admin/includes/deprecated.php:868
Used by 0 functions | Uses 1 function

※340※

```
feed_content_type()
```

Function: Return the content type for specified feed type.
Source: wp-includes/feed.php:706
Used by 3 functions | Uses 3 functions

※341※

```
feed_links()
```

Function: Display the links to the general feeds.
Source: wp-includes/general-template.php:2921
Used by 0 functions | Uses 13 functions

※342※

```
feed_links_extra()
```

Function: Display the links to the extra feeds such as category feeds.
Source: wp-includes/general-template.php:2967
Used by 0 functions | Uses 32 functions

※343※

```
fetch_feed()
```

Function: Build SimplePie object based on RSS or Atom feed from URL.
Source: wp-includes/feed.php:743
Used by 5 functions | Uses 6 functions

※344※

```
fetch_rss()
```

Function: Build Magpie object based on RSS from URL.
Source: wp-includes/rss.php:412
Used by 2 functions | Uses 5 functions

※345※

```
file_is_displayable_image()
```

Function: Validate that file is suitable for displaying within a web page.
Source: wp-admin/includes/image.php:869
Used by 1 function | Uses 2 functions

※346※

```
file_is_valid_image()
```

Function: Validate that file is an image.
Source: wp-admin/includes/image.php:856
Used by 0 functions | Uses 0 functions

※347※

```
filter_default_option()
```

Function: Filter the default value for the option.
Source: wp-includes/option.php:2288
Used by 0 functions | Uses 1 function

※348※

```
filter_SSL()
```

Function: Formats a URL to use https.
Source: wp-includes/ms-functions.php:2288
Used by 0 functions | Uses 4 functions

※349※

```
find_core_auto_update()
```

Function: Gets the best available (and enabled) Auto-Update for WordPress Core.
Source: wp-admin/includes/update.php:83
Used by 1 function | Uses 1 function

※350※

```
find_core_update()
```

Function:
Source: wp-admin/includes/update.php:190
Used by 3 functions | Uses 1 function

※351※

```
find_posts_div()
```

Function: Outputs the modal window used for attaching media to posts or pages in the media-listing screen.
Source: wp-admin/includes/template.php:1866
Used by 0 functions | Uses 6 functions

※352※

```
fix_import_form_size()
```

Function: Get the remaining upload space for this site.
Source: wp-admin/includes/ms.php:271
Used by 0 functions | Uses 2 functions

※353※

```
fix_phpmailer_messageid()
```

Function: Correct From host on outgoing mail to match the site domain
Source: wp-includes/ms-functions.php:2173
Used by 0 functions | Uses 1 function

※354※

```
floated_admin_avatar()
```

Function: Add avatars to relevant places in admin, or try to.
Source: wp-admin/includes/comment.php:190
Used by 0 functions | Uses 2 functions

※355※

```
flush_rewrite_rules()
```

Function: Remove rewrite rules and then recreate rewrite rules.
Source: wp-includes/rewrite.php:274
Used by 4 functions | Uses 1 function

※356※

```
force_balance_tags()
```

Function: Balances tags of string using a modified stack.
Source: wp-includes/formatting.php:2459
Used by 2 functions | Uses 0 functions

※357※

```
force_ssl_admin()
```

Function: Whether to force SSL used for the Administration Screens.
Source: wp-includes/functions.php:5056
Used by 5 functions | Uses 0 functions

※358※

```
force_ssl_content()
```

Function: Whether to force SSL on content.
Source: wp-includes/ms-functions.php:2266
Used by 1 function | Uses 0 functions

※359※

```
force_ssl_login()
```

Function: Whether SSL login should be forced.
Source: wp-includes/deprecated.php:3701
Used by 0 functions | Uses 2 functions

※360※

```
format_code_lang()
```

Function: Returns the language for a language code.
Source: wp-admin/includes/ms.php:336
Used by 1 function | Uses 2 functions

※361※

```
format_for_editor()
```

Function: Formats text for the editor.
Source: wp-includes/formatting.php:4192
Used by 0 functions | Uses 3 functions

※362※

```
format_to_edit()
```

Function: Acts on text which is about to be edited.
Source: wp-includes/formatting.php:2620
Used by 2 functions | Uses 3 functions

※363※

```
format_to_post()
```

Function: Formerly used to escape strings before inserting into the DB.
Source: wp-includes/deprecated.php:3422
Used by 0 functions | Uses 1 function

※364※

```
form_option()
```

Function: Print option value after sanitizing for forms.
Source: wp-includes/option.php:184
Used by 0 functions | Uses 2 functions

※365※

```
funky_javascript_callback()
```

Function: Callback used to change %uXXXX to &#YYY; syntax
Source: wp-includes/deprecated.php:2448
Used by 0 functions | Uses 0 functions

※366※

```
funky_javascript_fix()
```

Function: Fixes JavaScript bugs in browsers.
Source: wp-includes/deprecated.php:2466
Used by 0 functions | Uses 1 function

※367※

```
gallery_shortcode()
```

Function: Builds the Gallery shortcode output.
Source: wp-includes/media.php:1802
Used by 1 function | Uses 18 functions

※368※

```
gd_edit_image_support()
```

Function: Check if the installed version of GD supports particular image type
Source: wp-includes/deprecated.php:3308
Used by 0 functions | Uses 1 function

※369※

```
generate_postdata()
```

Function: Generates post data.
Source: wp-includes/query.php:1155
Used by 1 function | Uses 1 function

※370※

```
generate_random_password()
```

Function: Generates a random password.
Source: wp-includes/ms-deprecated.php:44
Used by 0 functions | Uses 2 functions

※371※

```
generic_ping()
```

Function: Sends pings to all of the ping site services.
Source: wp-includes/comment.php:2774
Used by 1 function | Uses 2 functions

※372※

```
get_404_template()
```

Function: Retrieve path of 404 template in current or parent template.
Source: wp-includes/template.php:94
Used by 0 functions | Uses 1 function

※373※

```
get_active_blog_for_user()
```

Function: Get one of a user’s active blogs
Source: wp-includes/ms-functions.php:40
Used by 3 functions | Uses 9 functions

※374※

```
get_adjacent_post()
```

Function: Retrieves the adjacent post.
Source: wp-includes/link-template.php:1697
Used by 4 functions | Uses 21 functions

※375※

```
get_adjacent_post_link()
```

Function: Retrieves the adjacent post link.
Source: wp-includes/link-template.php:2147
Used by 3 functions | Uses 10 functions

※376※

```
get_adjacent_post_rel_link()
```

Function: Retrieves the adjacent post relational link.
Source: wp-includes/link-template.php:1890
Used by 3 functions | Uses 11 functions

※377※

```
get_admin_page_parent()
```

Function:
Source: wp-admin/includes/plugin.php:1808
Used by 3 functions | Uses 0 functions

※378※

```
get_admin_page_title()
```

Function:
Source: wp-admin/includes/plugin.php:1880
Used by 0 functions | Uses 2 functions

※379※

```
get_admin_url()
```

Function: Retrieves the URL to the admin area for a given site.
Source: wp-includes/link-template.php:3295
Used by 7 functions | Uses 3 functions

※380※

```
get_admin_users_for_domain()
```

Function: Get the admin for a domain/path combination.
Source: wp-includes/ms-deprecated.php:432
Used by 0 functions | Uses 5 functions

※381※

```
get_alloptions()
```

Function: Retrieve all autoload options, or all options if no autoloaded ones exist.
Source: wp-includes/deprecated.php:1828
Used by 0 functions | Uses 2 functions

※382※

```
get_alloptions_110()
```

Function: Retrieve all options as it was for 1.2.
Source: wp-admin/includes/upgrade.php:2451
Used by 0 functions | Uses 2 functions

※383※

```
get_allowed_http_origins()
```

Function: Retrieve list of allowed HTTP origins.
Source: wp-includes/http.php:416
Used by 1 function | Uses 4 functions

※384※

```
get_allowed_mime_types()
```

Function: Retrieve list of allowed mime types and file extensions.
Source: wp-includes/functions.php:3028
Used by 6 functions | Uses 5 functions

※385※

```
get_allowed_themes()
```

Function: Get the allowed themes for the current site.
Source: wp-admin/includes/deprecated.php:1006
Used by 0 functions | Uses 2 functions

※386※

```
get_all_category_ids()
```

Function: Retrieves all category IDs.
Source: wp-includes/deprecated.php:1286
Used by 1 function | Uses 4 functions

※387※

```
get_all_page_ids()
```

Function: Get a list of page IDs.
Source: wp-includes/post.php:4839
Used by 0 functions | Uses 3 functions

※388※

```
get_all_post_type_supports()
```

Function: Get all the post type features
Source: wp-includes/post.php:1881
Used by 2 functions | Uses 0 functions

※389※

```
get_all_user_settings()
```

Function: Retrieve all user interface settings.
Source: wp-includes/option.php:1046
Used by 3 functions | Uses 2 functions

※390※

```
get_ancestors()
```

Function: Get an array of ancestor IDs for a given object.
Source: wp-includes/taxonomy.php:4497
Used by 4 functions | Uses 7 functions

※391※

```
get_approved_comments()
```

Function: Retrieve the approved comments for post $post_id.
Source: wp-includes/comment.php:162
Used by 0 functions | Uses 2 functions

※392※

```
get_archives()
```

Function: Retrieves a list of archives.
Source: wp-includes/deprecated.php:767
Used by 0 functions | Uses 2 functions

※393※

```
get_archives_link()
```

Function: Retrieve archive link content based on predefined or custom code.
Source: wp-includes/general-template.php:1737
Used by 1 function | Uses 5 functions

※394※

```
get_archive_template()
```

Function: Retrieve path of archive template in current or parent template.
Source: wp-includes/template.php:110
Used by 1 function | Uses 2 functions

※395※

```
get_attached_file()
```

Function: Retrieve attached file path based on attachment ID.
Source: wp-includes/post.php:495
Used by 24 functions | Uses 4 functions

※396※

```
get_attached_media()
```

Function: Retrieves media attached to the passed post.
Source: wp-includes/media.php:3993
Used by 2 functions | Uses 5 functions

※397※

```
get_attachment_fields_to_edit()
```

Function: Retrieves the attachment fields to edit form fields.
Source: wp-admin/includes/media.php:1344
Used by 1 function | Uses 18 functions

※398※

```
get_attachment_icon()
```

Function: Retrieve HTML content of icon attachment image element.
Source: wp-includes/deprecated.php:1916
Used by 1 function | Uses 5 functions

※399※

```
get_attachment_icon_src()
```

Function: Retrieve icon URL and Path.
Source: wp-includes/deprecated.php:1874
Used by 1 function | Uses 11 functions

※400※

```
get_attachment_innerHTML()
```

Function: Retrieve HTML content of image element.
Source: wp-includes/deprecated.php:1972
Used by 1 function | Uses 5 functions

※401※

```
get_attachment_link()
```

Function: Retrieves the permalink for an attachment.
Source: wp-includes/link-template.php:410
Used by 11 functions | Uses 11 functions

※402※

```
get_attachment_taxonomies()
```

Function: Retrieves taxonomies attached to given the attachment.
Source: wp-includes/media.php:3016
Used by 5 functions | Uses 4 functions

※403※

```
get_attachment_template()
```

Function: Retrieve path of attachment template in current or parent template.
Source: wp-includes/template.php:616
Used by 0 functions | Uses 2 functions

※404※

```
get_author_feed_link()
```

Function: Retrieves the feed link for a given author.
Source: wp-includes/link-template.php:786
Used by 3 functions | Uses 8 functions

※405※

```
get_author_link()
```

Function: Returns or Prints link to the author’s posts.
Source: wp-includes/deprecated.php:785
Used by 0 functions | Uses 2 functions

※406※

```
get_author_name()
```

Function: Retrieve the specified author’s preferred display name.
Source: wp-includes/deprecated.php:1573
Used by 0 functions | Uses 2 functions

※407※

```
get_author_posts_url()
```

Function: Retrieve the URL to the author page for the user with the ID provided.
Source: wp-includes/author-template.php:343
Used by 9 functions | Uses 6 functions

※408※

```
get_author_rss_link()
```

Function: Print/Return link to author RSS feed.
Source: wp-includes/deprecated.php:1156
Used by 0 functions | Uses 2 functions

※409※

```
get_author_template()
```

Function: Retrieve path of author template in current or parent template.
Source: wp-includes/template.php:174
Used by 0 functions | Uses 2 functions

※410※

```
get_author_user_ids()
```

Function: Get all user IDs.
Source: wp-admin/includes/deprecated.php:229
Used by 0 functions | Uses 5 functions

※411※

```
get_autotoggle()
```

Function: Gets the auto_toggle setting.
Source: wp-includes/deprecated.php:583
Used by 0 functions | Uses 1 function

※412※

```
get_available_languages()
```

Function: Get all available languages based on the presence of *.mo files in a given directory.
Source: wp-includes/l10n.php:1287
Used by 9 functions | Uses 2 functions

※413※

```
get_available_post_mime_types()
```

Function: Get all available post MIME types for a given post type.
Source: wp-includes/post.php:7139
Used by 1 function | Uses 2 functions

※414※

```
get_available_post_statuses()
```

Function: Get all the possible statuses for a post_type
Source: wp-admin/includes/post.php:1088
Used by 1 function | Uses 1 function

※415※

```
get_avatar()
```

Function: Retrieve the avatar `` tag for a user, email address, MD5 hash, comment, or post.
Source: wp-includes/pluggable.php:2571
Used by 15 functions | Uses 11 functions

※416※

```
get_avatar_data()
```

Function: Retrieves default data about the avatar.
Source: wp-includes/link-template.php:4077
Used by 3 functions | Uses 16 functions

※417※

```
get_avatar_url()
```

Function: Retrieves the avatar URL.
Source: wp-includes/link-template.php:4013
Used by 3 functions | Uses 1 function

※418※

```
get_background_color()
```

Function: Retrieve value for custom background color.
Source: wp-includes/theme.php:1622
Used by 4 functions | Uses 2 functions

※419※

```
get_background_image()
```

Function: Retrieve background image for custom background.
Source: wp-includes/theme.php:1602
Used by 6 functions | Uses 2 functions

※420※

```
get_block_categories()
```

Function: Returns all the block categories that will be shown in the block editor.
Source: wp-admin/includes/post.php:2146
Used by 0 functions | Uses 3 functions

※421※

```
get_block_editor_server_block_settings()
```

Function: Prepares server-registered blocks for the block editor.
Source: wp-admin/includes/post.php:2201
Used by 0 functions | Uses 1 function

※422※

```
get_blogaddress_by_domain()
```

Function: Get a full blog URL, given a domain and a path.
Source: wp-includes/ms-deprecated.php:365
Used by 0 functions | Uses 3 functions

※423※

```
get_blogaddress_by_id()
```

Function: Get a full blog URL, given a blog id.
Source: wp-includes/ms-blogs.php:41
Used by 2 functions | Uses 2 functions

※424※

```
get_blogaddress_by_name()
```

Function: Get a full blog URL, given a blog name.
Source: wp-includes/ms-blogs.php:62
Used by 0 functions | Uses 3 functions

※425※

```
get_bloginfo()
```

Function: Retrieves information about the current site.
Source: wp-includes/general-template.php:703
Used by 69 functions | Uses 14 functions

※426※

```
get_bloginfo_rss()
```

Function: RSS container for the bloginfo function.
Source: wp-includes/feed.php:26
Used by 5 functions | Uses 4 functions

※427※

```
get_blogs_of_user()
```

Function: Get the sites a user belongs to.
Source: wp-includes/user.php:597
Used by 13 functions | Uses 8 functions

※428※

```
get_blog_count()
```

Function: The number of active sites on your installation.
Source: wp-includes/ms-functions.php:125
Used by 5 functions | Uses 1 function

※429※

```
get_blog_details()
```

Function: Retrieve the details for a blog from the blogs table and blog options.
Source: wp-includes/ms-blogs.php:128
Used by 0 functions | Uses 15 functions

※430※

```
get_blog_id_from_url()
```

Function: Get a blog’s numeric ID from its URL.
Source: wp-includes/ms-functions.php:339
Used by 0 functions | Uses 3 functions

※431※

```
get_blog_list()
```

Function: Deprecated functionality to retrieve a list of all sites.
Source: wp-includes/ms-deprecated.php:186
Used by 1 function | Uses 6 functions

※432※

```
get_blog_option()
```

Function: Retrieve option value for a given blog id based on name of option.
Source: wp-includes/ms-blogs.php:347
Used by 5 functions | Uses 6 functions

※433※

```
get_blog_permalink()
```

Function: Get the permalink for a post on another blog.
Source: wp-includes/ms-functions.php:315
Used by 0 functions | Uses 3 functions

※434※

```
get_blog_post()
```

Function: Get a blog post from any site on the network.
Source: wp-includes/ms-functions.php:138
Used by 0 functions | Uses 3 functions

※435※

```
get_blog_status()
```

Function: Get a blog details field.
Source: wp-includes/ms-blogs.php:732
Used by 1 function | Uses 3 functions

※436※

```
get_body_class()
```

Function: Retrieves an array of the class names for the body element.
Source: wp-includes/post-template.php:604
Used by 1 function | Uses 40 functions

※437※

```
get_bookmark()
```

Function: Retrieve Bookmark data
Source: wp-includes/bookmark.php:22
Used by 7 functions | Uses 6 functions

※438※

```
get_bookmarks()
```

Function: Retrieves the list of bookmarks
Source: wp-includes/bookmark.php:134
Used by 4 functions | Uses 10 functions

※439※

```
get_bookmark_field()
```

Function: Retrieve single bookmark data item or field.
Source: wp-includes/bookmark.php:76
Used by 0 functions | Uses 3 functions

※440※

```
get_boundary_post()
```

Function: Retrieves the boundary post.
Source: wp-includes/link-template.php:2017
Used by 1 function | Uses 6 functions

※441※

```
get_boundary_post_rel_link()
```

Function: Get boundary post relational link.
Source: wp-includes/deprecated.php:2672
Used by 1 function | Uses 9 functions

※442※

```
get_broken_themes()
```

Function: Retrieves a list of broken themes.
Source: wp-admin/includes/deprecated.php:1028
Used by 0 functions | Uses 2 functions

※443※

```
get_calendar()
```

Function: Display calendar with days that have posts as links.
Source: wp-includes/general-template.php:2061
Used by 1 function | Uses 21 functions

※444※

```
get_cancel_comment_reply_link()
```

Function: Retrieve HTML content for cancel comment reply link.
Source: wp-includes/comment-template.php:1842
Used by 1 function | Uses 5 functions

※445※

```
get_categories()
```

Function: Retrieve list of category objects.
Source: wp-includes/category.php:26
Used by 7 functions | Uses 8 functions

※446※

```
get_category()
```

Function: Retrieves category data given a category ID or category object.
Source: wp-includes/category.php:92
Used by 2 functions | Uses 3 functions

※447※

```
get_category_by_path()
```

Function: Retrieve category based on URL containing the category slug.
Source: wp-includes/category.php:124
Used by 1 function | Uses 5 functions

※448※

```
get_category_by_slug()
```

Function: Retrieve category object by category slug.
Source: wp-includes/category.php:181
Used by 0 functions | Uses 2 functions

※449※

```
get_category_children()
```

Function: Retrieve category children list separated before and after the term IDs.
Source: wp-includes/deprecated.php:1251
Used by 1 function | Uses 5 functions

※450※

```
get_category_feed_link()
```

Function: Retrieves the feed link for a category.
Source: wp-includes/link-template.php:833
Used by 3 functions | Uses 1 function

※451※

```
get_category_link()
```

Function: Retrieve category link URL.
Source: wp-includes/category-template.php:19
Used by 3 functions | Uses 2 functions

※452※

```
get_category_parents()
```

Function: Retrieve category parents with separator.
Source: wp-includes/category-template.php:46
Used by 2 functions | Uses 2 functions

※453※

```
get_category_rss_link()
```

Function: Print/Return link to category RSS2 feed.
Source: wp-includes/deprecated.php:1135
Used by 0 functions | Uses 2 functions

※454※

```
get_category_template()
```

Function: Retrieve path of category template in current or parent template.
Source: wp-includes/template.php:214
Used by 0 functions | Uses 2 functions

※455※

```
get_category_to_edit()
```

Function: Get category object for given ID and ‘edit’ filter context.
Source: wp-admin/includes/taxonomy.php:40
Used by 0 functions | Uses 2 functions

※456※

```
get_catname()
```

Function: Retrieve the category name by the category ID.
Source: wp-includes/deprecated.php:1233
Used by 0 functions | Uses 2 functions

※457※

```
get_cat_ID()
```

Function: Retrieve the ID of a category from its name.
Source: wp-includes/category.php:198
Used by 2 functions | Uses 1 function

※458※

```
get_cat_name()
```

Function: Retrieve the name of a category from its ID.
Source: wp-includes/category.php:214
Used by 5 functions | Uses 2 functions

※459※

```
get_children()
```

Function: Retrieve all children of the post parent ID.
Source: wp-includes/post.php:638
Used by 6 functions | Uses 3 functions

※460※

```
get_clean_basedomain()
```

Function: Get base domain of network.
Source: wp-admin/includes/network.php:84
Used by 2 functions | Uses 2 functions

※461※

```
get_cli_args()
```

Function: Returns value of command line params.
Source: wp-admin/includes/class-wp-importer.php:283
Used by 0 functions | Uses 0 functions

※462※

```
get_column_headers()
```

Function: Get the column headers for a screen
Source: wp-admin/includes/screen.php:19
Used by 5 functions | Uses 3 functions

※463※

```
get_comment()
```

Function: Retrieves comment data given a comment ID or comment object.
Source: wp-includes/comment.php:194
Used by 66 functions | Uses 4 functions

※464※

```
get_commentdata()
```

Function: Retrieve an array of comment data about comment $comment_ID.
Source: wp-includes/deprecated.php:1218
Used by 0 functions | Uses 2 functions

※465※

```
get_comments()
```

Function: Retrieve a list of comments.
Source: wp-includes/comment.php:241
Used by 11 functions | Uses 1 function

※466※

```
get_comments_link()
```

Function: Retrieves the link to the current post comments.
Source: wp-includes/comment-template.php:805
Used by 2 functions | Uses 4 functions

※467※

```
get_comments_number()
```

Function: Retrieves the amount of comments a post has.
Source: wp-includes/comment-template.php:847
Used by 5 functions | Uses 3 functions

※468※

```
get_comments_number_text()
```

Function: Display the language string for the number of comments the current post has.
Source: wp-includes/comment-template.php:894
Used by 1 function | Uses 7 functions

※469※

```
get_comments_pagenum_link()
```

Function: Retrieves the comments page number link.
Source: wp-includes/link-template.php:2814
Used by 3 functions | Uses 8 functions

※470※

```
get_comments_popup_template()
```

Function: Retrieve path of comment popup template in current or parent template.
Source: wp-includes/deprecated.php:3714
Used by 0 functions | Uses 1 function

※471※

```
get_comment_author()
```

Function: Retrieve the author of the current comment.
Source: wp-includes/comment-template.php:24
Used by 5 functions | Uses 5 functions

※472※

```
get_comment_author_email()
```

Function: Retrieve the email of the author of the current comment.
Source: wp-includes/comment-template.php:86
Used by 1 function | Uses 3 functions

※473※

```
get_comment_author_email_link()
```

Function: Return the html email link to the author of the current comment.
Source: wp-includes/comment-template.php:178
Used by 1 function | Uses 5 functions

※474※

```
get_comment_author_IP()
```

Function: Retrieve the IP address of the author of the current comment.
Source: wp-includes/comment-template.php:267
Used by 2 functions | Uses 3 functions

※475※

```
get_comment_author_link()
```

Function: Retrieve the HTML link to the URL of the author of the current comment.
Source: wp-includes/comment-template.php:219
Used by 5 functions | Uses 5 functions

※476※

```
get_comment_author_rss()
```

Function: Retrieve the current comment author for use in the feeds.
Source: wp-includes/feed.php:324
Used by 1 function | Uses 3 functions

※477※

```
get_comment_author_url()
```

Function: Retrieve the url of the author of the current comment.
Source: wp-includes/comment-template.php:306
Used by 4 functions | Uses 4 functions

※478※

```
get_comment_author_url_link()
```

Function: Retrieves the HTML link of the url of the author of the current comment.
Source: wp-includes/comment-template.php:377
Used by 1 function | Uses 3 functions

※479※

```
get_comment_class()
```

Function: Returns the classes for the comment div as an array.
Source: wp-includes/comment-template.php:457
Used by 2 functions | Uses 6 functions

※480※

```
get_comment_count()
```

Function: The amount of comments in a post or total comments.
Source: wp-includes/comment.php:380
Used by 1 function | Uses 2 functions

※481※

```
get_comment_date()
```

Function: Retrieve the comment date of the current comment.
Source: wp-includes/comment-template.php:550
Used by 4 functions | Uses 5 functions

※482※

```
get_comment_excerpt()
```

Function: Retrieve the excerpt of the current comment.
Source: wp-includes/comment-template.php:595
Used by 1 function | Uses 6 functions

※483※

```
get_comment_guid()
```

Function: Retrieve the feed GUID for the current comment.
Source: wp-includes/feed.php:286
Used by 1 function | Uses 2 functions

※484※

```
get_comment_ID()
```

Function: Retrieve the comment id of the current comment.
Source: wp-includes/comment-template.php:658
Used by 2 functions | Uses 3 functions

※485※

```
get_comment_id_fields()
```

Function: Retrieve hidden input HTML for replying to comments.
Source: wp-includes/comment-template.php:1883
Used by 2 functions | Uses 3 functions

※486※

```
get_comment_link()
```

Function: Retrieve the link to a given comment.
Source: wp-includes/comment-template.php:707
Used by 12 functions | Uses 12 functions

※487※

```
get_comment_meta()
```

Function: Retrieve comment meta field for a comment.
Source: wp-includes/comment.php:491
Used by 3 functions | Uses 1 function

※488※

```
get_comment_pages_count()
```

Function: Calculate the total number of comment pages.
Source: wp-includes/comment.php:985
Used by 5 functions | Uses 3 functions

※489※

```
get_comment_reply_link()
```

Function: Retrieve HTML content for reply to comment link.
Source: wp-includes/comment-template.php:1627
Used by 1 function | Uses 15 functions

※490※

```
get_comment_statuses()
```

Function: Retrieve all of the WordPress supported comment statuses.
Source: wp-includes/comment.php:256
Used by 2 functions | Uses 2 functions

※491※

```
get_comment_text()
```

Function: Retrieve the text of the current comment.
Source: wp-includes/comment-template.php:959
Used by 3 functions | Uses 3 functions

※492※

```
get_comment_time()
```

Function: Retrieve the comment time of the current comment.
Source: wp-includes/comment-template.php:1017
Used by 3 functions | Uses 5 functions

※493※

```
get_comment_to_edit()
```

Function: Returns a WP_Comment object based on comment ID.
Source: wp-admin/includes/comment.php:106
Used by 0 functions | Uses 5 functions

※494※

```
get_comment_type()
```

Function: Retrieve the comment type of the current comment.
Source: wp-includes/comment-template.php:1062
Used by 4 functions | Uses 3 functions

※495※

```
get_compat_media_markup()
```

Function:
Source: wp-admin/includes/media.php:1826
Used by 2 functions | Uses 14 functions

※496※

```
get_core_checksums()
```

Function: Gets and caches the checksums for the given version of WordPress.
Source: wp-admin/includes/update.php:118
Used by 3 functions | Uses 8 functions

※497※

```
get_core_updates()
```

Function: Get available core updates.
Source: wp-admin/includes/update.php:32
Used by 8 functions | Uses 2 functions

※498※

```
get_currentuserinfo()
```

Function: Populate global variables with information about the currently logged in user.
Source: wp-includes/pluggable-deprecated.php:48
Used by 0 functions | Uses 2 functions

※499※

```
get_current_blog_id()
```

Function: Retrieve the current site ID.
Source: wp-includes/load.php:1095
Used by 61 functions | Uses 1 function

※500※

```
get_current_network_id()
```

Function: Retrieves the current network ID.
Source: wp-includes/load.php:1107
Used by 22 functions | Uses 4 functions

※501※

```
get_current_screen()
```

Function: Get the current screen object
Source: wp-admin/includes/screen.php:222
Used by 28 functions | Uses 0 functions

※502※

```
get_current_site()
```

Function: Get the current network.
Source: wp-includes/ms-functions.php:1742
Used by 0 functions | Uses 0 functions

※503※

```
get_current_site_name()
```

Function: This deprecated function formerly set the site_name property of the $current_site object.
Source: wp-includes/ms-load.php:522
Used by 0 functions | Uses 1 function

※504※

```
get_current_theme()
```

Function: Retrieve current theme name.
Source: wp-includes/deprecated.php:2940
Used by 0 functions | Uses 4 functions

※505※

```
get_current_user_id()
```

Function: Get the current user’s ID
Source: wp-includes/user.php:439
Used by 98 functions | Uses 1 function

※506※

```
get_custom_header()
```

Function: Get the header image data.
Source: wp-includes/theme.php:1326
Used by 3 functions | Uses 8 functions

※507※

```
get_custom_header_markup()
```

Function: Retrieve the markup for a custom header.
Source: wp-includes/theme.php:1563
Used by 1 function | Uses 3 functions

※508※

```
get_custom_logo()
```

Function: Returns a custom logo, linked to home.
Source: wp-includes/general-template.php:948
Used by 2 functions | Uses 13 functions

※509※

```
get_dashboard_blog()
```

Function: Get the “dashboard blog”, the blog where users without a blog edit their profile data.
Source: wp-includes/ms-deprecated.php:26
Used by 0 functions | Uses 4 functions

※510※

```
get_dashboard_url()
```

Function: Retrieves the URL to the user’s dashboard.
Source: wp-includes/link-template.php:3678
Used by 5 functions | Uses 11 functions

※511※

```
get_date_from_gmt()
```

Function: Converts a GMT date into the correct format for the blog.
Source: wp-includes/formatting.php:3520
Used by 7 functions | Uses 1 function

※512※

```
get_date_template()
```

Function: Retrieve path of date template in current or parent template.
Source: wp-includes/template.php:339
Used by 0 functions | Uses 1 function

※513※

```
get_day_link()
```

Function: Retrieves the permalink for the day archives with year and month.
Source: wp-includes/link-template.php:546
Used by 3 functions | Uses 7 functions

※514※

```
get_default_comment_status()
```

Function: Gets the default comment status for a post type.
Source: wp-includes/comment.php:276
Used by 4 functions | Uses 4 functions

※515※

```
get_default_feed()
```

Function: Retrieve the default feed.
Source: wp-includes/feed.php:78
Used by 15 functions | Uses 2 functions

※516※

```
get_default_link_to_edit()
```

Function: Retrieves the default link for editing.
Source: wp-admin/includes/bookmark.php:61
Used by 0 functions | Uses 3 functions

※517※

```
get_default_page_to_edit()
```

Function: Gets the default page information to use.
Source: wp-admin/includes/deprecated.php:1106
Used by 0 functions | Uses 2 functions

※518※

```
get_default_post_to_edit()
```

Function: Default post information to use when populating the “Write Post” form.
Source: wp-admin/includes/post.php:650
Used by 5 functions | Uses 17 functions

※519※

```
get_delete_post_link()
```

Function: Retrieves the delete posts link for post.
Source: wp-includes/link-template.php:1451
Used by 3 functions | Uses 9 functions

※520※

```
get_dirsize()
```

Function: Get the size of a directory.
Source: wp-includes/functions.php:7185
Used by 1 function | Uses 5 functions

※521※

```
get_dropins()
```

Function: Check the wp-content directory and retrieve all drop-ins with any plugin data.
Source: wp-admin/includes/plugin.php:428
Used by 2 functions | Uses 2 functions

※522※

```
get_dynamic_block_names()
```

Function: Returns an array of the names of all registered dynamic block types.
Source: wp-includes/blocks.php:103
Used by 0 functions | Uses 1 function

※523※

```
get_editable_authors()
```

Function: Gets author users who can edit posts.
Source: wp-admin/includes/deprecated.php:251
Used by 0 functions | Uses 4 functions

※524※

```
get_editable_roles()
```

Function: Fetch a filtered list of user roles that the current user is allowed to edit.
Source: wp-admin/includes/user.php:263
Used by 4 functions | Uses 3 functions

※525※

```
get_editable_user_ids()
```

Function: Gets the IDs of any users who can edit posts.
Source: wp-admin/includes/deprecated.php:279
Used by 2 functions | Uses 7 functions

※526※

```
get_editor_stylesheets()
```

Function: Retrieve any registered editor stylesheets
Source: wp-includes/theme.php:1984
Used by 1 function | Uses 8 functions

※527※

```
get_edit_bookmark_link()
```

Function: Displays the edit bookmark link.
Source: wp-includes/link-template.php:1555
Used by 3 functions | Uses 5 functions

※528※

```
get_edit_comment_link()
```

Function: Retrieves the edit comment link.
Source: wp-includes/link-template.php:1494
Used by 1 function | Uses 5 functions

※529※

```
get_edit_post_link()
```

Function: Retrieves the edit post link for post.
Source: wp-includes/link-template.php:1356
Used by 18 functions | Uses 6 functions

※530※

```
get_edit_profile_url()
```

Function: Retrieves the URL to the user’s profile editor.
Source: wp-includes/link-template.php:3724
Used by 6 functions | Uses 8 functions

※531※

```
get_edit_tag_link()
```

Function: Retrieves the edit link for a tag.
Source: wp-includes/link-template.php:945
Used by 0 functions | Uses 3 functions

※532※

```
get_edit_term_link()
```

Function: Retrieves the URL for editing a given term.
Source: wp-includes/link-template.php:994
Used by 6 functions | Uses 8 functions

※533※

```
get_edit_user_link()
```

Function: Retrieves the edit user link.
Source: wp-includes/link-template.php:1617
Used by 5 functions | Uses 8 functions

※534※

```
get_embed_template()
```

Function: Retrieves an embed template path in the current or parent template.
Source: wp-includes/template.php:553
Used by 0 functions | Uses 3 functions

※535※

```
get_enclosed()
```

Function: Retrieve enclosures already enclosed for a post.
Source: wp-includes/post.php:4712
Used by 1 function | Uses 3 functions

※536※

```
get_extended()
```

Function: Get extended entry info ().
Source: wp-includes/post.php:712
Used by 3 functions | Uses 0 functions

※537※

```
get_feed_build_date()
```

Function: Get the timestamp of the most recently modified post from WP_Query.
Source: wp-includes/feed.php:665
Used by 0 functions | Uses 7 functions

※538※

```
get_feed_link()
```

Function: Retrieves the permalink for the feed type.
Source: wp-includes/link-template.php:616
Used by 4 functions | Uses 7 functions

※539※

```
get_file()
```

Function:
Source: wp-admin/includes/noop.php:96
Used by 0 functions | Uses 0 functions

※540※

```
get_filesystem_method()
```

Function: Determines which method to use for reading, writing, modifying, or deleting files on the filesystem.
Source: wp-admin/includes/file.php:1850
Used by 4 functions | Uses 3 functions

※541※

```
get_file_data()
```

Function: Retrieve metadata from a file.
Source: wp-includes/functions.php:5697
Used by 5 functions | Uses 3 functions

※542※

```
get_file_description()
```

Function: Get the description for standard WordPress theme files and other various standard WordPress files
Source: wp-admin/includes/file.php:79
Used by 1 function | Uses 2 functions

※543※

```
get_footer()
```

Function: Load footer template.
Source: wp-includes/general-template.php:57
Used by 0 functions | Uses 3 functions

※544※

```
get_front_page_template()
```

Function: Retrieve path of front page template in current or parent template.
Source: wp-includes/template.php:373
Used by 0 functions | Uses 1 function

※545※

```
get_gmt_from_date()
```

Function: Returns a date in the GMT equivalent.
Source: wp-includes/formatting.php:3498
Used by 9 functions | Uses 1 function

※546※

```
get_header()
```

Function: Load header template.
Source: wp-includes/general-template.php:22
Used by 0 functions | Uses 3 functions

※547※

```
get_header_image()
```

Function: Retrieve header image for custom header.
Source: wp-includes/theme.php:1076
Used by 7 functions | Uses 6 functions

※548※

```
get_header_image_tag()
```

Function: Create image tag markup for a custom header image.
Source: wp-includes/theme.php:1099
Used by 2 functions | Uses 10 functions

※549※

```
get_header_textcolor()
```

Function: Retrieves the custom header text color in 3- or 6-digit hexadecimal form.
Source: wp-includes/theme.php:1027
Used by 2 functions | Uses 2 functions

※550※

```
get_header_video_settings()
```

Function: Retrieve header video settings.
Source: wp-includes/theme.php:1470
Used by 2 functions | Uses 9 functions

※551※

```
get_header_video_url()
```

Function: Retrieve header video URL for custom header.
Source: wp-includes/theme.php:1426
Used by 3 functions | Uses 8 functions

※552※

```
get_hidden_columns()
```

Function: Get a list of hidden columns.
Source: wp-admin/includes/screen.php:54
Used by 3 functions | Uses 5 functions

※553※

```
get_hidden_meta_boxes()
```

Function: Get Hidden Meta Boxes
Source: wp-admin/includes/screen.php:151
Used by 4 functions | Uses 5 functions

※554※

```
get_home_path()
```

Function: Get the absolute filesystem path to the root of the WordPress installation
Source: wp-admin/includes/file.php:105
Used by 4 functions | Uses 3 functions

※555※

```
get_home_template()
```

Function: Retrieve path of home template in current or parent template.
Source: wp-includes/template.php:355
Used by 0 functions | Uses 1 function

※556※

```
get_home_url()
```

Function: Retrieves the URL for a given site where the front end is accessible.
Source: wp-includes/link-template.php:3164
Used by 16 functions | Uses 9 functions

※557※

```
get_html_split_regex()
```

Function: Retrieve the regular expression for an HTML element.
Source: wp-includes/formatting.php:637
Used by 1 function | Uses 0 functions

※558※

```
get_http_origin()
```

Function: Get the HTTP Origin of the current request.
Source: wp-includes/http.php:393
Used by 3 functions | Uses 2 functions

※559※

```
get_id_from_blogname()
```

Function: Retrieves a sites ID given its (subdomain or directory) slug.
Source: wp-includes/ms-blogs.php:86
Used by 2 functions | Uses 3 functions

※560※

```
get_images_from_uri()
```

Function: Retrieve all image URLs from given URI.
Source: wp-admin/press-this.php:169
Used by 0 functions | Uses 0 functions

※561※

```
get_image_send_to_editor()
```

Function: Retrieves the image HTML to send to the editor.
Source: wp-admin/includes/media.php:133
Used by 2 functions | Uses 4 functions

※562※

```
get_image_tag()
```

Function: Gets an img tag for an image attachment, scaling it down if requested.
Source: wp-includes/media.php:368
Used by 1 function | Uses 6 functions

※563※

```
get_importers()
```

Function: Retrieve list of importers.
Source: wp-admin/includes/import.php:17
Used by 0 functions | Uses 0 functions

※564※

```
get_index_rel_link()
```

Function: Get site index relational link.
Source: wp-includes/deprecated.php:2724
Used by 1 function | Uses 6 functions

※565※

```
get_index_template()
```

Function: Retrieve path of index template in current or parent template.
Source: wp-includes/template.php:78
Used by 0 functions | Uses 1 function

※566※

```
get_inline_data()
```

Function: Adds hidden fields with the data for use in the inline editor for posts and pages.
Source: wp-admin/includes/template.php:304
Used by 1 function | Uses 19 functions

※567※

```
get_intermediate_image_sizes()
```

Function: Gets the available intermediate image sizes.
Source: wp-includes/media.php:838
Used by 6 functions | Uses 3 functions

※568※

```
get_language_attributes()
```

Function: Gets the language attributes for the html tag.
Source: wp-includes/general-template.php:3950
Used by 2 functions | Uses 6 functions

※569※

```
get_lastcommentmodified()
```

Function: The date the last comment was modified.
Source: wp-includes/comment.php:323
Used by 1 function | Uses 4 functions

※570※

```
get_lastpostdate()
```

Function: Retrieves the most recent time that a post on the site was published.
Source: wp-includes/post.php:6390
Used by 1 function | Uses 3 functions

※571※

```
get_lastpostmodified()
```

Function: Get the most recent time that a post on the site was modified.
Source: wp-includes/post.php:6419
Used by 2 functions | Uses 5 functions

※572※

```
get_last_updated()
```

Function: Get a list of most recently updated blogs.
Source: wp-includes/ms-blogs.php:756
Used by 0 functions | Uses 4 functions

※573※

```
get_link()
```

Function: Retrieves bookmark data based on ID.
Source: wp-includes/deprecated.php:2000
Used by 0 functions | Uses 2 functions

※574※

```
get_linkcatname()
```

Function: Gets the name of category by id.
Source: wp-includes/deprecated.php:1091
Used by 0 functions | Uses 3 functions

※575※

```
get_linkobjects()
```

Function: Gets an array of link objects associated with category n.
Source: wp-includes/deprecated.php:508
Used by 1 function | Uses 2 functions

※576※

```
get_linkobjectsbyname()
```

Function: Gets an array of link objects associated with category $cat_name.
Source: wp-includes/deprecated.php:457
Used by 0 functions | Uses 3 functions

※577※

```
get_linkrating()
```

Function: Legacy function that retrieved the value of a link’s link_rating field.
Source: wp-includes/deprecated.php:1076
Used by 1 function | Uses 2 functions

※578※

```
get_links()
```

Function: Gets the links associated with category by id.
Source: wp-includes/deprecated.php:924
Used by 3 functions | Uses 8 functions

※579※

```
get_linksbyname()
```

Function: Gets the links associated with category $cat_name.
Source: wp-includes/deprecated.php:395
Used by 1 function | Uses 3 functions

※580※

```
get_linksbyname_withrating()
```

Function: Gets the links associated with category ‘cat_name’ and display rating stars/chars.
Source: wp-includes/deprecated.php:540
Used by 0 functions | Uses 2 functions

※581※

```
get_links_list()
```

Function: Output entire list of links by category.
Source: wp-includes/deprecated.php:1017
Used by 0 functions | Uses 5 functions

※582※

```
get_links_withrating()
```

Function: Gets the links associated with category n and display rating stars/chars.
Source: wp-includes/deprecated.php:567
Used by 0 functions | Uses 2 functions

※583※

```
get_link_to_edit()
```

Function: Retrieves link data based on its ID.
Source: wp-admin/includes/bookmark.php:140
Used by 0 functions | Uses 1 function

※584※

```
get_locale()
```

Function: Retrieves the current locale.
Source: wp-includes/l10n.php:30
Used by 21 functions | Uses 6 functions

※585※

```
get_locale_stylesheet_uri()
```

Function: Retrieves the localized stylesheet URI.
Source: wp-includes/theme.php:273
Used by 1 function | Uses 5 functions

※586※

```
get_main_network_id()
```

Function: Get the main network ID.
Source: wp-includes/functions.php:5243
Used by 4 functions | Uses 5 functions

※587※

```
get_main_site_id()
```

Function: Gets the main site ID.
Source: wp-includes/functions.php:5201
Used by 2 functions | Uses 3 functions

※588※

```
get_media_embedded_in_content()
```

Function: Check the content blob for an audio, video, object, embed, or iframe tags.
Source: wp-includes/media.php:4043
Used by 0 functions | Uses 2 functions

※589※

```
get_media_item()
```

Function: Retrieve HTML form for modifying the image attachment.
Source: wp-admin/includes/media.php:1537
Used by 1 function | Uses 32 functions

※590※

```
get_media_items()
```

Function: Retrieve HTML for media items of post gallery.
Source: wp-admin/includes/media.php:1484
Used by 3 functions | Uses 3 functions

※591※

```
get_metadata()
```

Function: Retrieve metadata for the specified object.
Source: wp-includes/meta.php:488
Used by 11 functions | Uses 6 functions

※592※

```
get_metadata_by_mid()
```

Function: Get meta data by meta ID
Source: wp-includes/meta.php:603
Used by 7 functions | Uses 6 functions

※593※

```
get_meta_keys()
```

Function: Get a list of previously defined keys.
Source: wp-admin/includes/post.php:952
Used by 0 functions | Uses 1 function

※594※

```
get_meta_sql()
```

Function: Given a meta query, generates SQL clauses to be appended to a main query.
Source: wp-includes/meta.php:1003
Used by 0 functions | Uses 1 function

※595※

```
get_month_link()
```

Function: Retrieves the permalink for the month archives with year.
Source: wp-includes/link-template.php:505
Used by 3 functions | Uses 7 functions

※596※

```
get_most_active_blogs()
```

Function: Deprecated functionality to retrieve a list of the most active sites.
Source: wp-includes/ms-deprecated.php:219
Used by 0 functions | Uses 3 functions

※597※

```
get_most_recent_post_of_user()
```

Function: Get a user’s most recent post.
Source: wp-includes/ms-functions.php:1760
Used by 0 functions | Uses 4 functions

※598※

```
get_mu_plugins()
```

Function: Check the mu-plugins directory and retrieve all mu-plugin files with any plugin data.
Source: wp-admin/includes/plugin.php:359
Used by 2 functions | Uses 1 function

※599※

```
get_nav_menu_locations()
```

Function: Retrieves all registered navigation menu locations and the menus assigned to them.
Source: wp-includes/nav-menu.php:164
Used by 6 functions | Uses 1 function

※600※

```
get_network()
```

Function: Retrieves network data given a network ID or network object.
Source: wp-includes/ms-network.php:23
Used by 32 functions | Uses 4 functions

※601※

```
get_networks()
```

Function: Retrieves a list of networks.
Source: wp-includes/ms-network.php:63
Used by 4 functions | Uses 1 function

※602※

```
get_network_by_path()
```

Function: Retrieve the closest matching network for a domain and path.
Source: wp-includes/ms-load.php:141
Used by 0 functions | Uses 1 function

※603※

```
get_network_option()
```

Function: Retrieve a network’s option value based on the option name.
Source: wp-includes/option.php:1217
Used by 9 functions | Uses 12 functions

※604※

```
get_next_comments_link()
```

Function: Retrieves the link to the next comments page.
Source: wp-includes/link-template.php:2860
Used by 2 functions | Uses 8 functions

※605※

```
get_next_post()
```

Function: Retrieves the next post that is adjacent to the current post.
Source: wp-includes/link-template.php:1677
Used by 1 function | Uses 1 function

※606※

```
get_next_posts_link()
```

Function: Retrieves the next posts page link.
Source: wp-includes/link-template.php:2352
Used by 3 functions | Uses 5 functions

※607※

```
get_next_posts_page_link()
```

Function: Retrieves the next posts page link.
Source: wp-includes/link-template.php:2307
Used by 1 function | Uses 2 functions

※608※

```
get_next_post_link()
```

Function: Retrieves the next post link that is adjacent to the current post.
Source: wp-includes/link-template.php:2112
Used by 2 functions | Uses 1 function

※609※

```
get_nonauthor_user_ids()
```

Function: Gets all users who are not authors.
Source: wp-admin/includes/deprecated.php:314
Used by 0 functions | Uses 5 functions

※610※

```
get_num_queries()
```

Function: Retrieve the number of database queries during the WordPress execution.
Source: wp-includes/functions.php:1479
Used by 0 functions | Uses 0 functions

※611※

```
get_objects_in_term()
```

Function: Retrieve object_ids of valid taxonomy and term.
Source: wp-includes/taxonomy.php:711
Used by 2 functions | Uses 8 functions

※612※

```
get_object_subtype()
```

Function: Returns the object subtype for a given object ID of a specific type.
Source: wp-includes/meta.php:1406
Used by 6 functions | Uses 6 functions

※613※

```
get_object_taxonomies()
```

Function: Return the names or objects of the taxonomies which are registered for the requested object or object type, such as a post object or post type name.
Source: wp-includes/taxonomy.php:222
Used by 34 functions | Uses 1 function

※614※

```
get_object_term_cache()
```

Function: Retrieves the cached term objects for the given object ID.
Source: wp-includes/taxonomy.php:3324
Used by 8 functions | Uses 4 functions

※615※

```
get_oembed_endpoint_url()
```

Function: Retrieves the oEmbed endpoint URL for a given permalink.
Source: wp-includes/embed.php:396
Used by 1 function | Uses 4 functions

※616※

```
get_oembed_response_data()
```

Function: Retrieves the oEmbed response data for a given post.
Source: wp-includes/embed.php:501
Used by 2 functions | Uses 11 functions

※617※

```
get_oembed_response_data_for_url()
```

Function: Retrieves the oEmbed response data for a given URL.
Source: wp-includes/embed.php:576
Used by 2 functions | Uses 13 functions

※618※

```
get_oembed_response_data_rich()
```

Function: Filters the oEmbed response data to return an iframe embed code.
Source: wp-includes/embed.php:649
Used by 0 functions | Uses 8 functions

※619※

```
get_option()
```

Function: Retrieves an option value based on an option name.
Source: wp-includes/option.php:30
Used by 312 functions | Uses 15 functions

※620※

```
get_others_drafts()
```

Function: Retrieve drafts from other users.
Source: wp-admin/includes/deprecated.php:717
Used by 0 functions | Uses 2 functions

※621※

```
get_others_pending()
```

Function: Retrieve pending review posts from other users.
Source: wp-admin/includes/deprecated.php:732
Used by 0 functions | Uses 2 functions

※622※

```
get_others_unpublished_posts()
```

Function: Retrieves editable posts from other users.
Source: wp-admin/includes/deprecated.php:684
Used by 2 functions | Uses 5 functions

※623※

```
get_page()
```

Function: Retrieves page data given a page ID or page object.
Source: wp-includes/post.php:4866
Used by 0 functions | Uses 1 function

※624※

```
get_paged_template()
```

Function: Retrieve path of paged template in current or parent template.
Source: wp-includes/deprecated.php:3788
Used by 0 functions | Uses 2 functions

※625※

```
get_pagenum_link()
```

Function: Retrieves the link for a page number.
Source: wp-includes/link-template.php:2227
Used by 3 functions | Uses 13 functions

※626※

```
get_pages()
```

Function: Retrieve a list of pages (or hierarchical post type items).
Source: wp-includes/post.php:5194
Used by 5 functions | Uses 18 functions

※627※

```
get_page_by_path()
```

Function: Retrieves a page given its path.
Source: wp-includes/post.php:4883
Used by 9 functions | Uses 6 functions

※628※

```
get_page_by_title()
```

Function: Retrieve a page given its title.
Source: wp-includes/post.php:4985
Used by 0 functions | Uses 4 functions

※629※

```
get_page_children()
```

Function: Identify descendants of a given page ID in a list of page objects.
Source: wp-includes/post.php:5031
Used by 1 function | Uses 0 functions

※630※

```
get_page_hierarchy()
```

Function: Order the pages with children under parents in a flat list.
Source: wp-includes/post.php:5072
Used by 1 function | Uses 1 function

※631※

```
get_page_link()
```

Function: Retrieves the permalink for the current page or page ID.
Source: wp-includes/link-template.php:329
Used by 1 function | Uses 6 functions

※632※

```
get_page_of_comment()
```

Function: Calculate what page number a comment will appear on for comment paging.
Source: wp-includes/comment.php:1048
Used by 2 functions | Uses 8 functions

※633※

```
get_page_statuses()
```

Function: Retrieve all of the WordPress support page statuses.
Source: wp-includes/post.php:957
Used by 1 function | Uses 1 function

※634※

```
get_page_template()
```

Function: Retrieve path of page template in current or parent template.
Source: wp-includes/template.php:425
Used by 0 functions | Uses 6 functions

※635※

```
get_page_templates()
```

Function: Get the Page Templates available in this theme
Source: wp-admin/includes/theme.php:124
Used by 5 functions | Uses 2 functions

※636※

```
get_page_template_slug()
```

Function: Get the specific template name for a given post.
Source: wp-includes/post-template.php:1778
Used by 8 functions | Uses 2 functions

※637※

```
get_page_uri()
```

Function: Build the URI path for a page.
Source: wp-includes/post.php:5123
Used by 4 functions | Uses 3 functions

※638※

```
get_parent_post_rel_link()
```

Function: Get parent post relational link.
Source: wp-includes/deprecated.php:2752
Used by 1 function | Uses 8 functions

※639※

```
get_parent_theme_file_path()
```

Function: Retrieves the path of a file in the parent theme.
Source: wp-includes/link-template.php:4362
Used by 0 functions | Uses 3 functions

※640※

```
get_parent_theme_file_uri()
```

Function: Retrieves the URL of a file in the parent theme.
Source: wp-includes/link-template.php:4301
Used by 0 functions | Uses 3 functions

※641※

```
get_password_reset_key()
```

Function: Creates, stores, then returns a password reset key for user.
Source: wp-includes/user.php:2258
Used by 2 functions | Uses 13 functions

※642※

```
get_pending_comments_num()
```

Function: Get the number of pending comments on a post or posts
Source: wp-admin/includes/comment.php:143
Used by 5 functions | Uses 2 functions

※643※

```
get_permalink()
```

Function: Retrieves the full permalink for the current post or post ID.
Source: wp-includes/link-template.php:119
Used by 66 functions | Uses 18 functions

※644※

```
get_plugins()
```

Function: Check the plugins directory and retrieve all plugin files with plugin data.
Source: wp-admin/includes/plugin.php:278
Used by 15 functions | Uses 4 functions

※645※

```
get_plugin_data()
```

Function: Parses the plugin contents to retrieve plugin’s metadata.
Source: wp-admin/includes/plugin.php:68
Used by 10 functions | Uses 5 functions

※646※

```
get_plugin_files()
```

Function: Get a list of a plugin’s files.
Source: wp-admin/includes/plugin.php:231
Used by 1 function | Uses 4 functions

※647※

```
get_plugin_page_hook()
```

Function:
Source: wp-admin/includes/plugin.php:1961
Used by 2 functions | Uses 2 functions

※648※

```
get_plugin_page_hookname()
```

Function:
Source: wp-admin/includes/plugin.php:1978
Used by 4 functions | Uses 1 function

※649※

```
get_plugin_updates()
```

Function:
Source: wp-admin/includes/update.php:350
Used by 4 functions | Uses 2 functions

※650※

```
get_post()
```

Function: Retrieves post data given a post ID or post object.
Source: wp-includes/post.php:753
Used by 318 functions | Uses 3 functions

※651※

```
get_postdata()
```

Function: Retrieves all post data for a given post.
Source: wp-includes/deprecated.php:25
Used by 0 functions | Uses 2 functions

※652※

```
get_posts()
```

Function: Retrieves an array of the latest posts, or posts matching the given criteria.
Source: wp-includes/post.php:2003
Used by 18 functions | Uses 3 functions

※653※

```
get_posts_by_author_sql()
```

Function: Retrieve the post SQL based on capability, author, and type.
Source: wp-includes/post.php:6305
Used by 4 functions | Uses 7 functions

※654※

```
get_posts_nav_link()
```

Function: Retrieves the post pages link navigation for previous and next pages.
Source: wp-includes/link-template.php:2497
Used by 1 function | Uses 6 functions

※655※

```
get_post_ancestors()
```

Function: Retrieve ancestors of a post.
Source: wp-includes/post.php:796
Used by 3 functions | Uses 1 function

※656※

```
get_post_class()
```

Function: Retrieves an array of the class names for the post container element.
Source: wp-includes/post-template.php:479
Used by 2 functions | Uses 18 functions

※657※

```
get_post_comments_feed_link()
```

Function: Retrieves the permalink for the post comments feed.
Source: wp-includes/link-template.php:667
Used by 5 functions | Uses 13 functions

※658※

```
get_post_custom()
```

Function: Retrieve post meta fields, based on post ID.
Source: wp-includes/post.php:2198
Used by 7 functions | Uses 3 functions

※659※

```
get_post_custom_keys()
```

Function: Retrieve meta field names for a post.
Source: wp-includes/post.php:2217
Used by 2 functions | Uses 1 function

※660※

```
get_post_custom_values()
```

Function: Retrieve values for a custom post field.
Source: wp-includes/post.php:2242
Used by 1 function | Uses 1 function

※661※

```
get_post_datetime()
```

Function: Retrieve post published or modified time as a `DateTimeImmutable` object instance.
Source: wp-includes/general-template.php:2624
Used by 3 functions | Uses 2 functions

※662※

```
get_post_embed_html()
```

Function: Retrieves the embed code for a specific post.
Source: wp-includes/embed.php:431
Used by 2 functions | Uses 11 functions

※663※

```
get_post_embed_url()
```

Function: Retrieves the URL to embed a specific post in an iframe.
Source: wp-includes/embed.php:360
Used by 1 function | Uses 12 functions

※664※

```
get_post_field()
```

Function: Retrieve data from a post field based on Post ID.
Source: wp-includes/post.php:841
Used by 3 functions | Uses 2 functions

※665※

```
get_post_format()
```

Function: Retrieve the format slug for a post
Source: wp-includes/post-formats.php:17
Used by 10 functions | Uses 3 functions

※666※

```
get_post_format_link()
```

Function: Returns a link to a post format index.
Source: wp-includes/post-formats.php:148
Used by 0 functions | Uses 3 functions

※667※

```
get_post_format_slugs()
```

Function: Retrieves the array of post format slugs.
Source: wp-includes/post-formats.php:118
Used by 4 functions | Uses 1 function

※668※

```
get_post_format_string()
```

Function: Returns a pretty, translated version of a post format slug
Source: wp-includes/post-formats.php:131
Used by 6 functions | Uses 1 function

※669※

```
get_post_format_strings()
```

Function: Returns an array of post format slugs to their translated and pretty display versions
Source: wp-includes/post-formats.php:95
Used by 5 functions | Uses 1 function

※670※

```
get_post_galleries()
```

Function: Retrieves galleries from the passed post’s content.
Source: wp-includes/media.php:4085
Used by 2 functions | Uses 7 functions

※671※

```
get_post_galleries_images()
```

Function: Retrieve the image srcs from galleries from a post’s content, if present
Source: wp-includes/media.php:4181
Used by 0 functions | Uses 2 functions

※672※

```
get_post_gallery()
```

Function: Check a specified post’s content for gallery and, if present, return the first
Source: wp-includes/media.php:4154
Used by 1 function | Uses 3 functions

※673※

```
get_post_gallery_images()
```

Function: Checks a post’s content for galleries and return the image srcs for the first found gallery
Source: wp-includes/media.php:4196
Used by 0 functions | Uses 1 function

※674※

```
get_post_meta()
```

Function: Retrieves a post meta field for the given post ID.
Source: wp-includes/post.php:2109
Used by 61 functions | Uses 1 function

※675※

```
get_post_meta_by_id()
```

Function: Get post meta data by meta ID.
Source: wp-admin/includes/post.php:974
Used by 1 function | Uses 1 function

※676※

```
get_post_mime_type()
```

Function: Retrieve the mime type of an attachment based on the ID.
Source: wp-includes/post.php:866
Used by 3 functions | Uses 1 function

※677※

```
get_post_mime_types()
```

Function: Get default post mime types.
Source: wp-includes/post.php:2708
Used by 4 functions | Uses 7 functions

※678※

```
get_post_modified_time()
```

Function: Retrieve the time at which the post was last modified.
Source: wp-includes/general-template.php:2749
Used by 2 functions | Uses 5 functions

※679※

```
get_post_permalink()
```

Function: Retrieves the permalink for a post of a custom post type.
Source: wp-includes/link-template.php:262
Used by 1 function | Uses 11 functions

※680※

```
get_post_reply_link()
```

Function: Retrieve HTML content for reply to post link.
Source: wp-includes/comment-template.php:1767
Used by 1 function | Uses 10 functions

※681※

```
get_post_states()
```

Function: Function to retrieve an array of post states from a post.
Source: wp-admin/includes/template.php:2107
Used by 1 function | Uses 7 functions

※682※

```
get_post_stati()
```

Function: Get a list of post statuses.
Source: wp-includes/post.php:1151
Used by 18 functions | Uses 1 function

※683※

```
get_post_status()
```

Function: Retrieve the post status based on the post ID.
Source: wp-includes/post.php:887
Used by 22 functions | Uses 5 functions

※684※

```
get_post_statuses()
```

Function: Retrieve all of the WordPress supported post statuses.
Source: wp-includes/post.php:936
Used by 1 function | Uses 1 function

※685※

```
get_post_status_object()
```

Function: Retrieve a post status object by name.
Source: wp-includes/post.php:1124
Used by 15 functions | Uses 0 functions

※686※

```
get_post_taxonomies()
```

Function: Retrieve all taxonomies of a post with just the names.
Source: wp-includes/taxonomy.php:4387
Used by 0 functions | Uses 2 functions

※687※

```
get_post_thumbnail_id()
```

Function: Retrieve post thumbnail ID.
Source: wp-includes/post-thumbnail-template.php:50
Used by 16 functions | Uses 2 functions

※688※

```
get_post_time()
```

Function: Retrieve the time at which the post was written.
Source: wp-includes/general-template.php:2561
Used by 5 functions | Uses 5 functions

※689※

```
get_post_timestamp()
```

Function: Retrieve post published or modified time as a Unix timestamp.
Source: wp-includes/general-template.php:2667
Used by 2 functions | Uses 1 function

※690※

```
get_post_to_edit()
```

Function: Gets an existing post and format it for editing.
Source: wp-admin/includes/deprecated.php:1091
Used by 0 functions | Uses 2 functions

※691※

```
get_post_type()
```

Function: Retrieves the post type of the current post or of a given post.
Source: wp-includes/post.php:1206
Used by 24 functions | Uses 1 function

※692※

```
get_post_types()
```

Function: Get a list of all registered post type objects.
Source: wp-includes/post.php:1256
Used by 37 functions | Uses 1 function

※693※

```
get_post_types_by_support()
```

Function: Retrieves a list of post type names that support a specific feature.
Source: wp-includes/post.php:1922
Used by 0 functions | Uses 1 function

※694※

```
get_post_type_archive_feed_link()
```

Function: Retrieves the permalink for a post type archive feed.
Source: wp-includes/link-template.php:1268
Used by 1 function | Uses 8 functions

※695※

```
get_post_type_archive_link()
```

Function: Retrieves the permalink for a post type archive.
Source: wp-includes/link-template.php:1210
Used by 7 functions | Uses 8 functions

※696※

```
get_post_type_archive_template()
```

Function: Retrieve path of post type archive template in current or parent template.
Source: wp-includes/template.php:136
Used by 0 functions | Uses 3 functions

※697※

```
get_post_type_capabilities()
```

Function: Build an object with all post type capabilities out of a post type object
Source: wp-includes/post.php:1545
Used by 1 function | Uses 1 function

※698※

```
get_post_type_labels()
```

Function: Builds an object with all post type labels out of a post type object.
Source: wp-includes/post.php:1681
Used by 1 function | Uses 5 functions

※699※

```
get_post_type_object()
```

Function: Retrieves a post type object by name.
Source: wp-includes/post.php:1228
Used by 127 functions | Uses 0 functions

※700※

```
get_preferred_from_update_core()
```

Function: Selects the first update version from the update_core option.
Source: wp-admin/includes/update.php:14
Used by 4 functions | Uses 1 function

※701※

```
get_preview_post_link()
```

Function: Retrieves the URL used for the post preview.
Source: wp-includes/link-template.php:1315
Used by 9 functions | Uses 8 functions

※702※

```
get_previous_comments_link()
```

Function: Retrieves the link to the previous comments page.
Source: wp-includes/link-template.php:2921
Used by 2 functions | Uses 7 functions

※703※

```
get_previous_post()
```

Function: Retrieves the previous post that is adjacent to the current post.
Source: wp-includes/link-template.php:1662
Used by 1 function | Uses 1 function

※704※

```
get_previous_posts_link()
```

Function: Retrieves the previous posts page link.
Source: wp-includes/link-template.php:2448
Used by 3 functions | Uses 5 functions

※705※

```
get_previous_posts_page_link()
```

Function: Retrieves the previous posts page link.
Source: wp-includes/link-template.php:2408
Used by 1 function | Uses 2 functions

※706※

```
get_previous_post_link()
```

Function: Retrieves the previous post link that is adjacent to the current post.
Source: wp-includes/link-template.php:2079
Used by 2 functions | Uses 1 function

※707※

```
get_privacy_policy_template()
```

Function: Retrieve path of Privacy Policy page template in current or parent template.
Source: wp-includes/template.php:391
Used by 0 functions | Uses 1 function

※708※

```
get_privacy_policy_url()
```

Function: Retrieves the URL to the privacy policy page.
Source: wp-includes/link-template.php:4389
Used by 2 functions | Uses 5 functions

※709※

```
get_private_posts_cap_sql()
```

Function: Retrieve the private post SQL based on capability.
Source: wp-includes/post.php:6284
Used by 1 function | Uses 1 function

※710※

```
get_profile()
```

Function: Retrieve user data based on field.
Source: wp-includes/deprecated.php:2414
Used by 0 functions | Uses 3 functions

※711※

```
get_pung()
```

Function: Retrieve URLs already pinged for a post.
Source: wp-includes/post.php:4750
Used by 2 functions | Uses 3 functions

※712※

```
get_queried_object()
```

Function: Retrieve the currently-queried object.
Source: wp-includes/query.php:42
Used by 21 functions | Uses 1 function

※713※

```
get_queried_object_id()
```

Function: Retrieve ID of the current queried object.
Source: wp-includes/query.php:58
Used by 10 functions | Uses 1 function

※714※

```
get_query_template()
```

Function: Retrieve path to a template
Source: wp-includes/template.php:23
Used by 18 functions | Uses 4 functions

※715※

```
get_query_var()
```

Function: Retrieve variable in the WP_Query class.
Source: wp-includes/query.php:26
Used by 31 functions | Uses 1 function

※716※

```
get_random_header_image()
```

Function: Get random header image url from registered images in theme.
Source: wp-includes/theme.php:1219
Used by 2 functions | Uses 1 function

※717※

```
get_raw_theme_root()
```

Function: Get the raw theme root relative to the content directory with no filters applied.
Source: wp-includes/theme.php:668
Used by 7 functions | Uses 2 functions

※718※

```
get_real_file_to_edit()
```

Function: Get the real filesystem path to a file to edit within the admin.
Source: wp-admin/includes/deprecated.php:113
Used by 0 functions | Uses 1 function

※719※

```
get_registered_metadata()
```

Function: Retrieves registered metadata for a specified object.
Source: wp-includes/meta.php:1347
Used by 0 functions | Uses 4 functions

※720※

```
get_registered_meta_keys()
```

Function: Retrieves a list of registered meta keys for an object type.
Source: wp-includes/meta.php:1322
Used by 3 functions | Uses 0 functions

※721※

```
get_registered_nav_menus()
```

Function: Retrieves all registered navigation menu locations in a theme.
Source: wp-includes/nav-menu.php:147
Used by 5 functions | Uses 0 functions

※722※

```
get_registered_settings()
```

Function: Retrieves an array of registered settings.
Source: wp-includes/option.php:2265
Used by 2 functions | Uses 0 functions

※723※

```
get_rest_url()
```

Function: Retrieves the URL to a REST endpoint on a site.
Source: wp-includes/rest-api.php:344
Used by 7 functions | Uses 14 functions

※724※

```
get_role()
```

Function: Retrieve role object.
Source: wp-includes/capabilities.php:801
Used by 10 functions | Uses 2 functions

※725※

```
get_rss()
```

Function: Display RSS items in HTML list items.
Source: wp-includes/rss.php:939
Used by 0 functions | Uses 2 functions

※726※

```
get_sample_permalink()
```

Function: Get a sample permalink based off of the post name.
Source: wp-admin/includes/post.php:1324
Used by 2 functions | Uses 10 functions

※727※

```
get_sample_permalink_html()
```

Function: Returns the HTML of the sample permalink slug editor.
Source: wp-admin/includes/post.php:1405
Used by 1 function | Uses 11 functions

※728※

```
get_screen_icon()
```

Function: Retrieves the screen icon (no longer used in 3.8+).
Source: wp-admin/includes/deprecated.php:1240
Used by 1 function | Uses 1 function

※729※

```
get_search_comments_feed_link()
```

Function: Retrieves the permalink for the search results comments feed.
Source: wp-includes/link-template.php:1178
Used by 0 functions | Uses 6 functions

※730※

```
get_search_feed_link()
```

Function: Retrieves the permalink for the search results feed.
Source: wp-includes/link-template.php:1137
Used by 2 functions | Uses 7 functions

※731※

```
get_search_form()
```

Function: Display search form.
Source: wp-includes/general-template.php:201
Used by 1 function | Uses 15 functions

※732※

```
get_search_link()
```

Function: Retrieves the permalink for a search.
Source: wp-includes/link-template.php:1094
Used by 1 function | Uses 6 functions

※733※

```
get_search_query()
```

Function: Retrieves the contents of the search WordPress query variable.
Source: wp-includes/general-template.php:3905
Used by 5 functions | Uses 4 functions

※734※

```
get_search_template()
```

Function: Retrieve path of search template in current or parent template.
Source: wp-includes/template.php:469
Used by 0 functions | Uses 1 function

※735※

```
get_self_link()
```

Function: Returns the link for the currently displayed feed.
Source: wp-includes/feed.php:625
Used by 1 function | Uses 3 functions

※736※

```
get_settings()
```

Function: Get value based on option.
Source: wp-includes/deprecated.php:829
Used by 0 functions | Uses 2 functions

※737※

```
get_settings_errors()
```

Function: Fetch settings errors registered by add_settings_error()
Source: wp-admin/includes/template.php:1755
Used by 1 function | Uses 4 functions

※738※

```
get_shortcode_atts_regex()
```

Function: Retrieve the shortcode attributes regex.
Source: wp-includes/shortcodes.php:479
Used by 1 function | Uses 0 functions

※739※

```
get_shortcode_regex()
```

Function: Retrieve the shortcode regular expression for searching.
Source: wp-includes/shortcodes.php:230
Used by 6 functions | Uses 0 functions

※740※

```
get_shortcut_link()
```

Function: Retrieves the Press This bookmarklet link.
Source: wp-includes/deprecated.php:3907
Used by 0 functions | Uses 3 functions

※741※

```
get_sidebar()
```

Function: Load sidebar template.
Source: wp-includes/general-template.php:92
Used by 0 functions | Uses 3 functions

※742※

```
get_single_template()
```

Function: Retrieve path of single template in current or parent template. Applies to single Posts, single Attachments, and single custom post types.
Source: wp-includes/template.php:504
Used by 0 functions | Uses 4 functions

※743※

```
get_singular_template()
```

Function: Retrieves the path of the singular template in current or parent template.
Source: wp-includes/template.php:583
Used by 0 functions | Uses 1 function

※744※

```
get_site()
```

Function: Retrieves site data given a site ID or site object.
Source: wp-includes/ms-site.php:301
Used by 19 functions | Uses 5 functions

※745※

```
get_sites()
```

Function: Retrieves a list of sites matching requested arguments.
Source: wp-includes/ms-site.php:454
Used by 11 functions | Uses 1 function

※746※

```
get_sitestats()
```

Function: Gets the network’s site and user counts.
Source: wp-includes/ms-functions.php:17
Used by 0 functions | Uses 2 functions

※747※

```
get_site_allowed_themes()
```

Function: Deprecated functionality for getting themes network-enabled themes.
Source: wp-admin/includes/ms-deprecated.php:89
Used by 0 functions | Uses 2 functions

※748※

```
get_site_by_path()
```

Function: Retrieves the closest matching site object by its domain and path.
Source: wp-includes/ms-load.php:165
Used by 1 function | Uses 5 functions

※749※

```
get_site_icon_url()
```

Function: Returns the Site Icon URL.
Source: wp-includes/general-template.php:855
Used by 6 functions | Uses 8 functions

※750※

```
get_site_meta()
```

Function: Retrieves metadata for a site.
Source: wp-includes/ms-site.php:1083
Used by 0 functions | Uses 1 function

※751※

```
get_site_option()
```

Function: Retrieve an option value for the current network based on name of option.
Source: wp-includes/option.php:1150
Used by 69 functions | Uses 1 function

※752※

```
get_site_screen_help_sidebar_content()
```

Function: Returns the content for the help sidebar on the Edit Site screens.
Source: wp-admin/includes/ms.php:1150
Used by 0 functions | Uses 1 function

※753※

```
get_site_screen_help_tab_args()
```

Function: Returns the arguments for the help tab on the Edit Site screens.
Source: wp-admin/includes/ms.php:1126
Used by 0 functions | Uses 2 functions

※754※

```
get_site_transient()
```

Function: Get the value of a site transient.
Source: wp-includes/option.php:1741
Used by 40 functions | Uses 7 functions

※755※

```
get_site_url()
```

Function: Retrieves the URL for a given site where WordPress application files (e.g. wp-blog-header.php or the wp-admin/ folder) are accessible.
Source: wp-includes/link-template.php:3240
Used by 3 functions | Uses 7 functions

※756※

```
get_space_allowed()
```

Function: Returns the upload quota for the current blog.
Source: wp-includes/ms-functions.php:2457
Used by 7 functions | Uses 4 functions

※757※

```
get_space_used()
```

Function: Returns the space used by the current site.
Source: wp-includes/ms-functions.php:2433
Used by 4 functions | Uses 4 functions

※758※

```
get_status_header_desc()
```

Function: Retrieve the description for the HTTP status.
Source: wp-includes/functions.php:1270
Used by 5 functions | Uses 1 function

※759※

```
get_stylesheet()
```

Function: Retrieve name of the current stylesheet.
Source: wp-includes/theme.php:169
Used by 23 functions | Uses 3 functions

※760※

```
get_stylesheet_directory()
```

Function: Retrieve stylesheet directory path for current theme.
Source: wp-includes/theme.php:187
Used by 9 functions | Uses 4 functions

※761※

```
get_stylesheet_directory_uri()
```

Function: Retrieve stylesheet directory URI.
Source: wp-includes/theme.php:211
Used by 13 functions | Uses 4 functions

※762※

```
get_stylesheet_uri()
```

Function: Retrieves the URI of current theme stylesheet.
Source: wp-includes/theme.php:238
Used by 1 function | Uses 3 functions

※763※

```
get_subdirectory_reserved_names()
```

Function: Retrieves a list of reserved site on a sub-directory Multisite installation.
Source: wp-includes/ms-functions.php:2582
Used by 1 function | Uses 2 functions

※764※

```
get_submit_button()
```

Function: Returns a submit button, with provided text and appropriate class
Source: wp-admin/includes/template.php:2363
Used by 4 functions | Uses 2 functions

※765※

```
get_super_admins()
```

Function: Retrieve a list of super admins.
Source: wp-includes/capabilities.php:842
Used by 8 functions | Uses 1 function

※766※

```
get_tag()
```

Function: Retrieve post tag by tag ID or tag object.
Source: wp-includes/category.php:321
Used by 0 functions | Uses 1 function

※767※

```
get_tags()
```

Function: Retrieves all post tags.
Source: wp-includes/category.php:278
Used by 2 functions | Uses 4 functions

※768※

```
get_tags_to_edit()
```

Function: Get comma-separated list of tags available to edit.
Source: wp-admin/includes/taxonomy.php:245
Used by 0 functions | Uses 1 function

※769※

```
get_tag_feed_link()
```

Function: Retrieves the permalink for a tag feed.
Source: wp-includes/link-template.php:932
Used by 2 functions | Uses 1 function

※770※

```
get_tag_link()
```

Function: Retrieve the link to the tag.
Source: wp-includes/category-template.php:1113
Used by 1 function | Uses 1 function

※771※

```
get_tag_regex()
```

Function: Return RegEx body to liberally match an opening HTML tag.
Source: wp-includes/functions.php:6271
Used by 0 functions | Uses 1 function

※772※

```
get_tag_template()
```

Function: Retrieve path of tag template in current or parent template.
Source: wp-includes/template.php:260
Used by 0 functions | Uses 2 functions

※773※

```
get_taxonomies()
```

Function: Retrieves a list of registered taxonomy names or objects.
Source: wp-includes/taxonomy.php:193
Used by 16 functions | Uses 1 function

※774※

```
get_taxonomies_for_attachments()
```

Function: Retrieves all of the taxonomies that are registered for attachments.
Source: wp-includes/media.php:3077
Used by 3 functions | Uses 1 function

※775※

```
get_taxonomy()
```

Function: Retrieves the taxonomy object of $taxonomy.
Source: wp-includes/taxonomy.php:261
Used by 77 functions | Uses 1 function

※776※

```
get_taxonomy_labels()
```

Function: Builds an object with all taxonomy labels out of a taxonomy object.
Source: wp-includes/taxonomy.php:536
Used by 1 function | Uses 5 functions

※777※

```
get_taxonomy_template()
```

Function: Retrieve path of custom taxonomy term template in current or parent template.
Source: wp-includes/template.php:306
Used by 0 functions | Uses 2 functions

※778※

```
get_tax_sql()
```

Function: Given a taxonomy query, generates SQL to be appended to a main query.
Source: wp-includes/taxonomy.php:766
Used by 0 functions | Uses 1 function

※779※

```
get_template()
```

Function: Retrieve name of the current theme.
Source: wp-includes/theme.php:303
Used by 5 functions | Uses 3 functions

※780※

```
get_template_directory()
```

Function: Retrieve current theme directory.
Source: wp-includes/theme.php:321
Used by 9 functions | Uses 4 functions

※781※

```
get_template_directory_uri()
```

Function: Retrieve theme directory URI.
Source: wp-includes/theme.php:345
Used by 12 functions | Uses 4 functions

※782※

```
get_template_part()
```

Function: Loads a template part into a template.
Source: wp-includes/general-template.php:135
Used by 0 functions | Uses 4 functions

※783※

```
get_temp_dir()
```

Function: Determine a writable directory for temporary files.
Source: wp-includes/functions.php:2077
Used by 4 functions | Uses 2 functions

※784※

```
get_term()
```

Function: Get all Term data from database by Term ID.
Source: wp-includes/taxonomy.php:816
Used by 53 functions | Uses 10 functions

※785※

```
get_terms()
```

Function: Retrieve the terms in a given taxonomy or list of taxonomies.
Source: wp-includes/taxonomy.php:1138
Used by 33 functions | Uses 7 functions

※786※

```
get_terms_to_edit()
```

Function: Get comma-separated list of terms available to edit for the given post ID.
Source: wp-admin/includes/taxonomy.php:258
Used by 3 functions | Uses 8 functions

※787※

```
get_term_by()
```

Function: Get all Term data from database by Term field and data.
Source: wp-includes/taxonomy.php:925
Used by 16 functions | Uses 4 functions

※788※

```
get_term_children()
```

Function: Merge all term children into a single array of their IDs.
Source: wp-includes/taxonomy.php:1002
Used by 3 functions | Uses 5 functions

※789※

```
get_term_feed_link()
```

Function: Retrieves the feed link for a term.
Source: wp-includes/link-template.php:851
Used by 4 functions | Uses 13 functions

※790※

```
get_term_field()
```

Function: Get sanitized Term field.
Source: wp-includes/taxonomy.php:1046
Used by 4 functions | Uses 3 functions

※791※

```
get_term_link()
```

Function: Generate a permalink for a taxonomy term archive.
Source: wp-includes/taxonomy.php:4179
Used by 16 functions | Uses 15 functions

※792※

```
get_term_meta()
```

Function: Retrieves metadata for a term.
Source: wp-includes/taxonomy.php:1250
Used by 0 functions | Uses 1 function

※793※

```
get_term_parents_list()
```

Function: Retrieve term parents with separator.
Source: wp-includes/category-template.php:1329
Used by 1 function | Uses 7 functions

※794※

```
get_term_to_edit()
```

Function: Sanitizes Term for editing.
Source: wp-includes/taxonomy.php:1075
Used by 0 functions | Uses 3 functions

※795※

```
get_theme()
```

Function: Retrieve theme data.
Source: wp-includes/deprecated.php:2922
Used by 0 functions | Uses 2 functions

※796※

```
get_themes()
```

Function: Retrieve list of themes with theme data in theme directory.
Source: wp-includes/deprecated.php:2891
Used by 1 function | Uses 2 functions

※797※

```
get_theme_data()
```

Function: Retrieve theme data from parsed theme file.
Source: wp-includes/deprecated.php:3060
Used by 0 functions | Uses 4 functions

※798※

```
get_theme_feature_list()
```

Function: Retrieve list of WordPress theme features (aka theme tags).
Source: wp-admin/includes/theme.php:262
Used by 3 functions | Uses 6 functions

※799※

```
get_theme_file_path()
```

Function: Retrieves the path of a file in the theme.
Source: wp-includes/link-template.php:4332
Used by 0 functions | Uses 4 functions

※800※

```
get_theme_file_uri()
```

Function: Retrieves the URL of a file in the theme.
Source: wp-includes/link-template.php:4271
Used by 0 functions | Uses 5 functions

※801※

```
get_theme_mod()
```

Function: Retrieve theme modification value for the current theme.
Source: wp-includes/theme.php:918
Used by 23 functions | Uses 5 functions

※802※

```
get_theme_mods()
```

Function: Retrieve all theme modifications.
Source: wp-includes/theme.php:887
Used by 3 functions | Uses 6 functions

※803※

```
get_theme_root()
```

Function: Retrieve path to themes directory.
Source: wp-includes/theme.php:573
Used by 11 functions | Uses 3 functions

※804※

```
get_theme_roots()
```

Function: Retrieve theme roots.
Source: wp-includes/theme.php:371
Used by 1 function | Uses 2 functions

※805※

```
get_theme_root_uri()
```

Function: Retrieve URI for themes directory.
Source: wp-includes/theme.php:618
Used by 3 functions | Uses 7 functions

※806※

```
get_theme_starter_content()
```

Function: Expand a theme’s starter content configuration using core-provided data.
Source: wp-includes/theme.php:2038
Used by 1 function | Uses 6 functions

※807※

```
get_theme_support()
```

Function: Gets the theme support arguments passed when registering that support
Source: wp-includes/theme.php:2697
Used by 34 functions | Uses 0 functions

※808※

```
get_theme_updates()
```

Function:
Source: wp-admin/includes/update.php:545
Used by 4 functions | Uses 2 functions

※809※

```
get_theme_update_available()
```

Function: Retrieve the update link if there is a theme update available.
Source: wp-admin/includes/theme.php:168
Used by 2 functions | Uses 9 functions

※810※

```
get_the_archive_description()
```

Function: Retrieves the description for an author, post type, or term archive.
Source: wp-includes/general-template.php:1649
Used by 1 function | Uses 7 functions

※811※

```
get_the_archive_title()
```

Function: Retrieve the archive title based on the queried object.
Source: wp-includes/general-template.php:1558
Used by 1 function | Uses 20 functions

※812※

```
get_the_attachment_link()
```

Function: Retrieve HTML content of attachment image with link.
Source: wp-includes/deprecated.php:1846
Used by 0 functions | Uses 7 functions

※813※

```
get_the_author()
```

Function: Retrieve the author of the current post.
Source: wp-includes/author-template.php:23
Used by 6 functions | Uses 3 functions

※814※

```
get_the_author_aim()
```

Function: Retrieve the AIM address of the author of the current post.
Source: wp-includes/deprecated.php:1546
Used by 0 functions | Uses 2 functions

※815※

```
get_the_author_description()
```

Function: Retrieve the description of the author of the current post.
Source: wp-includes/deprecated.php:1312
Used by 0 functions | Uses 2 functions

※816※

```
get_the_author_email()
```

Function: Retrieve the email of the author of the current post.
Source: wp-includes/deprecated.php:1442
Used by 0 functions | Uses 2 functions

※817※

```
get_the_author_firstname()
```

Function: Retrieve the first name of the author of the current post.
Source: wp-includes/deprecated.php:1364
Used by 0 functions | Uses 2 functions

※818※

```
get_the_author_icq()
```

Function: Retrieve the ICQ number of the author of the current post.
Source: wp-includes/deprecated.php:1468
Used by 0 functions | Uses 2 functions

※819※

```
get_the_author_ID()
```

Function: Retrieve the ID of the author of the current post.
Source: wp-includes/deprecated.php:1613
Used by 0 functions | Uses 2 functions

※820※

```
get_the_author_lastname()
```

Function: Retrieve the last name of the author of the current post.
Source: wp-includes/deprecated.php:1390
Used by 0 functions | Uses 2 functions

※821※

```
get_the_author_link()
```

Function: Retrieve either author’s link or author’s name.
Source: wp-includes/author-template.php:229
Used by 1 function | Uses 5 functions

※822※

```
get_the_author_login()
```

Function: Retrieve the login name of the author of the current post.
Source: wp-includes/deprecated.php:1338
Used by 0 functions | Uses 2 functions

※823※

```
get_the_author_meta()
```

Function: Retrieves the requested data of the author of the current post.
Source: wp-includes/author-template.php:160
Used by 23 functions | Uses 3 functions

※824※

```
get_the_author_msn()
```

Function: Retrieve the MSN address of the author of the current post.
Source: wp-includes/deprecated.php:1520
Used by 0 functions | Uses 2 functions

※825※

```
get_the_author_nickname()
```

Function: Retrieve the nickname of the author of the current post.
Source: wp-includes/deprecated.php:1416
Used by 0 functions | Uses 2 functions

※826※

```
get_the_author_posts()
```

Function: Retrieve the number of posts by the author of the current post.
Source: wp-includes/author-template.php:264
Used by 1 function | Uses 2 functions

※827※

```
get_the_author_posts_link()
```

Function: Retrieves an HTML link to the author page of the current post’s author.
Source: wp-includes/author-template.php:293
Used by 1 function | Uses 7 functions

※828※

```
get_the_author_url()
```

Function: Retrieve the URL to the home page of the author of the current post.
Source: wp-includes/deprecated.php:1587
Used by 0 functions | Uses 2 functions

※829※

```
get_the_author_yim()
```

Function: Retrieve the Yahoo! IM name of the author of the current post.
Source: wp-includes/deprecated.php:1494
Used by 0 functions | Uses 2 functions

※830※

```
get_the_category()
```

Function: Retrieve post categories.
Source: wp-includes/category-template.php:76
Used by 5 functions | Uses 5 functions

※831※

```
get_the_category_by_ID()
```

Function: Retrieve category name based on category ID.
Source: wp-includes/category-template.php:108
Used by 1 function | Uses 2 functions

※832※

```
get_the_category_list()
```

Function: Retrieve category list for a post in either HTML list or custom format.
Source: wp-includes/category-template.php:132
Used by 1 function | Uses 11 functions

※833※

```
get_the_category_rss()
```

Function: Retrieve all of the post categories, formatted for use in feeds.
Source: wp-includes/feed.php:376
Used by 1 function | Uses 9 functions

※834※

```
get_the_comments_navigation()
```

Function: Retrieves navigation to next/previous set of comments, when applicable.
Source: wp-includes/link-template.php:3023
Used by 1 function | Uses 6 functions

※835※

```
get_the_comments_pagination()
```

Function: Retrieves a paginated navigation to next/previous set of comments, when applicable.
Source: wp-includes/link-template.php:3087
Used by 1 function | Uses 4 functions

※836※

```
get_the_content()
```

Function: Retrieve the post content.
Source: wp-includes/post-template.php:276
Used by 4 functions | Uses 12 functions

※837※

```
get_the_content_feed()
```

Function: Retrieve the post content for feeds.
Source: wp-includes/feed.php:185
Used by 1 function | Uses 5 functions

※838※

```
get_the_date()
```

Function: Retrieve the date on which the post was written.
Source: wp-includes/general-template.php:2394
Used by 4 functions | Uses 5 functions

※839※

```
get_the_excerpt()
```

Function: Retrieves the post excerpt.
Source: wp-includes/post-template.php:402
Used by 4 functions | Uses 6 functions

※840※

```
get_the_generator()
```

Function: Creates the generator XML or Comment for RSS, ATOM, etc.
Source: wp-includes/general-template.php:4568
Used by 1 function | Uses 7 functions

※841※

```
get_the_guid()
```

Function: Retrieve the Post Global Unique Identifier (guid).
Source: wp-includes/post-template.php:218
Used by 4 functions | Uses 3 functions

※842※

```
get_the_ID()
```

Function: Retrieve the ID of the current item in the WordPress Loop.
Source: wp-includes/post-template.php:27
Used by 14 functions | Uses 1 function

※843※

```
get_the_modified_author()
```

Function: Retrieve the author who last edited the current post.
Source: wp-includes/author-template.php:90
Used by 1 function | Uses 5 functions

※844※

```
get_the_modified_date()
```

Function: Retrieve the date on which the post was last modified.
Source: wp-includes/general-template.php:2465
Used by 1 function | Uses 5 functions

※845※

```
get_the_modified_time()
```

Function: Retrieve the time at which the post was last modified.
Source: wp-includes/general-template.php:2710
Used by 1 function | Uses 5 functions

※846※

```
get_the_password_form()
```

Function: Retrieve protected post password form content.
Source: wp-includes/post-template.php:1702
Used by 1 function | Uses 7 functions

※847※

```
get_the_permalink()
```

Function: Retrieves the full permalink for the current post or post ID.
Source: wp-includes/link-template.php:106
Used by 1 function | Uses 1 function

※848※

```
get_the_posts_navigation()
```

Function: Returns the navigation to next/previous set of posts, when applicable.
Source: wp-includes/link-template.php:2640
Used by 1 function | Uses 5 functions

※849※

```
get_the_posts_pagination()
```

Function: Retrieves a paginated navigation to next/previous set of posts, when applicable.
Source: wp-includes/link-template.php:2704
Used by 1 function | Uses 5 functions

※850※

```
get_the_post_navigation()
```

Function: Retrieves the navigation to next/previous post, when applicable.
Source: wp-includes/link-template.php:2562
Used by 1 function | Uses 5 functions

※851※

```
get_the_post_thumbnail()
```

Function: Retrieve the post thumbnail.
Source: wp-includes/post-thumbnail-template.php:134
Used by 1 function | Uses 11 functions

※852※

```
get_the_post_thumbnail_caption()
```

Function: Returns the post thumbnail caption.
Source: wp-includes/post-thumbnail-template.php:245
Used by 1 function | Uses 2 functions

※853※

```
get_the_post_thumbnail_url()
```

Function: Return the post thumbnail URL.
Source: wp-includes/post-thumbnail-template.php:213
Used by 1 function | Uses 2 functions

※854※

```
get_the_post_type_description()
```

Function: Retrieves the description for a post type archive.
Source: wp-includes/general-template.php:1675
Used by 1 function | Uses 4 functions

※855※

```
get_the_privacy_policy_link()
```

Function: Returns the privacy policy link with formatting, when applicable.
Source: wp-includes/link-template.php:4432
Used by 1 function | Uses 7 functions

※856※

```
get_the_tags()
```

Function: Retrieve the tags for a post.
Source: wp-includes/category-template.php:1125
Used by 1 function | Uses 3 functions

※857※

```
get_the_tag_list()
```

Function: Retrieve the tags for a post formatted as a string.
Source: wp-includes/category-template.php:1150
Used by 1 function | Uses 3 functions

※858※

```
get_the_taxonomies()
```

Function: Retrieve all taxonomies associated with a post.
Source: wp-includes/taxonomy.php:4330
Used by 1 function | Uses 10 functions

※859※

```
get_the_terms()
```

Function: Retrieve the terms of the taxonomy that are attached to the post.
Source: wp-includes/category-template.php:1230
Used by 9 functions | Uses 8 functions

※860※

```
get_the_term_list()
```

Function: Retrieve a post’s terms as a list with specified format.
Source: wp-includes/category-template.php:1275
Used by 2 functions | Uses 6 functions

※861※

```
get_the_time()
```

Function: Retrieve the time at which the post was written.
Source: wp-includes/general-template.php:2522
Used by 6 functions | Uses 5 functions

※862※

```
get_the_title()
```

Function: Retrieve post title.
Source: wp-includes/post-template.php:117
Used by 21 functions | Uses 7 functions

※863※

```
get_the_title_rss()
```

Function: Retrieve the current post title for the feed.
Source: wp-includes/feed.php:153
Used by 1 function | Uses 3 functions

※864※

```
get_to_ping()
```

Function: Retrieve URLs that need to be pinged.
Source: wp-includes/post.php:4778
Used by 2 functions | Uses 4 functions

※865※

```
get_trackback_url()
```

Function: Retrieve The current post’s trackback URL.
Source: wp-includes/comment-template.php:1124
Used by 2 functions | Uses 7 functions

※866※

```
get_transient()
```

Function: Get the value of a transient.
Source: wp-includes/option.php:679
Used by 16 functions | Uses 9 functions

※867※

```
get_translations_for_domain()
```

Function: Return the Translations instance for a text domain.
Source: wp-includes/l10n.php:1222
Used by 5 functions | Uses 1 function

※868※

```
get_udims()
```

Function: Calculated the new dimensions for a downsampled image.
Source: wp-admin/includes/deprecated.php:66
Used by 0 functions | Uses 2 functions

※869※

```
get_uploaded_header_images()
```

Function: Get the header images uploaded for the current theme.
Source: wp-includes/theme.php:1276
Used by 6 functions | Uses 6 functions

※870※

```
get_upload_iframe_src()
```

Function:
Source: wp-admin/includes/media.php:675
Used by 1 function | Uses 4 functions

※871※

```
get_upload_space_available()
```

Function: Determines if there is any upload space left in the current blog’s quota.
Source: wp-includes/ms-functions.php:2485
Used by 5 functions | Uses 3 functions

※872※

```
get_url_in_content()
```

Function: Extract and return the first URL from passed content.
Source: wp-includes/formatting.php:5471
Used by 0 functions | Uses 1 function

※873※

```
get_userdata()
```

Function: Retrieve user info by user ID.
Source: wp-includes/pluggable.php:82
Used by 71 functions | Uses 1 function

※874※

```
get_userdatabylogin()
```

Function: Retrieve user info by login name.
Source: wp-includes/pluggable-deprecated.php:66
Used by 0 functions | Uses 2 functions

※875※

```
get_usermeta()
```

Function: Retrieve user metadata.
Source: wp-includes/deprecated.php:2266
Used by 0 functions | Uses 4 functions

※876※

```
get_usernumposts()
```

Function: Retrieves the number of posts a user has written.
Source: wp-includes/deprecated.php:2433
Used by 0 functions | Uses 2 functions

※877※

```
get_users()
```

Function: Retrieve list of users matching criteria.
Source: wp-includes/user.php:573
Used by 9 functions | Uses 2 functions

※878※

```
get_users_drafts()
```

Function: Retrieve the user’s drafts.
Source: wp-admin/includes/user.php:306
Used by 0 functions | Uses 4 functions

※879※

```
get_users_of_blog()
```

Function: Get users for the site.
Source: wp-includes/deprecated.php:2373
Used by 0 functions | Uses 4 functions

※880※

```
get_user_by()
```

Function: Retrieve user info by a given field
Source: wp-includes/pluggable.php:98
Used by 31 functions | Uses 2 functions

※881※

```
get_user_by_email()
```

Function: Retrieve user info by email.
Source: wp-includes/pluggable-deprecated.php:83
Used by 0 functions | Uses 2 functions

※882※

```
get_user_count()
```

Function: The number of active users in your installation.
Source: wp-includes/ms-functions.php:109
Used by 6 functions | Uses 1 function

※883※

```
get_user_details()
```

Function: Deprecated functionality to retrieve user information.
Source: wp-includes/ms-deprecated.php:129
Used by 0 functions | Uses 2 functions

※884※

```
get_user_id_from_string()
```

Function: Get a numeric user ID from either an email address or a login.
Source: wp-includes/ms-deprecated.php:340
Used by 0 functions | Uses 3 functions

※885※

```
get_user_locale()
```

Function: Retrieves the locale of a user.
Source: wp-includes/l10n.php:94
Used by 33 functions | Uses 3 functions

※886※

```
get_user_meta()
```

Function: Retrieve user meta field for a user.
Source: wp-includes/user.php:826
Used by 20 functions | Uses 1 function

※887※

```
get_user_metavalues()
```

Function: Perform the query to get the $metavalues array(s) needed by _fill_user and _fill_many_users
Source: wp-includes/deprecated.php:2599
Used by 0 functions | Uses 2 functions

※888※

```
get_user_option()
```

Function: Retrieve user option that can be either per Site or per Network.
Source: wp-includes/user.php:466
Used by 30 functions | Uses 6 functions

※889※

```
get_user_setting()
```

Function: Retrieve user interface setting value based on setting name.
Source: wp-includes/option.php:972
Used by 15 functions | Uses 1 function

※890※

```
get_user_to_edit()
```

Function: Retrieve user data and filter it.
Source: wp-admin/includes/user.php:286
Used by 0 functions | Uses 1 function

※891※

```
get_weekstartend()
```

Function: Get the week start and end from the datetime or date string from MySQL.
Source: wp-includes/functions.php:531
Used by 1 function | Uses 1 function

※892※

```
get_wp_title_rss()
```

Function: Retrieve the blog title for the feed title.
Source: wp-includes/feed.php:100
Used by 2 functions | Uses 5 functions

※893※

```
get_year_link()
```

Function: Retrieves the permalink for the year archives.
Source: wp-includes/link-template.php:470
Used by 2 functions | Uses 6 functions

※894※

```
global_terms()
```

Function: Maintains a canonical list of terms by syncing terms created for each blog with the global terms table.
Source: wp-includes/ms-functions.php:1891
Used by 1 function | Uses 10 functions

※895※

```
global_terms_enabled()
```

Function: Determine whether global terms are enabled.
Source: wp-includes/functions.php:5284
Used by 5 functions | Uses 4 functions

※896※

```
got_mod_rewrite()
```

Function: Returns whether the server is running Apache with the mod_rewrite module loaded.
Source: wp-admin/includes/misc.php:16
Used by 3 functions | Uses 3 functions

※897※

```
got_url_rewrite()
```

Function: Returns whether the server supports URL rewriting.
Source: wp-admin/includes/misc.php:45
Used by 0 functions | Uses 4 functions

※898※

```
graceful_fail()
```

Function: Deprecated functionality to gracefully fail.
Source: wp-includes/ms-deprecated.php:89
Used by 0 functions | Uses 2 functions

※899※

```
grant_super_admin()
```

Function: Grants Super Admin privileges.
Source: wp-includes/capabilities.php:896
Used by 0 functions | Uses 7 functions

※900※

```
gzip_compression()
```

Function: Unused function.
Source: wp-includes/deprecated.php:1201
Used by 0 functions | Uses 1 function

※901※

```
hash_equals()
```

Function: Timing attack safe string comparison
Source: wp-includes/compat.php:313
Used by 10 functions | Uses 0 functions

※902※

```
hash_hmac()
```

Function:
Source: wp-includes/compat.php:156
Used by 0 functions | Uses 0 functions

※903※

```
has_action()
```

Function: Check if any action has been registered for a hook.
Source: wp-includes/plugin.php:565
Used by 10 functions | Uses 1 function

※904※

```
has_block()
```

Function: Determine whether a $post or a string contains a specific block type.
Source: wp-includes/blocks.php:81
Used by 1 function | Uses 2 functions

※905※

```
has_blocks()
```

Function: Determine whether a post or content string has blocks.
Source: wp-includes/blocks.php:56
Used by 4 functions | Uses 1 function

※906※

```
has_category()
```

Function: Check if the current post has any of given category.
Source: wp-includes/category-template.php:1418
Used by 1 function | Uses 1 function

※907※

```
has_custom_header()
```

Function: Check whether a custom header is set or not.
Source: wp-includes/theme.php:1514
Used by 1 function | Uses 3 functions

※908※

```
has_custom_logo()
```

Function: Determines whether the site has a custom logo.
Source: wp-includes/general-template.php:923
Used by 1 function | Uses 5 functions

※909※

```
has_excerpt()
```

Function: Determines whether the post has a custom excerpt.
Source: wp-includes/post-template.php:440
Used by 1 function | Uses 1 function

※910※

```
has_filter()
```

Function: Check if any filter has been registered for a hook.
Source: wp-includes/plugin.php:133
Used by 18 functions | Uses 0 functions

※911※

```
has_header_image()
```

Function: Check whether a header image is set or not.
Source: wp-includes/theme.php:1065
Used by 1 function | Uses 1 function

※912※

```
has_header_video()
```

Function: Check whether a header video is set or not.
Source: wp-includes/theme.php:1413
Used by 2 functions | Uses 1 function

※913※

```
has_image_size()
```

Function: Check if an image size exists.
Source: wp-includes/media.php:303
Used by 0 functions | Uses 1 function

※914※

```
has_meta()
```

Function: Get meta data for the given post ID.
Source: wp-admin/includes/post.php:988
Used by 2 functions | Uses 2 functions

※915※

```
has_nav_menu()
```

Function: Determines whether a registered nav menu location has a menu assigned to it.
Source: wp-includes/nav-menu.php:177
Used by 0 functions | Uses 4 functions

※916※

```
has_post_format()
```

Function: Check if a post has any of the given formats, or any format.
Source: wp-includes/post-formats.php:48
Used by 0 functions | Uses 2 functions

※917※

```
has_post_thumbnail()
```

Function: Determines whether a post has an image attached.
Source: wp-includes/post-thumbnail-template.php:25
Used by 3 functions | Uses 3 functions

※918※

```
has_shortcode()
```

Function: Whether the passed content contains the specified shortcode
Source: wp-includes/shortcodes.php:140
Used by 3 functions | Uses 3 functions

※919※

```
has_site_icon()
```

Function: Whether the site has a Site Icon.
Source: wp-includes/general-template.php:911
Used by 1 function | Uses 1 function

※920※

```
has_tag()
```

Function: Check if the current post has any of given tags.
Source: wp-includes/category-template.php:1443
Used by 0 functions | Uses 1 function

※921※

```
has_term()
```

Function: Check if the current post has any of given terms.
Source: wp-includes/category-template.php:1461
Used by 4 functions | Uses 3 functions

※922※

```
has_term_meta()
```

Function: Get all meta data, including meta IDs, for the given term ID.
Source: wp-includes/taxonomy.php:1303
Used by 1 function | Uses 3 functions

※923※

```
have_comments()
```

Function: Whether there are comments to loop over.
Source: wp-includes/query.php:953
Used by 0 functions | Uses 1 function

※924※

```
have_posts()
```

Function: Whether current WordPress query has results to loop over.
Source: wp-includes/query.php:893
Used by 3 functions | Uses 1 function

※925※

```
header_image()
```

Function: Display header image URL.
Source: wp-includes/theme.php:1262
Used by 0 functions | Uses 2 functions

※926※

```
header_textcolor()
```

Function: Displays the custom header text color in 3- or 6-digit hexadecimal form (minus the hash symbol).
Source: wp-includes/theme.php:1036
Used by 0 functions | Uses 1 function

※927※

```
heartbeat_autosave()
```

Function: Autosave with heartbeat
Source: wp-admin/includes/misc.php:1176
Used by 0 functions | Uses 4 functions

※928※

```
hello_dolly()
```

Function:
Source: wp-content/plugins/hello.php:54
Used by 0 functions | Uses 0 functions

※929※

```
hello_dolly_get_lyric()
```

Function:
Source: wp-content/plugins/hello.php:15
Used by 0 functions | Uses 0 functions

※930※

```
home_url()
```

Function: Retrieves the URL for the current site where the front end is accessible.
Source: wp-includes/link-template.php:3143
Used by 95 functions | Uses 1 function

※931※

```
htmlentities2()
```

Function: Convert entities, while preserving already-encoded entities.
Source: wp-includes/formatting.php:4394
Used by 0 functions | Uses 0 functions

※932※

```
html_type_rss()
```

Function: Display the HTML type based on the blog setting.
Source: wp-includes/feed.php:445
Used by 0 functions | Uses 1 function

※933※

```
human_readable_duration()
```

Function: Convert a duration to human readable format.
Source: wp-includes/functions.php:461
Used by 1 function | Uses 1 function

※934※

```
human_time_diff()
```

Function: Determines the difference between two timestamps.
Source: wp-includes/formatting.php:3695
Used by 9 functions | Uses 3 functions

※935※

```
iframe_footer()
```

Function: Generic Iframe footer for use with Thickbox
Source: wp-admin/includes/template.php:2034
Used by 2 functions | Uses 4 functions

※936※

```
iframe_header()
```

Function: Generic Iframe header for use with Thickbox
Source: wp-admin/includes/template.php:1953
Used by 2 functions | Uses 21 functions

※937※

```
iis7_add_rewrite_rule()
```

Function: Add WordPress rewrite rule to the IIS 7+ configuration file.
Source: wp-admin/includes/misc.php:792
Used by 1 function | Uses 1 function

※938※

```
iis7_delete_rewrite_rule()
```

Function: Delete WordPress rewrite rule from web.config file if it exists there
Source: wp-admin/includes/misc.php:755
Used by 1 function | Uses 1 function

※939※

```
iis7_rewrite_rule_exists()
```

Function: Check if rewrite rule for WordPress already exists in the IIS 7+ configuration file
Source: wp-admin/includes/misc.php:726
Used by 0 functions | Uses 0 functions

※940※

```
iis7_save_url_rewrite_rules()
```

Function: Updates the IIS web.config file with the current rules if it is writable.
Source: wp-admin/includes/misc.php:279
Used by 1 function | Uses 8 functions

※941※

```
iis7_supports_permalinks()
```

Function: Check if IIS 7+ supports pretty permalinks.
Source: wp-includes/functions.php:4975
Used by 4 functions | Uses 2 functions

※942※

```
image_add_caption()
```

Function: Adds image shortcode with caption to editor
Source: wp-admin/includes/media.php:186
Used by 0 functions | Uses 4 functions

※943※

```
image_align_input_fields()
```

Function: Retrieve HTML for the image alignment radio buttons with the specified one checked.
Source: wp-admin/includes/media.php:1087
Used by 1 function | Uses 3 functions

※944※

```
image_attachment_fields_to_edit()
```

Function: Retrieves the image attachment fields to edit form fields.
Source: wp-admin/includes/media.php:1252
Used by 0 functions | Uses 0 functions

※945※

```
image_attachment_fields_to_save()
```

Function: Filters input from media_upload_form_handler() and assigns a default post_title from the file name if none supplied.
Source: wp-admin/includes/media.php:1297
Used by 0 functions | Uses 2 functions

※946※

```
image_constrain_size_for_editor()
```

Function: Scale down the default size of an image.
Source: wp-includes/media.php:59
Used by 3 functions | Uses 6 functions

※947※

```
image_downsize()
```

Function: Scale an image to fit a particular size (such as ‘thumb’ or ‘medium’).
Source: wp-includes/media.php:185
Used by 5 functions | Uses 9 functions

※948※

```
image_edit_apply_changes()
```

Function: Performs group of changes on Editor specified.
Source: wp-admin/includes/image-edit.php:497
Used by 2 functions | Uses 5 functions

※949※

```
image_get_intermediate_size()
```

Function: Retrieves the image’s intermediate size (resized) path, width, and height.
Source: wp-includes/media.php:738
Used by 3 functions | Uses 7 functions

※950※

```
image_hwstring()
```

Function: Retrieve width and height attributes using given width and height values.
Source: wp-includes/media.php:149
Used by 2 functions | Uses 0 functions

※951※

```
image_link_input_fields()
```

Function: Retrieve HTML for the Link URL buttons with the default link type as specified.
Source: wp-admin/includes/media.php:1203
Used by 1 function | Uses 5 functions

※952※

```
image_make_intermediate_size()
```

Function: Resizes an image to make a thumbnail or intermediate size.
Source: wp-includes/media.php:654
Used by 0 functions | Uses 2 functions

※953※

```
image_media_send_to_editor()
```

Function: Retrieves the media element HTML to send to the editor.
Source: wp-admin/includes/media.php:1319
Used by 0 functions | Uses 3 functions

※954※

```
image_resize()
```

Function: Scale down an image to fit a particular size and save a new copy of the image.
Source: wp-includes/deprecated.php:3230
Used by 1 function | Uses 3 functions

※955※

```
image_resize_dimensions()
```

Function: Retrieves calculated resize dimensions for use in WP_Image_Editor.
Source: wp-includes/media.php:510
Used by 3 functions | Uses 5 functions

※956※

```
image_size_input_fields()
```

Function: Retrieve HTML for the size radio buttons with the specified one checked.
Source: wp-admin/includes/media.php:1125
Used by 1 function | Uses 6 functions

※957※

```
img_caption_shortcode()
```

Function: Builds the Caption shortcode output.
Source: wp-includes/media.php:1635
Used by 1 function | Uses 9 functions

※958※

```
includes_url()
```

Function: Retrieves the URL to the includes directory.
Source: wp-includes/link-template.php:3324
Used by 12 functions | Uses 3 functions

※959※

```
index_rel_link()
```

Function: Display relational link for the site index.
Source: wp-includes/deprecated.php:2737
Used by 0 functions | Uses 2 functions

※960※

```
init()
```

Function: Set up constants with default values, unless user overrides.
Source: wp-includes/rss.php:640
Used by 1 function | Uses 0 functions

※961※

```
insert_blog()
```

Function: Store basic site info in the blogs table.
Source: wp-includes/ms-deprecated.php:570
Used by 1 function | Uses 4 functions

※962※

```
insert_with_markers()
```

Function: Inserts an array of strings into a file (.htaccess ), placing it between BEGIN and END markers.
Source: wp-admin/includes/misc.php:109
Used by 1 function | Uses 6 functions

※963※

```
install_blog()
```

Function: Install an empty blog.
Source: wp-includes/ms-deprecated.php:605
Used by 1 function | Uses 20 functions

※964※

```
install_blog_defaults()
```

Function: Set blog defaults.
Source: wp-includes/ms-deprecated.php:675
Used by 0 functions | Uses 3 functions

※965※

```
install_dashboard()
```

Function:
Source: wp-admin/includes/plugin-install.php:263
Used by 0 functions | Uses 9 functions

※966※

```
install_global_terms()
```

Function: Install global terms.
Source: wp-admin/includes/upgrade.php:3317
Used by 0 functions | Uses 1 function

※967※

```
install_network()
```

Function: Install Network.
Source: wp-admin/includes/schema.php:933
Used by 0 functions | Uses 2 functions

※968※

```
install_plugins_favorites_form()
```

Function: Show a username form for the favorites page
Source: wp-admin/includes/plugin-install.php:366
Used by 0 functions | Uses 6 functions

※969※

```
install_plugins_upload()
```

Function: Upload from zip
Source: wp-admin/includes/plugin-install.php:347
Used by 0 functions | Uses 5 functions

※970※

```
install_plugin_information()
```

Function: Display plugin information in dialog box form.
Source: wp-admin/includes/plugin-install.php:512
Used by 0 functions | Uses 30 functions

※971※

```
install_plugin_install_status()
```

Function: Determine the status we can perform on a plugin.
Source: wp-admin/includes/plugin-install.php:434
Used by 4 functions | Uses 9 functions

※972※

```
install_popular_tags()
```

Function: Retrieve popular WordPress plugin tags.
Source: wp-admin/includes/plugin-install.php:242
Used by 1 function | Uses 4 functions

※973※

```
install_search_form()
```

Function: Displays a search form for searching plugins.
Source: wp-admin/includes/plugin-install.php:322
Used by 1 function | Uses 8 functions

※974※

```
install_themes_dashboard()
```

Function: Display tags filter for themes.
Source: wp-admin/includes/theme-install.php:136
Used by 0 functions | Uses 7 functions

※975※

```
install_themes_feature_list()
```

Function: Retrieve list of WordPress theme features (aka theme tags)
Source: wp-admin/includes/theme-install.php:62
Used by 0 functions | Uses 5 functions

※976※

```
install_themes_upload()
```

Function:
Source: wp-admin/includes/theme-install.php:180
Used by 0 functions | Uses 5 functions

※977※

```
install_theme_information()
```

Function: Display theme information in dialog box form.
Source: wp-admin/includes/theme-install.php:236
Used by 0 functions | Uses 8 functions

※978※

```
install_theme_search_form()
```

Function: Display search form for searching themes.
Source: wp-admin/includes/theme-install.php:91
Used by 1 function | Uses 7 functions

※979※

```
in_category()
```

Function: Check if the current post is within any of the given categories.
Source: wp-includes/category-template.php:245
Used by 0 functions | Uses 1 function

※980※

```
in_the_loop()
```

Function: Determines whether the caller is in the Loop.
Source: wp-includes/query.php:911
Used by 1 function | Uses 0 functions

※981※

```
iso8601_timezone_to_offset()
```

Function: Computes an offset in seconds from an iso8601 timezone.
Source: wp-includes/formatting.php:3538
Used by 0 functions | Uses 0 functions

※982※

```
iso8601_to_datetime()
```

Function: Converts an iso8601 date to MySQL DateTime format used by post_date[_gmt].
Source: wp-includes/formatting.php:3560
Used by 4 functions | Uses 1 function

※983※

```
is_404()
```

Function: Determines whether the query has resulted in a 404 (returns no results).
Source: wp-includes/query.php:819
Used by 11 functions | Uses 3 functions

※984※

```
is_active_sidebar()
```

Function: Determines whether a sidebar is in use.
Source: wp-includes/widgets.php:932
Used by 0 functions | Uses 4 functions

※985※

```
is_active_widget()
```

Function: Determines whether a given widget is displayed on the front end.
Source: wp-includes/widgets.php:866
Used by 3 functions | Uses 2 functions

※986※

```
is_admin()
```

Function: Determines whether the current request is for an administrative interface page.
Source: wp-includes/load.php:982
Used by 61 functions | Uses 0 functions

※987※

```
is_admin_bar_showing()
```

Function: Determines whether the admin bar should be showing.
Source: wp-includes/admin-bar.php:1176
Used by 4 functions | Uses 7 functions

※988※

```
is_allowed_http_origin()
```

Function: Determines if the HTTP origin is an authorized one.
Source: wp-includes/http.php:455
Used by 1 function | Uses 4 functions

※989※

```
is_archive()
```

Function: Determines whether the query is for an existing archive page.
Source: wp-includes/query.php:153
Used by 3 functions | Uses 3 functions

※990※

```
is_archived()
```

Function: Check if a particular blog is archived.
Source: wp-includes/ms-blogs.php:664
Used by 0 functions | Uses 1 function

※991※

```
is_attachment()
```

Function: Determines whether the query is for an existing attachment page.
Source: wp-includes/query.php:203
Used by 9 functions | Uses 3 functions

※992※

```
is_author()
```

Function: Determines whether the query is for an existing author archive page.
Source: wp-includes/query.php:231
Used by 9 functions | Uses 3 functions

※993※

```
is_avatar_comment_type()
```

Function: Check if this comment type allows avatars to be retrieved.
Source: wp-includes/link-template.php:4027
Used by 1 function | Uses 2 functions

※994※

```
is_blog_admin()
```

Function: Whether the current request is for a site’s admininstrative interface.
Source: wp-includes/load.php:1006
Used by 3 functions | Uses 0 functions

※995※

```
is_blog_installed()
```

Function: Determines whether WordPress is already installed.
Source: wp-includes/functions.php:1652
Used by 3 functions | Uses 11 functions

※996※

```
is_blog_user()
```

Function: Checks if the current user belong to a given site.
Source: wp-includes/deprecated.php:2821
Used by 0 functions | Uses 3 functions

※997※

```
is_category()
```

Function: Determines whether the query is for an existing category archive page.
Source: wp-includes/query.php:259
Used by 11 functions | Uses 3 functions

※998※

```
is_child_theme()
```

Function: Whether a child theme is in use.
Source: wp-includes/theme.php:152
Used by 4 functions | Uses 0 functions

※999※

```
is_client_error()
```

Function:
Source: wp-includes/rss.php:707
Used by 0 functions | Uses 0 functions

※1000※

```
is_comments_popup()
```

Function: Determines whether the current URL is within the comments popup window.
Source: wp-includes/deprecated.php:3732
Used by 0 functions | Uses 1 function

※1001※

```
is_comment_feed()
```

Function: Is the query for a comments feed?
Source: wp-includes/query.php:415
Used by 1 function | Uses 3 functions

※1002※

```
is_countable()
```

Function: Polyfill for is_countable() function added in PHP 7.3.
Source: wp-includes/compat.php:351
Used by 0 functions | Uses 0 functions

※1003※

```
is_customize_preview()
```

Function: Whether the site is being previewed in the Customizer.
Source: wp-includes/theme.php:3268
Used by 11 functions | Uses 0 functions

※1004※

```
is_date()
```

Function: Determines whether the query is for an existing date archive.
Source: wp-includes/query.php:344
Used by 1 function | Uses 3 functions

※1005※

```
is_day()
```

Function: Determines whether the query is for an existing day archive.
Source: wp-includes/query.php:370
Used by 3 functions | Uses 3 functions

※1006※

```
is_dynamic_sidebar()
```

Function: Determines whether the dynamic sidebar is enabled and used by the theme.
Source: wp-includes/widgets.php:905
Used by 0 functions | Uses 1 function

※1007※

```
is_email()
```

Function: Verifies that an email is valid.
Source: wp-includes/formatting.php:3374
Used by 22 functions | Uses 3 functions

※1008※

```
is_email_address_unsafe()
```

Function: Checks an email address against a list of banned domains.
Source: wp-includes/ms-functions.php:385
Used by 1 function | Uses 3 functions

※1009※

```
is_embed()
```

Function: Is the query for an embedded post?
Source: wp-includes/query.php:839
Used by 3 functions | Uses 3 functions

※1010※

```
is_error()
```

Function:
Source: wp-includes/rss.php:703
Used by 0 functions | Uses 0 functions

※1011※

```
is_feed()
```

Function: Determines whether the query is for a feed.
Source: wp-includes/query.php:395
Used by 5 functions | Uses 3 functions

※1012※

```
is_front_page()
```

Function: Determines whether the query is for the front page of the site.
Source: wp-includes/query.php:448
Used by 6 functions | Uses 3 functions

※1013※

```
is_header_video_active()
```

Function: Checks whether the custom header video is eligible to show on the current page.
Source: wp-includes/theme.php:1529
Used by 2 functions | Uses 3 functions

※1014※

```
is_home()
```

Function: Determines whether the query is for the blog homepage.
Source: wp-includes/query.php:481
Used by 6 functions | Uses 3 functions

※1015※

```
is_info()
```

Function:
Source: wp-includes/rss.php:691
Used by 0 functions | Uses 0 functions

※1016※

```
is_iterable()
```

Function: Polyfill for is_iterable() function added in PHP 7.1.
Source: wp-includes/compat.php:373
Used by 0 functions | Uses 0 functions

※1017※

```
is_lighttpd_before_150()
```

Function: Is the server running earlier than 1.5.0 version of lighttpd?
Source: wp-includes/functions.php:4926
Used by 0 functions | Uses 0 functions

※1018※

```
is_locale_switched()
```

Function: Whether switch_to_locale() is in effect.
Source: wp-includes/l10n.php:1626
Used by 0 functions | Uses 1 function

※1019※

```
is_local_attachment()
```

Function: Determines whether an attachment URI is local and really an attachment.
Source: wp-includes/post.php:5486
Used by 1 function | Uses 3 functions

※1020※

```
is_main_blog()
```

Function: Deprecated functionality to determin if the current site is the main site.
Source: wp-includes/ms-deprecated.php:154
Used by 0 functions | Uses 2 functions

※1021※

```
is_main_network()
```

Function: Determine whether a network is the main network of the Multisite installation.
Source: wp-includes/functions.php:5222
Used by 4 functions | Uses 3 functions

※1022※

```
is_main_query()
```

Function: Determines whether the query is the main query.
Source: wp-includes/query.php:863
Used by 0 functions | Uses 4 functions

※1023※

```
is_main_site()
```

Function: Determine whether a site is the main site of the current network.
Source: wp-includes/functions.php:5178
Used by 16 functions | Uses 3 functions

※1024※

```
is_month()
```

Function: Determines whether the query is for an existing month archive.
Source: wp-includes/query.php:535
Used by 3 functions | Uses 3 functions

※1025※

```
is_multisite()
```

Function: If Multisite is enabled.
Source: wp-includes/load.php:1074
Used by 146 functions | Uses 0 functions

※1026※

```
is_multi_author()
```

Function: Determines whether this site has more than one author.
Source: wp-includes/author-template.php:542
Used by 0 functions | Uses 5 functions

※1027※

```
is_nav_menu()
```

Function: Check if the given ID is a navigation menu.
Source: wp-includes/nav-menu.php:62
Used by 2 functions | Uses 2 functions

※1028※

```
is_nav_menu_item()
```

Function: Determines whether the given ID is a nav menu item.
Source: wp-includes/nav-menu.php:237
Used by 3 functions | Uses 2 functions

※1029※

```
is_network_admin()
```

Function: Whether the current request is for the network administrative interface.
Source: wp-includes/load.php:1033
Used by 15 functions | Uses 0 functions

※1030※

```
is_network_only_plugin()
```

Function: Checks for “Network: true” in the plugin header to see if this should be activated only as a network wide plugin. The plugin would also work when Multisite is not enabled.
Source: wp-admin/includes/plugin.php:582
Used by 4 functions | Uses 1 function

※1031※

```
is_new_day()
```

Function: Determines whether the publish date of the current post in the loop is different from the publish date of the previous post in the loop.
Source: wp-includes/functions.php:940
Used by 1 function | Uses 0 functions

※1032※

```
is_object_in_taxonomy()
```

Function: Determine if the given object type is associated with the given taxonomy.
Source: wp-includes/taxonomy.php:4476
Used by 9 functions | Uses 1 function

※1033※

```
is_object_in_term()
```

Function: Determine if the given object is associated with any of the given terms.
Source: wp-includes/taxonomy.php:4407
Used by 2 functions | Uses 7 functions

※1034※

```
is_page()
```

Function: Determines whether the query is for an existing single page.
Source: wp-includes/query.php:566
Used by 5 functions | Uses 3 functions

※1035※

```
is_paged()
```

Function: Determines whether the query is for paged results and not for the first page.
Source: wp-includes/query.php:590
Used by 4 functions | Uses 3 functions

※1036※

```
is_page_template()
```

Function: Determines whether currently in a page template.
Source: wp-includes/post-template.php:1742
Used by 1 function | Uses 3 functions

※1037※

```
is_php_version_compatible()
```

Function: Checks compatibility with the current PHP version.
Source: wp-includes/functions.php:7302
Used by 6 functions | Uses 0 functions

※1038※

```
is_plugin_active()
```

Function: Determines whether a plugin is active.
Source: wp-admin/includes/plugin.php:517
Used by 16 functions | Uses 2 functions

※1039※

```
is_plugin_active_for_network()
```

Function: Determines whether the plugin is active for the entire network.
Source: wp-admin/includes/plugin.php:557
Used by 6 functions | Uses 2 functions

※1040※

```
is_plugin_inactive()
```

Function: Determines whether the plugin is inactive.
Source: wp-admin/includes/plugin.php:536
Used by 2 functions | Uses 1 function

※1041※

```
is_plugin_page()
```

Function: Determines whether the current admin page is generated by a plugin.
Source: wp-includes/deprecated.php:2527
Used by 0 functions | Uses 1 function

※1042※

```
is_plugin_paused()
```

Function: Determines whether a plugin is technically active but was paused while loading.
Source: wp-admin/includes/plugin.php:2290
Used by 2 functions | Uses 1 function

※1043※

```
is_post_type_archive()
```

Function: Determines whether the query is for an existing post type archive page.
Source: wp-includes/query.php:178
Used by 9 functions | Uses 3 functions

※1044※

```
is_post_type_hierarchical()
```

Function: Whether the post type is hierarchical.
Source: wp-includes/post.php:1171
Used by 17 functions | Uses 2 functions

※1045※

```
is_post_type_viewable()
```

Function: Determines whether a post type is considered “viewable”.
Source: wp-includes/post.php:1968
Used by 11 functions | Uses 1 function

※1046※

```
is_preview()
```

Function: Determines whether the query is for a post or page preview.
Source: wp-includes/query.php:614
Used by 3 functions | Uses 3 functions

※1047※

```
is_privacy_policy()
```

Function: Determines whether the query is for the Privacy Policy page.
Source: wp-includes/query.php:511
Used by 1 function | Uses 3 functions

※1048※

```
is_protected_ajax_action()
```

Function: Determines whether we are currently handling an AJAX action that should be protected against WSODs.
Source: wp-includes/load.php:858
Used by 1 function | Uses 3 functions

※1049※

```
is_protected_endpoint()
```

Function: Determines whether we are currently on an endpoint that should be protected against WSODs.
Source: wp-includes/load.php:821
Used by 2 functions | Uses 5 functions

※1050※

```
is_protected_meta()
```

Function: Determine whether a meta key is protected.
Source: wp-includes/meta.php:1039
Used by 10 functions | Uses 2 functions

※1051※

```
is_random_header_image()
```

Function: Check if random header image is in use.
Source: wp-includes/theme.php:1239
Used by 4 functions | Uses 3 functions

※1052※

```
is_redirect()
```

Function:
Source: wp-includes/rss.php:699
Used by 0 functions | Uses 0 functions

※1053※

```
is_registered_sidebar()
```

Function: Checks if a sidebar is registered.
Source: wp-includes/widgets.php:332
Used by 6 functions | Uses 0 functions

※1054※

```
is_robots()
```

Function: Is the query for the robots file?
Source: wp-includes/query.php:634
Used by 2 functions | Uses 3 functions

※1055※

```
is_rtl()
```

Function: Determines whether the current locale is right-to-left (RTL).
Source: wp-includes/l10n.php:1560
Used by 18 functions | Uses 1 function

※1056※

```
is_search()
```

Function: Determines whether the query is for a search.
Source: wp-includes/query.php:658
Used by 6 functions | Uses 3 functions

※1057※

```
is_serialized()
```

Function: Check value to find if it was serialized.
Source: wp-includes/functions.php:590
Used by 5 functions | Uses 0 functions

※1058※

```
is_serialized_string()
```

Function: Check whether serialized data is of string type.
Source: wp-includes/functions.php:656
Used by 1 function | Uses 0 functions

※1059※

```
is_server_error()
```

Function:
Source: wp-includes/rss.php:711
Used by 0 functions | Uses 0 functions

※1060※

```
is_single()
```

Function: Determines whether the query is for an existing single post.
Source: wp-includes/query.php:691
Used by 10 functions | Uses 3 functions

※1061※

```
is_singular()
```

Function: Determines whether the query is for an existing single post of any post type (post, attachment, page, custom post types).
Source: wp-includes/query.php:723
Used by 20 functions | Uses 3 functions

※1062※

```
is_site_admin()
```

Function: Determine if user is a site admin.
Source: wp-includes/ms-deprecated.php:64
Used by 0 functions | Uses 4 functions

※1063※

```
is_site_meta_supported()
```

Function: Determines whether site meta is enabled.
Source: wp-includes/functions.php:5325
Used by 4 functions | Uses 5 functions

※1064※

```
is_ssl()
```

Function: Determines if SSL is used.
Source: wp-includes/load.php:1261
Used by 26 functions | Uses 0 functions

※1065※

```
is_sticky()
```

Function: Check if post is sticky.
Source: wp-includes/post.php:2267
Used by 11 functions | Uses 5 functions

※1066※

```
is_subdomain_install()
```

Function: Whether a subdomain configuration is enabled.
Source: wp-includes/ms-load.php:18
Used by 15 functions | Uses 0 functions

※1067※

```
is_success()
```

Function:
Source: wp-includes/rss.php:695
Used by 1 function | Uses 0 functions

※1068※

```
is_super_admin()
```

Function: Determine if user is a site admin.
Source: wp-includes/capabilities.php:860
Used by 7 functions | Uses 5 functions

※1069※

```
is_tag()
```

Function: Determines whether the query is for an existing tag archive page.
Source: wp-includes/query.php:287
Used by 10 functions | Uses 3 functions

※1070※

```
is_tax()
```

Function: Determines whether the query is for an existing custom taxonomy archive page.
Source: wp-includes/query.php:320
Used by 10 functions | Uses 3 functions

※1071※

```
is_taxonomy()
```

Function: Checks that the taxonomy name exists.
Source: wp-includes/deprecated.php:2489
Used by 0 functions | Uses 2 functions

※1072※

```
is_taxonomy_hierarchical()
```

Function: Determines whether the taxonomy object is hierarchical.
Source: wp-includes/taxonomy.php:310
Used by 20 functions | Uses 2 functions

※1073※

```
is_taxonomy_viewable()
```

Function: Determines whether a taxonomy is considered “viewable”.
Source: wp-includes/taxonomy.php:4609
Used by 2 functions | Uses 1 function

※1074※

```
is_term()
```

Function: Check if Term exists.
Source: wp-includes/deprecated.php:2506
Used by 0 functions | Uses 2 functions

※1075※

```
is_textdomain_loaded()
```

Function: Whether there are translations for the text domain.
Source: wp-includes/l10n.php:1246
Used by 2 functions | Uses 0 functions

※1076※

```
is_theme_paused()
```

Function: Determines whether a theme is technically active but was paused while loading.
Source: wp-admin/includes/theme.php:814
Used by 0 functions | Uses 2 functions

※1077※

```
is_time()
```

Function: Determines whether the query is for a specific time.
Source: wp-includes/query.php:747
Used by 0 functions | Uses 3 functions

※1078※

```
is_trackback()
```

Function: Determines whether the query is for a trackback endpoint call.
Source: wp-includes/query.php:771
Used by 2 functions | Uses 3 functions

※1079※

```
is_uninstallable_plugin()
```

Function: Whether the plugin can be uninstalled.
Source: wp-admin/includes/plugin.php:1164
Used by 1 function | Uses 2 functions

※1080※

```
is_upload_space_available()
```

Function: Determines if there is any upload space left in the current blog’s quota.
Source: wp-includes/ms-functions.php:2510
Used by 4 functions | Uses 2 functions

※1081※

```
is_user_admin()
```

Function: Whether the current request is for a user admin screen.
Source: wp-includes/load.php:1057
Used by 6 functions | Uses 0 functions

※1082※

```
is_user_logged_in()
```

Function: Determines whether the current visitor is a logged in user.
Source: wp-includes/pluggable.php:1001
Used by 45 functions | Uses 1 function

※1083※

```
is_user_member_of_blog()
```

Function: Find out whether a user is a member of a given blog.
Source: wp-includes/user.php:726
Used by 6 functions | Uses 6 functions

※1084※

```
is_user_option_local()
```

Function: Check whether a usermeta key has to do with the current blog.
Source: wp-includes/ms-deprecated.php:541
Used by 0 functions | Uses 4 functions

※1085※

```
is_user_spammy()
```

Function: Check to see whether a user is marked as a spammer, based on user login.
Source: wp-includes/ms-functions.php:2186
Used by 2 functions | Uses 2 functions

※1086※

```
is_wpmu_sitewide_plugin()
```

Function: Deprecated functionality for determining if the current plugin is network-only.
Source: wp-admin/includes/ms-deprecated.php:78
Used by 0 functions | Uses 2 functions

※1087※

```
is_wp_error()
```

Function: Check whether variable is a WordPress Error.
Source: wp-includes/load.php:1404
Used by 403 functions | Uses 0 functions

※1088※

```
is_wp_version_compatible()
```

Function: Checks compatibility with the current WordPress version.
Source: wp-includes/functions.php:7290
Used by 3 functions | Uses 1 function

※1089※

```
is_year()
```

Function: Determines whether the query is for an existing year archive.
Source: wp-includes/query.php:795
Used by 3 functions | Uses 3 functions

※1090※

```
json_decode()
```

Function:
Source: wp-includes/compat.php:304
Used by 0 functions | Uses 0 functions

※1091※

```
json_encode()
```

Function:
Source: wp-includes/compat.php:285
Used by 0 functions | Uses 0 functions

※1092※

```
json_last_error_msg()
```

Function: Retrieves the error string of the last json_encode() or json_decode() call.
Source: wp-includes/compat.php:380
Used by 0 functions | Uses 0 functions

※1093※

```
js_escape()
```

Function: Escape single quotes, specialchar double quotes, and fix line endings.
Source: wp-includes/deprecated.php:2057
Used by 0 functions | Uses 2 functions

※1094※

```
kses_init()
```

Function: Sets up most of the Kses filters for input form content.
Source: wp-includes/kses.php:2036
Used by 0 functions | Uses 3 functions

※1095※

```
kses_init_filters()
```

Function: Adds all Kses input form content filters.
Source: wp-includes/kses.php:1984
Used by 5 functions | Uses 2 functions

※1096※

```
kses_remove_filters()
```

Function: Removes all KSES input form content filters.
Source: wp-includes/kses.php:2013
Used by 5 functions | Uses 1 function

※1097※

```
language_attributes()
```

Function: Displays the language attributes for the html tag.
Source: wp-includes/general-template.php:3993
Used by 3 functions | Uses 1 function

※1098※

```
like_escape()
```

Function: Formerly used to escape strings before searching the DB. It was poorly documented and never worked as described.
Source: wp-includes/deprecated.php:3437
Used by 1 function | Uses 1 function

※1099※

```
links_add_base_url()
```

Function: Add a Base url to relative links in passed content.
Source: wp-includes/formatting.php:5079
Used by 1 function | Uses 0 functions

※1100※

```
links_add_target()
```

Function: Adds a Target attribute to all links in passed content.
Source: wp-includes/formatting.php:5125
Used by 1 function | Uses 0 functions

※1101※

```
links_popup_script()
```

Function: Show the link to the links popup and the number of links.
Source: wp-includes/deprecated.php:1062
Used by 0 functions | Uses 1 function

※1102※

```
link_advanced_meta_box()
```

Function: Display advanced link options form fields.
Source: wp-admin/includes/meta-boxes.php:1317
Used by 0 functions | Uses 2 functions

※1103※

```
link_categories_meta_box()
```

Function: Display link categories form fields.
Source: wp-admin/includes/meta-boxes.php:1086
Used by 0 functions | Uses 6 functions

※1104※

```
link_pages()
```

Function: Print list of pages based on arguments.
Source: wp-includes/deprecated.php:811
Used by 0 functions | Uses 2 functions

※1105※

```
link_submit_meta_box()
```

Function: Display link create form fields.
Source: wp-admin/includes/meta-boxes.php:1010
Used by 0 functions | Uses 11 functions

※1106※

```
link_target_meta_box()
```

Function: Display form fields for changing link target.
Source: wp-admin/includes/meta-boxes.php:1133
Used by 0 functions | Uses 1 function

※1107※

```
link_xfn_meta_box()
```

Function: Display xfn form fields.
Source: wp-admin/includes/meta-boxes.php:1199
Used by 0 functions | Uses 3 functions

※1108※

```
list_authors()
```

Function: Lists authors.
Source: wp-includes/deprecated.php:711
Used by 0 functions | Uses 2 functions

※1109※

```
list_cats()
```

Function: Lists categories.
Source: wp-includes/deprecated.php:615
Used by 0 functions | Uses 2 functions

※1110※

```
list_core_update()
```

Function:
Source: wp-admin/update-core.php:34
Used by 2 functions | Uses 12 functions

※1111※

```
list_files()
```

Function: Returns a listing of all files in the specified folder and all subdirectories up to 100 levels deep.
Source: wp-admin/includes/file.php:132
Used by 3 functions | Uses 2 functions

※1112※

```
list_meta()
```

Function: Outputs a post’s public meta data in the Custom Fields meta box.
Source: wp-admin/includes/template.php:560
Used by 1 function | Uses 5 functions

※1113※

```
list_plugin_updates()
```

Function: Display the upgrade plugins form.
Source: wp-admin/update-core.php:292
Used by 0 functions | Uses 15 functions

※1114※

```
list_theme_updates()
```

Function: Display the upgrade themes form.
Source: wp-admin/update-core.php:443
Used by 0 functions | Uses 7 functions

※1115※

```
list_translation_updates()
```

Function:
Source: wp-admin/update-core.php:525
Used by 0 functions | Uses 7 functions

※1116※

```
load_child_theme_textdomain()
```

Function: Load the child themes translated strings.
Source: wp-includes/l10n.php:895
Used by 0 functions | Uses 2 functions

※1117※

```
load_default_textdomain()
```

Function: Load default translated strings based on locale.
Source: wp-includes/l10n.php:739
Used by 3 functions | Uses 7 functions

※1118※

```
load_image_to_edit()
```

Function: Load an image resource for editing.
Source: wp-admin/includes/image.php:902
Used by 0 functions | Uses 3 functions

※1119※

```
load_muplugin_textdomain()
```

Function: Load the translated strings for a plugin residing in the mu-plugins directory.
Source: wp-includes/l10n.php:823
Used by 0 functions | Uses 4 functions

※1120※

```
load_plugin_textdomain()
```

Function: Loads a plugin’s translated strings.
Source: wp-includes/l10n.php:782
Used by 1 function | Uses 5 functions

※1121※

```
load_script_textdomain()
```

Function: Loads the script translated strings.
Source: wp-includes/l10n.php:918
Used by 1 function | Uses 11 functions

※1122※

```
load_script_translations()
```

Function: Loads the translation data for the given script handle and text domain.
Source: wp-includes/l10n.php:1048
Used by 1 function | Uses 4 functions

※1123※

```
load_template()
```

Function: Require the template file with WordPress environment.
Source: wp-includes/template.php:701
Used by 5 functions | Uses 1 function

※1124※

```
load_textdomain()
```

Function: Load a .mo file into the text domain $domain.
Source: wp-includes/l10n.php:612
Used by 7 functions | Uses 6 functions

※1125※

```
load_theme_textdomain()
```

Function: Load the theme’s translated strings.
Source: wp-includes/l10n.php:855
Used by 2 functions | Uses 5 functions

※1126※

```
locale_stylesheet()
```

Function: Display localized stylesheet link element.
Source: wp-includes/theme.php:701
Used by 0 functions | Uses 2 functions

※1127※

```
locate_template()
```

Function: Retrieve the name of the highest priority template file that exists.
Source: wp-includes/template.php:652
Used by 6 functions | Uses 1 function

※1128※

```
login_footer()
```

Function: Outputs the footer for the login page.
Source: wp-login.php:274
Used by 0 functions | Uses 7 functions

※1129※

```
login_header()
```

Function: Output the login page header.
Source: wp-login.php:35
Used by 0 functions | Uses 35 functions

※1130※

```
logIO()
```

Function: logIO() – Writes logging info to a file.
Source: xmlrpc.php:99
Used by 0 functions | Uses 1 function

※1131※

```
maintenance_nag()
```

Function:
Source: wp-admin/includes/update.php:693
Used by 0 functions | Uses 3 functions

※1132※

```
make_clickable()
```

Function: Convert plaintext URI to HTML links.
Source: wp-includes/formatting.php:2925
Used by 1 function | Uses 2 functions

※1133※

```
make_db_current()
```

Function: Updates the database tables to a new schema.
Source: wp-admin/includes/upgrade.php:2922
Used by 0 functions | Uses 1 function

※1134※

```
make_db_current_silent()
```

Function: Updates the database tables to a new schema, but without displaying results.
Source: wp-admin/includes/upgrade.php:2943
Used by 4 functions | Uses 1 function

※1135※

```
make_site_theme()
```

Function: Creates a site theme.
Source: wp-admin/includes/upgrade.php:3126
Used by 0 functions | Uses 4 functions

※1136※

```
make_site_theme_from_default()
```

Function: Creates a site theme from the default theme.
Source: wp-admin/includes/upgrade.php:3051
Used by 1 function | Uses 0 functions

※1137※

```
make_site_theme_from_oldschool()
```

Function: Creates a site theme from an existing theme.
Source: wp-admin/includes/upgrade.php:2958
Used by 1 function | Uses 1 function

※1138※

```
make_url_footnote()
```

Function: Strip HTML and put links at the bottom of stripped content.
Source: wp-includes/deprecated.php:1712
Used by 1 function | Uses 2 functions

※1139※

```
map_deep()
```

Function: Maps a function to all non-iterable elements of an array or an object.
Source: wp-includes/formatting.php:4826
Used by 7 functions | Uses 1 function

※1140※

```
map_meta_cap()
```

Function: Maps meta capabilities to primitive capabilities.
Source: wp-includes/capabilities.php:38
Used by 3 functions | Uses 26 functions

※1141※

```
maybe_add_column()
```

Function: Adds column to a database table if it doesn’t already exist.
Source: wp-admin/includes/upgrade.php:2379
Used by 0 functions | Uses 2 functions

※1142※

```
maybe_add_existing_user_to_blog()
```

Function: Add a new user to a blog by visiting /newbloguser/{key}/.
Source: wp-includes/ms-functions.php:2072
Used by 0 functions | Uses 8 functions

※1143※

```
maybe_convert_table_to_utf8mb4()
```

Function: If a table only contains utf8 or utf8mb4 columns, convert it to utf8mb4.
Source: wp-admin/includes/upgrade.php:2409
Used by 2 functions | Uses 3 functions

※1144※

```
maybe_create_table()
```

Function: Creates a table in the database if it doesn’t already exist.
Source: wp-admin/includes/upgrade.php:2307
Used by 0 functions | Uses 5 functions

※1145※

```
maybe_disable_automattic_widgets()
```

Function: Disables the Automattic widgets plugin, which was merged into core.
Source: wp-admin/includes/upgrade.php:3218
Used by 0 functions | Uses 1 function

※1146※

```
maybe_disable_link_manager()
```

Function: Disables the Link Manager on upgrade if, at the time of upgrade, no links exist in the DB.
Source: wp-admin/includes/upgrade.php:3238
Used by 0 functions | Uses 3 functions

※1147※

```
maybe_drop_column()
```

Function: Drop column from database table, if it exists.
Source: wp-admin/install-helper.php:119
Used by 0 functions | Uses 2 functions

※1148※

```
maybe_hash_hex_color()
```

Function: Ensures that any hex color is properly hashed.
Source: wp-includes/formatting.php:5948
Used by 0 functions | Uses 1 function

※1149※

```
maybe_redirect_404()
```

Function: Correct 404 redirects when NOBLOGREDIRECT is defined.
Source: wp-includes/ms-functions.php:2041
Used by 0 functions | Uses 6 functions

※1150※

```
maybe_serialize()
```

Function: Serialize data, if needed.
Source: wp-includes/functions.php:685
Used by 10 functions | Uses 1 function

※1151※

```
maybe_unserialize()
```

Function: Unserialize value only if it was serialized.
Source: wp-includes/functions.php:571
Used by 9 functions | Uses 1 function

※1152※

```
mbstring_binary_safe_encoding()
```

Function: Set the mbstring internal encoding to a binary safe encoding when func_overload is enabled.
Source: wp-includes/functions.php:6330
Used by 13 functions | Uses 0 functions

※1153※

```
mb_strlen()
```

Function:
Source: wp-includes/compat.php:100
Used by 0 functions | Uses 0 functions

※1154※

```
mb_substr()
```

Function:
Source: wp-includes/compat.php:45
Used by 0 functions | Uses 0 functions

※1155※

```
media_buttons()
```

Function: Adds the media button to the editor
Source: wp-admin/includes/media.php:624
Used by 0 functions | Uses 7 functions

※1156※

```
media_handle_sideload()
```

Function: Handles a side-loaded file in the same way as an uploaded file is handled by media_handle_upload().
Source: wp-admin/includes/media.php:437
Used by 2 functions | Uses 11 functions

※1157※

```
media_handle_upload()
```

Function: Save a file submitted from a POST request and create an attachment post for it.
Source: wp-admin/includes/media.php:290
Used by 2 functions | Uses 15 functions

※1158※

```
media_post_single_attachment_fields_to_edit()
```

Function: Retrieves the post non-image attachment fields to edito form fields.
Source: wp-admin/includes/media.php:1279
Used by 0 functions | Uses 0 functions

※1159※

```
media_send_to_editor()
```

Function: Adds image html to editor
Source: wp-admin/includes/media.php:268
Used by 2 functions | Uses 1 function

※1160※

```
media_sideload_image()
```

Function: Downloads an image from the specified URL and attaches it to a post.
Source: wp-admin/includes/media.php:977
Used by 0 functions | Uses 8 functions

※1161※

```
media_single_attachment_fields_to_edit()
```

Function: Retrieves the single non-image attachment fields to edit form fields.
Source: wp-admin/includes/media.php:1265
Used by 0 functions | Uses 0 functions

※1162※

```
media_upload_audio()
```

Function: Handles uploading an audio file.
Source: wp-admin/includes/deprecated.php:893
Used by 0 functions | Uses 2 functions

※1163※

```
media_upload_file()
```

Function: Handles uploading a generic file.
Source: wp-admin/includes/deprecated.php:919
Used by 0 functions | Uses 2 functions

※1164※

```
media_upload_flash_bypass()
```

Function: Displays the multi-file uploader message.
Source: wp-admin/includes/media.php:2961
Used by 0 functions | Uses 3 functions

※1165※

```
media_upload_form()
```

Function: Outputs the legacy media upload form.
Source: wp-admin/includes/media.php:2043
Used by 1 function | Uses 29 functions

※1166※

```
media_upload_form_handler()
```

Function: Handles form submissions for the legacy media uploader.
Source: wp-admin/includes/media.php:714
Used by 3 functions | Uses 17 functions

※1167※

```
media_upload_gallery()
```

Function: Retrieves the legacy media uploader form in an iframe.
Source: wp-admin/includes/media.php:1035
Used by 0 functions | Uses 3 functions

※1168※

```
media_upload_gallery_form()
```

Function: Adds gallery form to upload iframe
Source: wp-admin/includes/media.php:2482
Used by 0 functions | Uses 15 functions

※1169※

```
media_upload_header()
```

Function: Outputs the legacy media upload header.
Source: wp-admin/includes/media.php:2019
Used by 4 functions | Uses 1 function

※1170※

```
media_upload_html_bypass()
```

Function: Displays the browser’s built-in uploader message.
Source: wp-admin/includes/media.php:2990
Used by 0 functions | Uses 1 function

※1171※

```
media_upload_image()
```

Function: Handles uploading an image.
Source: wp-admin/includes/deprecated.php:880
Used by 0 functions | Uses 2 functions

※1172※

```
media_upload_library()
```

Function: Retrieves the legacy media library form in an iframe.
Source: wp-admin/includes/media.php:1061
Used by 0 functions | Uses 2 functions

※1173※

```
media_upload_library_form()
```

Function: Outputs the legacy media upload form for the media library.
Source: wp-admin/includes/media.php:2646
Used by 0 functions | Uses 27 functions

※1174※

```
media_upload_max_image_resize()
```

Function: Displays the checkbox to scale images.
Source: wp-admin/includes/media.php:3010
Used by 0 functions | Uses 6 functions

※1175※

```
media_upload_tabs()
```

Function: Defines the default media upload tabs
Source: wp-admin/includes/media.php:16
Used by 1 function | Uses 3 functions

※1176※

```
media_upload_text_after()
```

Function: Used to display a “After a file has been uploaded.
Source: wp-admin/includes/media.php:3003
Used by 0 functions | Uses 0 functions

※1177※

```
media_upload_type_form()
```

Function: Outputs the legacy media upload form for a given media type.
Source: wp-admin/includes/media.php:2259
Used by 0 functions | Uses 15 functions

※1178※

```
media_upload_type_url_form()
```

Function: Outputs the legacy media upload form for external media.
Source: wp-admin/includes/media.php:2333
Used by 0 functions | Uses 11 functions

※1179※

```
media_upload_video()
```

Function: Handles uploading a video file.
Source: wp-admin/includes/deprecated.php:906
Used by 0 functions | Uses 2 functions

※1180※

```
menu_page_url()
```

Function: Get the url to access a particular menu page based on the slug it was registered with.
Source: wp-admin/includes/plugin.php:1769
Used by 0 functions | Uses 3 functions

※1181※

```
metadata_exists()
```

Function: Determine if a meta key is set for a given object
Source: wp-includes/meta.php:562
Used by 3 functions | Uses 5 functions

※1182※

```
meta_box_prefs()
```

Function: Prints the meta box preferences for screen meta.
Source: wp-admin/includes/screen.php:99
Used by 1 function | Uses 4 functions

※1183※

```
meta_form()
```

Function: Prints the form in the Custom Fields meta box.
Source: wp-admin/includes/template.php:663
Used by 1 function | Uses 16 functions

※1184※

```
ms_allowed_http_request_hosts()
```

Function: Whitelists any domain in a multisite installation for safe HTTP requests.
Source: wp-includes/http.php:629
Used by 0 functions | Uses 3 functions

※1185※

```
ms_cookie_constants()
```

Function: Defines Multisite cookie constants.
Source: wp-includes/ms-default-constants.php:50
Used by 0 functions | Uses 3 functions

※1186※

```
ms_deprecated_blogs_file()
```

Function: Deprecated functionality for determining whether a file is deprecated.
Source: wp-admin/includes/ms-deprecated.php:110
Used by 0 functions | Uses 0 functions

※1187※

```
ms_file_constants()
```

Function: Defines Multisite file constants.
Source: wp-includes/ms-default-constants.php:98
Used by 0 functions | Uses 0 functions

※1188※

```
ms_is_switched()
```

Function: Determines if switch_to_blog() is in effect
Source: wp-includes/ms-blogs.php:652
Used by 2 functions | Uses 0 functions

※1189※

```
ms_load_current_site_and_network()
```

Function: Identifies the network and site of a requested domain and path and populates the corresponding network and site global objects as part of the multisite bootstrap process.
Source: wp-includes/ms-load.php:296
Used by 0 functions | Uses 13 functions

※1190※

```
ms_not_installed()
```

Function: Displays a failure message.
Source: wp-includes/ms-load.php:461
Used by 0 functions | Uses 9 functions

※1191※

```
ms_site_check()
```

Function: Checks status of current blog.
Source: wp-includes/ms-load.php:74
Used by 0 functions | Uses 8 functions

※1192※

```
ms_subdomain_constants()
```

Function: Defines Multisite subdomain constants and handles warnings and notices.
Source: wp-includes/ms-default-constants.php:131
Used by 0 functions | Uses 2 functions

※1193※

```
ms_upload_constants()
```

Function: Defines Multisite upload constants.
Source: wp-includes/ms-default-constants.php:18
Used by 0 functions | Uses 3 functions

※1194※

```
multisite_over_quota_message()
```

Function: Displays the out of storage quota message in Multisite.
Source: wp-admin/includes/media.php:3037
Used by 0 functions | Uses 3 functions

※1195※

```
mu_dropdown_languages()
```

Function: Generates and displays a drop-down of available languages.
Source: wp-admin/includes/ms.php:640
Used by 0 functions | Uses 7 functions

※1196※

```
mu_options()
```

Function: WPMU options.
Source: wp-admin/includes/ms-deprecated.php:46
Used by 0 functions | Uses 1 function

※1197※

```
mysql2date()
```

Function: Convert given MySQL date string into a different format.
Source: wp-includes/functions.php:30
Used by 31 functions | Uses 2 functions

※1198※

```
mysql_to_rfc3339()
```

Function: Parses and formats a MySQL datetime (Y-m-d H:i:s) for ISO8601 (Y-m-d\TH:i:s).
Source: wp-includes/functions.php:6493
Used by 3 functions | Uses 1 function

※1199※

```
network_admin_url()
```

Function: Retrieves the URL to the admin area for the network.
Source: wp-includes/link-template.php:3530
Used by 33 functions | Uses 5 functions

※1200※

```
network_domain_check()
```

Function: Check for an existing network.
Source: wp-admin/includes/network.php:19
Used by 1 function | Uses 3 functions

※1201※

```
network_edit_site_nav()
```

Function: Outputs the HTML for a network’s “Edit Site” tabular interface.
Source: wp-admin/includes/ms.php:1023
Used by 0 functions | Uses 11 functions

※1202※

```
network_home_url()
```

Function: Retrieves the home URL for the current network.
Source: wp-includes/link-template.php:3484
Used by 6 functions | Uses 8 functions

※1203※

```
network_settings_add_js()
```

Function: Print JavaScript in the header on the Network Settings screen.
Source: wp-admin/includes/ms.php:993
Used by 0 functions | Uses 0 functions

※1204※

```
network_site_url()
```

Function: Retrieves the site URL for the current network.
Source: wp-includes/link-template.php:3439
Used by 8 functions | Uses 6 functions

※1205※

```
network_step1()
```

Function: Prints step 1 for Network installation process.
Source: wp-admin/includes/network.php:109
Used by 0 functions | Uses 17 functions

※1206※

```
network_step2()
```

Function: Prints step 2 for Network installation process.
Source: wp-admin/includes/network.php:385
Used by 0 functions | Uses 21 functions

※1207※

```
newblog_notify_siteadmin()
```

Function: Notifies the network admin that a new site has been activated.
Source: wp-includes/ms-functions.php:1364
Used by 0 functions | Uses 13 functions

※1208※

```
newuser_notify_siteadmin()
```

Function: Notifies the network admin that a new user has been activated.
Source: wp-includes/ms-functions.php:1426
Used by 0 functions | Uses 10 functions

※1209※

```
new_user_email_admin_notice()
```

Function: Adds an admin notice alerting the user to check for confirmation request email after email address change.
Source: wp-includes/user.php:2888
Used by 0 functions | Uses 4 functions

※1210※

```
next_comments_link()
```

Function: Displays the link to the next comments page.
Source: wp-includes/link-template.php:2909
Used by 0 functions | Uses 1 function

※1211※

```
next_image_link()
```

Function: Displays next image link that has the same post parent.
Source: wp-includes/media.php:2937
Used by 0 functions | Uses 1 function

※1212※

```
next_post()
```

Function: Prints link to the next post.
Source: wp-includes/deprecated.php:171
Used by 0 functions | Uses 5 functions

※1213※

```
next_posts()
```

Function: Displays or retrieves the next posts page link.
Source: wp-includes/link-template.php:2330
Used by 1 function | Uses 2 functions

※1214※

```
next_posts_link()
```

Function: Displays the next posts page link.
Source: wp-includes/link-template.php:2391
Used by 0 functions | Uses 1 function

※1215※

```
next_post_link()
```

Function: Displays the next post link that is adjacent to the current post.
Source: wp-includes/link-template.php:2128
Used by 0 functions | Uses 1 function

※1216※

```
next_post_rel_link()
```

Function: Displays the relational link for the next post adjacent to the current post.
Source: wp-includes/link-template.php:1981
Used by 0 functions | Uses 1 function

※1217※

```
next_widget_id_number()
```

Function:
Source: wp-admin/includes/widgets.php:162
Used by 2 functions | Uses 0 functions

※1218※

```
nocache_headers()
```

Function: Set the headers to prevent caching for the different browsers.
Source: wp-includes/functions.php:1441
Used by 10 functions | Uses 1 function

※1219※

```
noindex()
```

Function: Displays a noindex meta tag if required by the blog configuration.
Source: wp-includes/general-template.php:3084
Used by 0 functions | Uses 2 functions

※1220※

```
normalize_whitespace()
```

Function: Normalize EOL characters and strip duplicate whitespace.
Source: wp-includes/formatting.php:5158
Used by 4 functions | Uses 0 functions

※1221※

```
number_format_i18n()
```

Function: Convert float number to format based on the locale.
Source: wp-includes/functions.php:388
Used by 48 functions | Uses 3 functions

※1222※

```
options_discussion_add_js()
```

Function: Output JavaScript to toggle display of additional settings if avatars are disabled.
Source: wp-admin/includes/options.php:15
Used by 0 functions | Uses 0 functions

※1223※

```
options_general_add_js()
```

Function: Display JavaScript on the page.
Source: wp-admin/includes/options.php:34
Used by 0 functions | Uses 2 functions

※1224※

```
options_permalink_add_js()
```

Function: Display JavaScript on the page.
Source: wp-admin/includes/deprecated.php:1503
Used by 0 functions | Uses 0 functions

※1225※

```
options_reading_add_js()
```

Function: Display JavaScript on the page.
Source: wp-admin/includes/options.php:108
Used by 0 functions | Uses 0 functions

※1226※

```
options_reading_blog_charset()
```

Function: Render the site charset setting.
Source: wp-admin/includes/options.php:130
Used by 0 functions | Uses 3 functions

※1227※

```
option_update_filter()
```

Function: Refreshes the value of the options whitelist available via the ‘whitelist_options’ hook.
Source: wp-admin/includes/plugin.php:2105
Used by 0 functions | Uses 1 function

※1228※

```
page_attributes_meta_box()
```

Function: Display page attributes form fields.
Source: wp-admin/includes/meta-boxes.php:915
Used by 0 functions | Uses 18 functions

※1229※

```
page_template_dropdown()
```

Function: Print out option HTML elements for the page templates drop-down.
Source: wp-admin/includes/template.php:867
Used by 2 functions | Uses 4 functions

※1230※

```
paginate_comments_links()
```

Function: Displays or retrieves pagination links for the comments on the current post.
Source: wp-includes/link-template.php:2970
Used by 1 function | Uses 10 functions

※1231※

```
paginate_links()
```

Function: Retrieve paginated link for archive post pages.
Source: wp-includes/general-template.php:4075
Used by 6 functions | Uses 16 functions

※1232※

```
parent_dropdown()
```

Function: Print out option HTML elements for the page parents drop-down.
Source: wp-admin/includes/template.php:891
Used by 1 function | Uses 6 functions

※1233※

```
parent_post_rel_link()
```

Function: Display relational link for parent item
Source: wp-includes/deprecated.php:2782
Used by 0 functions | Uses 2 functions

※1234※

```
parse_blocks()
```

Function: Parses blocks out of a content string.
Source: wp-includes/blocks.php:286
Used by 2 functions | Uses 2 functions

※1235※

```
parse_w3cdtf()
```

Function:
Source: wp-includes/rss.php:844
Used by 0 functions | Uses 0 functions

※1236※

```
path_is_absolute()
```

Function: Test if a given filesystem path is absolute.
Source: wp-includes/functions.php:1974
Used by 1 function | Uses 1 function

※1237※

```
path_join()
```

Function: Join two filesystem paths together.
Source: wp-includes/functions.php:2016
Used by 9 functions | Uses 1 function

※1238※

```
paused_plugins_notice()
```

Function: Renders an admin notice in case some plugins have been paused due to errors.
Source: wp-admin/includes/plugin.php:2384
Used by 0 functions | Uses 4 functions

※1239※

```
paused_themes_notice()
```

Function: Renders an admin notice in case some themes have been paused due to errors.
Source: wp-admin/includes/theme.php:916
Used by 0 functions | Uses 4 functions

※1240※

```
permalink_anchor()
```

Function: Displays the permalink anchor for the current post.
Source: wp-includes/link-template.php:78
Used by 0 functions | Uses 2 functions

※1241※

```
permalink_link()
```

Function: Print the permalink of the current post in the loop.
Source: wp-includes/deprecated.php:842
Used by 0 functions | Uses 2 functions

※1242※

```
permalink_single_rss()
```

Function: Print the permalink to the RSS feed.
Source: wp-includes/deprecated.php:856
Used by 0 functions | Uses 2 functions

※1243※

```
pingback()
```

Function: Pings back the links found in a post.
Source: wp-includes/comment.php:2797
Used by 1 function | Uses 14 functions

※1244※

```
pingback_ping_source_uri()
```

Function: Default filter attached to pingback_ping_source_uri to validate the pingback’s Source URI
Source: wp-includes/comment.php:2979
Used by 0 functions | Uses 1 function

※1245※

```
pings_open()
```

Function: Determines whether the current post is open for pings.
Source: wp-includes/comment-template.php:1244
Used by 6 functions | Uses 3 functions

※1246※

```
plugins_api()
```

Function: Retrieves plugin installer pages from the WordPress.org Plugins API.
Source: wp-admin/includes/plugin-install.php:102
Used by 4 functions | Uses 14 functions

※1247※

```
plugins_url()
```

Function: Retrieves a URL within the plugins or mu-plugins directory.
Source: wp-includes/link-template.php:3384
Used by 3 functions | Uses 5 functions

※1248※

```
plugin_basename()
```

Function: Gets the basename of a plugin.
Source: wp-includes/plugin.php:679
Used by 17 functions | Uses 1 function

※1249※

```
plugin_dir_path()
```

Function: Get the filesystem directory path (with trailing slash) for the plugin __FILE__ passed in.
Source: wp-includes/plugin.php:749
Used by 0 functions | Uses 1 function

※1250※

```
plugin_dir_url()
```

Function: Get the URL directory path (with trailing slash) for the plugin __FILE__ passed in.
Source: wp-includes/plugin.php:761
Used by 0 functions | Uses 2 functions

※1251※

```
plugin_sandbox_scrape()
```

Function: Load a given plugin attempt to generate errors.
Source: wp-admin/includes/plugin.php:2217
Used by 1 function | Uses 1 function

※1252※

```
populate_network()
```

Function: Populate network settings.
Source: wp-admin/includes/schema.php:961
Used by 0 functions | Uses 17 functions

※1253※

```
populate_network_meta()
```

Function: Creates WordPress network meta and sets the default values.
Source: wp-admin/includes/schema.php:1117
Used by 1 function | Uses 20 functions

※1254※

```
populate_options()
```

Function: Create WordPress options and set the default values.
Source: wp-admin/includes/schema.php:361
Used by 3 functions | Uses 16 functions

※1255※

```
populate_roles()
```

Function: Execute WordPress role creation for the various WordPress versions.
Source: wp-admin/includes/schema.php:689
Used by 3 functions | Uses 8 functions

※1256※

```
populate_roles_160()
```

Function: Create the roles for WordPress 2.0
Source: wp-admin/includes/schema.php:705
Used by 1 function | Uses 2 functions

※1257※

```
populate_roles_210()
```

Function: Create and modify WordPress roles for WordPress 2.1.
Source: wp-admin/includes/schema.php:798
Used by 1 function | Uses 1 function

※1258※

```
populate_roles_230()
```

Function: Create and modify WordPress roles for WordPress 2.3.
Source: wp-admin/includes/schema.php:846
Used by 1 function | Uses 1 function

※1259※

```
populate_roles_250()
```

Function: Create and modify WordPress roles for WordPress 2.5.
Source: wp-admin/includes/schema.php:859
Used by 1 function | Uses 1 function

※1260※

```
populate_roles_260()
```

Function: Create and modify WordPress roles for WordPress 2.6.
Source: wp-admin/includes/schema.php:872
Used by 1 function | Uses 1 function

※1261※

```
populate_roles_270()
```

Function: Create and modify WordPress roles for WordPress 2.7.
Source: wp-admin/includes/schema.php:886
Used by 1 function | Uses 1 function

※1262※

```
populate_roles_280()
```

Function: Create and modify WordPress roles for WordPress 2.8.
Source: wp-admin/includes/schema.php:900
Used by 1 function | Uses 1 function

※1263※

```
populate_roles_300()
```

Function: Create and modify WordPress roles for WordPress 3.0.
Source: wp-admin/includes/schema.php:913
Used by 1 function | Uses 1 function

※1264※

```
populate_site_meta()
```

Function: Creates WordPress site meta and sets the default values.
Source: wp-admin/includes/schema.php:1297
Used by 1 function | Uses 7 functions

※1265※

```
popuplinks()
```

Function: Adds element attributes to open links in new tabs.
Source: wp-includes/deprecated.php:3757
Used by 0 functions | Uses 1 function

※1266※

```
postbox_classes()
```

Function: Returns the list of classes to be used by a meta box.
Source: wp-admin/includes/post.php:1286
Used by 2 functions | Uses 3 functions

※1267※

```
posts_nav_link()
```

Function: Displays the post pages link navigation for previous and next pages.
Source: wp-includes/link-template.php:2537
Used by 0 functions | Uses 1 function

※1268※

```
post_author_meta_box()
```

Function: Display form field with list of authors.
Source: wp-admin/includes/meta-boxes.php:879
Used by 0 functions | Uses 2 functions

※1269※

```
post_categories_meta_box()
```

Function: Display post categories form fields.
Source: wp-admin/includes/meta-boxes.php:568
Used by 0 functions | Uses 12 functions

※1270※

```
post_class()
```

Function: Display the classes for the post div.
Source: wp-includes/post-template.php:453
Used by 0 functions | Uses 1 function

※1271※

```
post_comments_feed_link()
```

Function: Displays the comment feed link for a post.
Source: wp-includes/link-template.php:753
Used by 1 function | Uses 5 functions

※1272※

```
post_comment_meta_box()
```

Function: Display comments for post.
Source: wp-admin/includes/meta-boxes.php:821
Used by 0 functions | Uses 9 functions

※1273※

```
post_comment_meta_box_thead()
```

Function: Display comments for post table header
Source: wp-admin/includes/meta-boxes.php:809
Used by 0 functions | Uses 0 functions

※1274※

```
post_comment_status_meta_box()
```

Function: Display comments status form fields.
Source: wp-admin/includes/meta-boxes.php:773
Used by 0 functions | Uses 5 functions

※1275※

```
post_custom()
```

Function: Retrieve post custom meta data field.
Source: wp-includes/post-template.php:1067
Used by 0 functions | Uses 1 function

※1276※

```
post_custom_meta_box()
```

Function: Display custom fields form fields.
Source: wp-admin/includes/meta-boxes.php:739
Used by 0 functions | Uses 6 functions

※1277※

```
post_excerpt_meta_box()
```

Function: Display post excerpt form fields.
Source: wp-admin/includes/meta-boxes.php:677
Used by 0 functions | Uses 2 functions

※1278※

```
post_exists()
```

Function: Determines if a post exists based on title, content, date and type.
Source: wp-admin/includes/post.php:752
Used by 0 functions | Uses 4 functions

※1279※

```
post_format_meta_box()
```

Function: Display post format form elements.
Source: wp-admin/includes/meta-boxes.php:456
Used by 0 functions | Uses 9 functions

※1280※

```
post_form_autocomplete_off()
```

Function: Disables autocomplete on the ‘post’ form (Add/Edit Post screens) for WebKit browsers, as they disregard the autocomplete setting on the editor textarea. That can break the editor when the user navigates to it with the browser’s Back button. See #28037
Source: wp-admin/includes/deprecated.php:1487
Used by 0 functions | Uses 1 function

※1281※

```
post_password_required()
```

Function: Whether post requires password and correct password has been provided.
Source: wp-includes/post-template.php:845
Used by 11 functions | Uses 4 functions

※1282※

```
post_permalink()
```

Function: Retrieve permalink from post ID.
Source: wp-includes/deprecated.php:3625
Used by 0 functions | Uses 2 functions

※1283※

```
post_preview()
```

Function: Saves a draft or manually autosaves for the purpose of showing a post preview.
Source: wp-admin/includes/post.php:1855
Used by 0 functions | Uses 12 functions

※1284※

```
post_reply_link()
```

Function: Displays the HTML content for reply to post link.
Source: wp-includes/comment-template.php:1830
Used by 0 functions | Uses 1 function

※1285※

```
post_revisions_meta_box()
```

Function: Display list of revisions.
Source: wp-admin/includes/meta-boxes.php:902
Used by 0 functions | Uses 1 function

※1286※

```
post_slug_meta_box()
```

Function: Display slug form fields.
Source: wp-admin/includes/meta-boxes.php:862
Used by 0 functions | Uses 4 functions

※1287※

```
post_submit_meta_box()
```

Function: Displays post submit form fields.
Source: wp-admin/includes/meta-boxes.php:22
Used by 0 functions | Uses 30 functions

※1288※

```
post_tags_meta_box()
```

Function: Display post tags form fields.
Source: wp-admin/includes/meta-boxes.php:505
Used by 0 functions | Uses 8 functions

※1289※

```
post_thumbnail_meta_box()
```

Function: Display post thumbnail meta box.
Source: wp-admin/includes/meta-boxes.php:1358
Used by 0 functions | Uses 2 functions

※1290※

```
post_trackback_meta_box()
```

Function: Display trackback links form fields.
Source: wp-admin/includes/meta-boxes.php:699
Used by 0 functions | Uses 4 functions

※1291※

```
post_type_archive_title()
```

Function: Display or retrieve title for a post type archive.
Source: wp-includes/general-template.php:1365
Used by 4 functions | Uses 5 functions

※1292※

```
post_type_exists()
```

Function: Determines whether a post type is registered.
Source: wp-includes/post.php:1194
Used by 11 functions | Uses 1 function

※1293※

```
post_type_supports()
```

Function: Check a post type’s support for a given feature.
Source: wp-includes/post.php:1902
Used by 33 functions | Uses 0 functions

※1294※

```
prepend_attachment()
```

Function: Wrap attachment in paragraph tag before content.
Source: wp-includes/post-template.php:1649
Used by 1 function | Uses 12 functions

※1295※

```
prep_atom_text_construct()
```

Function: Determine the type of a string of data with the data formatted.
Source: wp-includes/feed.php:548
Used by 0 functions | Uses 1 function

※1296※

```
press_it()
```

Function: Press It form handler.
Source: wp-admin/press-this.php:26
Used by 0 functions | Uses 0 functions

※1297※

```
press_this_media_buttons()
```

Function:
Source: wp-admin/press-this.php:651
Used by 0 functions | Uses 0 functions

※1298※

```
preview_theme()
```

Function: Start preview theme output buffer.
Source: wp-includes/deprecated.php:3478
Used by 0 functions | Uses 1 function

※1299※

```
preview_theme_ob_filter()
```

Function: Callback function for ob_start() to capture all links in the theme.
Source: wp-includes/deprecated.php:3520
Used by 0 functions | Uses 1 function

※1300※

```
preview_theme_ob_filter_callback()
```

Function: Manipulates preview theme links in order to control and maintain location.
Source: wp-includes/deprecated.php:3537
Used by 0 functions | Uses 1 function

※1301※

```
previous_comments_link()
```

Function: Displays the link to the previous comments page.
Source: wp-includes/link-template.php:2955
Used by 0 functions | Uses 1 function

※1302※

```
previous_image_link()
```

Function: Displays previous image link that has the same post parent.
Source: wp-includes/media.php:2921
Used by 0 functions | Uses 1 function

※1303※

```
previous_post()
```

Function: Prints a link to the previous post.
Source: wp-includes/deprecated.php:135
Used by 0 functions | Uses 5 functions

※1304※

```
previous_posts()
```

Function: Displays or retrieves the previous posts page link.
Source: wp-includes/link-template.php:2428
Used by 1 function | Uses 2 functions

※1305※

```
previous_posts_link()
```

Function: Displays the previous posts page link.
Source: wp-includes/link-template.php:2475
Used by 0 functions | Uses 1 function

※1306※

```
previous_post_link()
```

Function: Displays the previous post link that is adjacent to the current post.
Source: wp-includes/link-template.php:2096
Used by 0 functions | Uses 1 function

※1307※

```
prev_post_rel_link()
```

Function: Displays the relational link for the previous post adjacent to the current post.
Source: wp-includes/link-template.php:1997
Used by 0 functions | Uses 1 function

※1308※

```
pre_schema_upgrade()
```

Function: Runs before the schema is upgraded.
Source: wp-admin/includes/upgrade.php:3254
Used by 1 function | Uses 6 functions

※1309※

```
print_admin_styles()
```

Function: Prints the styles queue in the HTML head on admin pages.
Source: wp-includes/script-loader.php:2679
Used by 0 functions | Uses 5 functions

※1310※

```
print_column_headers()
```

Function: Prints column headers for a particular screen.
Source: wp-admin/includes/list-table.php:87
Used by 0 functions | Uses 2 functions

※1311※

```
print_embed_comments_button()
```

Function: Prints the necessary markup for the embed comments button.
Source: wp-includes/embed.php:1080
Used by 0 functions | Uses 6 functions

※1312※

```
print_embed_scripts()
```

Function: Prints the JavaScript in the embed iframe header.
Source: wp-includes/embed.php:1035
Used by 0 functions | Uses 1 function

※1313※

```
print_embed_sharing_button()
```

Function: Prints the necessary markup for the embed sharing button.
Source: wp-includes/embed.php:1109
Used by 0 functions | Uses 2 functions

※1314※

```
print_embed_sharing_dialog()
```

Function: Prints the necessary markup for the embed sharing dialog.
Source: wp-includes/embed.php:1127
Used by 0 functions | Uses 7 functions

※1315※

```
print_embed_styles()
```

Function: Prints the CSS in the embed iframe header.
Source: wp-includes/embed.php:1002
Used by 0 functions | Uses 1 function

※1316※

```
print_emoji_detection_script()
```

Function: Print the inline Emoji detection script if it is not already printed.
Source: wp-includes/formatting.php:5559
Used by 0 functions | Uses 0 functions

※1317※

```
print_emoji_styles()
```

Function: Print the important emoji-related styles.
Source: wp-includes/formatting.php:5525
Used by 0 functions | Uses 1 function

※1318※

```
print_footer_scripts()
```

Function: Prints the scripts that were queued for the footer or too late for the HTML head.
Source: wp-includes/script-loader.php:2534
Used by 1 function | Uses 5 functions

※1319※

```
print_head_scripts()
```

Function: Prints the script queue in the HTML head on admin pages.
Source: wp-includes/script-loader.php:2495
Used by 1 function | Uses 9 functions

※1320※

```
print_late_styles()
```

Function: Prints the styles that were queued too late for the HTML head.
Source: wp-includes/script-loader.php:2713
Used by 1 function | Uses 5 functions

※1321※

```
privacy_ping_filter()
```

Function: Check whether blog is public before returning sites.
Source: wp-includes/comment.php:2896
Used by 0 functions | Uses 1 function

※1322※

```
query_posts()
```

Function: Sets up The Loop with query parameters.
Source: wp-includes/query.php:96
Used by 0 functions | Uses 1 function

※1323※

```
rawurlencode_deep()
```

Function: Navigates through an array, object, or scalar, and raw-encodes the values to be used in a URL.
Source: wp-includes/formatting.php:2763
Used by 2 functions | Uses 1 function

※1324※

```
readonly()
```

Function: Outputs the html readonly attribute.
Source: wp-includes/general-template.php:4694
Used by 0 functions | Uses 1 function

※1325※

```
recurse_dirsize()
```

Function: Get the size of a directory recursively.
Source: wp-includes/functions.php:7225
Used by 3 functions | Uses 2 functions

※1326※

```
redirect_canonical()
```

Function: Redirects incoming links to the proper URL based on the site url.
Source: wp-includes/canonical.php:42
Used by 1 function | Uses 69 functions

※1327※

```
redirect_guess_404_permalink()
```

Function: Attempts to guess the correct URL based on query vars
Source: wp-includes/canonical.php:684
Used by 1 function | Uses 9 functions

※1328※

```
redirect_post()
```

Function: Redirect to previous page.
Source: wp-admin/includes/post.php:1958
Used by 0 functions | Uses 7 functions

※1329※

```
redirect_this_site()
```

Function: Ensure that the current site’s domain is listed in the allowed redirect host list.
Source: wp-includes/ms-functions.php:1978
Used by 0 functions | Uses 1 function

※1330※

```
refresh_blog_details()
```

Function: Clear the blog details cache.
Source: wp-includes/ms-blogs.php:273
Used by 0 functions | Uses 2 functions

※1331※

```
refresh_user_details()
```

Function: Cleans the user cache for a specific user.
Source: wp-admin/includes/ms.php:314
Used by 0 functions | Uses 2 functions

※1332※

```
registered_meta_key_exists()
```

Function: Checks if a meta key is registered.
Source: wp-includes/meta.php:1257
Used by 2 functions | Uses 1 function

※1333※

```
register_activation_hook()
```

Function: Set the activation hook for a plugin.
Source: wp-includes/plugin.php:783
Used by 0 functions | Uses 2 functions

※1334※

```
register_admin_color_schemes()
```

Function: Registers the default admin color schemes.
Source: wp-includes/general-template.php:4297
Used by 0 functions | Uses 5 functions

※1335※

```
register_and_do_post_meta_boxes()
```

Function: Registers the default post meta boxes, and runs the `do_meta_boxes` actions.
Source: wp-admin/includes/meta-boxes.php:1397
Used by 0 functions | Uses 28 functions

※1336※

```
register_block_style()
```

Function: Registers a new block style.
Source: wp-includes/blocks.php:370
Used by 0 functions | Uses 1 function

※1337※

```
register_block_type()
```

Function: Registers a block type.
Source: wp-includes/blocks.php:26
Used by 0 functions | Uses 1 function

※1338※

```
register_column_headers()
```

Function: Register column headers for a particular screen.
Source: wp-admin/includes/list-table.php:75
Used by 0 functions | Uses 1 function

※1339※

```
register_deactivation_hook()
```

Function: Set the deactivation hook for a plugin.
Source: wp-includes/plugin.php:806
Used by 0 functions | Uses 2 functions

※1340※

```
register_default_headers()
```

Function: Register a selection of default headers to be displayed by the custom header admin UI.
Source: wp-includes/theme.php:1371
Used by 0 functions | Uses 0 functions

※1341※

```
register_importer()
```

Function: Register importer for WordPress.
Source: wp-admin/includes/import.php:54
Used by 0 functions | Uses 1 function

※1342※

```
register_initial_settings()
```

Function: Register default settings available in WordPress.
Source: wp-includes/option.php:1901
Used by 0 functions | Uses 3 functions

※1343※

```
register_meta()
```

Function: Registers a meta key.
Source: wp-includes/meta.php:1146
Used by 2 functions | Uses 7 functions

※1344※

```
register_nav_menu()
```

Function: Registers a navigation menu location for a theme.
Source: wp-includes/nav-menu.php:135
Used by 0 functions | Uses 1 function

※1345※

```
register_nav_menus()
```

Function: Registers navigation menu locations for a theme.
Source: wp-includes/nav-menu.php:90
Used by 1 function | Uses 3 functions

※1346※

```
register_new_user()
```

Function: Handles registering a new user.
Source: wp-includes/user.php:2476
Used by 0 functions | Uses 19 functions

※1347※

```
register_post_meta()
```

Function: Registers a meta key for posts.
Source: wp-includes/post.php:2166
Used by 0 functions | Uses 1 function

※1348※

```
register_post_status()
```

Function: Register a post status. Do not use before init.
Source: wp-includes/post.php:1029
Used by 1 function | Uses 3 functions

※1349※

```
register_post_type()
```

Function: Registers a post type.
Source: wp-includes/post.php:1405
Used by 1 function | Uses 7 functions

※1350※

```
register_rest_field()
```

Function: Registers a new field on an existing WordPress object type.
Source: wp-includes/rest-api.php:115
Used by 1 function | Uses 1 function

※1351※

```
register_rest_route()
```

Function: Registers a REST API route.
Source: wp-includes/rest-api.php:33
Used by 15 functions | Uses 4 functions

※1352※

```
register_setting()
```

Function: Register a setting and its data.
Source: wp-includes/option.php:2109
Used by 2 functions | Uses 6 functions

※1353※

```
register_sidebar()
```

Function: Builds the definition for a single sidebar and returns the ID.
Source: wp-includes/widgets.php:247
Used by 1 function | Uses 8 functions

※1354※

```
register_sidebars()
```

Function: Creates multiple sidebars.
Source: wp-includes/widgets.php:166
Used by 0 functions | Uses 3 functions

※1355※

```
register_sidebar_widget()
```

Function: Register widget for sidebar with backward compatibility.
Source: wp-includes/deprecated.php:2117
Used by 0 functions | Uses 3 functions

※1356※

```
register_taxonomy()
```

Function: Creates or modifies a taxonomy object.
Source: wp-includes/taxonomy.php:413
Used by 1 function | Uses 7 functions

※1357※

```
register_taxonomy_for_object_type()
```

Function: Add an already registered taxonomy to an object type.
Source: wp-includes/taxonomy.php:609
Used by 1 function | Uses 3 functions

※1358※

```
register_term_meta()
```

Function: Registers a meta key for terms.
Source: wp-includes/taxonomy.php:1326
Used by 0 functions | Uses 1 function

※1359※

```
register_theme_directory()
```

Function: Register a directory that contains themes.
Source: wp-includes/theme.php:396
Used by 0 functions | Uses 1 function

※1360※

```
register_uninstall_hook()
```

Function: Set the uninstallation hook for a plugin.
Source: wp-includes/plugin.php:837
Used by 0 functions | Uses 5 functions

※1361※

```
register_widget()
```

Function: Register a widget
Source: wp-includes/widgets.php:112
Used by 1 function | Uses 1 function

※1362※

```
register_widget_control()
```

Function: Registers widget control callback for customizing options.
Source: wp-includes/deprecated.php:2171
Used by 0 functions | Uses 3 functions

※1363※

```
rel_canonical()
```

Function: Outputs rel=canonical for singular queries.
Source: wp-includes/link-template.php:3807
Used by 0 functions | Uses 4 functions

※1364※

```
remove_accents()
```

Function: Converts all accent characters to ASCII characters.
Source: wp-includes/formatting.php:1601
Used by 2 functions | Uses 2 functions

※1365※

```
remove_action()
```

Function: Removes a function from a specified action hook.
Source: wp-includes/plugin.php:583
Used by 19 functions | Uses 1 function

※1366※

```
remove_all_actions()
```

Function: Remove all of the hooks from an action.
Source: wp-includes/plugin.php:596
Used by 0 functions | Uses 1 function

※1367※

```
remove_all_filters()
```

Function: Remove all of the hooks from a filter.
Source: wp-includes/plugin.php:301
Used by 2 functions | Uses 0 functions

※1368※

```
remove_all_shortcodes()
```

Function: Clear all shortcodes.
Source: wp-includes/shortcodes.php:108
Used by 1 function | Uses 0 functions

※1369※

```
remove_custom_background()
```

Function: Remove custom background support.
Source: wp-includes/deprecated.php:3045
Used by 0 functions | Uses 2 functions

※1370※

```
remove_custom_image_header()
```

Function: Remove image header support.
Source: wp-includes/deprecated.php:3008
Used by 0 functions | Uses 2 functions

※1371※

```
remove_editor_styles()
```

Function: Removes all visual editor stylesheets.
Source: wp-includes/theme.php:1964
Used by 0 functions | Uses 3 functions

※1372※

```
remove_filter()
```

Function: Removes a function from a specified filter hook.
Source: wp-includes/plugin.php:276
Used by 39 functions | Uses 0 functions

※1373※

```
remove_image_size()
```

Function: Remove a new image size.
Source: wp-includes/media.php:318
Used by 0 functions | Uses 0 functions

※1374※

```
remove_menu_page()
```

Function: Remove a top-level admin menu.
Source: wp-admin/includes/plugin.php:1715
Used by 0 functions | Uses 0 functions

※1375※

```
remove_meta_box()
```

Function: Removes a meta box from one or more screens.
Source: wp-admin/includes/template.php:1375
Used by 1 function | Uses 3 functions

※1376※

```
remove_option_update_handler()
```

Function: Unregister a setting
Source: wp-admin/includes/deprecated.php:183
Used by 0 functions | Uses 2 functions

※1377※

```
remove_option_whitelist()
```

Function: Removes a list of options from the options whitelist.
Source: wp-admin/includes/plugin.php:2161
Used by 0 functions | Uses 0 functions

※1378※

```
remove_permastruct()
```

Function: Removes a permalink structure.
Source: wp-includes/rewrite.php:230
Used by 2 functions | Uses 1 function

※1379※

```
remove_post_type_support()
```

Function: Remove support for a feature from a post type.
Source: wp-includes/post.php:1865
Used by 0 functions | Uses 0 functions

※1380※

```
remove_query_arg()
```

Function: Removes an item or items from a query string.
Source: wp-includes/functions.php:1135
Used by 21 functions | Uses 1 function

※1381※

```
remove_rewrite_tag()
```

Function: Removes an existing rewrite tag (like %postname%).
Source: wp-includes/rewrite.php:185
Used by 2 functions | Uses 1 function

※1382※

```
remove_role()
```

Function: Remove role, if it exists.
Source: wp-includes/capabilities.php:829
Used by 0 functions | Uses 2 functions

※1383※

```
remove_shortcode()
```

Function: Removes hook for shortcode.
Source: wp-includes/shortcodes.php:91
Used by 0 functions | Uses 0 functions

※1384※

```
remove_submenu_page()
```

Function: Remove an admin submenu.
Source: wp-admin/includes/plugin.php:1739
Used by 0 functions | Uses 0 functions

※1385※

```
remove_theme_mod()
```

Function: Remove theme modification name from current theme list.
Source: wp-includes/theme.php:987
Used by 5 functions | Uses 4 functions

※1386※

```
remove_theme_mods()
```

Function: Remove theme modifications option for current theme.
Source: wp-includes/theme.php:1009
Used by 1 function | Uses 4 functions

※1387※

```
remove_theme_support()
```

Function: Allows a theme to de-register its support of a certain feature
Source: wp-includes/theme.php:2732
Used by 2 functions | Uses 1 function

※1388※

```
remove_user_from_blog()
```

Function: Remove a user from a blog.
Source: wp-includes/ms-functions.php:236
Used by 5 functions | Uses 13 functions

※1389※

```
render_block()
```

Function: Renders a single block into a HTML string.
Source: wp-includes/blocks.php:220
Used by 4 functions | Uses 6 functions

※1390※

```
request_filesystem_credentials()
```

Function: Displays a form to the user to request for their FTP/SSH details in order to connect to the filesystem.
Source: wp-admin/includes/file.php:1946
Used by 8 functions | Uses 20 functions

※1391※

```
require_if_theme_supports()
```

Function: Checks a theme’s support for a given feature before loading the functions which implement it.
Source: wp-includes/theme.php:2889
Used by 0 functions | Uses 1 function

※1392※

```
require_wp_db()
```

Function: Load the database class file and instantiate the `$wpdb` global.
Source: wp-includes/load.php:408
Used by 0 functions | Uses 1 function

※1393※

```
reset_mbstring_encoding()
```

Function: Reset the mbstring internal encoding to a users previously set encoding.
Source: wp-includes/functions.php:6361
Used by 12 functions | Uses 1 function

※1394※

```
reset_password()
```

Function: Handles resetting the user’s password.
Source: wp-includes/user.php:2442
Used by 0 functions | Uses 5 functions

※1395※

```
restore_current_blog()
```

Function: Restore the current blog, after calling switch_to_blog()
Source: wp-includes/ms-blogs.php:568
Used by 34 functions | Uses 9 functions

※1396※

```
restore_current_locale()
```

Function: Restores the translations according to the original locale.
Source: wp-includes/l10n.php:1610
Used by 0 functions | Uses 1 function

※1397※

```
restore_previous_locale()
```

Function: Restores the translations according to the previous locale.
Source: wp-includes/l10n.php:1594
Used by 18 functions | Uses 1 function

※1398※

```
rest_api_default_filters()
```

Function: Registers the default REST API filters.
Source: wp-includes/rest-api.php:173
Used by 0 functions | Uses 2 functions

※1399※

```
rest_api_init()
```

Function: Registers rewrite rules for the API.
Source: wp-includes/rest-api.php:141
Used by 0 functions | Uses 2 functions

※1400※

```
rest_api_loaded()
```

Function: Loads the REST API.
Source: wp-includes/rest-api.php:284
Used by 0 functions | Uses 2 functions

※1401※

```
rest_api_register_rewrites()
```

Function: Adds REST rewrite rules.
Source: wp-includes/rest-api.php:156
Used by 1 function | Uses 2 functions

※1402※

```
rest_authorization_required_code()
```

Function: Returns a contextual HTTP error code for authorization failure.
Source: wp-includes/rest-api.php:1016
Used by 42 functions | Uses 1 function

※1403※

```
rest_cookie_check_errors()
```

Function: Checks for errors when using cookie-based authentication.
Source: wp-includes/rest-api.php:879
Used by 0 functions | Uses 7 functions

※1404※

```
rest_cookie_collect_status()
```

Function: Collects cookie authentication status.
Source: wp-includes/rest-api.php:933
Used by 0 functions | Uses 1 function

※1405※

```
rest_do_request()
```

Function: Do a REST request.
Source: wp-includes/rest-api.php:427
Used by 1 function | Uses 2 functions

※1406※

```
rest_ensure_request()
```

Function: Ensures request arguments are a request object (for consistency).
Source: wp-includes/rest-api.php:486
Used by 1 function | Uses 1 function

※1407※

```
rest_ensure_response()
```

Function: Ensures a REST response is a response object (for consistency).
Source: wp-includes/rest-api.php:512
Used by 48 functions | Uses 1 function

※1408※

```
rest_filter_response_fields()
```

Function: Filter the API response to include only a white-listed set of response object fields.
Source: wp-includes/rest-api.php:726
Used by 0 functions | Uses 3 functions

※1409※

```
rest_get_avatar_sizes()
```

Function: Retrieves the pixel sizes for avatars.
Source: wp-includes/rest-api.php:1188
Used by 3 functions | Uses 2 functions

※1410※

```
rest_get_avatar_urls()
```

Function: Retrieves the avatar urls in various sizes.
Source: wp-includes/rest-api.php:1170
Used by 2 functions | Uses 2 functions

※1411※

```
rest_get_date_with_gmt()
```

Function: Parses a date into both its local and UTC equivalent, in MySQL datetime format.
Source: wp-includes/rest-api.php:982
Used by 2 functions | Uses 3 functions

※1412※

```
rest_get_server()
```

Function: Retrieves the current REST server instance.
Source: wp-includes/rest-api.php:443
Used by 6 functions | Uses 4 functions

※1413※

```
rest_get_url_prefix()
```

Function: Retrieves the URL prefix for any API resource.
Source: wp-includes/rest-api.php:318
Used by 2 functions | Uses 2 functions

※1414※

```
rest_handle_deprecated_argument()
```

Function: Handles _deprecated_argument() errors.
Source: wp-includes/rest-api.php:557
Used by 0 functions | Uses 1 function

※1415※

```
rest_handle_deprecated_function()
```

Function: Handles _deprecated_function() errors.
Source: wp-includes/rest-api.php:533
Used by 0 functions | Uses 1 function

※1416※

```
rest_handle_options_request()
```

Function: Handles OPTIONS requests for the server.
Source: wp-includes/rest-api.php:612
Used by 0 functions | Uses 0 functions

※1417※

```
rest_is_boolean()
```

Function: Determines if a given value is boolean-like.
Source: wp-includes/rest-api.php:1134
Used by 1 function | Uses 0 functions

※1418※

```
rest_is_field_included()
```

Function: Given an array of fields to include in a response, some of which may be `nested.fields`, determine whether the provided field should be included in the response body.
Source: wp-includes/rest-api.php:790
Used by 1 function | Uses 0 functions

※1419※

```
rest_is_ip_address()
```

Function: Determines if an IP address is valid.
Source: wp-includes/rest-api.php:1095
Used by 2 functions | Uses 1 function

※1420※

```
rest_output_link_header()
```

Function: Sends a Link header for the REST API.
Source: wp-includes/rest-api.php:849
Used by 0 functions | Uses 2 functions

※1421※

```
rest_output_link_wp_head()
```

Function: Outputs the REST API link tag into page header.
Source: wp-includes/rest-api.php:834
Used by 0 functions | Uses 2 functions

※1422※

```
rest_output_rsd()
```

Function: Adds the REST API URL to the WP RSD endpoint.
Source: wp-includes/rest-api.php:816
Used by 0 functions | Uses 2 functions

※1423※

```
rest_parse_date()
```

Function: Parses an RFC3339 time into a Unix timestamp.
Source: wp-includes/rest-api.php:956
Used by 2 functions | Uses 0 functions

※1424※

```
rest_parse_request_arg()
```

Function: Parse a request argument based on details registered to the route.
Source: wp-includes/rest-api.php:1073
Used by 2 functions | Uses 3 functions

※1425※

```
rest_preload_api_request()
```

Function: Append result of internal request to REST API for purpose of preloading data to be attached to a page.
Source: wp-includes/rest-api.php:1508
Used by 0 functions | Uses 4 functions

※1426※

```
rest_sanitize_boolean()
```

Function: Changes a boolean-like value into the proper boolean value.
Source: wp-includes/rest-api.php:1113
Used by 1 function | Uses 0 functions

※1427※

```
rest_sanitize_request_arg()
```

Function: Sanitize a request argument based on details registered to the route.
Source: wp-includes/rest-api.php:1050
Used by 1 function | Uses 1 function

※1428※

```
rest_sanitize_value_from_schema()
```

Function: Sanitize a value based on a schema.
Source: wp-includes/rest-api.php:1392
Used by 6 functions | Uses 7 functions

※1429※

```
rest_send_allow_header()
```

Function: Sends the “Allow” header to state all methods that can be sent to the current route.
Source: wp-includes/rest-api.php:661
Used by 1 function | Uses 0 functions

※1430※

```
rest_send_cors_headers()
```

Function: Sends Cross-Origin Resource Sharing headers with API requests.
Source: wp-includes/rest-api.php:580
Used by 0 functions | Uses 3 functions

※1431※

```
rest_url()
```

Function: Retrieves the URL to a REST endpoint.
Source: wp-includes/rest-api.php:413
Used by 28 functions | Uses 1 function

※1432※

```
rest_validate_request_arg()
```

Function: Validate a request argument based on details registered to the route.
Source: wp-includes/rest-api.php:1030
Used by 4 functions | Uses 1 function

※1433※

```
rest_validate_value_from_schema()
```

Function: Validate a value based on a schema.
Source: wp-includes/rest-api.php:1213
Used by 9 functions | Uses 10 functions

※1434※

```
resume_plugin()
```

Function: Tries to resume a single plugin.
Source: wp-admin/includes/plugin.php:2345
Used by 0 functions | Uses 7 functions

※1435※

```
resume_theme()
```

Function: Tries to resume a single theme.
Source: wp-admin/includes/theme.php:865
Used by 0 functions | Uses 6 functions

※1436※

```
retrieve_password()
```

Function: Handles sending password retrieval email to user.
Source: wp-login.php:356
Used by 0 functions | Uses 18 functions

※1437※

```
retrieve_widgets()
```

Function: Look for “lost” widgets, this has to run at least on each theme change.
Source: wp-includes/widgets.php:1232
Used by 2 functions | Uses 4 functions

※1438※

```
revoke_super_admin()
```

Function: Revokes Super Admin privileges.
Source: wp-includes/capabilities.php:943
Used by 0 functions | Uses 7 functions

※1439※

```
rewind_posts()
```

Function: Rewind the loop posts.
Source: wp-includes/query.php:923
Used by 0 functions | Uses 1 function

※1440※

```
rich_edit_exists()
```

Function: Determine if TinyMCE is available.
Source: wp-includes/deprecated.php:3387
Used by 0 functions | Uses 1 function

※1441※

```
rsd_link()
```

Function: Display the link to the Really Simple Discovery service endpoint.
Source: wp-includes/general-template.php:3055
Used by 0 functions | Uses 2 functions

※1442※

```
rss2_site_icon()
```

Function: Displays Site Icon in RSS2.
Source: wp-includes/feed.php:599
Used by 0 functions | Uses 4 functions

※1443※

```
rss_enclosure()
```

Function: Display the rss enclosure for the current post.
Source: wp-includes/feed.php:469
Used by 0 functions | Uses 7 functions

※1444※

```
safecss_filter_attr()
```

Function: Filters an inline style attribute and removes disallowed rules.
Source: wp-includes/kses.php:2053
Used by 1 function | Uses 6 functions

※1445※

```
sanitize_bookmark()
```

Function: Sanitizes all bookmark fields
Source: wp-includes/bookmark.php:333
Used by 3 functions | Uses 1 function

※1446※

```
sanitize_bookmark_field()
```

Function: Sanitizes a bookmark field.
Source: wp-includes/bookmark.php:398
Used by 5 functions | Uses 7 functions

※1447※

```
sanitize_category()
```

Function: Sanitizes category data based on context.
Source: wp-includes/category.php:248
Used by 0 functions | Uses 1 function

※1448※

```
sanitize_category_field()
```

Function: Sanitizes data in single category key field.
Source: wp-includes/category.php:263
Used by 0 functions | Uses 1 function

※1449※

```
sanitize_comment_cookies()
```

Function: Sanitizes the cookies sent to the user already.
Source: wp-includes/comment.php:589
Used by 0 functions | Uses 6 functions

※1450※

```
sanitize_email()
```

Function: Strips out all characters that are not allowable in an email.
Source: wp-includes/formatting.php:3588
Used by 4 functions | Uses 2 functions

※1451※

```
sanitize_file_name()
```

Function: Sanitizes a filename, replacing whitespace with dashes.
Source: wp-includes/formatting.php:2003
Used by 3 functions | Uses 6 functions

※1452※

```
sanitize_hex_color()
```

Function: Sanitizes a hex color.
Source: wp-includes/formatting.php:5902
Used by 1 function | Uses 0 functions

※1453※

```
sanitize_hex_color_no_hash()
```

Function: Sanitizes a hex color without a hash. Use sanitize_hex_color() when possible.
Source: wp-includes/formatting.php:5927
Used by 2 functions | Uses 1 function

※1454※

```
sanitize_html_class()
```

Function: Sanitizes an HTML classname to ensure it only contains valid characters.
Source: wp-includes/formatting.php:2329
Used by 15 functions | Uses 3 functions

※1455※

```
sanitize_key()
```

Function: Sanitizes a string key.
Source: wp-includes/formatting.php:2129
Used by 55 functions | Uses 2 functions

※1456※

```
sanitize_meta()
```

Function: Sanitize meta value.
Source: wp-includes/meta.php:1067
Used by 4 functions | Uses 4 functions

※1457※

```
sanitize_mime_type()
```

Function: Sanitize a mime type
Source: wp-includes/formatting.php:5350
Used by 0 functions | Uses 2 functions

※1458※

```
sanitize_option()
```

Function: Sanitises various option values based on the nature of the option.
Source: wp-includes/formatting.php:4554
Used by 7 functions | Uses 17 functions

※1459※

```
sanitize_post()
```

Function: Sanitize every post field.
Source: wp-includes/post.php:2306
Used by 7 functions | Uses 1 function

※1460※

```
sanitize_post_field()
```

Function: Sanitize post field based on context.
Source: wp-includes/post.php:2352
Used by 5 functions | Uses 11 functions

※1461※

```
sanitize_sql_orderby()
```

Function: Ensures a string is a valid SQL ‘order by’ clause.
Source: wp-includes/formatting.php:2307
Used by 0 functions | Uses 0 functions

※1462※

```
sanitize_term()
```

Function: Sanitize Term all fields.
Source: wp-includes/taxonomy.php:1473
Used by 9 functions | Uses 1 function

※1463※

```
sanitize_term_field()
```

Function: Cleanse the field value in the term based on the context.
Source: wp-includes/taxonomy.php:1524
Used by 8 functions | Uses 13 functions

※1464※

```
sanitize_textarea_field()
```

Function: Sanitizes a multiline string from user input or from the database.
Source: wp-includes/formatting.php:5235
Used by 0 functions | Uses 3 functions

※1465※

```
sanitize_text_field()
```

Function: Sanitizes a string from user input or from the database.
Source: wp-includes/formatting.php:5207
Used by 34 functions | Uses 3 functions

※1466※

```
sanitize_title()
```

Function: Sanitizes a title, or returns a fallback title.
Source: wp-includes/formatting.php:2159
Used by 38 functions | Uses 3 functions

※1467※

```
sanitize_title_for_query()
```

Function: Sanitizes a title with the ‘query’ context.
Source: wp-includes/formatting.php:2194
Used by 1 function | Uses 1 function

※1468※

```
sanitize_title_with_dashes()
```

Function: Sanitizes a title, replacing whitespace and a few other characters with dashes.
Source: wp-includes/formatting.php:2211
Used by 4 functions | Uses 2 functions

※1469※

```
sanitize_trackback_urls()
```

Function: Sanitize space or carriage return separated URLs that are used to send trackbacks.
Source: wp-includes/formatting.php:5371
Used by 2 functions | Uses 2 functions

※1470※

```
sanitize_url()
```

Function: Performs esc_url() for database or redirect usage.
Source: wp-includes/deprecated.php:2016
Used by 0 functions | Uses 2 functions

References:

[1]. Functions | WordPress Developer Resources

https://developer.wordpress.org/reference/functions/

*EOF*
