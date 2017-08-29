# Brightcove single video sharing
This Proof of concept is basically for sharing videos from website which are loaded from brightcove.

### Problem Statement
If there are multiple videos on a webpage and there isn't a separate page for each video, then it is difficult to share single video. However you can share the page itself which contains multiple video. But this is not as per expectation. 

This is because, for sharing single video you would require specific meta tags which can create tiles on social websites.

### Solution
A separate page can be created from server side by passing parameters as query string. Based on the query string meta tags will be populated & the page url can be shared. Again, before sharing the url an additional query string is appended, notifying that if user land up on the shared url it wont trigger the sharing again. And that it!!!



