# logout-once-wordpress-blog
 
This code is only for Jetpack connected Self Hosted WordPress blogs.
 
Currently you have to logout twice. One from your blog and another time from WordPress.com.
 
This code will help you Logout from both at once pertaining you have Jetpack Toolbar active.
 
Place below code in functions.php or <a href="https://kunaldesai.blog/create-wordpress-blog-specific-plugin/" terget="_blank">WordPress Blog Specific Plugin</a>
 
 
// To logout of your blog and WordPress.com all at once

add_filter( 'jetpack_masterbar_should_logout_from_wpcom', '__return_true' );
