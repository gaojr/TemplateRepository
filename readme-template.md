# Welcome to <%= projectName %> 👋

<% if (projectVersion) { -%>
![Version](https://img.shields.io/badge/version-<%= projectVersion %>-orange.svg?cacheSeconds=3600)
<% } -%>
<% if (licenseName && licenseUrl) { -%>
[![License: <%= licenseName %>](https://img.shields.io/badge/license-<%= licenseName %>-green.svg?cacheSeconds=3600)](<%= licenseUrl %>)
<% } -%>

<% if (projectDescription) { -%>
> <%= projectDescription %>
<% } -%>

<% if (projectPrerequisites && projectPrerequisites.length) { -%>
## Prerequisites

<% projectPrerequisites.map(({ name, value }) => { -%>
- <%= name %> <%= value %>
<% }) -%>
<% } -%>

<% if (contributingUrl) { -%>
## Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](<%= contributingUrl %>).
<% } -%>

## Show your support

Give a ⭐️ if this project helped you!

***

*This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)*