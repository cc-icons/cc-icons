Creative Commons Web Fonts
======

Creative Commons Web Fonts is a suite of pictographic Creative Commons icons for easy scalable vector graphics,
created and maintained by [Richard Ba](http://twitter.com/richardba).

##License
- Creative Commons Web Fonts documentation is licensed under the CC BY 3.0 License:
  - http://creativecommons.org/licenses/by/3.0/
  
##Versioning

Font Awesome will be maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered
with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions, including new icons, without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit http://semver.org.

##Author
- Email: richardtrle at gmail dot com
- Twitter: http://twitter.com/richardba
- GitHub: https://github.com/richardba

##Component
To include as a [component](http://github.com/component/component), just run

    $ component install richardba/cc-icons

Or add

    "richardba/cc-icons": "*"

to the `dependencies` in your `component.json`.

## Hacking on Font Awesome

From the root of the repository, install the tools used to develop.

    $ bundle install
    $ npm install

Build the project and documentation:

    $ bundle exec jekyll build

Or serve it on a local server on http://localhost:7998/cc-icons/:

    $ bundle exec jekyll serve