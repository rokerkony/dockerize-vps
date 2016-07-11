# Example how to set up VPS with docker for multiple websites

Example show 2 applications:
 - [konradcerny.cz](http://konradcerny.cz) with `nginx:latest` and `PHP 5.5`
 - [my-other-site.com](http://my-other-site.com) with `nginx:latest` and `PHP 7.0`

Application code should be located in `/srv/www/konradcerny.cz` or `/srv/www/my-other-site.com`.
Content of these folders will linked as a volume to proper image.

For more information follow this article on [medium.com](http://...)
