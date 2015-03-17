#### **(step 10)** Add your SSH Keys

Unless you want to access your repositories exclusively via Smart HTTP, users will need to set a public key to connect via SSH.

To do this, open a browser, login to Redmine and follow the "My Account" link in the upper right-hand corner of the page then "Add SSH keys" link.

SSH Keys should be unique, that is, the keys you set in Redmine **should not** already exist in the Gitolite repo.

<div class="alert alert-danger" role="alert" markdown="1">
In particular, **do not re-use the key you set as the Gitolite admin key**.
</div>

At this point, the plugin should work. If not, take a look here : [Troubleshooting]({{ site.baseurl }}/configuration/troubleshooting).

[Let me know if it works ! (or not)](https://github.com/jbox-web/redmine_git_hosting/issues/339)