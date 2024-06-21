# How does it work?

There's a task to do. The idea is to discuss the design of a system that can
implement that functionality and start implementing it.

One of us should share the screen and start writing the documentation and the
code. The interviewer will have two different roles at the same time:

- Product Owner: will answer questions about the requirements and give feedback
  on the design and implementation.
- Junior developer: pairing with the other developer to implement the system.

The goal is to have an agreement about the initial design and start the
implementation. It doesn't need to be functional.

# Task

We are going to be searching abstracts of articles from the English Wikipedia,
which is currently a gzipped XML file of about 785mb and contains about 6.27
million abstracts.

The file is one large XML file that contains all abstracts. One abstract in
this file is contained by a `doc` element, and looks roughly like this (I've
omitted elements we're not interested in):

```xml
<doc>
    <title>Wikipedia: London Beer Flood</title>
    <url>https://en.wikipedia.org/wiki/London_Beer_Flood</url>
    <abstract>The London Beer Flood was an accident at Meux & Co's Horse Shoe Brewery, London, on 17 October 1814. It took place when one of the  wooden vats of fermenting porter burst.</abstract>
    ...
</doc>
```

We should implement a search system with the following characteristics:

- Ignore the 25 most common words in the English language.
- Relevancy should be based on the number of times the search term appears in
  the abstract.
- Propose a better way for relevancy that term occurrences.

# Design 


# Resources

- [Dataset]
- [Building a full-text search engine in 150 lines of Python code]

[Dataset]: https://dumps.wikimedia.org/enwiki/latest/
[Building a full-text search engine in 150 lines of Python code]: https://bart.degoe.de/building-a-full-text-search-engine-150-lines-of-code/
