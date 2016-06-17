#You Don't Know JS

突然想翻译一下，所以有了此文，学业不精、水平有限。

##Up & Going

###Forward

What was the last new thing you learned?

你最近学习的一件新事物是什么呢？

Perhaps it was a foreign language, like Italian or German. Or maybe it was a graphics editor, like Photoshop. Or a cooking technique or woodworking or an exercise routine. I want you to remember that feeling when you finally got it: the lightbulb moment. When things went from blurry to crystal clear, as you mastered the table saw or understood the difference between masculine and feminine nouns in French. How did it feel? Pretty amazing, right?

可能它是一门外语，比如意大利语或者德语。或者它可能是一个图像编辑器，比如Photoshop。或者是一门烹饪技术、木工手艺、保持健身。我希望你能想起最终掌握它的时候的感觉（脑补下小灯泡）。当事物从模糊不清到清晰明了，当你掌握了台锯的使用方法或者理解了法语中阳性名词与阴性名词的区别时，感觉如何？相当爽，是不是？

Now I want you to travel back a little bit further in your memory to right before you learned your new skill. How did that feel? Probably slightly intimidating and maybe a little bit frustrating, right? At one point, we all did not know the things that we know now and that’s totally OK; we all start somewhere. Learning new material is an exciting adventure, especially if you are looking to learn the subject efficiently.

现在我希望你能在记忆中探索地更深入一些。在你学会一项新技能之前感觉如何？可能有轻微的害怕还有点沮丧是不是？我们都一度了解我们现在掌握的事物，这样就OK了。我们都从某些地方开始我们的人生旅程。学习新的事物是一项令人激动的冒险，特别是当你想要高效地的学习这门课程的时候。

I teach a lot of beginner coding classes. The students who take my classes have often tried teaching themselves subjects like HTML or JavaScript by reading blog posts or copying and pasting code, but they haven’t been able to truly master the material that will allow them to code their desired outcome. And because they don’t truly grasp the ins and outs of certain coding topics, they can’t write powerful code or debug their own work, as they don’t really understand what is happening.

我教过大量的新手编码课程。上我的课程的学生们通常试着通过阅读博客或者复制粘贴代码自学比如HTML或者JavaScript这些课程，但是他们还没有真正掌握能够编码出他们预期输出结果的事物。而且因为他们没有真正掌握编码主题的来龙去脉，他们不能写出强力的代码或者debug他们的工作，因为他们无法真正理解发生了什么。

I always believe in teaching my classes the proper way, meaning I teach web standards, semantic markup, well-commented code, and other best practices. I cover the subject in a thorough manner to explain the hows and whys, without just tossing out code to copy and paste. When you strive to comprehend your code, you create better work and become better at what you do. The code isn’t just your job anymore, it’s your craft. This is why I love Up & Going. Kyle takes us on a deep dive through syntax and terminology to give a great introduction to JavaScript without cutting corners. This book doesn’t skim over the surface, but really allows us to genuinely understand the concepts we will be writing.

//TODO序言翻译一下性价比不是很高，之后翻译（留坑一）

Because it’s not enough to be able to duplicate jQuery snippets into your website, the same way it’s not enough to learn how to open, close, and save a document in Photoshop. Sure, once I learn a few basics about the program I could create and share a design I made. But without legitimately knowing the tools and what is behind them, how can I define a grid, or craft a legible type system, or optimize graphics for web use. The same goes for JavaScript. Without knowing how loops work, or how to define variables, or what scope is, we won’t be writing the best code we can. We don’t want to settle for anything less -- this is, after all, our craft.

The more you are exposed to JavaScript, the clearer it becomes. Words like closures, objects, and methods might seem out of reach to you now, but this book will help those terms come into clarity. I want you to keep those two feelings of before and after you learn something in mind as you begin this book. It might seem daunting, but you’ve picked up this book because you are starting an awesome journey to hone your knowledge. Up & Going is the start of our path to understanding programming. Enjoy the lightbulb moments!

###Preface（前言）

I'm sure you noticed, but "JS" in the book series title is not an abbreviation for words used to curse about JavaScript, though cursing at the language's quirks is something we can probably all identify with!

From the earliest days of the web, JavaScript has been a foundational technology that drives interactive experience around the content we consume. While flickering mouse trails and annoying pop-up prompts may be where JavaScript started, nearly 2 decades later, the technology and capability of JavaScript has grown many orders of magnitude, and few doubt its importance at the heart of the world's most widely available software platform: the web.

But as a language, it has perpetually been a target for a great deal of criticism, owing partly to its heritage but even more to its design philosophy. Even the name evokes, as Brendan Eich once put it, "dumb kid brother" status next to its more mature older brother "Java". But the name is merely an accident of politics and marketing. The two languages are vastly different in many important ways. "JavaScript" is as related to "Java" as "Carnival" is to "Car".

Because JavaScript borrows concepts and syntax idioms from several languages, including proud C-style procedural roots as well as subtle, less obvious Scheme/Lisp-style functional roots, it is exceedingly approachable to a broad audience of developers, even those with just little to no programming experience. The "Hello World" of JavaScript is so simple that the language is inviting and easy to get comfortable with in early exposure.

While JavaScript is perhaps one of the easiest languages to get up and running with, its eccentricities make solid mastery of the language a vastly less common occurrence than in many other languages. Where it takes a pretty in-depth knowledge of a language like C or C++ to write a full-scale program, full-scale production JavaScript can, and often does, barely scratch the surface of what the language can do.

Sophisticated concepts which are deeply rooted into the language tend instead to surface themselves in seemingly simplistic ways, such as passing around functions as callbacks, which encourages the JavaScript developer to just use the language as-is and not worry too much about what's going on under the hood.

It is simultaneously a simple, easy-to-use language that has broad appeal, and a complex and nuanced collection of language mechanics which without careful study will elude true understanding even for the most seasoned of JavaScript developers.

Therein lies the paradox of JavaScript, the Achilles' Heel of the language, the challenge we are presently addressing. Because JavaScript can be used without understanding, the understanding of the language is often never attained.

####Mission

If at every point that you encounter a surprise or frustration in JavaScript, your response is to add it to the blacklist, as some are accustomed to doing, you soon will be relegated to a hollow shell of the richness of JavaScript.

While this subset has been famously dubbed "The Good Parts", I would implore you, dear reader, to instead consider it the "The Easy Parts", "The Safe Parts", or even "The Incomplete Parts".

This You Don't Know JavaScript book series offers a contrary challenge: learn and deeply understand all of JavaScript, even and especially "The Tough Parts".

Here, we address head on the tendency of JS developers to learn "just enough" to get by, without ever forcing themselves to learn exactly how and why the language behaves the way it does. Furthermore, we eschew the common advice to retreat when the road gets rough.

I am not content, nor should you be, at stopping once something just works, and not really knowing why. I gently challenge you to journey down that bumpy "road less traveled" and embrace all that JavaScript is and can do. With that knowledge, no technique, no framework, no popular buzzword acronym of the week, will be beyond your understanding.

These books each take on specific core parts of the language which are most commonly misunderstood or under-understood, and dive very deep and exhaustively into them. You should come away from reading with a firm confidence in your understanding, not just of the theoretical, but the practical "what you need to know" bits.

The JavaScript you know right now is probably parts handed down to you by others who've been burned by incomplete understanding. That JavaScript is but a shadow of the true language. You don't really know JavaScript, yet, but if you dig into this series, you will. Read on, my friends. JavaScript awaits you.

####Summary

JavaScript is awesome. It's easy to learn partially, and much harder to learn completely (or even sufficiently). When developers encounter confusion, they usually blame the language instead of their lack of understanding. These books aim to fix that, inspiring a strong appreciation for the language you can now, and should, deeply know.

Note: Many of the examples in this book assume modern (and future-reaching) JavaScript engine environments, such as ES6. Some code may not work as described if run in older (pre-ES6) engines.

###Chapter 1: Into Programming

Welcome to the You Don't Know JS (YDKJS) series.

欢迎来到你不懂JS（YDKJS）系列。

Up & Going is an introduction to several basic concepts of programming -- of course we lean toward JavaScript (often abbreviated JS) specifically -- and how to approach and understand the rest of the titles in this series. Especially if you're just getting into programming and/or JavaScript, this book will briefly explore what you need to get up and going.

Up & Going章节是编程的一些基础概念的介绍－当然，我们特别地学习倾向于JavaScript（通常简称JS）－以及如何处理和理解这一系列的其它标题。尤其是如果你刚刚进入编程或者JavaScript领域，这本书将会简要探讨为了变得Up & Going你需要什么。

This book starts off explaining the basic principles of programming at a very high level. It's mostly intended if you are starting YDKJS with little to no prior programming experience, and are looking to these books to help get you started along a path to understanding programming through the lens of JavaScript.

这本书从一个很高的层次出发对编程的基本原理进行解释。它主要是为了如果你在开始阅读YDKJS时几乎没有任何编程经验，而且你在寻找这些书籍来帮助你开始沿着一条路线通过JavaScript这个镜头来理解程序设计。

Chapter 1 should be approached as a quick overview of the things you'll want to learn more about and practice to get into programming. There are also many other fantastic programming introduction resources that can help you dig into these topics further, and I encourage you to learn from them in addition to this chapter.

第一章应该被当作一个你想要了解更多并且练习来进入编程世界的事物的快速的概述。还有很多其他的能够帮助你深入挖掘这些主题的精彩的编程介绍资源，而且我鼓励你除了本章之外从他们那里学习。

Once you feel comfortable with general programming basics, Chapter 2 will help guide you to a familiarity with JavaScript's flavor of programming. Chapter 2 introduces what JavaScript is about, but again, it's not a comprehensive guide -- that's what the rest of the YDKJS books are for!

一旦你对一般的编程基础感到舒适，第二章将会帮助引导你熟悉JavaScript的特点。第二章介绍了什么是JavaScript，但是它不是权威指南－－这就是YDKJS这本书剩下的部分的内容！

If you're already fairly comfortable with JavaScript, first check out Chapter 3 as a brief glimpse of what to expect from YDKJS, then jump right in!

如果你已经能够相当舒适地使用JavaScript，首先翻到第三章简单瞥一眼看看你期待从YDNJS中得到什么，然后跳进去吧！

####Code

Let's start from the beginning.

让我们从头开始。

A program, often referred to as source code or just code, is a set of special instructions to tell the computer what tasks to perform. Usually code is saved in a text file, although with JavaScript you can also type code directly into a developer console in a browser, which we'll cover shortly.

一个程序通常指的是源代码或者只是代码，它是一系列特殊指令来告诉电脑要运行什么命令。通常代码是保存在文本文件中的，尽管使用JavaScript的时候你也可以直接在浏览器的开发者控制台中敲代码，这个我们会在稍后介绍。

The rules for valid format and combinations of instructions is called a computer language, sometimes referred to as its syntax, much the same as English tells you how to spell words and how to create valid sentences using words and punctuation.

指令的有效格式和组合的规则称作伊恩计算机语言，有时也被称为它的语法，就像英语告诉你如何拼写单词以及如何用单词和标点符号创造有效的句子一样。

//TODO第一章后面有点简单，找时间翻译（留坑二）

###Chapter 2: Into JavaScript

In the previous chapter, I introduced the basic building blocks of programming, such as variables, loops, conditionals, and functions. Of course, all the code shown has been in JavaScript. But in this chapter, we want to focus specifically on things you need to know about JavaScript to get up and going as a JS developer.

在之前的章节中，我介绍了程序的构造快，比如变量，循环，条件和方法。当然所有显示的代码都已经在JavaScript中。但是在这一章，我们想要尤其专注于作为一名JS开发人员为了变得Up & Going需要知道的关于JavaScript的一些知识。

We will introduce quite a few concepts in this chapter that will not be fully explored until subsequent YDKJS books. You can think of this chapter as an overview of the topics covered in detail throughout the rest of this series.

在这一章中我们将要介绍大量的的概念不过不会探索到JavaScript的全部直到后面的YDKJS。你可以把这一章概括为这个系列的其他部分的内容的详细介绍。

Especially if you're new to JavaScript, you should expect to spend quite a bit of time reviewing the concepts and code examples here multiple times. Any good foundation is laid brick by brick, so don't expect that you'll immediately understand it all the first pass through.

尤其是如果你是JavaScript初学者，你应该花点时间多次回顾这些概念和代码示例。任何好的地基都是一块一块砖堆砌起来的，所以不要期待你会第一次就立即搞懂这些。

Your journey to deeply learn JavaScript starts here.

你的旅程就是从这里开始深入地学习JavaScript。

Note: As I said in Chapter 1, you should definitely try all this code yourself as you read and work through this chapter. Be aware that some of the code here assumes capabilities introduced in the newest version of JavaScript at the time of this writing (commonly referred to as "ES6" for the 6th edition of ECMAScript -- the official name of the JS specification). If you happen to be using an older, pre-ES6 browser, the code may not work. A recent update of a modern browser (like Chrome, Firefox, or IE) should be used.

小贴士：正如我在第一章中所说的，你应该在阅读本章和工作的过程中确切的自己尝试所有代码。需要注意的是这里的部分代码假定了在撰写本文时在JavaScript最新版本中介绍了的功能已经可以使用（通常被称作“ES6”作为ECMAScript的第六版－－JS规范的官方命名）。如果你碰巧在使用一个老版本的、ES6之前的浏览器，这些代码可能不能正常工作。最近更新的现代浏览器（比如Chrome，Firefox，IE）应该是可以使用的。



