---
title: "Virtualise your dev environment"
---

# <a name="intro"></a>Introduction

wharfrat is intended to make it easy and convenient to use a development
environment in a docker container. The benefits of this are:

 * **Simple:** A new development environment is setup with a single simple
   command, meaning new team members are ready to go immediately.

 * **Shared:** Everyone with access to the project (and docker) has access to
   the development environment.

 * **Controlled:** Everyone gets a development environment created from the same
 image - no more "works for me" issues.

 * **Versioned:** The configuration is version controlled, meaning you get the
 development environment that matches the code branch you are working on.

A short demo of wharfrat:

<script type="text/javascript"
 src="https://asciinema.org/a/t9MJ9wW0QSuCHY1MHNctpLTMg.js"
 id="asciicast-t9MJ9wW0QSuCHY1MHNctpLTMg" async></script>

To learn more about wharfrat, please checkout the documentation:

 * [Current version](https://docs.wharfr.at/en/stable/)
 * [Development version](https://docs.wharfr.at/en/latest/)

## <a name="installation"></a>Installation

To install, please follow the [Installation
Instructions](https://docs.wharfr.at/en/stable/020_installation.html).

 in the
manual or download the latest native binary on the [GitHub Download
Page](https://github.com/wharfr/wharfrat/releases/latest).

## <a name="contribute"></a>Contributing

All contributions are welcome! More information can be found in [the
contribution guidelines]
(https://github.com/wharfr/wharfrat/blob/master/CONTRIBUTING.md).

If you discover a bug or something didn't work the way you expected, please feel
free to [open a GitHub issue](https://github.com/wharfr/wharfrat/issues/new).

If you would like to help improve this site, then it can also be found on [GitHub](https://github.com/wharfr/wharfr.at).

## Blog

For more information regarding wharfrat development, have a look at [our
blog](/blog). The latest posts are:

{% for post in site.posts limit:3 %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}

## <a name="license"></a>License

wharfrat is licensed under the [MIT License]
(https://github.com/wharf/wharfrat/blob/master/LICENSE).
