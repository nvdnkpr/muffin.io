# ![muffin image](https://secure.gravatar.com/avatar/e422d31c03da8d8db685dde4a350eb3d?s=60) muffin.io

Muffin is a full stack development tool for creating modern webapps. It is designed to help the developer become more productive without getting in the way.

All documentation, samples and demos are on the hompage - [http://muffin.io](http://muffin.io).

## Installation

Install Muffin using npm:

```bash
$ [sudo] npm install -g muffin.io
```

Muffin comes with a command line tool aptly named `muffin`.

To use Google App Engine as the backend stack, you need to install the [Google App Engine SDK for Python](https://developers.google.com/appengine/downloads#Google_App_Engine_SDK_for_Python).

To use Node.js/MongoDB as the backend stack, you need to [install MongoDB](http://docs.mongodb.org/manual/installation/). The easiest way to install MongoDB on Mac OS X is using Homebrew:

```bash
$ brew update
$ brew install mongodb
```

## Quick Start

Create a new project:

```bash
$ muffin new <project-name>
```

This sets up a project boilerplate with only the frontend stack. To specify a server stack, you can use the `--server` or `-s` option:

```bash
$ muffin new <project-name> -s [nodejs|gae]
```

Install dependencies:

```bash
$ cd /path/to/your/project
$ muffin install
```

Start the development server while watching for file changes:

```bash
$ muffin watch -s
```

Now point your browser to `http://localhost:4000` and see your app in action.


## License

Released under the MIT license.
