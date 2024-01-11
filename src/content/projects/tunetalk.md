---
title: "TuneTalk"
description: "Site that allows users to search for albums from Spotify and write reviews"
pubDate: "5"
heroImage: "/TuneTalkCover.png"
tags: ["JavaScript", "React.js", "HTML", "CSS", "Third-Party API"]
---

TuneTalk is a site that allows users to search for albums from Spotify and write reviews. Users can freely search the site to see other reviews, but must make an account in order to write new reviews. Administrators have a separate account that can be used to moderate other users and reviews if necessary. 

Site: https://main--melodic-liger-3a353c.netlify.app/
Repository: https://github.com/JamesColesanti/tunetalk-react-web-app

### Major Features

#### Search for Albums
Anyone who visits the site can use the search feature. Results come directly from the Spotify API, allowing the site to stay up-to-date with all the latest releases. Clicking a result will bring up that album's TuneTalk page, which displays any reviews that have been written.

![alt text](/TuneTalkSearch.png)

#### Write/View Reviews
On an album's custom page, users can view previously written review and write their own. Users will need to create an account on TuneTalk in order to write reviews.

![alt text](/TuneTalkWriteReviews.png)

#### (Admin) Moderate Users/Reviews
Admin users can moderate the site through a custom portal. This allows admins to view all users, and remove any if necessary. They can also make other users admins.

![alt text](/TuneTalkAdminModUsers.png)

Another feature specific for admin users is the ability to delete certain reviews. When an admin is logged in, an "X" will appear in the top right corner of every review. This can be clicked to delete the review.

![alt text](/TuneTalkAdminModReviews.png)
