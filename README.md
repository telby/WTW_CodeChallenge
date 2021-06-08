# WTW_CodeChallenge
 
Requirements:

    1. Use Ansible to install NGINX on a Debian based Linux distribution such as Ubuntu.
	2. Script should configure the host to allow traffic to NGINX.
	3. Config should persist on host restart.
	4. Write an NGINX configuration for the new virtual host described in step
		a. Should listen to port 3200.
		b. Should proxy traffic from www.example.com and deliver it to a backend host named localhost on port 3400.
	5. Send all non www.example.com traffic to a custom 404 page.
	6. NGINX should start if the host is restarted.
	7. You must use git for source control and push your code to github.com. Please send me the link to your repository at least 1 day before the second interview.