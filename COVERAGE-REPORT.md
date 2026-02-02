# API Coverage Report: Codebase vs OpenAPI Specs

Generated: Mon Feb  2 16:04:50 UTC 2026

## instagram (spec: 36 endpoints)

**API URLs in codebase (3):**
- `https://instagram.com/{id}`
- `https://www.instagram.com/oauth/authorize?{id}`
- `https://{id}`

**Paths in spec (36):**
- `/ig_hashtag_search`
- `/me`
- `/{comment-id}`
- `/{comment-id}/replies`
- `/{hashtag-id}`
- `/{hashtag-id}/recent_media`
- `/{hashtag-id}/top_media`
- `/{media-id}`
- `/{media-id}/comments`
- `/{media-id}/insights`
- `/{media-id}/product_tags`
- `/{user-id}`
- `/{user-id}/available_catalogs`
- `/{user-id}/business_discovery`
- `/{user-id}/comments_filter`
- `/{user-id}/content_publishing_limit`
- `/{user-id}/insights`
- `/{user-id}/insights/audience`
- `/{user-id}/insights/content`
- `/{user-id}/live_media`
- `/{user-id}/media`
- `/{user-id}/media_containers`
- `/{user-id}/media_publish`
- `/{user-id}/mentions`
- `/{user-id}/product_catalogs`
- `/{user-id}/shopping_tags`
- `/{user-id}/stories`
- `/{user-id}/subscribed_apps`
- `/{user-id}/tags`

---

## facebook (spec: 28 endpoints)

**API URLs in codebase (5):**
- `https://facebook.com/{id}`
- `https://graph.facebook.com/{id}/picture?type=normal`
- `https://www.facebook.com/stories/{id}`
- `https://www.facebook.com/v18.0/dialog/oauth?{id}`
- `https://www.facebook.com/{id}`

**Paths in spec (28):**
- `/me`
- `/me/accounts`
- `/{comment-id}`
- `/{comment-id}/comments`
- `/{page-id}`
- `/{page-id}/feed`
- `/{page-id}/insights`
- `/{page-id}/photos`
- `/{page-id}/posts`
- `/{page-id}/videos`
- `/{photo-id}`
- `/{post-id}`
- `/{post-id}/comments`
- `/{post-id}/insights`
- `/{post-id}/likes`
- `/{video-id}`
- `/{video-id}/insights`

---

## tiktok (spec: 22 endpoints)

**API URLs in codebase (4):**
- `https://open.tiktokapis.com/v2/video/list/?{id}`
- `https://tiktok.com/@{id}`
- `https://www.tiktok.com/v2/auth/authorize/?{id}`
- `https://{id}`

**Paths in spec (22):**
- `/auth/authorize`
- `/comment/delete/`
- `/comment/publish/`
- `/oauth/client_credentials/`
- `/oauth/revoke/`
- `/oauth/token/`
- `/oauth/token/info/`
- `/post/publish/content/init/`
- `/post/publish/creator_info/query/`
- `/post/publish/inbox/video/init/`
- `/post/publish/status/fetch/`
- `/post/publish/video/init/`
- `/research/user/info/`
- `/research/video/query/`
- `/share/video/`
- `/user/info/`
- `/user/info/extended/`
- `/video/embed/`
- `/video/list/`
- `/video/query/`
- `/{upload_url}`

---

## youtube (spec: 42 endpoints)

**API URLs in codebase (10):**
- `https://accounts.google.com/o/oauth2/auth?{id}`
- `https://www.googleapis.com/upload/youtube/v3/thumbnails/set?videoId={id}`
- `https://www.googleapis.com/upload/youtube/v3/videos?uploadType=resumable&part=snippet,status`
- `https://www.googleapis.com/youtube/v3/channels?part=contentDetails&mine=true&access_token={id}`
- `https://www.googleapis.com/youtube/v3/playlistItems?part=snippet,contentDetails&playlistId={id}&maxResults=50&access_token={id}`
- `https://www.googleapis.com/youtube/v3/videos?part=statistics&id={id}&access_token={id}`
- `https://www.youtube.com/watch?v={id}`
- `https://youtube.com/@{id}`
- `https://youtube.com/channel/{id}`
- `https://youtubeanalytics.googleapis.com/v2/reports?{id}`

**Paths in spec (42):**
- `/activities`
- `/captions`
- `/captions/{id}`
- `/channelSections`
- `/channels`
- `/commentThreads`
- `/comments`
- `/i18nLanguages`
- `/i18nRegions`
- `/members`
- `/membershipsLevels`
- `/playlistItems`
- `/playlists`
- `/search`
- `/subscriptions`
- `/thumbnails/set`
- `/videoAbuseReportReasons`
- `/videoCategories`
- `/videos`
- `/videos/getRating`
- `/videos/rate`
- `/videos/reportAbuse`
- `/watermarks/set`
- `/watermarks/unset`

---

## linkedin (spec: 26 endpoints)

**API URLs in codebase (12):**
- `https://api.linkedin.com/rest/socialActions/{id}/comments`
- `https://api.linkedin.com/v2/networkSizes/{id}?edgeType=CompanyFollowedByMember`
- `https://api.linkedin.com/v2/organizations/{id}?projection=(id,localizedName,vanityName,logoV2(original~:playableStreams,cropped~:playableStreams),websiteUrl,localizedSpecialties,industries)`
- `https://api.linkedin.com/v2/organizations/{id}?projection=(localizedName,vanityName,logoV2(original~:playableStreams,cropped~:playableStreams))`
- `https://api.linkedin.com/v2/people/(id:{id})?projection=(id,localizedFirstName,localizedLastName,vanityName,profilePicture(displayImage~:playableStreams))`
- `https://api.linkedin.com/v2/socialActions/{id}/comments`
- `https://api.linkedin.com/v2/socialActions/{id}/comments/{id}`
- `https://api.linkedin.com/v2/socialActions/{id}/comments?count={id}&start={id}`
- `https://api.linkedin.com/v2/userinfo`
- `https://www.linkedin.com/feed/update/{id}`
- `https://www.linkedin.com/feed/update/{id}/`
- `https://www.linkedin.com/in/{id}/`

**Paths in spec (26):**
- `/rest/images`
- `/rest/images/{id}`
- `/rest/organizationalEntityFollowerStatistics`
- `/rest/organizationalEntityShareStatistics`
- `/rest/organizations`
- `/rest/organizations/{id}`
- `/rest/people/(id{personId})`
- `/rest/posts`
- `/rest/posts/{id}`
- `/rest/posts?ids=List({id1},{id2})`
- `/rest/reactions`
- `/rest/socialActions/{entityId}/comments`
- `/rest/socialMetadata/{entityId}`
- `/rest/videos`
- `/rest/videos/{id}`

---

## pinterest (spec: 231 endpoints)

**API URLs in codebase (3):**
- `https://pinterest.com/{id}`
- `https://www.pinterest.com/oauth/?{id}`
- `https://www.pinterest.com/pin/{id}/`

**Paths in spec (231):**
- `/ad_accounts`
- `/advanced_auction/items/get`
- `/advanced_auction/items/submit`
- `/boards`
- `/businesses/employers`
- `/businesses/invites`
- `/catalogs`
- `/catalogs/available_filter_values`
- `/catalogs/feeds`
- `/catalogs/items`
- `/catalogs/items/batch`
- `/catalogs/product_groups`
- `/catalogs/product_groups/multiple`
- `/catalogs/products/get_by_product_group_filters`
- `/catalogs/reports`
- `/catalogs/reports/stats`
- `/integrations`
- `/integrations/commerce`
- `/integrations/logs`
- `/media`
- `/notifications`
- `/oauth/conversion_token`
- `/oauth/token`
- `/oauth/token/revoke`
- `/pins`
- `/pins/analytics`
- `/resources/ad_account_countries`
- `/resources/delivery_metrics`
- `/resources/lead_form_questions`
- `/resources/metrics_ready_state`
- `/search/boards`
- `/search/partner/pins`
- `/search/pins`
- `/terms/related`
- `/terms/suggested`
- `/trends/product_categories/details`
- `/trends/product_categories/trending`
- `/trends/topics/featured`
- `/user_account`
- `/user_account/analytics`
- `/user_account/analytics/top_pins`
- `/user_account/analytics/top_video_pins`
- `/user_account/businesses`
- `/user_account/followers`
- `/user_account/following`
- `/user_account/following/boards`
- `/user_account/websites`
- `/user_account/websites/verification`

---

## twitter (spec: 145 endpoints)

**API URLs in codebase (7):**
- `https://api.twitter.com/2/users/{id}/tweets?max_results={id}&tweet.fields=created_at,attachments,entities&expansions=attachments.media_keys&media.fields=preview_image_url,url,type`
- `https://api.twitter.com/2/users/{id}/tweets?max_results={id}&tweet.fields=created_at,attachments,entities,public_metrics&expansions=attachments.media_keys&media.fields=preview_image_url,url,type`
- `https://api.x.com/2/media/upload?command=STATUS&media_id={id}`
- `https://twitter.com/i/web/status/{id}`
- `https://upload.twitter.com/1.1/media/upload.json?command=STATUS&media_id={id}`
- `https://x.com/i/oauth2/authorize?{id}`
- `https://x.com/{id}`

**Paths in spec (145):**
- ``

---

## threads (spec: 29 endpoints)

**API URLs in codebase (4):**
- `https://threads.net/@{id}`
- `https://threads.net/oauth/authorize?{id}`
- `https://www.threads.com/@{id}/post/{id}`
- `https://www.threads.com/post/{id}`

**Paths in spec (29):**
- `/v1.0/me`
- `/v1.0/me/accounts`
- `/v1.0/me/followers`
- `/v1.0/me/following`
- `/v1.0/me/insights/demographic`
- `/v1.0/me/insights/performance`
- `/v1.0/me/media`
- `/v1.0/me/media_containers`
- `/v1.0/me/rate_limit_status`
- `/v1.0/me/subscriptions`
- `/v1.0/me/threads`
- `/v1.0/me/threads/bulk_publish`
- `/v1.0/me/threads/feed`
- `/v1.0/me/threads_insights`
- `/v1.0/search`
- `/v1.0/trending`
- `/v1.0/{media-id}`
- `/v1.0/{reply-id}`
- `/v1.0/{thread-id}`
- `/v1.0/{thread-id}/conversation`
- `/v1.0/{thread-id}/hide`
- `/v1.0/{thread-id}/insights`
- `/v1.0/{thread-id}/publish`
- `/v1.0/{thread-id}/replies`
- `/v1.0/{thread-id}/unhide`

---

## reddit (spec: 50 endpoints)

**API URLs in codebase (4):**
- `https://reddit.com/user/{id}`
- `https://www.reddit.com/api/v1/authorize?{id}`
- `https://www.reddit.com/r/{id}/comments/{id}`
- `https://www.reddit.com{id}`

**Paths in spec (50):**
- `/api/approve`
- `/api/comment`
- `/api/compose`
- `/api/del`
- `/api/distinguish`
- `/api/editusertext`
- `/api/friend`
- `/api/multi/user/{username}/{multiname}`
- `/api/read_message`
- `/api/remove`
- `/api/save`
- `/api/submit`
- `/api/subscribe`
- `/api/unfriend`
- `/api/unsave`
- `/api/v1/me`
- `/api/v1/me/karma`
- `/api/v1/me/prefs`
- `/api/v1/user/{username}/trophies`
- `/api/vote`
- `/best`
- `/comments/{article}`
- `/message/inbox`
- `/message/sent`
- `/message/unread`
- `/r/all`
- `/r/popular`
- `/r/{subreddit}`
- `/r/{subreddit}/about`
- `/r/{subreddit}/about/moderators`
- `/r/{subreddit}/about/modqueue`
- `/r/{subreddit}/about/reports`
- `/r/{subreddit}/api/flair`
- `/r/{subreddit}/api/flairlist`
- `/r/{subreddit}/api/wiki/edit`
- `/r/{subreddit}/controversial`
- `/r/{subreddit}/hot`
- `/r/{subreddit}/new`
- `/r/{subreddit}/rising`
- `/r/{subreddit}/search`
- `/r/{subreddit}/top`
- `/r/{subreddit}/wiki/pages`
- `/r/{subreddit}/wiki/revisions/{page}`
- `/r/{subreddit}/wiki/{page}`
- `/search`
- `/subreddits/search`
- `/user/{username}/about`
- `/user/{username}/comments`
- `/user/{username}/submitted`

---

## bluesky (spec: 34 endpoints)

**API URLs in codebase (3):**
- `https://bsky.app/profile/{id}`
- `https://bsky.app/profile/{id}/post/{id}`
- `https://plc.directory/{id}`

**Paths in spec (34):**
- `/xrpc/app.bsky.actor.getPreferences`
- `/xrpc/app.bsky.actor.getProfile`
- `/xrpc/app.bsky.actor.getProfiles`
- `/xrpc/app.bsky.actor.getSuggestions`
- `/xrpc/app.bsky.actor.putPreferences`
- `/xrpc/app.bsky.actor.searchActors`
- `/xrpc/app.bsky.actor.searchActorsTypeahead`
- `/xrpc/app.bsky.feed.getAuthorFeed`
- `/xrpc/app.bsky.feed.getLikes`
- `/xrpc/app.bsky.feed.getPostThread`
- `/xrpc/app.bsky.feed.getPosts`
- `/xrpc/app.bsky.feed.getRepostedBy`
- `/xrpc/app.bsky.feed.getTimeline`
- `/xrpc/app.bsky.feed.searchPosts`
- `/xrpc/app.bsky.graph.getBlocks`
- `/xrpc/app.bsky.graph.getFollowers`
- `/xrpc/app.bsky.graph.getFollows`
- `/xrpc/app.bsky.graph.getMutes`
- `/xrpc/app.bsky.graph.muteActor`
- `/xrpc/app.bsky.graph.unmuteActor`
- `/xrpc/app.bsky.notification.getUnreadCount`
- `/xrpc/app.bsky.notification.listNotifications`
- `/xrpc/app.bsky.notification.updateSeen`
- `/xrpc/chat.bsky.convo.getConvo`
- `/xrpc/chat.bsky.convo.getMessages`
- `/xrpc/chat.bsky.convo.listConvos`
- `/xrpc/chat.bsky.convo.sendMessage`
- `/xrpc/com.atproto.repo.createRecord`
- `/xrpc/com.atproto.repo.deleteRecord`
- `/xrpc/com.atproto.repo.getRecord`
- `/xrpc/com.atproto.repo.putRecord`
- `/xrpc/com.atproto.server.createSession`

---

## googlebusiness (spec: 27 endpoints)

**API URLs in codebase (8):**
- `https://accounts.google.com/o/oauth2/auth?{id}`
- `https://mybusiness.googleapis.com/v4/accounts/{id}/locations/{id}/localPosts`
- `https://mybusiness.googleapis.com/v4/accounts/{id}/locations/{id}/localPosts/{id}`
- `https://mybusiness.googleapis.com/v4/accounts/{id}/locations/{id}/localPosts?pageSize={id}`
- `https://mybusiness.googleapis.com/v4/accounts/{id}/locations/{id}/reviews`
- `https://mybusiness.googleapis.com/v4/{id}/reply`
- `https://oauth2.googleapis.com/tokeninfo?access_token={id}`
- `https://www.google.com/maps/search/?api=1&query={id}`

**Paths in spec (27):**
- `/v4/accounts`
- `/v4/categories`
- `/v4/{name}`
- `/v4/{name}/locations/{locationId}`
- `/v4/{name}/locationsreportInsights`
- `/v4/{name}/reply`
- `/v4/{name}fetchVerificationOptions`
- `/v4/{name}verify`
- `/v4/{parent}/answersupsert`
- `/v4/{parent}/localPosts`
- `/v4/{parent}/locations`
- `/v4/{parent}/media`
- `/v4/{parent}/mediastartUpload`
- `/v4/{parent}/questions`
- `/v4/{parent}/reviews`

---

## telegram (spec: 34 endpoints)

**API URLs in codebase (1):**
- `https://t.me/{id}/{id}`

**Paths in spec (34):**
- `/answerInlineQuery`
- `/deleteChatPhoto`
- `/deleteWebhook`
- `/exportChatInviteLink`
- `/forwardMessage`
- `/getChat`
- `/getChatAdministrators`
- `/getChatMember`
- `/getChatMembersCount`
- `/getFile`
- `/getMe`
- `/getUpdates`
- `/getUserProfilePhotos`
- `/getWebhookInfo`
- `/kickChatMember`
- `/leaveChat`
- `/pinChatMessage`
- `/promoteChatMember`
- `/restrictChatMember`
- `/sendAudio`
- `/sendChatAction`
- `/sendContact`
- `/sendDocument`
- `/sendLocation`
- `/sendMessage`
- `/sendPhoto`
- `/sendVideo`
- `/sendVoice`
- `/setChatDescription`
- `/setChatPhoto`
- `/setChatTitle`
- `/setWebhook`
- `/unbanChatMember`
- `/unpinChatMessage`

---

## snapchat (spec: 27 endpoints)

**API URLs in codebase (0):**
- ``

**Paths in spec (27):**
- `/adaccounts`
- `/adaccounts/{ad_account_id}`
- `/adaccounts/{ad_account_id}/ads`
- `/adaccounts/{ad_account_id}/ads/{ad_id}/stats`
- `/adaccounts/{ad_account_id}/adsquads`
- `/adaccounts/{ad_account_id}/adsquads/{ad_squad_id}/stats`
- `/adaccounts/{ad_account_id}/campaigns`
- `/adaccounts/{ad_account_id}/campaigns/{campaign_id}`
- `/adaccounts/{ad_account_id}/campaigns/{campaign_id}/stats`
- `/adaccounts/{ad_account_id}/creatives`
- `/adaccounts/{ad_account_id}/media`
- `/adaccounts/{ad_account_id}/segments`
- `/adaccounts/{ad_account_id}/segments/{segment_id}/users`
- `/organizations`
- `/organizations/{organization_id}`
- `/targeting/demographics`
- `/targeting/geos`
- `/targeting/interests`

---

