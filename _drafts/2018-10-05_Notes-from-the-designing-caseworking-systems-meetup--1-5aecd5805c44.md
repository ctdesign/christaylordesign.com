<div>

# Notes from the designing caseworking systems meetup #1 

</div>

::: 
A write-up of the talks and workshop from a 'designing caseworking
systems meetup' that I organised in October 2017
:::

::::::::::: 
:::::: 
::: section-divider

------------------------------------------------------------------------
:::

:::: section-content
::: 
### Designing caseworking systems meetup #1 

*Update Mar 2019: I'm organising another meet-up soon, sign up to the
mailing list here to be notified of when tickets are available:*
[http://eepurl.com/gkO2JL](http://eepurl.com/gkO2JL){.markup--anchor
.markup--p-anchor data-href="http://eepurl.com/gkO2JL"
rel="nofollow noopener noopener noopener" target="_blank"}
:::
::::
::::::

:::::: 
::: section-divider

------------------------------------------------------------------------
:::

:::: section-content
::: 
*Over the last year I organised two meet-ups for people designing
caseworking systems in government. Previously I'd hosted write-ups of
the events on a dedicated site
(*[*https://cross-gov-caseworking.herokuapp.com*](https://cross-gov-caseworking.herokuapp.com){.markup--anchor
.markup--p-anchor
data-href="https://cross-gov-caseworking.herokuapp.com"
rel="nofollow noopener noopener noopener" target="_blank"}*) but as that
site is password protected (because reasons) I thought it would be
better to move over the write-ups of the events to Medium for better
visibility.*

<figure id="6656" class="graf graf--figure graf-after--p">
<img src="https://cdn-images-1.medium.com/max/800/0*v8tFTPy53DgUUq91"
class="graf-image" data-image-id="0*v8tFTPy53DgUUq91" data-width="1024"
data-height="768" data-is-featured="true" />
</figure>

Most government departments use various forms of caseworking system for
staff to process applications for licences, grant permission to do
things and to record decisions.

[Back on 10th October
2017](https://twitter.com/i/moments/919881570508558339?ref_src=twsrc%5Etfw%7Ctwcamp%5Emoment&ref_url=https%3A%2F%2Fcross-gov-caseworking.herokuapp.com%2Fblog%2Fdesigning-caseworking-systems%2F){.markup--anchor
.markup--p-anchor
data-href="https://twitter.com/i/moments/919881570508558339?ref_src=twsrc%5Etfw%7Ctwcamp%5Emoment&ref_url=https%3A%2F%2Fcross-gov-caseworking.herokuapp.com%2Fblog%2Fdesigning-caseworking-systems%2F"
rel="noopener" target="_blank"}, I ran a meet-up for people working on
caseworking systems at Aviation House in London, so they could share
what they're doing and look for common patterns that we might be able to
re-use across government.

Below is a write-up of the day.

*HUGE thanks to both* [*Alice
Noakes*](https://twitter.com/@AliceNoakes){.markup--anchor
.markup--p-anchor data-href="https://twitter.com/@AliceNoakes"
rel="noopener" target="_blank"} *and* [*Joe
Lanman*](https://twitter.com/@joelanman){.markup--anchor
.markup--p-anchor data-href="https://twitter.com/@joelanman"
rel="noopener" target="_blank"} *for doing all of the actual hard work
of taking notes.*

### Agenda 

-   [10:30--11:00: Arrival]
-   [11:00--12:30: Show and tells of case-working systems and a talk on
    service patterns and language in case-working]
-   [12:30--13:30: Lunch]
-   [13:30--16:00: Workshop on identifying common patterns and
    components]

### The morning speakers 

#### Presentation on casework for registration of land boundaries 

*HM Land Registry, presented by Sam Brierley (Head of UR and Design)*

<figure id="da7a" class="graf graf--figure graf--iframe graf-after--p">
<div class="iframe">
<div id="player" class="slides" data-referer="" data-host="">
<div class="sd-player state-initial js-sd-player" data-start-slide="0"
data-url="https://speakerdeck.com/ctdesign/1-dot-sam-researching-casework"
data-ratio="1.7777777777777777">
<div class="sd-player-title">
<div class="sd-player-avatar">
<a href="https://speakerdeck.com/ctdesign" target="_parent"
aria-label="SpeakerDeck profile page for "><img
src="https://secure.gravatar.com/avatar/20473746d7da441591510b4c0e4eb0b3?s=47"
class="avatar" loading="eager" width="47" height="47" /></a>
</div>
<div class="sd-player-title-name">
<a
href="https://speakerdeck.com/ctdesign/1-dot-sam-researching-casework"
class="sd-player-title-link"
target="_parent">1.sam-researching-casework.pdf</a>
</div>
<div class="sd-player-title-author">
by <a href="https://speakerdeck.com/ctdesign"
class="sd-player-title-link" target="_parent"></a>
</div>
<div class="sd-player-title-mark">
<a href="https://speakerdeck.com/" target="_parent"
aria-label="SpeakerDeck Homepage"><img
src="https://d1eu30co0ohy4w.cloudfront.net/assets/mark-white-8d908558fe78e8efc8118c6fe9b9b1a9846b182c503bdc6902f97df4ddc9f3af.svg"
alt="Speaker Deck" /></a>
</div>
</div>
<div class="sd-player-controls">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWNoZXZyb24tbGVmdCBpY29uLXBsYXllciI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWNoZXZyb24tbGVmdCIgLz48L3N2Zz4="
class="icon icon-chevron-left icon-player" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWNoZXZyb24tcmlnaHQgaWNvbi1wbGF5ZXIiPjx1c2UgeGxpbms6aHJlZj0iL2ljb25zL2ljb25zLnN2Zz92PTIwMjUtMDEtMjYjaWNvbi1jaGV2cm9uLXJpZ2h0IiAvPjwvc3ZnPg=="
class="icon icon-chevron-right icon-player" />
<div class="sd-player-spacer">

</div>
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXNoYXJlIGljb24tcGxheWVyIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tc2hhcmUiIC8+PC9zdmc+"
class="icon icon-share icon-player" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZ1bGxzY3JlZW4gaWNvbi1wbGF5ZXIgc2QtcGxheWVyLWVuYWJsZS1mdWxsc2NyZWVuIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tZnVsbHNjcmVlbiIgLz48L3N2Zz4="
class="icon icon-fullscreen icon-player sd-player-enable-fullscreen" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZ1bGxzY3JlZW4gaWNvbi1wbGF5ZXIgc2QtcGxheWVyLWRpc2FibGUtZnVsbHNjcmVlbiI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZ1bGxzY3JlZW4iIC8+PC9zdmc+"
class="icon icon-fullscreen icon-player sd-player-disable-fullscreen" />
</div>
<div class="current-slide-note" hidden="">

</div>
<div class="sd-player-gradient">

</div>
<div class="sd-player-scrubber js-sd-player-scrubber">
<div class="sd-player-scrubber-bar">
<div class="sd-player-scrubber-progress js-sd-player-scrubber-progress">

</div>
</div>
</div>
<div class="sd-player-preview js-sd-player-preview">

</div>
<div class="sd-player-share-menu" hidden="">
<div class="sd-player-share-menu-overlay js-sd-player-share-close">

</div>
<div class="sd-player-share-menu-container">
<div class="sd-player-share-menu-group sd-player-share-menu-group-head">
Link
Embed
Share
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXggIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24teCIgLz48L3N2Zz4="
class="icon icon-x" />
</div>
<div class="sd-player-share-menu-group">
Beginning
This slide
</div>
<div class="sd-player-share-menu-buttons">
<div class="sd-player-share-menu-action active" data-selected-by="link"
data-group="type">
Copy link URL
Copy link URL
</div>
<div
class="sd-player-share-menu-action sd-player-share-menu-action-stacked"
data-selected-by="embed" data-group="type">
Copy iframe embed code
Copy iframe embed code
Copy javascript embed code
Copy javascript embed code
</div>
<div class="sd-player-share-menu-action" data-selected-by="share"
data-group="type">
<div class="sd-player-share-menu-action active js-sd-player-share-start"
data-selected-by="beginning" data-group="start">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZhY2Vib29rICI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZhY2Vib29rIiAvPjwvc3ZnPg=="
class="icon icon-facebook" /> Share
<a
href="https://twitter.com/intent/tweet?text=1.sam-researching-casework.pdf&amp;url=https://speakerdeck.com/ctdesign/1-dot-sam-researching-casework"
class="sd-player-btn twitter-share-button js-twitter-button-start"
target="_blank"><img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXR3aXR0ZXIgIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tdHdpdHRlciIgLz48L3N2Zz4="
class="icon icon-twitter" /> Tweet</a>
</div>
<div class="sd-player-share-menu-action js-sd-player-share-slide"
data-selected-by="slide" data-group="start">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZhY2Vib29rICI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZhY2Vib29rIiAvPjwvc3ZnPg=="
class="icon icon-facebook" /> Share
<a
href="https://twitter.com/intent/tweet?text=1.sam-researching-casework.pdf&amp;url=https://speakerdeck.com/ctdesign/1-dot-sam-researching-casework?slide=1"
class="sd-player-btn twitter-share-button js-twitter-button-slide"
target="_blank"><img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXR3aXR0ZXIgIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tdHdpdHRlciIgLz48L3N2Zz4="
class="icon icon-twitter" /> Tweet</a>
</div>
</div>
</div>
</div>
</div>
<div class="sd-player-presenter">
<div class="sd-player-presenter-container js-sd-player-presenter">
<div
class="sd-player-slide sd-player-presenter-previous js-sd-player-previous-slide">

</div>
<div
class="sd-player-slide sd-player-presenter-current js-sd-player-current-slide">

</div>
<div
class="sd-player-slide sd-player-presenter-next js-sd-player-next-slide">

</div>
</div>
</div>
<div class="sd-player-slides js-sd-player-slides">
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_0.jpg?10906623"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_0.jpg?10906623"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-1" class="sd-player-slides--heading">Slide 1</h2>
<h3 id="slide-1-text">Slide 1 text</h3>
<div class="sd-player-slides--text">
Researching ‘casework’ Property boundaries - myth and legend
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_1.jpg?10906624"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_1.jpg?10906624"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-2" class="sd-player-slides--heading">Slide 2</h2>
<h3 id="slide-2-text">Slide 2 text</h3>
<div class="sd-player-slides--text">
Boundary queries - lots of them and they’re emotive Title boundary Legal
boundary (invisible and imprecise) Physical boundary (a wall)
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_2.jpg?10906625"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_2.jpg?10906625"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-3" class="sd-player-slides--heading">Slide 3</h2>
<h3 id="slide-3-text">Slide 3 text</h3>
<div class="sd-player-slides--text">
Research aims ● what’s the [customer] trying to do - what are their
needs? ● what are call handlers and caseworkers doing and why? ● what’s
it like for caseworkers when they use the existing systems? ● what
actually needs to happen* behind the scenes? * not just what’s currently
happening
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_3.jpg?10906626"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_3.jpg?10906626"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-4" class="sd-player-slides--heading">Slide 4</h2>
<h3 id="slide-4-text">Slide 4 text</h3>
<div class="sd-player-slides--text">
Approach 1. Desk research (volumetrics, staff surveys, speed of service
etc) 2. Contextual research (observing calls, triage, workflow) 3.
Themed workshops (3 half-day workshops in 2 locations) 4. Playback of
quick wins and long-term solutions
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_4.jpg?10906627"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_4.jpg?10906627"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-5" class="sd-player-slides--heading">Slide 5</h2>
<h3 id="slide-5-text">Slide 5 text</h3>
<div class="sd-player-slides--text">
Contextual research: 2 key types of boundary query Citizens phone us to
ask us who owns a fence, wall or hedge (usually because it needs
repairing) Solicitors send us letters about boundary location disputes
(they want us to investigate and provide a definitive answer, or at
least arbitrate)
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_5.jpg?10906628"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_5.jpg?10906628"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-6" class="sd-player-slides--heading">Slide 6</h2>
<h3 id="slide-6-text">Slide 6 text</h3>
<div class="sd-player-slides--text">
We found out that users had heard a lot of myths
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_6.jpg?10906629"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_6.jpg?10906629"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-7" class="sd-player-slides--heading">Slide 7</h2>
<h3 id="slide-7-text">Slide 7 text</h3>
<div class="sd-player-slides--text">
It’s a myth that... ● Both of you ‘own’ a boundary feature ● If you come
out of any door in your property and turn left, you own that boundary ●
If the fence posts are on your side, you own the fence ● The title plan
will have T marks on it that show ownership ● The ‘Party Wall Act’
explains ownership of a boundary feature ● HMLR can fix title plan
issues ● HMLR knows the answer ● HMLR can arbitrate
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_7.jpg?10906630"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_7.jpg?10906630"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-8" class="sd-player-slides--heading">Slide 8</h2>
<h3 id="slide-8-text">Slide 8 text</h3>
<div class="sd-player-slides--text">
We found 1 issue straight away HM Land Registry can’t tell you who owns
a physical boundary ‘feature’ - ie a wall, hedge or fence. ● sometimes
your deeds or title will say who owns it - but we can’t tell you that ●
you can make an agreement with your neighbour and have this registered ●
but this isn’t easy to do...and it’s only valid while you both own your
properties This is the main reason citizens call us about boundaries -
yet it’s a myth that we have the answer or can help
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_8.jpg?10906631"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_8.jpg?10906631"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-9" class="sd-player-slides--heading">Slide 9</h2>
<h3 id="slide-9-text">Slide 9 text</h3>
<div class="sd-player-slides--text">
Who owns (and must fix) the fence that blew over?
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_9.jpg?10906632"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_9.jpg?10906632"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-10" class="sd-player-slides--heading">Slide 10</h2>
<h3 id="slide-10-text">Slide 10 text</h3>
<div class="sd-player-slides--text">
Pain points “Poor quality or incomplete applications” “Ineligible
applications” “Systems that make it really hard to do your job”
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_10.jpg?10906633"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_10.jpg?10906633"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-11" class="sd-player-slides--heading">Slide 11</h2>
<h3 id="slide-11-text">Slide 11 text</h3>
<div class="sd-player-slides--text">
“Bad internal user experience creates a burden that means the people in
your organisation won’t always have the motivation, time, or willpower
to do what it takes to deliver a level of service that is going to work
best for your customers.” Ben Holliday
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_11.jpg?10906634"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_11.jpg?10906634"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-12" class="sd-player-slides--heading">Slide 12</h2>
<h3 id="slide-12-text">Slide 12 text</h3>
<div class="sd-player-slides--text">
We asked what happens when users struggle ● “they get things wrong” ●
“they call for advice which we can’t provide” ● “they think we can
arbitrate when we can’t” We have to fix all this, which takes time,
money and patience - and causes delay. Every service failure = a pain
point for us.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_12.jpg?10906635"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_12.jpg?10906635"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-13" class="sd-player-slides--heading">Slide 13</h2>
<h3 id="slide-13-text">Slide 13 text</h3>
<div class="sd-player-slides--text">
We heard some legendary ‘received wisdom’ “I need to check everything I
can, including the applicant’s ID so I know their interest” (nope) “We
need to help them sort this out” (also nope) “We’re the authoritative
source of information on boundaries” (we’re not) “All applicants should
know the process” (haha)
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_13.jpg?10906636"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_13.jpg?10906636"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-14" class="sd-player-slides--heading">Slide 14</h2>
<h3 id="slide-14-text">Slide 14 text</h3>
<div class="sd-player-slides--text">
Quick wins Reducing demand for services by encouraging self-service
Reducing avoidable contacts by tackling myths
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_14.jpg?10906637"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_14.jpg?10906637"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-15" class="sd-player-slides--heading">Slide 15</h2>
<h3 id="slide-15-text">Slide 15 text</h3>
<div class="sd-player-slides--text">
So far ● Boundary guidance for citizens on GOV.UK rewritten and
simplified ● Mythbusting boundaries blog published ● Key referrers
identified, contacted and asked to link to the new guidance (rather than
giving out our phone number) ● Updated HMLR guidance on boundary
disputes ● Call centre staff guidance updated
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_15.jpg?10906638"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_15.jpg?10906638"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-16" class="sd-player-slides--heading">Slide 16</h2>
<h3 id="slide-16-text">Slide 16 text</h3>
<div class="sd-player-slides--text">
Service map: reporting boundary location errors
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_16.jpg?10906639"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_16.jpg?10906639"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-17" class="sd-player-slides--heading">Slide 17</h2>
<h3 id="slide-17-text">Slide 17 text</h3>
<div class="sd-player-slides--text">
Started a conversation about reported boundary location errors... 0.04%
are registration errors on our part 90% of queries
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_17.jpg?10906640"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_17.jpg?10906640"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-18" class="sd-player-slides--heading">Slide 18</h2>
<h3 id="slide-18-text">Slide 18 text</h3>
<div class="sd-player-slides--text">
Is this fence in the wrong place?
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_18.jpg?10906641"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_18.jpg?10906641"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-19" class="sd-player-slides--heading">Slide 19</h2>
<h3 id="slide-19-text">Slide 19 text</h3>
<div class="sd-player-slides--text">
Helped frame the problems we’re trying to solve “We need a better way
for people to ask us to correct a boundary location error which they
think is our fault.” For this to happen: 1. They’ll have to provide
evidence - title deed and title plan 2. We’ll check this against our
records 3. We’ll make a decision 4. We’ll tell the applicant about the
outcome - and what to do next
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/slide_19.jpg?10906642"
data-preview-url="https://files.speakerdeck.com/presentations/1910ac12ec6a4e6eb07b38ad85c09631/preview_slide_19.jpg?10906642"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-20" class="sd-player-slides--heading">Slide 20</h2>
<h3 id="slide-20-text">Slide 20 text</h3>
<div class="sd-player-slides--text">
Emerging patterns for our registration casework 1. user identifies the
property 2. user explains why the change is needed (eligibility) 3. HMLR
checks against its records 4. HMLR makes a decision (to change or not to
change) 5. HMLR notifies the user of the outcome (and what to do next)
Identifying common service stages means we can assemble services from
common components, eg ‘Find property’, ‘Submit’, ‘Route’ etc
</div>
</div>
</div>
</div>
</div>
<div id="fb-root">

</div>
</div>
</div>
<figcaption><a
href="https://drive.google.com/file/d/0B7y7fXAz33PoZWgyb0JPVEFoMjA/view"
class="markup--anchor markup--figure-anchor"
data-href="https://drive.google.com/file/d/0B7y7fXAz33PoZWgyb0JPVEFoMjA/view"
rel="nofollow noopener"
target="_blank">https://drive.google.com/file/d/0B7y7fXAz33PoZWgyb0JPVEFoMjA/view</a></figcaption>
</figure>

Boundaries are a big issue for Land Registry --- seen in volume of calls
that's high with queries.

Boundaries are emotive for people, and they are imprecise --- lots of
different interpretation eg physical boundary might not be in the place
of the legal boundary.

Caseworkers use the term customer, not user.

Used a strategy to get caseworker buy-in by providing some quick wins to
make short term improvements, a trade off for needing commitment in the
long term.

Myths: Users expect Land Registry to be able to do things they can't.
Main reason of call is 'who owns this wall' but Land Registry can't
help.

An issue for call handlers and caseworkers was that they could help, but
advisory policy says that's not possible.

Pain points:

-   [Poor quality applications]
-   [Applications that should never have been made]
-   [Caseworking is hard!]
-   [Case workers also have misunderstandings about the process]

We looked for quick wins, encouraged self-service.

Content and guidance was improved, for users and case-workers.

A service map was not so useful in itself, but helped start
conversations.

90% of calls are from users who think HMLR have made a mistake in
location of boundary. 0.04% are actual errors made by HMLR.

We identified common service stages, means they can assemble from common
components.

**Questions for the speaker:**

Q: Where did these myths come from?\
A: The middle men (conveyancers) mean Land Registry is a black box to
users. Also the paper work flow is complex.

Q: Do you see this as case-working design or service design?\
A: Previously case-working, more recently service design. Steve Railton
from Transformation Directorate at GDS is supporting this move.

Q: I recognise all this from our experiences at DWP. I see caseworkers
as 'detectives' --- they really want to know everything about the
applicant, even if they don't need all the pieces of info to make
decisions.\
A (Ben): Caseworking can move from a deductive process to a
considerative process when caseworkers know what the limits of your
decision making are --- creating model offices --- and able to do this
by starting with apprentices, who don't have 30 years of caseworking
experience.\
A (Chris): People worry we're going to get rid of their jobs, (with new
caseworking systems)\
Ben: Telling people we'll take away all the 'cookie cutter easy work' so
you can just focus on the tricky, legally sensitive stuff is not a good
message

#### Presentation on Licensing for International Trade and Enterprise (LITE) 

*DIT, presented by Jonathan Hirsch(UX architect)*

<figure id="1e07" class="graf graf--figure graf--iframe graf-after--p">
<div class="iframe">
<div id="player" class="slides" data-referer="" data-host="">
<div class="sd-player state-initial js-sd-player" data-start-slide="0"
data-url="https://speakerdeck.com/ctdesign/caseworking1-dot-2-jon-lite-show-and-tell"
data-ratio="1.3333333333333333">
<div class="sd-player-title">
<div class="sd-player-avatar">
<a href="https://speakerdeck.com/ctdesign" target="_parent"
aria-label="SpeakerDeck profile page for "><img
src="https://secure.gravatar.com/avatar/20473746d7da441591510b4c0e4eb0b3?s=47"
class="avatar" loading="eager" width="47" height="47" /></a>
</div>
<div class="sd-player-title-name">
<a
href="https://speakerdeck.com/ctdesign/caseworking1-dot-2-jon-lite-show-and-tell"
class="sd-player-title-link"
target="_parent">caseworking1.2.jon-lite-show-and-tell.pdf</a>
</div>
<div class="sd-player-title-author">
by <a href="https://speakerdeck.com/ctdesign"
class="sd-player-title-link" target="_parent"></a>
</div>
<div class="sd-player-title-mark">
<a href="https://speakerdeck.com/" target="_parent"
aria-label="SpeakerDeck Homepage"><img
src="https://d1eu30co0ohy4w.cloudfront.net/assets/mark-white-8d908558fe78e8efc8118c6fe9b9b1a9846b182c503bdc6902f97df4ddc9f3af.svg"
alt="Speaker Deck" /></a>
</div>
</div>
<div class="sd-player-controls">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWNoZXZyb24tbGVmdCBpY29uLXBsYXllciI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWNoZXZyb24tbGVmdCIgLz48L3N2Zz4="
class="icon icon-chevron-left icon-player" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWNoZXZyb24tcmlnaHQgaWNvbi1wbGF5ZXIiPjx1c2UgeGxpbms6aHJlZj0iL2ljb25zL2ljb25zLnN2Zz92PTIwMjUtMDEtMjYjaWNvbi1jaGV2cm9uLXJpZ2h0IiAvPjwvc3ZnPg=="
class="icon icon-chevron-right icon-player" />
<div class="sd-player-spacer">

</div>
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXNoYXJlIGljb24tcGxheWVyIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tc2hhcmUiIC8+PC9zdmc+"
class="icon icon-share icon-player" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZ1bGxzY3JlZW4gaWNvbi1wbGF5ZXIgc2QtcGxheWVyLWVuYWJsZS1mdWxsc2NyZWVuIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tZnVsbHNjcmVlbiIgLz48L3N2Zz4="
class="icon icon-fullscreen icon-player sd-player-enable-fullscreen" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZ1bGxzY3JlZW4gaWNvbi1wbGF5ZXIgc2QtcGxheWVyLWRpc2FibGUtZnVsbHNjcmVlbiI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZ1bGxzY3JlZW4iIC8+PC9zdmc+"
class="icon icon-fullscreen icon-player sd-player-disable-fullscreen" />
</div>
<div class="current-slide-note" hidden="">

</div>
<div class="sd-player-gradient">

</div>
<div class="sd-player-scrubber js-sd-player-scrubber">
<div class="sd-player-scrubber-bar">
<div class="sd-player-scrubber-progress js-sd-player-scrubber-progress">

</div>
</div>
</div>
<div class="sd-player-preview js-sd-player-preview">

</div>
<div class="sd-player-share-menu" hidden="">
<div class="sd-player-share-menu-overlay js-sd-player-share-close">

</div>
<div class="sd-player-share-menu-container">
<div class="sd-player-share-menu-group sd-player-share-menu-group-head">
Link
Embed
Share
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXggIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24teCIgLz48L3N2Zz4="
class="icon icon-x" />
</div>
<div class="sd-player-share-menu-group">
Beginning
This slide
</div>
<div class="sd-player-share-menu-buttons">
<div class="sd-player-share-menu-action active" data-selected-by="link"
data-group="type">
Copy link URL
Copy link URL
</div>
<div
class="sd-player-share-menu-action sd-player-share-menu-action-stacked"
data-selected-by="embed" data-group="type">
Copy iframe embed code
Copy iframe embed code
Copy javascript embed code
Copy javascript embed code
</div>
<div class="sd-player-share-menu-action" data-selected-by="share"
data-group="type">
<div class="sd-player-share-menu-action active js-sd-player-share-start"
data-selected-by="beginning" data-group="start">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZhY2Vib29rICI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZhY2Vib29rIiAvPjwvc3ZnPg=="
class="icon icon-facebook" /> Share
<a
href="https://twitter.com/intent/tweet?text=caseworking1.2.jon-lite-show-and-tell.pdf&amp;url=https://speakerdeck.com/ctdesign/caseworking1-dot-2-jon-lite-show-and-tell"
class="sd-player-btn twitter-share-button js-twitter-button-start"
target="_blank"><img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXR3aXR0ZXIgIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tdHdpdHRlciIgLz48L3N2Zz4="
class="icon icon-twitter" /> Tweet</a>
</div>
<div class="sd-player-share-menu-action js-sd-player-share-slide"
data-selected-by="slide" data-group="start">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZhY2Vib29rICI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZhY2Vib29rIiAvPjwvc3ZnPg=="
class="icon icon-facebook" /> Share
<a
href="https://twitter.com/intent/tweet?text=caseworking1.2.jon-lite-show-and-tell.pdf&amp;url=https://speakerdeck.com/ctdesign/caseworking1-dot-2-jon-lite-show-and-tell?slide=1"
class="sd-player-btn twitter-share-button js-twitter-button-slide"
target="_blank"><img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXR3aXR0ZXIgIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tdHdpdHRlciIgLz48L3N2Zz4="
class="icon icon-twitter" /> Tweet</a>
</div>
</div>
</div>
</div>
</div>
<div class="sd-player-presenter">
<div class="sd-player-presenter-container js-sd-player-presenter">
<div
class="sd-player-slide sd-player-presenter-previous js-sd-player-previous-slide">

</div>
<div
class="sd-player-slide sd-player-presenter-current js-sd-player-current-slide">

</div>
<div
class="sd-player-slide sd-player-presenter-next js-sd-player-next-slide">

</div>
</div>
</div>
<div class="sd-player-slides js-sd-player-slides">
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_0.jpg?10906643"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_0.jpg?10906643"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-1" class="sd-player-slides--heading">Slide 1</h2>
<h3 id="slide-1-text">Slide 1 text</h3>
<div class="sd-player-slides--text">
LITE (Licensing for International Trade and Enterprise) Case processing
overview Jonathan Hirsch, 11th October 2017
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_1.jpg?10906644"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_1.jpg?10906644"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-2" class="sd-player-slides--heading">Slide 2</h2>
<h3 id="slide-2-text">Slide 2 text</h3>
<div class="sd-player-slides--text">
Context: the service map
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_2.jpg?10906645"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_2.jpg?10906645"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-3" class="sd-player-slides--heading">Slide 3</h2>
<h3 id="slide-3-text">Slide 3 text</h3>
<div class="sd-player-slides--text">
Case processing
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_3.jpg?10906646"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_3.jpg?10906646"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-4" class="sd-player-slides--heading">Slide 4</h2>
<h3 id="slide-4-text">Slide 4 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_4.jpg?10906647"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_4.jpg?10906647"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-5" class="sd-player-slides--heading">Slide 5</h2>
<h3 id="slide-5-text">Slide 5 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_5.jpg?10906648"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_5.jpg?10906648"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-6" class="sd-player-slides--heading">Slide 6</h2>
<h3 id="slide-6-text">Slide 6 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_6.jpg?10906649"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_6.jpg?10906649"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-7" class="sd-player-slides--heading">Slide 7</h2>
<h3 id="slide-7-text">Slide 7 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_7.jpg?10906650"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_7.jpg?10906650"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-8" class="sd-player-slides--heading">Slide 8</h2>
<h3 id="slide-8-text">Slide 8 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_8.jpg?10906651"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_8.jpg?10906651"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-9" class="sd-player-slides--heading">Slide 9</h2>
<h3 id="slide-9-text">Slide 9 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_9.jpg?10906652"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_9.jpg?10906652"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-10" class="sd-player-slides--heading">Slide 10</h2>
<h3 id="slide-10-text">Slide 10 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_10.jpg?10906653"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_10.jpg?10906653"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-11" class="sd-player-slides--heading">Slide 11</h2>
<h3 id="slide-11-text">Slide 11 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_11.jpg?10906654"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_11.jpg?10906654"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-12" class="sd-player-slides--heading">Slide 12</h2>
<h3 id="slide-12-text">Slide 12 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_12.jpg?10906655"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_12.jpg?10906655"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-13" class="sd-player-slides--heading">Slide 13</h2>
<h3 id="slide-13-text">Slide 13 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_13.jpg?10906656"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_13.jpg?10906656"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-14" class="sd-player-slides--heading">Slide 14</h2>
<h3 id="slide-14-text">Slide 14 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_14.jpg?10906657"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_14.jpg?10906657"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-15" class="sd-player-slides--heading">Slide 15</h2>
<h3 id="slide-15-text">Slide 15 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_15.jpg?10906658"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_15.jpg?10906658"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-16" class="sd-player-slides--heading">Slide 16</h2>
<h3 id="slide-16-text">Slide 16 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_16.jpg?10906659"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_16.jpg?10906659"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-17" class="sd-player-slides--heading">Slide 17</h2>
<h3 id="slide-17-text">Slide 17 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_17.jpg?10906660"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_17.jpg?10906660"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-18" class="sd-player-slides--heading">Slide 18</h2>
<h3 id="slide-18-text">Slide 18 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/slide_18.jpg?10906661"
data-preview-url="https://files.speakerdeck.com/presentations/167049a9c74047bba14c44eb0e69cb81/preview_slide_18.jpg?10906661"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-19" class="sd-player-slides--heading">Slide 19</h2>
<h3 id="slide-19-text">Slide 19 text</h3>
<div class="sd-player-slides--text">
No content
</div>
</div>
</div>
</div>
</div>
<div id="fb-root">

</div>
</div>
</div>
<figcaption><a
href="https://drive.google.com/file/d/0B7y7fXAz33PoUzR2YXc2aWRXUXc/view"
class="markup--anchor markup--figure-anchor"
data-href="https://drive.google.com/file/d/0B7y7fXAz33PoUzR2YXc2aWRXUXc/view"
rel="nofollow noopener"
target="_blank">https://drive.google.com/file/d/0B7y7fXAz33PoUzR2YXc2aWRXUXc/view</a></figcaption>
</figure>

This service can cover anything from a large corporation that has a
department dedicated to submitting applications, to an individual who
wants to take their rifle abroad for a competition.

**'Design like you're right, test like you're wrong'** --- they needed
something that works pretty good when they get started.

We started by making a service map.

The stages of activities across the user's journey were split up across
different internal depts. All located in different places.

We found that everyone loves the way they currently work --- even though
the UI is terrible and inaccessible, they love it.

The outcome is a 'bunch of letters' for the user --- could be a refusal
letter, could be granted, or a combo of these for different parts of the
application.

A user quote on viewing the system they have designed: '**Get rid of all
the white space --- put content in there'**.

The team started with GDS patterns, but they don't always work --- so
they're taking the 'spirit' of the patterns.

The design currently uses the language of the existing case workers,
things that make sense for them now, for example 'work basket'.
Acknowledges that this could cause problems for new users of the system.

Task screens are basically simple forms. But some are more non-linear.

The team think it's better to show disabled options than not show --- a
prompt to caseworker that there's stuff that needs to be done to
proceed, eg to issue a license or bounce it back to someone else.

They researched the working environment of caseworkers--- all
caseworkers have big screens, so they've optimised for large screen
(1200px) --- 'if someone doesn't have a big screen --- buy them a new
one' --- it's cheaper to buy monitors than do the design work for
smaller screens.

The team have created a set of guidance and examples in a design
library.

Caseworker users often had two screens --- 'they liked popups'.

They might need to work on single rows, or bulk edit.

Jon showed an interesting right-hand 'side panel' that slides in over
the table to edit the rows. Tested really well with users, who can still
scroll up and down the table while editing. They used this side panel on
other screens too.

Research is hard --- users are very used to old system. They told their
users where things had moved to. They're used to small text on wide
screens, no white-space, not accessible.

Caseworkers keen to have as much on the screen as possible.

\[Shows a pattern where table rows expand to show lots more info\]. This
allows people who need all that info to see it, and see it for multiple
specific rows.

'I think this is a deviation from the pattern --- showing a sub form
when you click a radio button'

It's been a balancing act --- ease of use, accessible, scalable, showing
lots of information.

**Questions for the speaker:**

Q: Did you test with users with accessibility needs?\
A: Had a user with low vision with a very large screen, it worked for
him. We have a decision to use JS without a fallback.

Q: Did you have a content designer? Do you think it would benefit?\
A: We did have access to a content designer at some times. We worked
closely with caseworkers. The data is what it is, not much opportunity
for different wording. There is a need to get a content designer
involved. 'Complete but not finished' is the approach we're trying to
take, so something being missing is not an issue in testing.

Q. About 'due dates' --- the ones in the prototype are relative --- what
research backs this up?\
A: We've done a lot on this, days elapsed, days remaining, progress
against SLA (two in some cases) days remaining is what matters (from
research). On target, breaching target. If case is bounced back to
applicant, the clock stops. We got to days remaining in a circle, colour
coded for breaching SLA (red amber green)

Q: Caseworkers cherry-picking work --- is that a problem you looked at?\
A: Managers allocate work. There is some discretion, in theory working
on most urgent, in practice maybe another one because I can get it done.
There's no requirement to force users to do the next one (priority) on
the list.

#### Presentation on Booking travel within and out of the UK 

*Home Office, presented by Helena Du Toit( Interaction Designer)*

<figure id="eb22" class="graf graf--figure graf--iframe graf-after--p">
<div class="iframe">
<div id="player" class="slides" data-referer="" data-host="">
<div class="sd-player state-initial js-sd-player" data-start-slide="0"
data-url="https://speakerdeck.com/ctdesign/caseworking1-dot-3-helena-booking-travel"
data-ratio="1.7777777777777777">
<div class="sd-player-title">
<div class="sd-player-avatar">
<a href="https://speakerdeck.com/ctdesign" target="_parent"
aria-label="SpeakerDeck profile page for "><img
src="https://secure.gravatar.com/avatar/20473746d7da441591510b4c0e4eb0b3?s=47"
class="avatar" loading="eager" width="47" height="47" /></a>
</div>
<div class="sd-player-title-name">
<a
href="https://speakerdeck.com/ctdesign/caseworking1-dot-3-helena-booking-travel"
class="sd-player-title-link"
target="_parent">caseworking1.3.helena-booking-travel.pdf</a>
</div>
<div class="sd-player-title-author">
by <a href="https://speakerdeck.com/ctdesign"
class="sd-player-title-link" target="_parent"></a>
</div>
<div class="sd-player-title-mark">
<a href="https://speakerdeck.com/" target="_parent"
aria-label="SpeakerDeck Homepage"><img
src="https://d1eu30co0ohy4w.cloudfront.net/assets/mark-white-8d908558fe78e8efc8118c6fe9b9b1a9846b182c503bdc6902f97df4ddc9f3af.svg"
alt="Speaker Deck" /></a>
</div>
</div>
<div class="sd-player-controls">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWNoZXZyb24tbGVmdCBpY29uLXBsYXllciI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWNoZXZyb24tbGVmdCIgLz48L3N2Zz4="
class="icon icon-chevron-left icon-player" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWNoZXZyb24tcmlnaHQgaWNvbi1wbGF5ZXIiPjx1c2UgeGxpbms6aHJlZj0iL2ljb25zL2ljb25zLnN2Zz92PTIwMjUtMDEtMjYjaWNvbi1jaGV2cm9uLXJpZ2h0IiAvPjwvc3ZnPg=="
class="icon icon-chevron-right icon-player" />
<div class="sd-player-spacer">

</div>
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXNoYXJlIGljb24tcGxheWVyIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tc2hhcmUiIC8+PC9zdmc+"
class="icon icon-share icon-player" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZ1bGxzY3JlZW4gaWNvbi1wbGF5ZXIgc2QtcGxheWVyLWVuYWJsZS1mdWxsc2NyZWVuIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tZnVsbHNjcmVlbiIgLz48L3N2Zz4="
class="icon icon-fullscreen icon-player sd-player-enable-fullscreen" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZ1bGxzY3JlZW4gaWNvbi1wbGF5ZXIgc2QtcGxheWVyLWRpc2FibGUtZnVsbHNjcmVlbiI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZ1bGxzY3JlZW4iIC8+PC9zdmc+"
class="icon icon-fullscreen icon-player sd-player-disable-fullscreen" />
</div>
<div class="current-slide-note" hidden="">

</div>
<div class="sd-player-gradient">

</div>
<div class="sd-player-scrubber js-sd-player-scrubber">
<div class="sd-player-scrubber-bar">
<div class="sd-player-scrubber-progress js-sd-player-scrubber-progress">

</div>
</div>
</div>
<div class="sd-player-preview js-sd-player-preview">

</div>
<div class="sd-player-share-menu" hidden="">
<div class="sd-player-share-menu-overlay js-sd-player-share-close">

</div>
<div class="sd-player-share-menu-container">
<div class="sd-player-share-menu-group sd-player-share-menu-group-head">
Link
Embed
Share
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXggIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24teCIgLz48L3N2Zz4="
class="icon icon-x" />
</div>
<div class="sd-player-share-menu-group">
Beginning
This slide
</div>
<div class="sd-player-share-menu-buttons">
<div class="sd-player-share-menu-action active" data-selected-by="link"
data-group="type">
Copy link URL
Copy link URL
</div>
<div
class="sd-player-share-menu-action sd-player-share-menu-action-stacked"
data-selected-by="embed" data-group="type">
Copy iframe embed code
Copy iframe embed code
Copy javascript embed code
Copy javascript embed code
</div>
<div class="sd-player-share-menu-action" data-selected-by="share"
data-group="type">
<div class="sd-player-share-menu-action active js-sd-player-share-start"
data-selected-by="beginning" data-group="start">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZhY2Vib29rICI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZhY2Vib29rIiAvPjwvc3ZnPg=="
class="icon icon-facebook" /> Share
<a
href="https://twitter.com/intent/tweet?text=caseworking1.3.helena-booking-travel.pdf&amp;url=https://speakerdeck.com/ctdesign/caseworking1-dot-3-helena-booking-travel"
class="sd-player-btn twitter-share-button js-twitter-button-start"
target="_blank"><img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXR3aXR0ZXIgIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tdHdpdHRlciIgLz48L3N2Zz4="
class="icon icon-twitter" /> Tweet</a>
</div>
<div class="sd-player-share-menu-action js-sd-player-share-slide"
data-selected-by="slide" data-group="start">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZhY2Vib29rICI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZhY2Vib29rIiAvPjwvc3ZnPg=="
class="icon icon-facebook" /> Share
<a
href="https://twitter.com/intent/tweet?text=caseworking1.3.helena-booking-travel.pdf&amp;url=https://speakerdeck.com/ctdesign/caseworking1-dot-3-helena-booking-travel?slide=1"
class="sd-player-btn twitter-share-button js-twitter-button-slide"
target="_blank"><img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXR3aXR0ZXIgIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tdHdpdHRlciIgLz48L3N2Zz4="
class="icon icon-twitter" /> Tweet</a>
</div>
</div>
</div>
</div>
</div>
<div class="sd-player-presenter">
<div class="sd-player-presenter-container js-sd-player-presenter">
<div
class="sd-player-slide sd-player-presenter-previous js-sd-player-previous-slide">

</div>
<div
class="sd-player-slide sd-player-presenter-current js-sd-player-current-slide">

</div>
<div
class="sd-player-slide sd-player-presenter-next js-sd-player-next-slide">

</div>
</div>
</div>
<div class="sd-player-slides js-sd-player-slides">
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_0.jpg?10906815"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_0.jpg?10906815"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-1" class="sd-player-slides--heading">Slide 1</h2>
<h3 id="slide-1-text">Slide 1 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Booking travel within and out of the UK
Helena du Toit Interaction Designer @hadutoit
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_1.jpg?10906816"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_1.jpg?10906816"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-2" class="sd-player-slides--heading">Slide 2</h2>
<h3 id="slide-2-text">Slide 2 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Our caseworkers
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_2.jpg?10906817"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_2.jpg?10906817"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-3" class="sd-player-slides--heading">Slide 3</h2>
<h3 id="slide-3-text">Slide 3 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology May rarely use computers outside of work.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_3.jpg?10906818"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_3.jpg?10906818"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-4" class="sd-player-slides--heading">Slide 4</h2>
<h3 id="slide-4-text">Slide 4 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Told to be ‘digital’.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_4.jpg?10906819"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_4.jpg?10906819"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-5" class="sd-player-slides--heading">Slide 5</h2>
<h3 id="slide-5-text">Slide 5 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_5.jpg?10906820"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_5.jpg?10906820"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-6" class="sd-player-slides--heading">Slide 6</h2>
<h3 id="slide-6-text">Slide 6 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Act on what they are measured on.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_6.jpg?10906821"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_6.jpg?10906821"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-7" class="sd-player-slides--heading">Slide 7</h2>
<h3 id="slide-7-text">Slide 7 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Not trusted.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_7.jpg?10906822"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_7.jpg?10906822"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-8" class="sd-player-slides--heading">Slide 8</h2>
<h3 id="slide-8-text">Slide 8 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_8.jpg?10906823"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_8.jpg?10906823"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-9" class="sd-player-slides--heading">Slide 9</h2>
<h3 id="slide-9-text">Slide 9 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Very fearful of doing something wrong and
being blamed.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_9.jpg?10906824"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_9.jpg?10906824"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-10" class="sd-player-slides--heading">Slide 10</h2>
<h3 id="slide-10-text">Slide 10 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Resilient.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/slide_10.jpg?10906825"
data-preview-url="https://files.speakerdeck.com/presentations/0470992f895040d7ac721110b5ccc84a/preview_slide_10.jpg?10906825"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-11" class="sd-player-slides--heading">Slide 11</h2>
<h3 id="slide-11-text">Slide 11 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Demo
</div>
</div>
</div>
</div>
</div>
<div id="fb-root">

</div>
</div>
</div>
<figcaption><a
href="https://drive.google.com/file/d/0B7y7fXAz33PoeEVoVy1LY21GMlk/view"
class="markup--anchor markup--figure-anchor"
data-href="https://drive.google.com/file/d/0B7y7fXAz33PoeEVoVy1LY21GMlk/view"
rel="nofollow noopener"
target="_blank">https://drive.google.com/file/d/0B7y7fXAz33PoeEVoVy1LY21GMlk/view</a></figcaption>
</figure>

This is a travel booking system where caseworker books travel for a
person or a whole family --- this info is collected and goes to the
travel agent to find flights etc. Then the system takes info from the
travel agent and displays it.

From research we found that caseworkers:

-   [rarely use computers outside of work, especially work of this
    complexity.]
-   [are told to 'be digital' --- but what does this mean?
    Paperless?]
-   [act on what they are measured on (you get what you measure)]
-   [work on a desktop machine, and generate the same no. of docs in Doc
    Gen then print all the files off any way for records]
-   [don't seem to be trusted, eg 'cherry-picking' 'they're not doing X'
    'need to make sure they are checking Y']
-   [are fearful of making a mistake and being blamed. For example, if
    they see an empty text box they fill it with everything possibly
    relevant in case it's ever looked back over and their work is called
    into question.]

They're resilient --- they have worked with terrible systems. They
create workarounds and are proud of it.

#### Presentation on service design and internal systems 

*Home Office --- Ayesha Moarif --- Service Design Lead*

<figure id="5790" class="graf graf--figure graf--iframe graf-after--p">
<div class="iframe">
<div id="player" class="slides" data-referer="" data-host="">
<div class="sd-player state-initial js-sd-player" data-start-slide="0"
data-url="https://speakerdeck.com/ctdesign/caseworking1-dot-4-ayesha-design"
data-ratio="1.7777777777777777">
<div class="sd-player-title">
<div class="sd-player-avatar">
<a href="https://speakerdeck.com/ctdesign" target="_parent"
aria-label="SpeakerDeck profile page for "><img
src="https://secure.gravatar.com/avatar/20473746d7da441591510b4c0e4eb0b3?s=47"
class="avatar" loading="eager" width="47" height="47" /></a>
</div>
<div class="sd-player-title-name">
<a
href="https://speakerdeck.com/ctdesign/caseworking1-dot-4-ayesha-design"
class="sd-player-title-link"
target="_parent">caseworking1.4.ayesha-design-.pdf</a>
</div>
<div class="sd-player-title-author">
by <a href="https://speakerdeck.com/ctdesign"
class="sd-player-title-link" target="_parent"></a>
</div>
<div class="sd-player-title-mark">
<a href="https://speakerdeck.com/" target="_parent"
aria-label="SpeakerDeck Homepage"><img
src="https://d1eu30co0ohy4w.cloudfront.net/assets/mark-white-8d908558fe78e8efc8118c6fe9b9b1a9846b182c503bdc6902f97df4ddc9f3af.svg"
alt="Speaker Deck" /></a>
</div>
</div>
<div class="sd-player-controls">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWNoZXZyb24tbGVmdCBpY29uLXBsYXllciI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWNoZXZyb24tbGVmdCIgLz48L3N2Zz4="
class="icon icon-chevron-left icon-player" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWNoZXZyb24tcmlnaHQgaWNvbi1wbGF5ZXIiPjx1c2UgeGxpbms6aHJlZj0iL2ljb25zL2ljb25zLnN2Zz92PTIwMjUtMDEtMjYjaWNvbi1jaGV2cm9uLXJpZ2h0IiAvPjwvc3ZnPg=="
class="icon icon-chevron-right icon-player" />
<div class="sd-player-spacer">

</div>
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXNoYXJlIGljb24tcGxheWVyIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tc2hhcmUiIC8+PC9zdmc+"
class="icon icon-share icon-player" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZ1bGxzY3JlZW4gaWNvbi1wbGF5ZXIgc2QtcGxheWVyLWVuYWJsZS1mdWxsc2NyZWVuIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tZnVsbHNjcmVlbiIgLz48L3N2Zz4="
class="icon icon-fullscreen icon-player sd-player-enable-fullscreen" />
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZ1bGxzY3JlZW4gaWNvbi1wbGF5ZXIgc2QtcGxheWVyLWRpc2FibGUtZnVsbHNjcmVlbiI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZ1bGxzY3JlZW4iIC8+PC9zdmc+"
class="icon icon-fullscreen icon-player sd-player-disable-fullscreen" />
</div>
<div class="current-slide-note" hidden="">

</div>
<div class="sd-player-gradient">

</div>
<div class="sd-player-scrubber js-sd-player-scrubber">
<div class="sd-player-scrubber-bar">
<div class="sd-player-scrubber-progress js-sd-player-scrubber-progress">

</div>
</div>
</div>
<div class="sd-player-preview js-sd-player-preview">

</div>
<div class="sd-player-share-menu" hidden="">
<div class="sd-player-share-menu-overlay js-sd-player-share-close">

</div>
<div class="sd-player-share-menu-container">
<div class="sd-player-share-menu-group sd-player-share-menu-group-head">
Link
Embed
Share
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXggIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24teCIgLz48L3N2Zz4="
class="icon icon-x" />
</div>
<div class="sd-player-share-menu-group">
Beginning
This slide
</div>
<div class="sd-player-share-menu-buttons">
<div class="sd-player-share-menu-action active" data-selected-by="link"
data-group="type">
Copy link URL
Copy link URL
</div>
<div
class="sd-player-share-menu-action sd-player-share-menu-action-stacked"
data-selected-by="embed" data-group="type">
Copy iframe embed code
Copy iframe embed code
Copy javascript embed code
Copy javascript embed code
</div>
<div class="sd-player-share-menu-action" data-selected-by="share"
data-group="type">
<div class="sd-player-share-menu-action active js-sd-player-share-start"
data-selected-by="beginning" data-group="start">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZhY2Vib29rICI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZhY2Vib29rIiAvPjwvc3ZnPg=="
class="icon icon-facebook" /> Share
<a
href="https://twitter.com/intent/tweet?text=caseworking1.4.ayesha-design-.pdf&amp;url=https://speakerdeck.com/ctdesign/caseworking1-dot-4-ayesha-design"
class="sd-player-btn twitter-share-button js-twitter-button-start"
target="_blank"><img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXR3aXR0ZXIgIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tdHdpdHRlciIgLz48L3N2Zz4="
class="icon icon-twitter" /> Tweet</a>
</div>
<div class="sd-player-share-menu-action js-sd-player-share-slide"
data-selected-by="slide" data-group="start">
<img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWZhY2Vib29rICI+PHVzZSB4bGluazpocmVmPSIvaWNvbnMvaWNvbnMuc3ZnP3Y9MjAyNS0wMS0yNiNpY29uLWZhY2Vib29rIiAvPjwvc3ZnPg=="
class="icon icon-facebook" /> Share
<a
href="https://twitter.com/intent/tweet?text=caseworking1.4.ayesha-design-.pdf&amp;url=https://speakerdeck.com/ctdesign/caseworking1-dot-4-ayesha-design?slide=1"
class="sd-player-btn twitter-share-button js-twitter-button-slide"
target="_blank"><img
src="data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLXR3aXR0ZXIgIj48dXNlIHhsaW5rOmhyZWY9Ii9pY29ucy9pY29ucy5zdmc/dj0yMDI1LTAxLTI2I2ljb24tdHdpdHRlciIgLz48L3N2Zz4="
class="icon icon-twitter" /> Tweet</a>
</div>
</div>
</div>
</div>
</div>
<div class="sd-player-presenter">
<div class="sd-player-presenter-container js-sd-player-presenter">
<div
class="sd-player-slide sd-player-presenter-previous js-sd-player-previous-slide">

</div>
<div
class="sd-player-slide sd-player-presenter-current js-sd-player-current-slide">

</div>
<div
class="sd-player-slide sd-player-presenter-next js-sd-player-next-slide">

</div>
</div>
</div>
<div class="sd-player-slides js-sd-player-slides">
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_0.jpg?10906826"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_0.jpg?10906826"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-1" class="sd-player-slides--heading">Slide 1</h2>
<h3 id="slide-1-text">Slide 1 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Service design &amp; internal systems
Ayesha Moarif Service Design Lead
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_1.jpg?10906827"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_1.jpg?10906827"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-2" class="sd-player-slides--heading">Slide 2</h2>
<h3 id="slide-2-text">Slide 2 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_2.jpg?10906828"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_2.jpg?10906828"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-3" class="sd-player-slides--heading">Slide 3</h2>
<h3 id="slide-3-text">Slide 3 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_3.jpg?10906829"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_3.jpg?10906829"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-4" class="sd-player-slides--heading">Slide 4</h2>
<h3 id="slide-4-text">Slide 4 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Casework systems • End users vs system
users • “Digitising” how it works now • Policy or procedure? • Pressure
to keep running
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_4.jpg?10906830"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_4.jpg?10906830"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-5" class="sd-player-slides--heading">Slide 5</h2>
<h3 id="slide-5-text">Slide 5 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Casework systems How we make decisions
about an application more effectively and efficiently
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_5.jpg?10906831"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_5.jpg?10906831"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-6" class="sd-player-slides--heading">Slide 6</h2>
<h3 id="slide-6-text">Slide 6 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Frame what needs solving within the
end-to-end service 1.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_6.jpg?10906832"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_6.jpg?10906832"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-7" class="sd-player-slides--heading">Slide 7</h2>
<h3 id="slide-7-text">Slide 7 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Get or apply Claim Report Become Learn
Check
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_7.jpg?10906833"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_7.jpg?10906833"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-8" class="sd-player-slides--heading">Slide 8</h2>
<h3 id="slide-8-text">Slide 8 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Home Office services
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_8.jpg?10906834"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_8.jpg?10906834"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-9" class="sd-player-slides--heading">Slide 9</h2>
<h3 id="slide-9-text">Slide 9 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Use key service stages to set outcomes 2.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_9.jpg?10906835"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_9.jpg?10906835"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-10" class="sd-player-slides--heading">Slide 10</h2>
<h3 id="slide-10-text">Slide 10 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Getting a permission • Find out • Choose
and act • Make a decision • Fulfil decision • Meet rules • Enforce rules
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_10.jpg?10906836"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_10.jpg?10906836"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-11" class="sd-player-slides--heading">Slide 11</h2>
<h3 id="slide-11-text">Slide 11 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Getting a permission • Find out • Choose
and act • Make a decision • Fulfil decision • Meet rules • Enforce rules
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_11.jpg?10906837"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_11.jpg?10906837"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-12" class="sd-player-slides--heading">Slide 12</h2>
<h3 id="slide-12-text">Slide 12 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Service outcomes Find out Comply Enforce
Choose Act Decide Fulfil Apply for correct thing correct way Know what
to expect by when Know what entitled to or not
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_12.jpg?10906838"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_12.jpg?10906838"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-13" class="sd-player-slides--heading">Slide 13</h2>
<h3 id="slide-13-text">Slide 13 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Service outcomes Find out Comply Enforce
Choose Act Decide Fulfil Apply for correct thing correct way Know what
to expect by when Know what entitled to or not Get information needed
for accurate and efficient decision Make a timely and accurate decision,
less time spent on simpler decisions Issue permission with checkable
entitlement Provider outcomes
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_13.jpg?10906839"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_13.jpg?10906839"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-14" class="sd-player-slides--heading">Slide 14</h2>
<h3 id="slide-14-text">Slide 14 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Service outcomes Find out Comply Enforce
Choose Act Decide Fulfil Apply for correct thing correct way Know what
to expect by when Know what entitled to or not Get information needed
for accurate and efficient decision Make a timely and accurate decision,
less time spent on simpler decisions Issue permission with checkable
entitlement Provider outcomes Ratio of incorrect to ineligible
applications Time taken to make decision Grant, refusal, challenge and
overturn rates Possible measures
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_14.jpg?10906840"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_14.jpg?10906840"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-15" class="sd-player-slides--heading">Slide 15</h2>
<h3 id="slide-15-text">Slide 15 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Service outcomes Find out Comply Enforce
Choose Act Decide Fulfil Apply for correct thing correct way Know what
to expect by when Know what entitled to or not Get information needed
for accurate and efficient decision Make a timely and accurate decision,
less time spent on simpler decisions Issue permission with checkable
entitlement Provider outcomes Ratio of incorrect to ineligible
applications Time taken to make decision Grant, refusal, challenge and
overturn rates Possible measures
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_15.jpg?10906841"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_15.jpg?10906841"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-16" class="sd-player-slides--heading">Slide 16</h2>
<h3 id="slide-16-text">Slide 16 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Understand what activities need to happen
3.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_16.jpg?10906842"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_16.jpg?10906842"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-17" class="sd-player-slides--heading">Slide 17</h2>
<h3 id="slide-17-text">Slide 17 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology A service Find out Comply Enforce Choose
Act Decide Fulfil Things users need to do Things providers need to do
Activities Activities e.g. “Visiting the UK” or “Getting an alcohol
license” Major steps e.g. applying, being notified Sub-services
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_17.jpg?10906843"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_17.jpg?10906843"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-18" class="sd-player-slides--heading">Slide 18</h2>
<h3 id="slide-18-text">Slide 18 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Check suitability Check eligibility Check
entitlement Make decision Notify of a decision Issue proof Caseworking
Unclear activity What actually needs to happen?
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_18.jpg?10906844"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_18.jpg?10906844"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-19" class="sd-player-slides--heading">Slide 19</h2>
<h3 id="slide-19-text">Slide 19 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Things still likely to happen even in 10
years’ time whether human, a computer, artificial intelligence… or some
other way we haven’t imagined yet
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_19.jpg?10906845"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_19.jpg?10906845"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-20" class="sd-player-slides--heading">Slide 20</h2>
<h3 id="slide-20-text">Slide 20 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Ways we could do these activities What
actually needs to happen Check eligibility Check entitlement Make
decision Remove need for checks Use what we know Manual checks Automate
checks Triage checks Issue proof
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_20.jpg?10906846"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_20.jpg?10906846"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-21" class="sd-player-slides--heading">Slide 21</h2>
<h3 id="slide-21-text">Slide 21 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology See how this happens now and how it could
happen 4.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_21.jpg?10906847"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_21.jpg?10906847"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-22" class="sd-player-slides--heading">Slide 22</h2>
<h3 id="slide-22-text">Slide 22 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology A service Find out Comply Enforce Choose
Act Decide Fulfil Things users need to do Things providers need to do
The ability to do them Technology Activities Activities Capabilities
Systems and tools to enable delivery Data The actual data e.g. name, DOB
Major steps e.g. applying, being notified Sub-services e.g. “Visiting
the UK” or “Getting an alcohol license”
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_22.jpg?10906848"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_22.jpg?10906848"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-23" class="sd-player-slides--heading">Slide 23</h2>
<h3 id="slide-23-text">Slide 23 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_23.jpg?10906849"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_23.jpg?10906849"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-24" class="sd-player-slides--heading">Slide 24</h2>
<h3 id="slide-24-text">Slide 24 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_24.jpg?10906850"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_24.jpg?10906850"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-25" class="sd-player-slides--heading">Slide 25</h2>
<h3 id="slide-25-text">Slide 25 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_25.jpg?10906851"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_25.jpg?10906851"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-26" class="sd-player-slides--heading">Slide 26</h2>
<h3 id="slide-26-text">Slide 26 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Desired outcomes Current issues Ways to
measure them Ideas to test High volume of incorrectly filled
applications Financial eligibility proof unclear and inconsistent Get
just the information needed to make a decision - Ratio of incomplete to
complete application - Speed of eligibility check for x cohorts - Check
before you start - Form redesign - Add key fields from proof to form -
Skip cohort verified by HMRC Exam ple
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_26.jpg?10906852"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_26.jpg?10906852"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-27" class="sd-player-slides--heading">Slide 27</h2>
<h3 id="slide-27-text">Slide 27 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Decision-making across multiple services 5.
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_27.jpg?10906853"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_27.jpg?10906853"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-28" class="sd-player-slides--heading">Slide 28</h2>
<h3 id="slide-28-text">Slide 28 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology A service Another service Decision: Grant
refugee status to asylum seekers Decision: Agree to offer refuge through
resettlement What’s the input? What decisions need to be made? What
decision outcomes? What data required? What activities undertaken? What
artefacts or proof?
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_28.jpg?10906854"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_28.jpg?10906854"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-29" class="sd-player-slides--heading">Slide 29</h2>
<h3 id="slide-29-text">Slide 29 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology Casework systems How we make decisions
about an application more effectively and efficiently
</div>
</div>
</div>
<div class="sd-player-slide js-sd-slide"
data-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/slide_29.jpg?10906855"
data-preview-url="https://files.speakerdeck.com/presentations/5b31732d61bf47a8ae9aeed1b04ae667/preview_slide_29.jpg?10906855"
data-slide-note="">
<div class="sd-player-slides--content visually-hidden">
<h2 id="slide-30" class="sd-player-slides--heading">Slide 30</h2>
<h3 id="slide-30-text">Slide 30 text</h3>
<div class="sd-player-slides--text">
Digital, Data and Technology More to read Building internal systems vs
providing services
https://hodigital.blog.gov.uk/2017/04/20/building-internal-systems-v-providing-
services/ What we mean by service outcomes and measurement
https://hodigital.blog.gov.uk/2017/08/04/what-we-mean-by-service-outcomes-
and-measurement/ Creating a common language to describe services
https://hodigital.blog.gov.uk/2016/12/21/creating-a-common-language-to-
describe-services/
</div>
</div>
</div>
</div>
</div>
<div id="fb-root">

</div>
</div>
</div>
<figcaption><a
href="https://drive.google.com/file/d/0B7y7fXAz33PoaEVkNVNMZUl5T2M/view"
class="markup--anchor markup--figure-anchor"
data-href="https://drive.google.com/file/d/0B7y7fXAz33PoaEVkNVNMZUl5T2M/view"
rel="nofollow noopener"
target="_blank">https://drive.google.com/file/d/0B7y7fXAz33PoaEVkNVNMZUl5T2M/view</a></figcaption>
</figure>

Instead of thinking 'case working' --- think how do we make decisions
about an application more effectively and efficiently?

Find big stages in services that are not likely to change.

Caseworking = Make a decision, fulfil a decision stages.

Think of the things that are unlikely to change in 10 years. *How* it
happens might change but it still happens.

Set measures for outcomes so when you try new stuff you know how it
performs.

It's great that we have patterns, check before you start.

-   [Break down]
-   [Whats the input?]
-   [Decisions to be made]
-   [Decision outcomes]
-   [Data required]
-   [Activities undertaken]
-   [Artefacts or proof]

What are similarities and differences across services in the above?

Kate Tarling has written well about this already:

-   [[Types and stages of
    services](https://hodigital.blog.gov.uk/2017/07/31/types-and-stages-of-services/){.markup--anchor
    .markup--li-anchor
    data-href="https://hodigital.blog.gov.uk/2017/07/31/types-and-stages-of-services/"
    rel="noopener" target="_blank"}]
-   [[Building internal systems v providing
    services](https://hodigital.blog.gov.uk/2017/04/20/building-internal-systems-v-providing-services/){.markup--anchor
    .markup--li-anchor
    data-href="https://hodigital.blog.gov.uk/2017/04/20/building-internal-systems-v-providing-services/"
    rel="noopener" target="_blank"}]

### The afternoon workshop 

<figure id="ff33" class="graf graf--figure graf-after--h3">
<img
src="https://cdn-images-1.medium.com/max/800/0*aSmdAOfDZDAN86yl.jpg"
class="graf-image" data-image-id="0*aSmdAOfDZDAN86yl.jpg"
data-width="1024" data-height="768" />
</figure>

The intention of the afternoon was to run two workshops, one to look at
what common components and design patterns we could identify and one one
the common stages of caseworking. But in the end we only had time for
the first.

We'd asked the attendees to bring along printed screenshots of their
caseworking systems with them for our exercise.

We then split everyone up into smaller mixed groups and pinned up the
screenshots on the walls.

Each team then reviewed and discussed each others designs to look for
common patterns and components, which they then wrote on post-its and
presented back to the rest of the room for discussion.

I've written up the [notes from the group
session](https://docs.google.com/document/d/10YQNEAVNzZh1Eiao84jkwbpriVewOJ-VmnIqI6ne9SU/edit?usp=sharing){.markup--anchor
.markup--p-anchor
data-href="https://docs.google.com/document/d/10YQNEAVNzZh1Eiao84jkwbpriVewOJ-VmnIqI6ne9SU/edit?usp=sharing"
rel="noopener" target="_blank"}.

We generally found a lot of commonalities around the need for things
like case lists, case view pages and the need to record and perfrom
actions on cases.

The outputs from this workshop form the basis for the a caseworking
resource that I've published which contains screenshots of examples of
work categorised by type:
[https://cross-gov-caseworking.herokuapp.com](https://cross-gov-caseworking.herokuapp.com){.markup--anchor
.markup--p-anchor
data-href="https://cross-gov-caseworking.herokuapp.com"
rel="nofollow noopener" target="_blank"}

I'm always looking for examples to include on the site --- so please let
me know if you have some that you'd like to add.

Contact me via a gov email address at
chris.taylor@digital.homeoffice.gov.uk for the username and password.
:::
::::
::::::
:::::::::::

By [Chris T](https://medium.com/@ctdesign) on
[October 5, 2018](https://medium.com/p/5aecd5805c44).

[Canonical
link](https://medium.com/@ctdesign/notes-from-the-designing-caseworking-systems-meetup-1-5aecd5805c44)

Exported from [Medium](https://medium.com) on February 9, 2025.
