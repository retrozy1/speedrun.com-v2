Gets information about a site article (news post).
# Parameters
### Required
- id **and/or** slug

# Response
```
article
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
relatedArticleList[]
    #article#
gameList[]
    #game#
userList[]
    #user#
```
## Notable Property Descriptions
- publishTarget: Always "news".
- publishTags: Tags on the article.
- gameList: Games embedded in the article.
- userList: Includes the creator of the article, anybody @mentioned in the article, and the creators of related articles.
- community: Bollean, true when posted by a non-admin user, false **OR** missing when marked as "official site news".

## Object Types
TODO

  
