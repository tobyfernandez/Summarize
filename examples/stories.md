---
created: 2024-08-23T18:45:27 (UTC -05:00)
tags: []
source: https://www.quantamagazine.org/computer-scientist-donald-knuth-cant-stop-telling-stories-20200416/
author: By Steven Strogatz
---

# The Computer Scientist Who Can’t Stop Telling Stories | Quanta Magazine

> ## Excerpt
> For pioneering computer scientist Donald Knuth, good coding is synonymous with beautiful expression.

---
_The Art of Computer Programming_ is more than a how-to manual. Just as Isaac Asimov and Eric Temple Bell wove narratives and characters into their science and math stories, Knuth delights in telling stories of computer science.

“The best way to communicate from one human being to another is through story,” he said.

This passion for communication helped him play another starring role in the story of computer science beyond his magnum opus. When his publisher sent him galley proofs for the second edition of volume 2 in the 1970s, Knuth was disturbed by the arrangement and appearance of the numbers, symbols and words on the pages. He flew to Los Angeles to see a machine that printed glossy magazines digitally, hoping it could provide aesthetic relief, but it was too expensive. Nonetheless, on that trip he began developing a computer language that would allow him to typeset mathematics digitally.

Back at Stanford, Knuth put aside _The Art of Computer Programming_ for nearly a decade to develop [TeX](https://www.tug.org/whatis.html) (pronounced “tech”), a sophisticated, game-changing program that put digital typography on a desktop computer. He made it open source, much to the benefit of professional mathematicians, computer scientists, economists, engineers, linguists, statisticians and anyone else who lacked technical symbols on their keyboards but understood the placement of complicated formulas better than their publishers. In a world of often ephemeral computer programs, TeX has endured as the gold standard for making scientific papers more beautiful and easier for experts to read and understand.

Knuth’s interest in storytelling also led him to develop a philosophy of [literate programming](https://www-cs-faculty.stanford.edu/~knuth/lp.html) — a method for writing computer programs as literary essays. A literate program intersperses source code with elegant prose written in a familiar language, such as English. The source code delivers functionality and efficiency, while the exposition addresses a human reader, rather than the computer’s compiler. Anyone who later updates or debugs a literate program will avoid the often time-consuming and costly problem of trying to understand the original programmer’s algorithms, design decisions and implementation strategies. Knuth is a computer scientist who understands that words matter.

_Quanta Magazine_ spoke with Knuth in February at his home on the Stanford campus. The interview has been condensed and edited for clarity.

### Have you always been interested in writing?

Early on, I was advised that the real world would be too hard for me. I didn’t expect to discover anything new, but I loved conveying my enjoyment of ideas in writing.

In sixth grade, a couple friends and I started a two-page paper on a ditto machine. We had jokes. In high school, every Monday night as the newspaper editor, I did an all-nighter to get the paper out. I saw my first line of type in college as the student paper copy editor. In my junior and senior years, we started the engineering and science review. For example, I wrote, “Th<sub>5</sub>E<sub>4</sub> CH<sub>3</sub>EmIC<sub>2</sub>Al<sub>2</sub> Ca<sub>3</sub>P<sub>4</sub>Er.” Every word was a chemical formula.

### And that led to your magnum opus? Do you think of it as another story?

_The Art of Computer Programming_ is a manifesto. It describes the way I love to do math and the way I wish I had been taught. Beginning on Page 1, I tell the story of algorithms. Most textbooks at the time didn’t explore the human side of discoveries. They just said, “This is how chemistry works,” or “This is how physics works.”

I also tell a technical story. I say, “Here’s something that doesn’t work, and here’s a way to solve that problem.” Instead of presenting only facts, I add drama. Science is much easier to learn if you know the sequence of discoveries. Also, I’m unable to resist a good story. I viewed myself not as a pioneer, but as a journalist.

### Beyond the story, then, what’s _The Art of Computer Programming_ about_?_

After two years of writing my book, I realized that its novelty was quantitatively determining how good a program is. I didn’t just want to say one program was better than another. I wanted to say one is 13.8% better than another, and explain how to compare them.

Author A would talk about algorithm A, and author B would talk about his competing algorithm B. And author A never wrote about algorithm B, and author B never wrote about algorithm A. Also, authors A and B used different computers. As a neutral journalist, I explained both from one point of view. Asking, “How good is an algorithm really?” is a fun problem. That’s the analysis of algorithms.

### Is “the analysis of algorithms” just a different way of saying “the art of computer programming”?

I was at a Society for Industrial and Applied Mathematics conference in 1967 when somebody asked what I did. In those days, computer science was partitioned into numerical analysis, artificial intelligence and programming languages. That was it. I realized I needed a name for what I do.

My book’s novelty was its rigorous studies of how good the algorithms were. I decided that the next time I was asked this question, I would say, “Analysis of algorithms.” My definition was: If I’m interested in it, it’s the analysis of algorithms. It wasn’t a very good definition.

Later, I decided to justify it. I decided it was the quantitative study of how good an algorithm is, which I divided into two parts. One part considered all possible algorithms for a certain problem. The other part considered one particular algorithm for a certain problem.

Analysis of algorithms was going to be my life’s work. I told my publisher to change the title of my book to _The Analysis of Algorithms_. My publisher said, “That will never sell.” They made the right decision. Still, I was happy when, 40 years later, five or six books came out with the title _Analysis of Algorithms_.

### But for you, programming is also about more than functionality. When you designed TeX, for example, you wanted to find [“the most pleasing curve”](https://projecteuclid.org/download/pdf_1/euclid.bams/1183544082) that connects certain points. Were you trying to program beauty?

My program had to connect points in some way that reverse-engineered what a good calligrapher would do. The letter “S” comes to a point where the curvature changes from positive to negative. Then maybe it stays steady for a while. The letter’s designers followed some logic to make lines into letter shapes. I wanted to capture not only the design’s outcome, but the intelligence behind it. That’s like writing a computer program.

I talked to designers to understand what they were trying to achieve. The math was there to capture the design in a quantitative way. With mathematics, I put little dials on everything. I could say the letter “A” has got this point, that thickness, angles here, tapering there, a hump in the bottom and a certain serif length.

I never intended to replace designers. I only wanted to capture for future generations exactly what we were doing then. With TeX, a design is reproducible.

### Did you anticipate TeX’s global acceptance or its ability to endure?

TeX was only supposed to be for my secretary and myself. [Phyllis \[Astrid Benson Winkler\]](https://www-cs-faculty.stanford.edu/~knuth/news98.html) was a wonderful secretary. She could read my handwriting and make it beautiful. Printing technology was going down the tubes because the tried-and-true methods were becoming too expensive. Nearly every piece of mathematics published in the 1970s looked atrocious. In the _American Mathematical Monthly_, the subscripts were in a different font from main-line text. I knew computer programming could make books look good again.

I finished debugging a trial version of TeX in April 1978. In May, I had 10 users. In June, I had 100 users. In July, I had 1,000. Each new group would say, “You’ve gotta have this feature.” Five years later, I released what is essentially the TeX we have now. That was designed for Americans. Then the Europeans started to use it. So in the 1980s, I made it work for world languages.

### It sounds like discovery has always been part of your process. Does that remain true today?

I write an average of five new programs every week. Poets have to write poems. I have to write computer programs.

The ultimate test of whether I understand something is if I can explain it to a computer. I can say something to you and you’ll nod your head, but I’m not sure that I explained it well. But the computer doesn’t nod its head. It repeats back exactly what I tell it. In most of life, you can bluff, but not with computers.
