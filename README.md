#### Started a project at SpawnFest 2022

SpawnFest 2022 was fun. Setting aside this amount of time to explore something new is a blast.

Sadly, there's nothing to see yet. Ideally one would publish some code, so I am DNF in this contest (did not finish).

This repo will be archived at the end of the contest, so I'll instead publish the project that *started* at this SpawnFest into a repo I'll make under the name [festigial](github.com/mrluc/festigial). (Like ['vestigial'](https://www.merriam-webster.com/dictionary/vestigial): 'remaining in a form that is small or imperfectly developed and not able to function')

Here's my idea, and where I got stuck -- in case I can't finish it, or someone wants to do it better.

My idea was that I wanted to take Dockyard's recent great idea, LiveView Native, and run with it in a different direction -- implementing a new renderer for LiveView in Rust, even a very limited one. For the proof-of-concept, I'd thought of doing this via plugging virtual dom events into an existing analagous library, like a 3d engine's scene graph (prior art: the many alternative React renderers).

There's not a layer to build this on just yet, but there *are* a few phx channel libraries and virtual dom implementations in Rust, so how hard could it be?

Turns out, I got stuck way earlier than I'd have guessed: on the move from "phx channels" to "phx *liveview* channels". I've spent the time I could get (Saturday afternoon through Sunday morning) between Rust, WireGuard, and LiveView, with forks of a few Phoenix-related Rust repos. As of this writing, I'm still fighting to get LiveViews to mount against my client!

If you're like me, that sounds like a *good time*, and it is! It's pretty fun. There's no way I wrap anything up in time for the SpawnFest deadline, though.

Till next time! 👋 And kudos to the others who also came in without a fully-formed idea and who were able to wrap up something useful and/or cool.
