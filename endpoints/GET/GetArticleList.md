Gets a list of site articles (news posts).
# Parameters
### Optional
- limit

# Response
```
articleList[]
    id
    slug
    title
    summary
    body
    userId
    createDate
    updateDate
    publishDate
    publishTarget
    publishTags[]
        #publishTag#
    coverImagePath
    commentsCount
    ?community
pagination
    count
    page
    pages
    per
gameList[]
    #game#
userList[]
    #user#
```
## Notable Parameter Descriptions
- limit: Maximum and default is 500 articles.
## Notable Property Descriptions
- publishTarget: Always "news".
- publishTags: Tags on the article.
- gameList: Games embedded in the article.
- userList: Includes the creator of the article, anybody @mentioned in the article, and the creators of related articles.
- community: Bollean, true when posted by a non-admin user, false **OR** missing when marked as "official site news".

## Object Types
TODO

  
