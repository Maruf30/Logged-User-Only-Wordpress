# Logged-User-Only-Wordpress


<?php if (is_user_logged_in() ): ?>
	<a href="<?php echo wp_logout_url() ?>" title="Logout">Logout</a>
<?php else: ?> 
        <a href="http://example.com/wp-login.php" title="Logout">Member Login</a>
<?php endif ?>
