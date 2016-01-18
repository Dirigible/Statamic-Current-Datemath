# Current Datemath
Run addition and subtraction operations on today's date. A plugin for [Statamic](http://statamic.com) (v1).

---------------------

The `{{ current_datemath }}` tag accepts integers in `add` and `subtract` parameters. As you might expect, `add` increases the date by the provided number of days while `subtract` decreases the date.

The tag also accepts the standard `format` parameter found in the `{{ current_date }}` tag.

#### Usage

If today is *2015-08-10*, `{{ current_datemath add="10" }}` will return *2015-08-20*.

If today is *2015-08-10*, `{{ current_datemath minus="10" format="F jS"}}` will return *July 31st*.
