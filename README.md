# show_listings
The function is a Wordpress shortcode to get the number of rows with specific categories of the columns.

The show listing function shows how many active job listings there are on the platform. The SQL query active jobs on the platform.

This current function takes the:
table = wp=posts,
post_status (column) = publish,
post_type (column) = hp_listing

publish means a job is currently and actively listed
hp_listing is the category given to posted jobs
