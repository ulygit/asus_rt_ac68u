# How to contribute

I'm really glad you're reading this, because working together is better than working alone!

Here are some important resources:

  * [Cloudflare API](http://opengovernment.org/pages/developer) has all the technical details for interfacing with Cloudflare services
  * [Cloudflare "Tokens" support](https://support.cloudflare.com/hc/en-us/articles/200167836-Managing-API-Tokens-and-Keys) has details on the new API Token approach to access control over your Cloudflare account

## Testing

Please test your code thoroughly including failure modes (e.g. connection down, invalid credentials, conflicting inputs, etc.)

## Submitting changes

Please send a [GitHub Pull Request to opengovernment](https://github.com/opengovernment/opengovernment/pull/new/master) with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)). Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."

Please include any necessary changes to documentation within your same, single commit. Also include your name in the Contributors sections of the README with a one-line description of your contribution.

## Coding conventions

Review existing code and you'll get the hang of it. Strive for readability:

  * Use identation consist with existing code
  * Use if-then-else and similar block structures consistent with existing code
  * This is open source software. Consider the people who will read your code, and make it look nice for them. It's sort of like driving a car: Perhaps you love doing donuts when you're alone, but with passengers the goal is to make the ride as smooth as possible.

Thanks!
