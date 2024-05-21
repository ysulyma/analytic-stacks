# Analytic Stacks

This is an attempt to crowd-source notes for the Clausen-Scholze course on [Analytic Stacks](https://www.youtube.com/playlist?list=PLx5f8IelFRgGmu6gmL-Kf_Rl_6Mm7juZO).

I downloaded the (auto-generated) YouTube captions, ran them through ChatGPT/Anthropic to clean them up, and they now need to be corrected and edited by humans.

These notes are not endorsed by either Clausen or Scholze; any errors are solely the fault of the transcribers. Sections in red were auto-generated from the captions and have not yet been cleaned up by humans.

## Contributing

- clone the repo, make your changes, then make a Pull Request to this repo

- Look at `15-stacks.tex` for an example of how to format the notes. In particular, add displaymath `\[\]`, `\begin{example}` environments, etc.

- check [this thread](https://github.com/ysulyma/analytic-stacks/issues/2) to make sure no one else is working on the lecture you want to do. Add a comment to say that you're working on that lecture

- for the section you choose, **watch the original video** and edit the text as you follow along. (You can watch at 1.5x or 2x speed.) Note that some parts of the transcript may be missing!

- this is very time-consuming—you don't have to do an entire lecture! A chunk of 20 minutes is helpful. However, start from the earliest unfinished text and move the `\begin{unfinished}{time}` marker down.

- when an erroneous statement is made, and corrected later in the lecture, record the corrected statement (but add a Remark if the subtlety is interesting)

- take a look in `macros.tex` to see what macros are already available

- use `\note{}` to add notes like if you didn't hear something

- use the `\yt{}` macros to create links to moments in the video (**warning:** don't do this for `\subsection{}`, it currently breaks the links in the TOC)

- add citations where possible, use `\citeme` for things to flag to come back to

- once you finish as much as you're going to do, update or remove your comment from [this thread](https://github.com/ysulyma/analytic-stacks/issues/2) so that others can pick up where you left off
