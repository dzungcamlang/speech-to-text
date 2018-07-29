Title:  on batch processing audio speech to text
Subtitle:    using google cloud and ibm watson speech to text apis
Project:     speech-to-text
Author:      Mark Plutowski
Affiliation: Plutosoft Delimited
Web:         https://pluteski.github.io
Date:        2017-04-22


# How not to wreck a nice beach
![Quora](https://qph.ec.quoracdn.net/main-qimg-609e5b0b3c91845ab81f0d4448df864f-c)
<p style="text-align: right;"><em>(Quora)</em></p>

People nowadays commonly use speech-to-text tools for myriad uses,
including writing text messages, entering todo lists,
and writing emails.  However, increasing numbers of enterprising
sorts including just plain folk are starting to warm up to
using dictation software for writing longer form content
such as journals and even novels.

Dictation software has been generally available for many years,
in the form of
commercial off the shelf application software, text editors in desktop
operating systems, notepads in tablet devices,
email clients in mobile phones,
and more recently in cloud-based document editors, available
to the user from any device that can run a web browser.

But what if you have a large-ish number of audio files?
It turns out there isn't a comparably inexpensive and easy way
to handle even modestly sized
batches of files using those just aforementioned tools.
There do exist commercially available alternatives, which will gladly
take those batches of audio files off your hands and return
high quality text. But these are still rather
human labor intensive, which means that they remain expensive.

The typical going rate is about a $1/minute, although with a bit
of coding effort (typically meaning slicing files into uniform size work units,
farming said work units out to a distributed online on-demand work force
such as mechanical turk, then resplicing the files back together)
apparently can bring the price down to somewhat, say 70 cents/minute.
(The slicing and resplicing is needed for quality assurance as well
as to reduce privacy and security issues.)
That 70 cents a minute is still rather unaffordable to the typical consumer who is a tad long-winded,
much less the odd sort who just happens to have a boat load of such files.
Not to mention the concerns related to having unknown on-demand workers
hearing an early preview of your memoirs
(cf. [Long Form Voice Transcription, Wired, April 2016](https://www.wired.com/2016/04/long-form-voice-transcription/)).

Fortunately, an affordable alternative is emerging, that is,
if you're willing to write a bit of code.
All of the hyperscale cloud api providers have made their deep
learning speech-to-text models available for a small fraction of the
dollar cost of the aforementioned human-corrected transcription services,
and two of them are now appealing enough for use by individuals
or nonprofits to apply to long form content.
Currently you can get cloud api based speech transcription
for
[prices ranging from 2 to 2.4 cents per minute](https://github.com/pluteski/speech-to-text/wiki/Cloud-API-Pricing),
with an additional allowance free on a monthly basis.
Moreover, they effortlessly handle large batches in a single bound.
You upload your files to the cloud, offloading the
processing from your laptop. Whereas your desktop software or even
embedded operating system software would slow your entire machine down
to a crawl during this process
you could be processing batches of files in parallel
up in the cloud.

Although there is still that small issue of having to write some code
in order to get this amazing cost and time reduction.
[I went and wrote said code.](https://github.com/pluteski/speech-to-text)

So this amazing capability is generally available
at a reasonable price
to anyone with a laptop, internet connection,
and credit card with an embarrassingly low limit.
But it isn't all peaches and chocolate just yet.
There is a still a ways to go before these APIs are reliably useful
for converting conversational audio recorded in the wild using
mobile phones amidst the usual ambient sounds.
Nonetheless, the results are tantalizingly good enough
and the pricing dramatically low enough that the time has come to dip
my metaphorical toes in the water.

I intend to write more about my experiences using these
powerful cloud APIs, so stay tuned if this is of interest
to you.  Although I myself tend to cringe when the blogger ends
their post by promising an enticing followup, which invariably never
comes.  But I really do sincerely intend to write more on this.
Of course, that's what they would all say, I'm sure.

I have already compiled a backlog of interesting results just waiting
to be converted into
intriguing visuals and wrapped in witty yet insightful prose. Promise.

Actually you don't need to wait until then, as
[here is some additional background on the project](https://github.com/pluteski/speech-to-text/wiki/Background).
Here are the
[results of a preliminary comparison between IBM and Google](https://github.com/pluteski/speech-to-text/wiki/Findings).
Here are
[results made over reference documents](https://github.com/pluteski/speech-to-text/wiki/Comparison-over-reference-documents).
And here are some
[results made over audio collected in the wild](https://github.com/pluteski/speech-to-text/wiki/Comparison-of-transcript-word-count).
There are several conclusions that can be drawn from these findings,
which will be the subject of a future post.

In closing, my findings indicate to me that I should be able to
extract useful text from my recordings,
albeit probably not for the purpose of transcribing meeting minutes.
The transcript text generated by the cloud API is largely recognizable to me, although
that is often in the same way as my handwriting is recognizable to me
because I vaguely remember generating it.
The error rates are still too high
for these transcripts to allow me to reliably parse meaningful
whole sentences much less serve as document of record.

These cloud APIs do not have the same quality as
do personalized devices. Voicemail transcripts provided by my
phone are subjectively better than what I'm seeing with these cloud APIs.
One reason is that because the cloud APIs cannot be
trained on my voice, although IBM does allow specifying
a [custom language model](https://www.ibm.com/watson/developercloud/doc/speech-to-text/custom.html#addWords).

The accuracy being provided
by the cloud APIs may be suitable for
indexing audio files to make them more easily searchable
(although phonemes might turn out to be the better data unit
for indexing audio than words,
[e.g., Deepgram](https://twimlai.com/from-particle-physics-to-audio-ai-with-scott-stephenson/)).
I fully expect the current results to
be adequately informative to support meaningful textmining and trend
analysis.

Upon reviewing the current batch of results it is fascinating
to me how a badly transcribed
sequence of just a few words in a row can turn large swaths of text
into complete gibberish. If you tell a linguist you intend to
*recognize speech* they might bid you luck, but an evesdropping
surfer taking that to mean instead
that you intend to *wreck a nice beach* might wish you harm.

We humans are pretty amazing in our ability
to understand each other's muffled speech despite the
poor connection and background noise
much less the tinnitus and what have you.

Nonetheless, I foresee a not too distant future where
it will be possible to cheaply attain human level accuracy
transcription of speaker-independent long-form speech
from noisy recordings obtained using mobile devices. Culminating in,
as [Wired's Jesse Jarnow](https://www.wired.com/2016/04/long-form-voice-transcription/) puts it,
'bizarre kinds of unforeseen societal change'.

Until then, court stenographers shouldn't have much to worry about.

<div id="disqus_thread"></div>
<script>

var disqus_config = function () {
this.page.url = "https://pluteski.github.io/speech-to-text/"
this.page.identifier = "pluteski-github-io-speech-to-text"
};
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://pluteski-github-io-speech-to-text.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments.</a></noscript>

###### fin
