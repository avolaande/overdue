# overdue

Written by Avo Laande

Plugin for [todo.sh](http://todotxt.org/) that moves the `due:` date of every open task that is past due to today, so all overdue To-Do's show up in one list for Today.

Tasks without a `due:` date, completed (`x`) tasks and recurring (`rec:`) tasks are left untouched. Recurring tasks keep their original `due:` date, because the recurrence logic uses it to calculate the next due date. The exception is daily recurring tasks (`rec:1d`, `rec:d`, `rec:+1d`, `rec:+d`), which are moved to today like any other overdue task.

## Usage

`todo.sh overdue`

## Installation

Copy `overdue` into your `.todo.actions.d` folder. Refer to [Creating and Installing Add-ons](https://github.com/todotxt/todo.txt-cli/wiki/Creating-and-Installing-Add-ons) for more details.

## License

This code is licensed under the GPL v3.0 license. See LICENSE for further details.
