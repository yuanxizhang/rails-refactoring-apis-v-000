# Working with APIs

## Instructions

This lab builds on the [Rails Github API](https://github.com/learn-co-curriculum/rails-github-api/) lab. You're provided with code from that lab.

1. Create a new model `GithubRepo` in `app/models/github_repo.rb`. Since you're not storing `GithubRepo` in a database, this class does _not_ need to inherit from Active Record. Create the file manually – using `rails g model` will automatically inherit from Active Record and create a migration. Build out the `GithubRepo` class to pass the model tests.

2. Move authentication from your controller to your service objects.

3. Implement the `#initialize` method for your `GithubService` objects.

4. Move the rest of your API calls into the `GithubService` object. Analyze the test requirements, and get the application working. 

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/rails-refactoring-apis' title='Working with APIs'>Working with APIs</a> on Learn.co and start learning to code for free.</p>
