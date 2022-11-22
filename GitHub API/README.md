# GitHub API:
The main idea is not the report itself, instead the power query "M Language" recursive calls to GitHub API and fetch repositories based on a keyword.

### Example:
1. Search for "power bi"
1. "per_page" will specify how many search results a response will contain [default 30, max 100]
1. Then "page" parameter to specify how many pages [start 1, no upper limit].
1. Together "per_page" = 30 and "page" = 10 then 300 results will be fetched.
1. If empty results are returned, this means no further calls is needed. Total count is reached for choosen keyword.


### Dashboard
<img src="https://github.com/ahmadhatahet/power-bi/blob/master/GitHub%20API/Dashboard.png" width="512">