---
title: "Commenting on collections"
order: 38
page_id: "commenting_on_collections"
warning: false
---

Postman provides a quick way to collaborate with your team members by allowing you to post comments on collections and requests. This is an easy way to provide valuable feedback to your team members on your collections and requests.

This topic describes the following sections:

* [Posting comments](#posting-comments)
* [Reading comments](#reading-comments)
* [Editing comments](#editing-comments)
* [Deleting comments](#deleting-comments)
* [Tagging members in comments](#tagging-members-in-comments)
* [Markdown support](#markdown-support)

## Posting comments

**Notes:**

* Postman app currently supports comments on requests only.
* Team members must have access to the collection in question in order to post comments.
* You can only post comments on saved requests.

### Posting comments on a collection

You can leave a comment on a collection through the [Postman Dashboard](https://app.getpostman.com). To post a comment on a collection, navigate to the `Collections` tab at the top of the page, select the collection you want to leave a comment on, then click **Comments**.

[![comment collection](https://user-images.githubusercontent.com/5029719/71972143-0302e200-3204-11ea-9eed-7db783785711.png)](https://user-images.githubusercontent.com/5029719/71972143-0302e200-3204-11ea-9eed-7db783785711.png)

### Posting comments on a request

You can comment on requests via the [web dashboard](https://app.getpostman.com) or the Postman app. When you comment on a request, it is reflected in both the Dashboard and the app.

To post a comment, select the corresponding request and click **Comments**. Write your comment, then click **Add Comment** to publish. The procedure to post a comment is similar in the Postman app and the dashboard.

[![post comments](https://assets.postman.com/postman-docs/comment-general.gif)](https://assets.postman.com/postman-docs/comment-general.gif)

> If someone tags you in a comment on a private collection that you don’t have access for, Postman sends a notification to you. However, you can’t read the comment until the collection or the request is shared with you.  

## Reading comments

You can see comments made by teammates on requests and collections with the Postman app or the [web dashboard](https://app.getpostman.com).

### Reading comments on the Postman app

To review comments, navigate to the request in question and click **Comments** to view all comments associated with the request.

> The comment button displays the number of existing comments between brackets.

[![read comments app](https://user-images.githubusercontent.com/5029719/71972448-8c1a1900-3204-11ea-8c9e-eae41eb5c54a.png)](https://user-images.githubusercontent.com/5029719/71972448-8c1a1900-3204-11ea-8c9e-eae41eb5c54a.png)

### Reading comments on the Postman dashboard

You can read the comments made on a collection through the [Postman Dashboard](https://app.getpostman.com).

To read the comments on a collection, navigate to the **Collections** tab at the top of the page, select the collection in mind, then click **Comments**.

[![read comment collection dashboard](https://user-images.githubusercontent.com/5029719/71084214-b3913f00-218c-11ea-8796-cab07431775f.gif)](https://user-images.githubusercontent.com/5029719/71084214-b3913f00-218c-11ea-8796-cab07431775f.gif)

To read the comments on a specific request, navigate to the **Collections** tab at the top of the page, select the collection to which the request belongs, select the request, then click **Comments**.

[![read comment request dashboard](https://user-images.githubusercontent.com/5029719/71084799-f56eb500-218d-11ea-9850-8f2bb4701cc7.gif)](https://user-images.githubusercontent.com/5029719/71084799-f56eb500-218d-11ea-9850-8f2bb4701cc7.gif)

## Editing comments

After posting a comment, you can go back, edit your comment and save your changes. Only you as a creator of the comment will be able to update/modify your comment.

[![edit comments](https://user-images.githubusercontent.com/5029719/71972899-84a73f80-3205-11ea-8721-f54ac0a4a03d.png)](https://user-images.githubusercontent.com/5029719/71972899-84a73f80-3205-11ea-8721-f54ac0a4a03d.png)

## Deleting comments

You can delete your comments by clicking **delete**:

[![delete comments](https://user-images.githubusercontent.com/5029719/71972924-91c42e80-3205-11ea-8b97-61142d7e6919.png)](https://user-images.githubusercontent.com/5029719/71972924-91c42e80-3205-11ea-8b97-61142d7e6919.png)

> For moderation purposes, Admins can delete anyone’s comment. However, admins will not be able to update/modify a comment.

## Tagging members in comments

Sometimes you may want to call the attention of a team member when posting a comment. In such a scenario, you can tag a person by typing the @ symbol followed by the member’s name and then choosing the corresponding name from the auto-suggested list. When you tag a member in your comment, Postman notifies the member by sending a notification.

[![post comments](https://assets.postman.com/postman-docs/comment-mention.png)](https://assets.postman.com/postman-docs/comment-mention.png)

The user tagged in your comment will get a notification by email and/or in-app as long as they have not disabled these types of notifications. The notifications in-app are shown at the top-right on the bell icon. To navigate to the comment, the recipient can click the collection name.

[![receive comment](https://user-images.githubusercontent.com/5029719/71098559-cb2af080-21a9-11ea-95ae-68b5dbb2eea9.png)](https://user-images.githubusercontent.com/5029719/71098559-cb2af080-21a9-11ea-95ae-68b5dbb2eea9.png)

## Markdown support

Postman comments support Markdown. For more information on formatting using Markdown refer to [Markdown in API Documentation](https://documenter.getpostman.com/view/33232/markdown-in-api-documentation/JsGc?version=latest).

[![post comments](https://assets.postman.com/postman-docs/comment-markdown.png)](https://assets.postman.com/postman-docs/comment-markdown.png)
