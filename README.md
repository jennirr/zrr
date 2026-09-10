# Why Are We Here?

## If AI Can Write the Code

In 2026, AI can already generate working code from a short description. As a designer, this makes the question of why I should still learn programming feel very real. I do not expect to become a professional programmer, and I probably will not need to write every line of code myself in the future.

However, I still think learning programming matters because **generating code is not the same as knowing whether the code actually does what I want**.

For me, the purpose of learning programming is therefore changing. It is becoming less about memorising syntax or competing with AI at writing code, and more about being able to understand, question, and judge what the machine produces.

## When a Prompt Is Not Enough

I realised this while developing my undergraduate VR project in Unity. In the project, users could discover virtual plants, collect them, and eventually unlock a virtual garden after collecting three plants.

The interaction sounds simple when described in one sentence. Today, I could ask an AI system:

> Write a Unity script that lets a user collect virtual plants and unlock a garden after collecting three.

AI could probably generate a script within seconds. But the actual interaction contains many decisions that are missing from that sentence.

When exactly should a plant be considered collected? Can the same plant be collected twice? What kind of visual or sound feedback should appear after collection? Where should the number of collected plants be stored? What should happen at the exact moment when the count reaches three? Most importantly, does the generated script actually work with the XR interaction system already used in my Unity project?

These questions are not simply technical details. They affect the experience I am designing.

A piece of code can run successfully and still produce an interaction that feels wrong. AI may be able to generate the implementation, but I still need to define what the system should actually do.

## Writing Code and Judging Code

This is why I think the difference between **writing code** and **judging code** is becoming more important.

If AI generates a script that does not work, I need enough programming knowledge to understand whether the problem comes from a variable, an event, an object reference, or the interaction logic itself. Without that understanding, I can only keep asking AI to try again and hope that one of its answers works.

More importantly, I also need to recognise situations where the code technically works but does not match my design intention.

Ada Lovelace raised a related question in her notes on Charles Babbage's Analytical Engine. She argued that the machine could perform operations that humans knew how to instruct it to perform. Although today's generative AI is very different from Babbage's machine, I think the underlying problem is still relevant: producing an output is not the same as deciding what the output should be.

Her writing also suggests that translating an idea into a form a machine can process requires us to organise that idea more precisely. For me, this is one reason programming remains useful. It forces a vague design intention to become a set of behaviours, conditions, and relationships.

## What Programming Means to Me Now

Dylan Beattie's [*The Art of Code*](https://dylanbeattie.net/talks/the-art-of-code.html) presents programming as more than technical problem-solving. Through examples of generative art, live coding, and experimental programs, he shows that code can also become a creative medium.

I do not necessarily see code becoming my main artistic medium. I am still a designer first. However, understanding programming changes what I am able to imagine and how precisely I can describe an interactive experience.

Learning what variables, events, conditions, and systems can do gives me more ways to think about interaction. In this sense, programming does not only help me realise an idea after I have designed it. It can also influence the way I form the idea in the first place.

## So Why Am I Here?

I am not learning programming because I believe humans must continue writing every line of code themselves. AI will probably become much faster and more capable at that task.

I am learning programming because I do not want to lose the ability to understand what I am asking for, question what AI gives me, and decide whether the result actually serves my design.

As coding becomes easier to access, more people will be able to produce technically functional results. But a working result is not automatically a good design.

For me, the skill that survives is judgement. I may write less code myself in the future, but I still want to understand enough programming to tell the difference between **code that simply runs and code that actually does what I mean**.

## References

Beattie, D. (2019). *The art of code*. Dylan Beattie. https://dylanbeattie.net/talks/the-art-of-code.html

Lovelace, A. A. (1843). Notes by the translator. In L. F. Menabrea, *Sketch of the Analytical Engine invented by Charles Babbage*. *Scientific Memoirs, 3*, 666–731. https://www.fourmilab.ch/babbage/sketch.html