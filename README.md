# Vulcan
## Framework for web application

Uses Go as a base language

### ToDo
- Store templates in tmpl/ and page data in data/
- Add handler to make web root redirect to /view/FrontPage
- Tidy up templates using valid HTML and adding CSS
- Reformat templates and base code to use pongo2
- Implement inter-Page linking by converting instances of [PageName] to <a href="/view/PageName">PageName</a> - possibly using regexp.ReplaceAllFunc to do this
