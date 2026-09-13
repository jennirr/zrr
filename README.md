# Why Are We Here?

In 2026, AI can already generate working code from a short description. As a designer rather than a programmer, this makes the question of why I should still learn programming feel very real. If I can describe what I want and receive a usable script within seconds, spending time learning syntax can sometimes seem unnecessary.

I do not think the answer is that humans should continue writing every line of code by themselves. AI will almost certainly become better at doing that. For me, the value of learning programming is shifting somewhere else. What matters is not only whether I can produce code, but whether I can understand what the code is doing, recognise when something is wrong, and decide whether it actually matches my design intention.

I realised this more clearly while developing my undergraduate VR project in Unity. In the project, users discover and collect virtual plants. After collecting three plants, they can unlock and enter a virtual garden.

Described in one sentence, the interaction sounds simple. Today, I could ask an AI system to “write a Unity script that lets the user collect plants and unlock a garden after three have been collected,” and it could probably generate something reasonable very quickly.

But when I was actually building the experience, the interaction was much more specific than that sentence suggests. When exactly should a plant be considered collected? Can the same plant be collected twice? How does the system update the collection count? What feedback tells the user that the action has succeeded? What happens when the count reaches three? Does the script work correctly with the XR interaction system already used in the project?

These decisions are not only technical details. They directly affect the experience I am designing.

This is where I began to see a difference between **writing code** and **judging code**. AI can provide a script, but I still need enough programming knowledge to understand whether that script fits my project. If something does not work, I need to know whether the problem comes from a variable, an event, an object reference, or the interaction logic itself. Otherwise, my only option is to keep asking AI for another answer and hope that one of them works.

More importantly, code can technically work and still be wrong for the design. A plant might disappear when selected and the counter might increase correctly, but if the feedback is confusing or the timing feels wrong, the interaction is still unsuccessful. AI can help implement the behaviour, but I still have to decide what that behaviour should actually be.

Ada Lovelace raised a related idea in her notes on Charles Babbage's Analytical Engine. She discussed how the machine could carry out operations that humans knew how to instruct it to perform. The technology she was describing is completely different from today's generative AI, but I find the underlying question still relevant: producing an output is not the same as deciding what the output should be.

Programming also forces me to make vague ideas more precise. “Collecting a plant” sounds like one simple action from a designer's perspective, but once I try to build it, that idea becomes a series of conditions, events, states, and responses. Learning programming therefore helps me understand how an idea is translated into a working system.

Dylan Beattie's [*The Art of Code*](https://dylanbeattie.net/talks/the-art-of-code.html) also made me reconsider what programming can mean for a designer. He presents code not only as technical problem-solving, but also as a medium for creative exploration.

I do not think code will become my main artistic medium. I still see myself as a designer first. However, understanding programming changes the way I think about what is possible. Once I understand concepts such as variables, conditions, events, and systems, I can imagine interactions more precisely instead of treating technology as a black box that simply turns ideas into results.

For me, this is why I am still here.

I am not learning programming because I want to become faster than AI at writing code. I am learning it because I want to understand what I am asking the machine to do, question the answers it gives me, and remain responsible for the final experience.

As AI makes coding more accessible, producing something that works may become easier. But a working result is not automatically a good design. What becomes more important to me is judgement: being able to tell the difference between **code that simply runs and code that actually does what I mean**.

## References

Beattie, D. (2019). *The art of code*. Dylan Beattie. https://dylanbeattie.net/talks/the-art-of-code.html

Lovelace, A. A. (1843). Notes by the translator. In L. F. Menabrea, *Sketch of the Analytical Engine invented by Charles Babbage*. *Scientific Memoirs, 3*, 666–731. https://www.fourmilab.ch/babbage/sketch.html