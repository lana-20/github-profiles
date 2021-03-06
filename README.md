| [Github Profiles](https://github.com/lana-20/50_Projects_in_50_Days/tree/main/GithubProfiles) | [Live Demo](https://lana-20.github.io/github-profiles/) |
|----|----|

In this project, I am using the GitHub API to fetch users.
I am able to search for GitHub users to get some of their profie data and display it in a card.
And I am making a separate request to get the user's latest 10 repositories, which also display in the card.
If I search for eg. "florinpop17" you see his avatar, name, bio, followers, following, his latest 10 repos.
Of course, I can searh for my own eg. "lana-20". But if I search for something that is not a name, 
it will say "No profile with this username", and do some error handling as well.

GitHub REST API documentation: https://docs.github.com/en/rest.

Fetch users: https://docs.github.com/en/rest/reference/users#get-a-user.

Fetch user's repos: https://docs.github.com/en/rest/reference/repos#list-repositories-for-a-user.

I am also using Axios instead of the Fetch API: https://github.com/axios/axios, https://cdnjs.com/libraries/axios.
Axios is a library, a promise-based HTTP client for the browser and node.js.
I prefer Axios when working on any medium to large size projects. It has better features.
It is easier to use. The error handling is better. I am using it with async/await, but it can 
definitely be used with the .then .catch syntax.
