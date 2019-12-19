### [Light Table](http://lighttable.com/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/light-table.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/light-table/archive/master.zip) option and unzip them.

#### Activating theme

Go to `Settings -> User behaviors` and add the following lines:

    [:app :lt.objs.style/provide-theme "dracula" "/path/to/theme/dracula.css"]
    [:editor :lt.objs.style/set-theme "dracula"]

You can put the CSS anywhere and just make the path in the first line use it.
