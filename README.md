# JIRA-and-Confluence-Data-Using-R-
This can be done by calling JIRA APIs (Rest) from your R code.
Sample code:
req <- GET(TJIRA_API_URL, path = "rest/api/2/issue/XXXX", authenticate(user = JIRA_USER, password = JIRA_API_KEY, type="basic"), verbose(), accept_json())
