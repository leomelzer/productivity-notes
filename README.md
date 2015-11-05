# Productivity: Notes
Template for my personal GTD needs

## What

You tried apps to keep track of your todos but somehow it didn't work?

You still have a pen, a printer and like the feel of paper?

Then maybe this notes template is for you! Simply print it out, fold the page in half, fill out the box on top and start adding items! Enjoy the satisfying feeling of checking items and doodling around.

## Why

I followed a couple different methods, tools and styles to keep track of my todo items. Without really realizing drawing a simple list of items on a folded A4 page did the trick for me. I just carry it with me if I feel the need, otherwise it's just waiting on my desk.

Usually I just made the list myself and drew the checkboxes and lines myself but after a while this approach felt too cumbersome. That's why I tried to make it digital, at least a part of it.

The box on top of the template can be used in multiple ways, e.g. you can use a page per project or just fill in the current date to keep track of when you started with your list. Or make it a Kanban-style list with "Backlog/Doing/Done". Or add your name!

I decided to use A5 as a format after several trials with different sizes. In the end this just felt like the best compromise of whitespace and content. This is why `notes.pdf` is formatted as a document in format A5 with 2 (identical) pages. Simply print it as A4 with two pages per sheet. You can use the `./print` command which will try to take care of that for you.

Want to archive your notes to later review what happened when? Simply stack the paper and put it in a safe place. It's that simple!

## How

If you'd like to adapt the template to your needs, simply fork the repository and edit the `notes.html` in your favorite `$EDITOR`. If you have [`wkhtmltopdf`](http://wkhtmltopdf.org/) installed, you can simply run `./update` to produce a new version of the PDF file.

If you run out of templates you can also just call `./print MyPrinterName` and the PDF will be added to the respective printing queue using the CUPS `lp` command.
