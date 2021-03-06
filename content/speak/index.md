---
title: ""
draft: false
hide_top_sentence: true
---
<style type="text/css">
	#logo {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      transform: scale(0.5);
    }
	#question-container {
	  min-width: 60vw;
	  max-width: min(90vw, 500px);
	}

	details {
	    font-family: sans-serif;
	    font-size: 1.5rem;
	    border-radius: 4px;
	    padding: .5em .5em 0;
	    margin-bottom: 2rem;
	}

	summary {
	    cursor: pointer;
	    font-family: 'Press Start 2P', cursive;
	    line-height: 1.4rem;
	    font-weight: bold;
	    margin: -.5em -.5em 0;
	    padding: .5em;
	    border: 1px solid #aaa;
	    font-size: 1.2rem;
	    letter-spacing: 1px;
	    /* Works on Chrome, but not Firefox.
	       SHAMEFUL DISPLAY.       
	    display: flex;
	    flex-direction: row-reverse;
	    justify-content: space-between;
	    align-items: center;
	    */
	}

	details[open] {
	    padding: .5em;
	    color: white;
	}

	details[open] summary {
	    border-bottom: 1px solid #aaa;
	    margin-bottom: .5em;
	}

	details > summary::-webkit-details-marker {
	  display: none;
	}

	details a {
	  color: #FFFF54;
	}
</style>
<div id="question-container">
    <details>
      <summary>What is Zig SHOWTIME?</summary>
      <p>
        Zig SHOWTIME is a live-streamed show that airs on Twitch where (mostly) 
        members of the Zig community present on a topic and take questions from
        the viewers. Every episode features two speakers.
      </p>
      <p>
        <a href="https://youtu.be/Unq712gqu2U">
          Link to the first episode.
        </a> 
        <br>
        <a href="https://kristoff.it/blog/future-online-meetups">
          Here you can read more about the concept.
        </a> 
      </p>
    </details>
    <details>
      <summary>Why should I speak?</summary>
      <p>
        From your point of view, speaking should be an activity that you choose to
        perform for enjoyment, personal growth or a mix of the two.
      </p>
      <p>
        We often hear that becoming a better communicator is an important "soft skill"
        to have, but it's rarely the case that companies really support that effort. 
        Speaking at events like Zig SHOWTIME can really help.
      </p>
      <p>
        From the point of view of the community, we need to make it easier for people
        interested in Zig to be excited and learn more about the language. 
        <br>
        Zig SHOWTIME is an opportunity to have fun during the live stream, 
        but also create something useful thanks to the fact that 
        <a href="https://www.youtube.com/channel/UC2EQzAewrC10KCDFSS4j-zA">
          all talks are archived on YouTube</a>.
      </p>
    </details>
    <details>
      <summary>I've never spoken publicly before.</summary>
      Don't worry, we accept first-time speakers and if you point out that you might
      need help, we'll be happy to support you. As of now we've aired 3 episodes and
      for a few of the speakers that was the first time they spoke publicly.
    </details>
    <details>
      <summary>I fear I might not be a good speaker.</summary>
      <p>
        If you're not an experienced speaker, chances are that your estimate of your 
        own speaking ability is imprecise. People tend to stress over their flaws and
        underestimate their strenghts much more than the public usually does.
      </p>
      <p>
        As the organizer of the show, I'm happy to have new speakers present even 
        (and especially) if they're not at the peak of their public speaking ability.
        To become a better speaker you need experience, and I'd be happy to support
        your growth if that means that as you improve, you will also give better talks
        in this show. In other words, from my point of view it's a rational investment.
      </p>
      <p>
        If you feel you would not be accepted by the public on the grounds of not being a native speaker / 
        gender / sexual orientation / race / ..., rest assured that the Zig community is welcoming
        to all kinds of people, and I'll be present throughout the whole presentation.
      </p>
    </details>
    <details>
      <summary>What are the prerequisites for speaking?</summary>
      <p>
        To be a speaker first of all you need to have a pair of headphones an a decent 
        microphone. The need for a good mic is self-evident, while the need for headphones
        (earbuds or any non-speaker device) is because during the Q&A part of your talk you
        will need to hear the question being posed to you without producing audio feedback
        and the usual noises that you can find in company meetings.
      </p>
      <p>
        While not strictly mandatory, it's also recommended to have a webcam of some sort (some 
        speakers have already used their phones for that purpose in the past) so that the public
        can see your face, especially during the Q&A. If you don't want to share your face, or
        you don't have a webcam, we can definitely find an alternative solution.
      </p>
      <p>
        Finally, you will probably share slides or some code. For that you will need a connection
        that can support that video stream. As of now, we're using 
        <a href="https://laplace.madeby.monster/">https://laplace.madeby.monster/</a>.
      </p>
    </details>
    <details>
      <summary>What can I speak about?</summary>
      <p>
        Clearly Zig SHOWTIME focuses on talks around Zig, but we're also open to talks about topics that
        are adjacent to Zig, like {systems, embedded, low-level} programming, WebAssembly, just to name 
        a few. If it's something that's worth knowing for a member of the Zig community, we want to hear about it.
      </p>
      <p>
        As for Zig-specific topics, we are interested in learning about your Zig project, be it a game,
        an application, a library, or even a PR that you sent to the main project. On top of that we also
        don't mind talks that explain some of the basics, like stack vs heap, how manual memory management 
        works, etc.
      </p>
      <p>
        There's also room for other less-conventional topics or formats (e.g. livecoding).
        I only ask that you try to package your talk in a 20-minute sesson (30 at most).
        If you want to tackle a problem that requires more time, please break it down into two
        separate talks. We love returning speakers, while &mdash; as you can imagine &mdash; 
        people's attention spans are farily narrow, especially when watching content on a screen.
      </p>
    </details>
    <details>
      <summary>How does the submission process work?</summary>
      <p>
        Fill the form linked at the bottom of this page. As soon as I can, I will get in 
        contact with you to schedule your talk. In the Google form you will be asked for your
        availability on either Saturday or Sunday at varying times. These are just indicative times,
        when it will come to schedule your talk I will work with you to make sure we can find a date
        and time that works for you (and the other speaker).
      </p>
      <p>
        The show doesn't air always at the same time. We change it depending on the needs of the speakers.
      </p>
    </details>
  </div>
  <div style="margin-top: 25px"></div>
  <a class="cf button" target="_blank" href="https://forms.gle/umLuHc8y2coqjaqAA">CALL FOR SPEAKERS</a>