# Analytic Stacks

This is an attempt to crowd-source notes for the Clausen-Scholze course on [Analytic Stacks](https://www.youtube.com/playlist?list=PLx5f8IelFRgGmu6gmL-Kf_Rl_6Mm7juZO).

I downloaded the (auto-generated) YouTube captions, ran them through ChatGPT/Anthropic to clean them up, and they now need to be reviewed and edited by humans.

## Contributing

- clone the repo, make your changes, then make a Pull Request to this repo

- Look at `15-stacks.tex` for an example of how to format the notes

- for the section you choose, **watch the original video** and edit the text as you follow along. Note that some parts of the transcript may be missing!

- this is very time-consuming—you don't have to do an entire lecture! A chunk of 20 minutes is helpful. However, start from the earliest unfinished text and move the `\begin{unfinished}{time}` marker down.

- when an erroneous statement is made, and corrected later in the lecture, record the corrected statement (but add a Remark if the subtlety is interesting)

- take a look in `macros.tex` to see what macros are already available

- use `\note{}` to add notes like if you didn't hear something

- use the `\yt{}` macros to create links to moments in the video (**warning:** don't do this for `\subsection{}`, it currently breaks the links in the TOC)

- add citations where possible, use `\citeme` for things to flag to come back to
