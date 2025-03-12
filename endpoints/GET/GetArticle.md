Gets information about a site article (news post).
## Required Parameters
- id OR
- slug

_Bruteforced, other parameters may exist_

# Response
```
article
  body
  commentsCount
  ?community?
  coverImagePath
  createDate
  id
  publishDate
  publishTags[]
    #publishTag#
  publishTarget
  slug
  stickyDate
  summary
  title
  updateDate
  userId
gameList
  #game#
relatedArticleList
  #article#
userList
  #user#
```
## Property Descriptions
- publishTags: Tags on the article, such as "site", "site news", "opinion".
- publishTarget: Always "news".
- 





  
