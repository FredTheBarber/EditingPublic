﻿# Purpose of this Guide

The purpose of any style guide is help your text be consistent. Consistency is desirable since it makes your text easier to read. This style guide's goal is specifically is to help you achieve consistency in two areas:
1) Consistency of topics related to translation from Japanese, i.e., considerations of typography and word choice which you wouldn't really find if you were to read a general-purpose style guide like the MLA Handbook, the Chicago Manual of Style, or the AP Style Guide. Since it's not so widely-covered, this is a little more up-in-the-air, and I'll mostly be offering you options from which you should select one, and then consistently apply it.
2) Consistency of typography. There's going to be a whole lot of stuff about things like capitalization, spacing, and punctuation. This is dry material, but it's an important part of making your text as readable as possible. These rules are generally cut-and-dry and based on existing standards in other published works, and effectively descend from one of those style guides mentioned above (MLA, Chicago, AP). If you feel really motivated, go read one of those and offer me suggestions for improvements here.

One thing to note: as mentioned in 2), the goal isn't just consistency within your own text. We're also aiming to be consistent with existing standards of other published works. Keep that in mind when considering any deviation from a recommendation here.

This document is a template. You should make a copy of it for your project and customize it for your project (and feel free to delete this top section when you do so). It's also strongly recommended to create a Glossary for your project, to ensure everybody is translating/romanizing names the same way, which if you like you can add to the same customized document.


# JP Translation-Specific Style

## Honorifics

Typically, you should transliterate honorifics only if it's appropriate to your setting (e.g., if your VN takes place in a fictional country, there is little justification for keeping honorifics; if it takes place in a Japanese high school, there is somewhat more justification). Even if the setting justifies it, it's still recommended to jettison honorifics. Note that this decision is often complicated by Japanese VN writers' tendency to really enjoy writing scenes where characters make a big deal out of the way they refer to each other, especially with respect to the honorifics they use. If your VN has such scenes, you might simply keep the honorifics around to avoid dealing with rewriting those scenes into some semblance of sanity.

Once you've made a decision either way, the most important thing is to be consistent in applying it.

When transliterating honorifics, they should be set off from the name or form of address with a hyphen:
- Dearest Fred-chan, thank you for writing this guide.


## Other Sometimes-Untranslated Terms

Even if keeping honorifics, you should generally translate other Japanese words, even if some translations you may have read have chosen to keep them: senpai, sensei, onee-san, bento, and so forth are sometimes left untranslated. Generally speaking, just translate them. Again, whatever you do, do it consistently.


## Name Order

Take your pick, but again, be consistent (noticing a theme here?). Personally I find the English order, GivenName FamilyName, more natural and would recommend it by default for a new project, but it's not really a big deal. The fact that the resulting name order will be different from the voice over name order will not be confusing to people. Anybody who can listen to the VO carefully enough to realize that will also be able to understand what's being done.

Being consistent, once again, is the most important thing.


## Interjections And Non-Lexical Conversational Sounds

The convention for non-lexical conversational sounds (no I did not just google that; I googled it months ago) is to use translated Anglicized sounds, not transliterated sounds. For instance, "eh" may infrequently be an appropriate replacement for the Japanese "eh", but probably not as often as it comes up - probably usually you should go for something like "huh" or "what" instead. Mix it up, as appropriate given context and voice acting. How surprised are they? How deadpan is the delivery? "What", "Huh", and "Eh" are all viable translations with different nuances, and you should employ all of them as appropriate. And there are certainly more options which I haven't listed here. Similarly, "wai" => "yay", "uwaa" => "whoa" or "wow", and so forth.

Bottom line: you're not transliterating, you're translating, and that goes for things that aren't dictionary words just as much as it does for dictionary words.

List of common sounds and corresponding English:
* "Eh?" -> "Huh?/What?"
* "Wai!" -> "Yay!"
* "Uuu" -> "Aww"
* "Ita" -> "Ouch"/"Ow"
* "Uwah" -> "Whoa"

In addition to non-lexical conversational sounds, there are also Japanese onomatopoeia. Using English onomatopoeia where they exist is ideal: "Achoo", "Cough", "Hic", "Sob", "Gulp", "Slurp", etc.,

Where there are not equivalent English onomatopoeia, or where the Japanese is just a sound anyway, here are some options you have for translating, rather than transliterating:
* "Haah" or "Phew" for a sigh.
* "Mmm" for that sound when you wake up in the morning.
* "Hwaah" for a yawn (stick some more "a"s on that if you want, for really long yawns; maybe a "phwaaaaah" if the voice over has got enough of that sound going on).
* "Mwah" for a kiss (though you'll certainly need to vary it up a little for H scene sounds).
* "Gugugu" (or other angry noises) -> "Grrrr"

That'll cover most of your cases. For wilder things, try to transcribe what you hear in a way that looks reasonable in English, probably mostly relying on some combination of the letters A, H, M, N, and the diphthong PH (which generally looks more sound effecty than an F).


## Sound Effects

Unfortunately, that leaves Japanese sound effects and H scene noises, both of which are difficult. What does it sound like when someone stares at you? Nothing at all... unless you're Japanese.
For SFX which are voiced (jii is a VN staple), go non-literal and make up something reasonable if at all possible. Worst-case scenario, just straight-up write "Stare"; your readers have seen it before and will be forgiving. But seriously, try to make up something reasonable they'd say, even if it's "Grrrr...".
For SFX which are not spoken aloud, you have a lot more leeway. Feel free to replace with a colorful narration of the actual event, or even with just an appropriate English onomatopoeia. It's totally viable for a line to just say "Bang!" or "Pop.", and you should feel at liberty to just write out something with some flavor like: "I crashed to the floor."


## A sidebar on \*sound effects inside asterisks\*

Completely avoid using English sound effects inside asterisks. They are even less acceptable inside dialogue than they are inside narration, and dialogue is where you'll always be tempted to use them. Just don't do it, and you'll end up happier with the result.


## Wasei Eigo

Wasei Eigo (English words which have been co-opted into Japanese) are considered problematic because Japanese frequently uses these English words in ways which are nonsense if the English word is used directly in translation. Treat these words the same as any other Japanese word: translate them. Don't have any bias either towards or against using the wasei eigo word directly; just write whatever the sentence means in an appropriate, natural, readable way.


## On Japanese Quotation Marks

Japanese uses unique quotation marks. Assuming you aren't forced to keep them by your game engine (your game engine may need them to recognize certain sequences as dialogue vs. narration and render the script accordingly; usually it's not worth fighting the engine), it's recommended that you jettison them. Depending on the game, you then may have options:
1. Don't use any quotation marks at all.
1. Replace them with appropriate English quotation marks (single or double "straight" quotes; never "smart" quotes, since your game engine will almost certainly choke on those).

The former is my personal preference for purely ADV-style games, i.e., when each spoken dialogue line appears in a dedicated text box with a name captioned above it. The reason for this is that the purpose of a quotation mark is to indicate that a person is speaking - but when there is a name caption present, there is no such indication needed, and thus the quotation marks provide no additional information to the reader; they're just in the way.

The latter is fine, too, and is essential for NVL-style games (where narration and dialogue, sometimes from multiple characters, are all appended successively over a single frame; for a famous example, see Fate/Stay Night).


## On American Quotation Marks in Scripts

When using quotation marks:
* For outer quotations in spoken lines, use straight double quotes: "
* For inner quotations in spoken lines, use straight single quotes: '
Examples:
* "Come on, let's go."
* "But you said, 'Don't go in there.'"

But there are exceptions: when someone is speaking at a distance, it's appropriate to instead use single straight quotes for the outer quotation. This is pretty rare. One common instance is if the person in question is speaking over a telephone, walkie-talkie, etc. Another example would be in a scene depicting a flashback. And in the extremely rare circumstance that someone at a distance is quoting someone else, the inner quotation should correspondingly change to use double straight quotes.


## Quotation Marks and indentation

Japanese VNs always (as far as I know) use fixed-width characters. Morever, in ADV-style games, whenever a dialogue line runs onto more than one visible line, the second and subsequent lines are always (as far as I know) all indented by one character to match the indentation of the first line for the quotation mark. This gives it the look of a block quotation, and is rather prettier than not indenting. I think this is worth doing, if you're using a fixed-width font (and definitely not something you should do if you don't have a fixed-width font, since it will look even worse).


## Stuttering

Stuttering is common in VNs, where it is almost always used to show surprise. Sounds which are stuttered should generally be separated by a hyphen, even if the original Japanese uses some other punctuation, such as a comma, to separate them. When stuttering happens on the initial part of a sentence, as is most common, the repeated initial sound should be capitalized as well. Additionally, if the sound being stuttered is a digraph (two characters indicating a single sound), the entire digraph should be repeated.
Examples:
* "Wh-Who do you think you are?"
* "Th-That ain't necessarily so."
* "Why are you looking at m-me?"
* "I-I wasn't doing anything."

As a general note, stuttering can be way over-used in VNs... if you cut some of them out on the sly, you'll have my thanks, at least.


# General style (punctuation etc.)

## Use American English

As an American, I strongly recommend you use American English.


## Tense And Person

The original narration of events as they occur will most likely be written in the first-person and either the present tense or the past tense. It's recommended that you keep the tense of the original work, unless it is itself inconsistent (and the inconsistency doesn't follow some obvious rules). In that event, it's recommended that you ensure consistency of tense of current events across your narration, ignoring any tendency to do otherwise in the original.

The key point here is that you should make a conscious choice and stick with it. Be consistent. If you need to switch for any reason, make sure the rules are simple. Majo Koi was initially pretty confusing. We developed some rules, but they were complicated: the rhyme and reason of what we were doing was not obvious to readers of the prologue, so it looked sloppy, and in cases we simply made mistakes because the rules were complicated. Make your life and your readers' life easier: have simple rules, and follow them.


## Sidebar on Past Tense

Writing in past tense is pretty hard, actually, if you've never done it before. If you choose to narrate your VN in past tense, which I honestly think does read a little better than present tense, I suggest you read the following blog post and put the trick to use constantly while working, because it's very easy both to slip into present tense, and to accidentally put to use words and phrases that don't work in past tense: https://forums.fuwanovel.net/blogs/entry/1669-one-weird-trick-for-writing-in-past-tense/

## Spacing after a full sentence

Just like you'll see everywhere in this style guide, you should put exactly one space after a sentence. Not two. That goes for all writing these days, although when I was a youngster, they actually did teach us to use two spaces when typing. That was a holdover from the days when people used typewriters. We've come a long way since then. Put one space after a sentence.

## Capitalization of Titles

Titles which are sometimes capitalized (for instance, "Principal", "General", or "King") should follow these rules:
* Capitalize the title when it is used as a name.
* Lower-case it when it is not used like a name, and instead is used like the role in general.

Rule of thumb: if you wrote "the" or "my" or something along those lines before the title, then the title shouldn't be capitalized. Otherwise, it probably should.
Exception to the rule of thumb: "Your Majesty" (despite that "Your" in front of it) is itself a title, and is one which is always used like a name, and thus should be capitalized always.

Examples:
* "My princess must never know that I'm actually a yandere."
* "I shall quietly dispatch anyone who gets too close to Queen Alice."
* "You're coming to the principal's office with me, bub."
* "Oh my, Principal Tokeizaka, you really are the best."
* "I love you, Mom."
* "I love my dad."


## Numbers

I recommend the MLA style (or at least, the MLA style as I understand it).
* If n <= 100, write it out.
* Hyphenate compound numbers from twenty-one through ninety-nine.
* If n is a "round number", or a portion of it is a round number, write it, or that portion of it, out.
* Otherwise, write it with numerals. If a number should be written using many numerals, use a "," to split groups of three numerals. 

Examples:
three
twenty-five
one hundred
101
999,999
one million
101 billion

Exceptions: 
* The time of day should be written with numerals. "6 o'clock", "5:15", etc.,
* If the way the number is said requires some additional punctuation (frankly, the only example I know of for this is if it is a percentage or money), use numerals: e.g., "50%", "$5"


## Ellipses

An ellipsis should be exactly three periods. Not two. Not four. And also not the unicode ellipsis character. Three periods.
Generally, don't use multiple, sequential ellipses, even if the Japanese script likes to put two Unicode ellipsis characters all over the place; one set of three dots is fine.
The lone exception to the "single ellipsis" rule: when multiple lines of ellipses of different length are used to indicate passage of time, it's okay to use the same technique as the JP original (although you should move in multiples of three dots, even if, for instance, the original JP goes through multiples of six dots). 
Example:
* "..."
* "......"
* "........."
* "New scene!"


## Spacing around Ellipses

A leading ellipsis in a line SHOULD NOT have a space afterwards.
Example:
* "...Good morning"

An ellipsis in the middle of the line SHOULD have a space afterwards
Example:
* "But then... what should I do?"

An ellipsis SHOULD NOT have a space immediately preceding it.
* "But I don't even like pancakes..."


## Capitalization and the Ellipsis

After an ellipsis, the next sentence SHOULD be capitalized IF AND ONLY IF the subsequent phrase is a separate sentence from the original and is an independent clause (i.e., it can stand alone as a sentence).
Examples:
* "I think you're... cute."
* "You make me so mad... I'm going to kill you!"


## When to Use Ellipses

Japanese over-uses them, in all positions. Leading ellipses especially often seem unnecessary and can be deleted, particularly when the corresponding voiced line has no corresponding hesitation. That said, don't feel obligated to remove all or even most of them, but do look critically at every ellipsis and consider deleting it, just to declutter.

In spite of that, rarely, it may be reasonable to add an ellipsis yourself. This is an especially useful technique to show that one thought has been broken up across multiple lines, and even more so if the lines are interrupted.
Example:
* "I think you're..."
* "You think I'm what?"
* "...cute."


## Don't put commas at the ends of lines and then not capitalize the next line

I see this done rarely:

> I wanted to go see her,
> but I didn't have the confidence.

It looks sloppy and bad. Either you should turn these into two separate, indepenent clauses (and in fact, they already are; you can just use a period there and capitalize the "but" on the next line and call it a day), or you should add trailing and leading ellipses, like mentioned in the previous section.

## Hyphens, en-dashes and em-dashes

Don't use multiple successive hyphens or en-dashes to indicate cut off-speech or asides. The English punctuation to use in these situations is the em-dash, Unicode codepoint U+2014, which can be typed with alt+0151 or copied from the "Character Map" application. When properly encoded, the em-dash should be useable in your VN engine, even if it uses Shift-JIS encoding.

The em-dash should generally be used to indicate an interrupted thought. It should most commonly be used at the end of a sentence, when a character gets cut off mid-speech by another character, e.g.:
> "Yes, but what about your—"
> "Shut up!"

Typically, asides can be executed less obtrusively with commas, but if you really want to, you can use em-dashes for an aside in the middle of a sentence.
- "Back when I was younger — and only for a moment, mind you — I did consider it."

En-dashes are probably not applicable to your script at all. Don't worry about them.
Hyphens should be used for certain compound words, and will probably appear from time to time.
Example:
* "I laid the bouquet on the grave of my never-to-be-forgotten princess."

That said, if you find yourself frequently using hyphenated descriptions like the one immediately above, do be wary of whether you might be keeping too much of the Japanese syntax. It's a trap some people fall into. In English, that sort of grammatical construct is pretty unusual and calls a lot of attention to itself, but it is not so in Japanese, so frankly, even if the original is doing it, you probably shouldn't be. Only consider doing that sort of thing rarely, when you're looking to set the prose off a little.


## The Interrobang

Technically you should never use (or see) the interrobang, which is actually a single character with "?" and "!" overlaid. However, since people react melodramatically in VNs all the time, you'll probably see a fair number of sentences ending with both exclamation points and question marks.

Rule: when using "?!" at the end of a sentence to signify a surprised question, always use them in that order, not the opposite order.
Example: 
* "What did he just say?!"

If you really, really, want to, do the opposite order. I'm not going to come after you for doing so, though it will hurt my eyes a little. As always, just make sure that, whatever you do, you're consistent.


## Semicolon

Generally reserved for more intelligent characters, the semicolon should be used to separate two independent clauses in a single sentence. You should know what a comma splice is (if not, go look it up now). If you've written one, and you really feel like the line ought to be written that way, rather than separated by a conjunction or split into two sentences, because you believe the two independent clauses are so tightly logically connected, then that's probably a good time to use a semicolon. Careful you don't overuse them; I know I'm prone to doing so.


## Colon

The only common circumstance where you might want to use a colon is before writing a list of items which requires some separation from the rest of the sentence for clarity. There's a good example I wrote up above in this guide, actually:
* Using English onomatopoeia where they exist is ideal: "Achoo", "Cough", "Hic", "Sob", "Gulp", "Slurp", etc.,

That said, you may very well write your entire translated VN without using a colon. That's fine. There are other, rare cases where the big separation provided by a colon may be appropriate. If you do find yourself in one of them, just go read up on the usage of the colon as a punctuation mark somewhere else and make sure you're using it correctly. It's rarely necessary or beneficial, so you might as well simplify by avoiding it.


## Punctuation around quotation marks

Style guides consistently recommend that punctuation goes inside quotation marks, and also that when quoting, the quotation should be introduced with a comma. Frankly, I often think that the punctuation inside the quotation marks looks unnatural and incorrect. Fortunately, inner quotations are rare in VNs, except for single words (and even these can often be simply eliminated). In that case alone, I diverge from typical style guides and recommend you move the punctuation outside the inner quotation:
> "You're a shazzbot, Harry."
> "What the hell is a 'shazzbot'?!"

If you have a pretty long phrase inside a quotation, then it often looks natural to leave the punctuation inside, and you should do so.

And of course, there's a single ultimate simplifying option for this problematic area: just rework the sentence to avoid having the quotation next to the punctuation, or to avoid having the quotation at all.
> "You're a shazzbot, Harry."
> "What does that even mean?!"