# Don't Panic!

Browser filters and strategies for dealing with
[Dark Patterns](https://darkpatterns.org), which are defined as:

> Dark Patterns are tricks used in websites and apps that make you buy or sign up 
> for things that you didn't mean to. 
>
> **How do Dark Patterns work?**
>
> When you use the web, you don’t read every word on every page - you skim read and make assumptions. If a company wants to trick you into doing something, they can take advantage of this by making a page look like it is saying one thing when it is in fact saying another.

The set of tools and concepts here aim to help you defend yourself against these
types of behaviours.

## Naming

> “What is it?” asked Arthur.
> 
> “The Hitchhiker’s Guide to the Galaxy. It’s a sort of electronic book. It tells you everything you need to know about anything. That’s its job.”
Arthur turned it over nervously in his hands.
>
> “I like the cover,” he said. “_'Don’t Panic'_. It’s the first helpful or intelligible thing anybody’s said to me all day.”

From _The Hitchhiker’s Guide to the Galaxy_ by Douglas Adams. 

The aim of this project is to calm the plethora of dark patterns experienced online,
many of which seek to induce fear, anxiety and panic to influence your behaviour as
you browse.

## Installation

1. Install [uBlock Origin](https://github.com/gorhill/uBlock).  Make sure it's the _real_ uBlock Origin and [not
   from ublock.org](https://github.com/gorhill/uBlock/wiki/uBlock-Origin-is-completely-unrelated-to-the-web-site-ublock.org)
1. Open the uBlock Origin [Dashboard](https://github.com/gorhill/uBlock/wiki/Dashboard)
1. Click [Filter Lists], scroll to the bottom and use `Import` from this URL:

       https://github.com/davidjb/dont-panic/raw/master/ublock-cosmetic.txt
       
1. Click `Apply Changes` and the filter will be auto-downloaded and kept up-to-date
   for you in accordance with your update settings.

## Contributing

Pull requests are welcome to improve filter lists, expand documentation or improve
any other aspect.

## Licence

MIT; see the `LICENSE` file.

## Resources

* uBlock Origin: [Static filter syntax](https://github.com/gorhill/uBlock/wiki/Static-filter-syntax);
  [:style() syntax](https://github.com/gorhill/uBlock/wiki/Static-filter-syntax#style);
  [Procedural cosmetic syntax](https://github.com/gorhill/uBlock/wiki/Procedural-cosmetic-filters)
