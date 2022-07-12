---
  
title: Class IssuesAssociationRequest
description:
taxonomy:
    category: git-integration-for-jira-data-center

---


* Package [com.bigbrassband.jira.git.rest.publicmodels](README.html)
*  *[Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html)*  > [IssuesAssociationRequest](IssuesAssociationRequest.html)

Created by isvirkina on 29.06.18.


## Summary
#### Constructors
| Visibility | Signature |
| --- | --- |
| `public` | [IssuesAssociationRequest](#issuesassociationrequest)() |
| `public` | [IssuesAssociationRequest](#issuesassociationrequestlist)( *[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)* < *[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)* > changeStrs) |

#### Methods
| Type and modifiers | Method signature |
| --- | --- |
| `public` [IssuesAssociationRequest](IssuesAssociationRequest.html) | [addLink](#addlinkstring)( *[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)*  issueKey) |
| `public`  *[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)* < *[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)* > | [getChangeStrs](#getchangestrs)() |
| `public` [IssuesAssociationRequest](IssuesAssociationRequest.html) | [removeLink](#removelinkstring)( *[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)*  issueKey) |
| `public` `void` | [setChangeStrs](#setchangestrslist)( *[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)* < *[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)* > changeStrs) |
| `public`  *[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)* <[CommitIssueChange](../../services/indexer/revisions/CommitIssueChange.html)> | [transform](#transformstring-string-int)( *[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)*  author,  *[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)*  commitHash, `int` commitTime) |



# Constructors
## IssuesAssociationRequest()




## IssuesAssociationRequest(List<String>)





# Methods
## addLink(String)




## getChangeStrs()




## removeLink(String)




## setChangeStrs(List<String>)




## transform(String, String, int)




