### WeHeartIt sold, purged and is an image editing app now. These endpoints wont work for anything now.

## 💗 WeHeartIt API Endpoints 

Reverse engineered endpoints from decompiled sources of weheartit.com's official Android App.

The version of the app used for decompiling is `v9.0.1.RC-GP-Free(21892)`, released on `20th June 2022`.

All the endpoints are categorized by request methods that can be utilized on them. See [here](https://restfulapi.net/http-methods/) if you don't know what that means.

<details>
<summary> 🖇️ GET </summary>

|    uri     |
|:-----------|
| `/api/v2/articles` |
| `/api/v2/badges?reactions=1` |
| `/api/v2/c2/entries/{entryId}/collections` |
| `/api/v2/c2/entries/{entryId}` |
| `/api/v2/articles/channel/{id}` |
| `/api/v2/inspirations/{id}/collections?include=colors` |
| `/api/v2/inspirations/{id}/channel_info` |
| `/api/v2/inspirations/{id}/members?include=recent_hearts` |
| `/api/v2/collections/{collectionId}/collaborators` |
| `/api/v2/collections/{id}/followers` |
| `/api/v2/lists/collections/{code}` |
| `/api/v2/entries/{id}/comments` |
| `/api/v2/entries/{entryId}/context?include=context_user_collections,actionable,actions,video,promoted_cta` |
| `/api/v2/lists/entries/{code}` |
| `/api/v2/user/followers?include=recent_hearts` |
| `/api/v2/user/following?include=recent_hearts` |
| `/api/v2/articles/following` |
| `/api/v2/user/alerts` |
| `/api/v2/user/blocked_contacts` |
| `/api/v2/collections/{id}?include=user,collaboration` |
| `/api/v2/collections/{collectionId}/entries` |
| `/api/v2/inbox/conversations/{postcard_id}/postcards?include=colors,promoted,promoted_cta,video,actions` |
| `/api/v2/inbox/conversations` |
| `/api/v2/user` |
| `/api/v2/user` |
| `/api/v2/user/collections?include=user` |
| `/api/v2/entries/{entry_id}?include=promoted,promoted_cta,actions,video,reaction_counts` |
| `/api/v2/entries/{entry_id}/via/{user_id}?include=promoted,promoted_cta,actions,video` |
| `/api/v2/entries/{entry_id}/hearters?include=recent_hearts` |
| `/api/v2/users/{user_id}/followers?include=recent_hearts` |
| `/api/v2/users/{user_id}/following?include=recent_hearts` |
| `/api/v2/user/dashboard/grouped?include=promoted,promoted_cta,colors,following_status,actions,video,featured_post,reaction_counts` |
| `/api/v2/inspirations/{code}` |
| `/api/v2/inspirations/{id}/entries?include=promoted,promoted_cta,colors,actions,video` |
| `/api/v2/inspirations?include=colors` |
| `/api/v2/entries?sticky=0` |
| `/api/v2/inbox/conversations/recipients` |
| `/api/v2/entries/{entryId}/similar` |
| `/api/v2/registration/{tag}/collections` |
| `/api/v2/tags/{tagName}/entries` |
| `/api/v2/collections?include=user,following_status` |
| `/api/v2/users?include=following_status,recent_hearts` |
| `/api/v2/users/{user_id}/collections?include=user&sort=recency` |
| `/api/v2/users/{user_id}` |
| `/api/v2/users/{username}?username=true` |
| `/api/v2/user/recent_collections` |
| `/api/v2/users/{userId}/uploads?include=user` |
| `/api/v2/users/identities` |
| `/api/v2/user/channels` |
| `/api/v2/notifications?mark_as_read=true` |
| `/api/v2/products?platform=android&tag=v6` |
| `/api/v2/entries/{entryId}/reactions` |
| `/api/v2/articles/recommended` |
| `/api/v2/articles/channel/{id}/recommended` |
| `/api/v2/articles/following/recommended` |
| `/api/v2/search/collections?include=user` |
| `/api/v2/search/entries` |
| `/api/v2/search/users?include=following_status,recent_hearts` |
| `/api/v2/entries/sticky?media_type=article` |
| `/api/v2/search/suggestions` |
| `/api/v2/promoted_topics` |
| `/api/v2/users/{userId}/canvas?include=colors,actions,video&exclude=tags` |
| `/api/v2/users/{userId}/entries` |
| `/api/v2/user/purchases` |
| `/api/v2/lists/users/{code}?include=recent_hearts` |
</details>

<details>
<summary> 🖇️ POST </summary>

| uri |
|:----|
|`/oauth/token/`|
|`/upload/`|
| `/api/v2/collections/{collectionId}/collaborators/abandon` |
| `/api/v2/devices/activate` |
| `/api/v2/collections/{collection_id}/entries/{entry_id}` |
| `/api/v2/collections/{id}/entries` |
| `/api/v2/user/block_user` |
| `/api/v2/user/update_password` |
| `/api/v2/collections?include=user` |
| `/api/v2/entries` |
| `/api/v2/users` |
| `/api/v2/shared_urls` |
| `/api/v2/devices/deactivate` |
| `/api/v2/follow` |
| `/api/v2/hearts/{entryId}` |
| `/api/v2/collections/{collectionId}/collaborators/{userId}/add` |
| `/api/v2/invitations` |
| `/api/v2/user/experiments/invoke` |
| `/api/v2/inspirations/join` |
| `/api/v2/user/accounts` |
| `/api/v2/inbox/conversations/open_shared` |
| `/api/v2/entries/{id}/comments` |
| `/api/v2/entries/{entryId}/reactions` |
| `/api/v2/recover_accounts` |
| `/api/v2/devices/push_token` |
| `/api/v2/collections/{collectionId}/collaborators/{userId}/remove` |
| `/api/v2/entries/{entryId}/reports` |
| `/api/v2/search/contacts` |
| `/api/v2/inbox/conversations` |
| `/api/v2/user/cover/{id}` |
| `/api/v2/inbox/conversations/create_shared` |
| `/api/v2/push_notifications/open` |
| `/api/v2/tracking` |
| `/api/v2/user/unblock_user` |
| `/api/v2/user/canvas` |
| `/api/v2/purchases` |
| `/api/v2/entries/{entryId}/view` |
</details>

<details>
<summary> 🖇️ DELETE </summary>

|uri|
|:----|
| `/api/v2/user/` |
| `/api/v2/collections/{id}` |
| `/api/v2/entries/{entryId}/comments/{commentId}` |
| `/api/v2/inbox/conversations/{conversationId}` |
| `/api/v2/entries/{id}` |
| `/api/v2/notifications/{id}` |
| `/api/v2/user/cover` |
| `/api/v2/collections/{id}/entries` |
| `/api/v2/collections/{collection_id}/entries/{entry_id}` |
| `/api/v2/entries/{entryId}/reactions` |
| `/api/v2/user/canvas` |
| `/api/v2/follow/{type}/{id}` |
| `/api/v2/hearts` |
| `/api/v2/hearts/{entryId}` |
| `/api/v2/user/accounts/{service}` |

</details>

<details>
<summary> 🖇️ PUT </summary>

|uri|
|:----|
| `/api/v2/notifications/{id}` |
| `/api/v2/user/invitations/count?increment=1` |
| `/api/v2/inspirations/{id}/join` |
| `/api/v2/inspirations/{id}/leave` |
| `/api/v2/collections/{id}` |
| `/api/v2/entries/{entryId}/comments/{commentId}` |
| `/api/v2/entries/{id}` |
| `/api/v2/user` |

</details>

---

#### for details on how this information was gathered, see [here](https://aswinnnn.github.io/blog/Reverse-Engineering-the-We-Heart-It-API/)
##### If you're looking for an API wrapper for this, checkout [weheartpy](https://github.com/aswinnnn/weheartpy), which is a _work in progress_.
