# Vulcan
## Framework for web application

Uses Go as a base language

### ToDo
- <del>Store templates in tmpl/ and page data in data/</del>
- Add handler to make web root redirect to /view/FrontPage
- <del>Tidy up templates using valid HTML and adding CSS</del>
- Add Quill, CKeditor or similar
- Add image upload handler
change data storage to use database instead of flat file
- Reformat templates and base code to use pongo2
- Implement inter-Page linking by converting instances of [PageName] to <a href="/view/PageName">PageName</a> - possibly using regexp.ReplaceAllFunc to do this
- Refactor to use PostgreSQL to store page data
