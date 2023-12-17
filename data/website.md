For my clients I recommend a CMS solution such as [Sanity](https://sanity.io), the flexibility is incredible and as long as you can make a graphql query your frontend can use all your content hosted on Sanity. For a long while I used Sanity for my own site as well, however, working as a single freelance developer I often found that I did not have time to update my website content and to gether all the documentation I would need for each project. The vast majority of my content was also already hosted on [GitHub](https://github.com/svey-xyz) and I did not want to have to maintain two databases. This lead me to look for other solutions.

With a bit of work I was able to use [GitHub's graphql api](https://docs.github.com/en/graphql) to query all of the content I would need for my site. The site you are looking at now is built without a traditional CMS and every piece of data is queried from [my GitHub profile](https://github.com/svey-xyz).