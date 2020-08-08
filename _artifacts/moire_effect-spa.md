---
layout: post
title: Moiré Effect
categories: video analog
tags: [Interference, Video, Analog]
lang: Español
---

Moiré affects composite color video signals only - not RGB, S-Video or color difference signals. Moire may occur during the original tape playback process, or it may be recorded into the video signal.

In mathematics, physics, and art, a moiré pattern (/mwɑrˈeɪ/; French: [mwaˈʁe]) is a secondary and visually evident superimposed pattern created, for example, when two identical (usually transparent) patterns on a flat or curved surface (such as closely spaced straight lines drawn radiating from a point or taking the form of a grid) are overlaid while displaced or rotated a small amount from one another.<sup><a href="#fn1" id="ref1">1</a></sup>

<blockquote>The term 'moiré' is used as a collective description for detailed, periodic structures that appear as regular patterns or move about in an irregular, agitated way. They may either appear superimposed on the entire picture area, irrespective of the image content, or only superimposed on parts of the image, depending on the content. In the second case, it is possible to distinguish between two different types: (1) finely structured areas of image content are overlaid by shimmering chromatic effects, often easiest to see on delicately patterned clothing; (2) highly saturated color areas and colored vertical edges with strongly contrasting hues are overlaid by finely-striped patterns in the luminance.<sup><a href="#fn2" id="ref2">2</a></sup></blockquote>  

Moire is caused by the misinterpretation of signal components during demodulation. If the luminance signal is interpreted as chrominance, the effect is called “cross-color”. For its cousin, “cross-luma”, see the [dot crawl]({{ site.baseurl }}/artifacts/dot_crawl.html) artifact. When composite encoded video is read and processed from video tape, during demodulation, the luminance carrier is combined with a color subcarrier to create a complete image. The full baseband video spectrum is 5 MHz, and the color subcarrier runs at 3.58 MHz. Due to the shared transmission frequencies over one location (usually one coaxial video cable), data can be misinterpreted during multiplexing, resulting in a “rainbow” effect in image areas with a lot of detail.

When other methods of signal transmission are used, such as component or S-Video, these effects are eliminated because the luminance and chrominance components are transmitted separately.

## Can it be fixed?

Always use S-Video or component video signal formats to transfer original content. If it is necessary to use a composite video signal, use equipment that can accurately process the source video with 3-D comb filtering.

## Example(s)

<img src="{{ site.baseurl }}/images/Moire_640x480.jpg">
<sub>Shown here is a fine crosshatch pattern with plenty of moiré, generated by a test signal generator and output as a composite signal to a Sony PVM-14M4U.</sub>

## References

<sup id="fn1">1. Wikipedia, [Moiré pattern](http://en.wikipedia.org/wiki/Moir%C3%A9_pattern). <a href="#ref1" title="Jump back to footnote 1 in the text.">↩</a></sup>   
<sup id="fn2">2. Johannes Gfeller, Agathe Jarczyk, and Joanna Phillips, “Moire effect” in _Compendium of Image Errors in Analogue Video_ (edited by Swiss Institute for Art Research, Zürich: Scheidegger & Spiess, 2012), p.98, videos 50 and 51. <a href="#ref2" title="Jump back to footnote 2 in the text.">↩</a></sup>