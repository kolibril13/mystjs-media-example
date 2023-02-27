---
title: Media Example
subject: Testing
subtitle: Lorem ipsum dolor sit.
authors:
  - name: John Doe
exports:
  - format: pdf
    template: arxiv_two_column
---

Content:

* Image in [](#fig-img).  
* Video in [](#fig-vid-embedded).  
* Not embedded Video in [](#fig-vid-not-embedded).  
* Interactive Slider in [](#fig-widget).  
* GIF in [](#fig-gif).  


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

:::{figure} #my-img
:name: fig-img
Image from matplotlib
:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

In the .ipynb file, the video looks like this:

```
"data": {
"text/html": [
  "<video controls autoplay loop style=\"max-width: 60%;\"  >\n",
  " <source src=\"data:video/mp4;base64,AAAAIGZ0eXBpc29tAAACAGlzb21pc28yYXZjMW1wNDEAAAAIZnJlZQAAMyttZGF0AAACrgYF//+q3EXpvebZSLeWLNgg2SPu73gyNjQgLSBjb3JlIDE2NCByMzA5NSBiYWVlNDAwIC0gSC4yNjQvTVBFRy00IEFWQyBjb2RlYyAtIENvcHlsZWZ0IDIwMDMtMjAyMiAtI...
```

:::{figure} #my-vid-embedded
:name: fig-vid-embedded
Embedded video
:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.


In the .ipynb file, the video looks like this:

```

"data": {
"text/html": [
  "<video src=\"media/jupyter/Example@2023-02-24@19-05-39.mp4\" controls autoplay loop style=\"max-width: 60%;\"  >\n",
  "      Your browser does not support the <code>video</code> element.\n",
  "    </video>"
],
"text/plain": [
  "<IPython.core.display.Video object>"
]
},
"metadata": {},
"output_type": "display_data"
}
```

:::{figure} #my-vid-not-embedded
:name: fig-vid-not-embedded
Not embedded video
:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.


:::{figure} #my-widget
:name: fig-widget
Interactive ImageSlider
:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

:::{figure} #my-gif
:name: fig-gif
:width: 300px
Animated GIF
:::


Hello World!

:::{figure} #my-svg
:name: fig-svg
:width: 100px
My svg
:::


:::{figure} #my-dataframe
:name: fig-df
:width: 100px
My dataframe
:::




 <!-- For pdf export, run `myst build 01-hello.md` -->