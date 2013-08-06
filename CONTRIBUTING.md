# Contributing

We are excited that you want to help make DuckDuckGo Search & Stories better!

* If there isn't already an open issue that describes your bug or feature, submit one.
  * If you're submitting a **bug**, please describe a way we can reproduce the problem and the affected versions.
  * If you're submitting a **feature** (cool!), make sure you contact us beforehand so that you aren't duplicating effort.


## Changes
* **Bugs** fork the repository on GitHub and create a topic branch from **master** with your GitHub username in the branch name like:
  `git checkout -b nilnilnil/NPE-stories-longpress origin/master`
* **Features** fork the repository on GitHub and create a topic branch from **develop** with your GitHub username in the branch name like:
  `git checkout -b nilnilnil/sooper_feature origin/develop`
* Don't make huge commits.
* Check whitespace with `git diff --check` before committing.
* Add tests that check what you've done.
* PRs with failing tests will not be accepted.

**Commits:**
````
    (#GH_ISSUE) Make the example in CONTRIBUTING imperative and concrete

    Without this patch applied the example commit message in the CONTRIBUTING
    document is not a concrete example.  This is a problem because the
    contributor is left to imagine what the commit message should look like
    based on a description rather than an example.  This patch fixes the
    problem by making the example concrete and imperative.

    The first line is a real life imperative statement with a GitHub issue #.
    The body describes the behavior without the patch, why this is a problem,
    and how the patch fixes the problem when applied.
````

## Caveats
DuckDuckGo Search & Stories represents a ton of hard work from people all around the world. We've spent a long time thinking about exactly what makes a great mobile experience. While we'd love to accept each an every pull request, that probably wouldn't lead to a coherent experience. If you would like to get more involved, mail us at android@duckduckgo.com.

## Additional Resources

* [Issues](https://github.com/duckduckgo/android/issues)
* [Chat](https://dukgo.com/blog/using-pidgin-with-xmpp-jabber)
* [General info](http://help.dukgo.com/customer/portal/articles/378777-contributing)
* [GitHub pull request documentation](http://help.github.com/send-pull-requests/)
* [General GitHub documentation](http://help.github.com/)