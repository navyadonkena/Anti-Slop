# **Anti-Slop**

## **A Library of AI Writing Patterns**

Every writer has a distinct way of expressing themselves. Take authors like Agatha Christie or William Shakespeare, for example. When you read enough of their work, you start picking up on their story telling techniques, the way they build their narratives, and develop stories. Eventually, you develop an instinct for their writing and can recognize it even without seeing their name. 

Writers treat their writing as a craft. With every story or piece of content, they draw from their personal experiences, try to understand their audience, and experiment with different ways of communicating their ideas. They pay attention to what resonates with readers and which stories hold their attention. 

When they sense their audience is losing interest, or their stories are starting to feel predictable, they explore different ways to approach a subject. Sometimes, they even rethink the direction of their writing altogether. Their style keeps evolving with every story they write. 

Of course, there are different forms of writing beyond creative writing. It includes business writing, technical writing, journalism, academic writing etc,. The purpose and audience have changed over time, as have the mediums through which we communicate. A writer's desire to keep getting better at their craft has always remained constant. They've learnt to adapt their style to the context, pay attention to what's resonating with their audience, and keep refining how they communicate. They also experiment with different approaches, explore new styles, and challenge themselves to find better ways of expressing their ideas.

Generative AI presents an interesting contradiction. LLMs are trained on enormous volumes of text from different authors, genres, countries, disciplines, and writing styles. Yet, despite all this diversity, their outputs often feel surprisingly similar and monotonous.

Certain words, phrases, sentence constructions, transitions, and stylistic choices keep appearing across different subjects and formats. The individual patterns may differ between models, but the underlying tendency towards formulaic writing remains remarkably similar.

When generative AI first became widely accessible, writers, marketers, and businesses were quick to accelerate content production. A year or two later, the excitement started to wear off and novelty gave way to fatigue. People began noticing familiar patterns, vocabulary, predictable phrasing, sentence constructions, and repetitive ways of expressing ideas.  

These patterns are not necessarily exclusive to AI because many of them are perfectly legitimate expressions in human writing. The problem is their disproportionate frequency, repetitive use, and predictable placement in AI-generated content.

## **What is Anti-Slop Library?** 

Anti-Slop is an evolving reference library that documents these patterns, explains how they manifest in writing, and identifies their variations across language models.

The library covers two kinds of patterns:

* **Common AI writing patterns:** Words, phrases, expressions, sentence constructions, and stylistic tendencies that appear across multiple AI models, including Claude, GPT, Gemini, and others.  
* **Model-specific writing patterns:** Distinctive writing tics and tendencies associated with individual models, model families, or specific model versions.

New models, updates, and changes in training or post-training can introduce new patterns, reinforce existing ones, or change how frequently certain patterns appear. As a result, AI writing patterns are not static.

This document is intended to be a continuously maintained and periodically updated resource. New patterns, variations, and model-specific observations will be added as they emerge. Existing entries will be reviewed and refined to reflect changes in model behaviour, new research, and further observations.

The objective is not to eliminate particular words or expressions from writing, nor to label every occurrence as an indication of AI-generated content. It is to recognise repetitive tendencies, understand why they occur, and build a more comprehensive understanding of how language models write.

---

## **Pattern 1: Contrastive Parallelism/Mirrored Contrast**

Contrastive parallelism is a rhetorical construction that places two ideas, actions, qualities, or outcomes against each other to emphasise a distinction. It often follows a structure in which the AI first introduces or rejects one idea, then presents another as the alternative, correction, or more important point.

The construction can use explicit contrast markers such as not, rather than, and instead of. It can also rely on parallel phrasing, where two parts of a sentence mirror each other.

### **Common forms and variations**

|  Form | Patterns/ Examples |
| ----- | ----- |
| Direct negation and replacement | It's not X. It's Y It’s X, not Y. This isn't about X. It's about Y Not X, but Y We're not doing X. We're doing Y |
| Rather-than constructions | Rather than X, we Y Choose X rather than Y Focus on X rather than Y |
| Instead-of constructions | Instead of X, we Y Instead of treating it as a liability, consider it an asset  |
| Short, compressed contrasts  | In use, not demoed Liability, not an asset Prevention, not reaction Built for production, not just experimentation |

## **Pattern 2: Teaser Sentences/Delayed Context**

**Also known as:** False suspense, empty hook. 

Teaser sentences are broad, often vague statements that hint at an idea, problem, development, or revelation without actually explaining it.

They often sound like they're setting up something important. But many of them do little to hook the reader or add meaning. Instead, they delay the context, make readers wait for the actual point, and use up their attention without giving them much in return.

### **Common forms and variations**

|  Form | Patterns/ Examples |
| ----- | ----- |
| Here’s the thing ….  | Here's the thing... And here's the thing... Here's what... Here's why... Here's the catch... Here's the interesting part... Here's what you need to know... Here's where it gets interesting... |
| The real X …..  | The real challenge is... The real opportunity is... The bigger question is... The real problem was... The actual issue is... The bigger picture... The real story is... |
| This is where X ….  | This is where X comes in This is where X matters This is where things change This is where it gets interesting This is where the difference becomes clear This is where the real work begins |
| That’s when X….  | That's when X happens ….  That's when things changed …..  That's when everything clicked ….  That's when we realised ... And that's when ... That's when the real work began …  |
| X told a different story …  | X told a different story The numbers told a different story The data revealed something else The results painted a different picture The reality was quite different X didn't tell the whole story There's more to X than meets the eye  |
| The real question is ….  | The real question is... The question isn't whether X, but Y. The question now becomes... The bigger question is... What happens when X? The question worth asking is... |
| X needs more than Y | X needs more than Y. It needs Z The demo needs more than data. It needs context The demo is the easy part. Deploying it is the hardest part  |

### **Editorial guidance**

* Is this sentence communicating an actual idea, or just announcing one?  
* Does it create genuine curiosity, or simply delay the context?  
* Can the next sentence stand on its own without this opening?  
* Does the sentence introduce a meaningful transition between two ideas?  
* Is this construction appearing repeatedly throughout the article?

## **Pattern 3: Contextually Incongruent Wording**

Contextually incongruent wording refers to the use of words or expressions that are grammatically correct but don't align with the specific meaning, function, or context in which they're used.

LLMs sometimes select words based on their semantic similarity to the intended concept, rather than whether they are the most appropriate choice in that particular context.

However, words aren't interchangeable just because they have similar meanings or associations. Every word carries:

*  A specific function  
* A defined scope  
* Typical collocations (the words it naturally appears with)  
* An underlying cause-and-effect relationship 

For a word to fit naturally, its meaning must align with the subject, the action being described, and the surrounding technical or operational context.

For example, *accuracy* and *reliability* are related concepts, but they don't describe the same thing. Accuracy concerns how close a result is to the correct value. Reliability concerns how consistently a system performs as expected. Using *accuracy* to describe overall system reliability can therefore misrepresent what is actually being discussed.

Similarly, *feasible* describes whether something can be done under given conditions. It isn't necessarily the right word when discussing whether an implementation is practical, efficient, or straightforward.

### **Examples**

| Expression used in AI-generated content | Why it doesn't fit naturally | More appropriate alternatives |
| ----- | ----- | ----- |
| "Touches the billing system" | *Touches* doesn't specify what interaction takes place between the two systems. | Integrates with / reads from / writes to / connects to the billing system |
| "Is this feasible?" (when discussing practical implementation) | *Feasible* establishes whether something is possible, but doesn't necessarily address compatibility with the existing setup or implementation constraints. | Will this work with your current setup? / Can this be implemented with the existing infrastructure? |
| "The right path" (when discussing an implementation decision) | *Path* is broad and doesn't identify whether the reference is to a method, technical approach, or available option. | The right approach / the right implementation option / the appropriate method |
| "Commit on a six-month horizon" | *Commit on a horizon* is an unnatural collocation. A horizon describes a planning period, not the point at which someone makes a commitment. | Commit to a six-month timeline / Plan over a six-month period |

### **Editorial guidance**

* Is this the word a subject-matter expert would naturally use here?  
* Does the word accurately describe the action or concept?  
* Is the expression commonly used in this particular domain?  
* Is the writer choosing a sophisticated-sounding word where a simpler one would be clearer?  
* Does the sentence communicate a specific action, or rely on generic business language?  
* Would replacing the expression make the sentence more precise?

## **Pattern 4: Anthropomorphic AI Language**

Anthropomorphic AI language refers to the use of human-like actions, abilities, or characteristics when describing AI models, software, systems, or other non-human entities.

In AI-generated content, this often appears when models describe technical processes using verbs associated with human perception, understanding, memory, reasoning, or communication.

For example, phrases such as *“the dashboard tells you what happens next”* attribute human-like abilities to systems that perform computational tasks.

### **Common forms and variations**

| Form | Examples |
| ----- | ----- |
| Attributing human understanding | AI understands your business The model understands your customers |
| Attributing perception | AI sees patterns The system looks at your data |
| Attributing communication | Models tell you what happens next AI explains what your data means |
| Attributing memory | The model remembers your preferences AI never forgets your instructions |
| Attributing decision-making | AI decides which leads matter most The model chooses the best response |

### **Editorial guidance**

* Does the verb describe an actual computational operation?  
* Is the sentence attributing human perception, awareness, or understanding to a system?  
* Can the underlying operation be described more precisely?  
* Does the expression exaggerate what the product or model can actually do?  
* Would a technical reader interpret the statement differently from its intended meaning?

### **Not every human-like expression is incorrect**

Anthropomorphic language isn't automatically bad. Expressions such as *the system remembers your preferences* can be acceptable shorthand when the system genuinely stores and retrieves that information.

Likewise, *AI sees patterns* is widely understood as figurative language. It may be perfectly acceptable in introductory or conversational content.

The problem arises when human-like descriptions replace technical accuracy or create misleading expectations about system capabilities.

**Core editorial principle:** Describe what the system actually does, rather than attributing human abilities to it.

## **Pattern 5: Rule-of-Three**

**Also known as:** Tricolon, list-of-three, Triadic phrasing, Three-item list stacking

Three-item list stacking refers to the repeated use of three words, phrases, qualities, or ideas in succession to create a sense of completeness, emphasis, or rhythm. The construction often appears in a parallel structure, where three items follow the same grammatical pattern.

### **Common formulas and variations**

| Formula | Structure | Examples |
| ----- | ----- | ----- |
| **Noun triad** | *\[noun\], \[noun\], and \[noun\]* | Tools, training, and documentation Needs, challenges, and goals Cost, security, and scalability |
| **Adjective or comparative triad** | *\[adj\], \[adj\], and \[adj\]* / *faster, more \[adj\], and more \[adj\]* | Innovative, transformative, and groundbreaking Faster, more accurate, and more efficient |
| **Verb-phrase triad** | *\[verb\] X, \[verb\] Y, and \[verb\] Z* | Streamline workflows, reduce costs, and boost productivity Attract, engage, and convert  |
| **Clause triad** | *\[subject\] \[verb\], \[subject\] \[verb\], and \[subject\] \[verb\]* | Teams move faster, leaders see more, and customers stay longer |
| **Sentence triad** | *\[Short sentence\]. \[Short sentence\]. \[Short sentence\].* | It saves time. It cuts costs. It scales with you |
| **Negation triad** | *No X. No Y. Just Z.* | No spreadsheets. No guesswork. Just answers |
| **Range sweep (merism)** | *From X to Y* *From X to Y to Z* | From startups to enterprises From strategy to execution to measurement |
| **Structural triad** | Three bullets, three takeaways, three sections, or three benefits presented as a recurring structure. | A blog where every H2 has exactly three bullet points. |
| **Stacked triads** | Several triads in a row, or a triad nested inside another triad. | Our platform helps sales, marketing, and support teams capture, organise, and act on customer data faster, smarter, and at scale |
| **Padded lists** | The same list-building tendency extended to four or five generic items. | Speed, accuracy, security, scalability, and ease of use  |

### **Variation: Exhaustive Listing**

Another variation of this pattern is exhaustive listing, where the AI stacks four, five, or more words, phrases, or ideas in succession.

Instead of limiting the list to three items, the sentence keeps adding related terms to create an impression of completeness. This often results in long, padded lists where some items overlap in meaning or add very little information.

**Examples:**

* "Speed, accuracy, security, scalability, and ease of use."  
* "Planning, coordination, execution, monitoring, and optimisation."  
* "Identify, analyse, evaluate, prioritise, implement, and measure."  
* "Improve visibility, efficiency, productivity, collaboration, and performance."

### **Editorial suggestion**

When you encounter these lists, circle back to the original intent and scope of the sentence. What exactly are you trying to communicate? Does every item contribute something meaningful, or are some included simply to make the statement sound comprehensive?

Eliminate anything that isn't necessary. If the list contains several distinct ideas that need explanation, split the sentence into smaller parts or group related items together.

## **Pattern 6: Vagueness** 

Vagueness refers to the use of words, expressions, or references that lack sufficient specificity to communicate a clear meaning.

In AI-generated content, this often appears through vague pronouns, broad descriptors, undefined terms, and subjective evaluations. The sentence may be grammatically correct and sound natural, but the reader is left to infer what is being discussed.

Two common forms are vague referents and vague evaluations: 

### **1\. Vague referents**

Vague referents occur when a word or phrase points to something without clearly identifying what that something is. The reader has to guess what the sentence refers to, often because the surrounding context doesn't provide enough information.

| Expression | What's unclear? | More specific alternative |
| ----- | ----- | ----- |
| "Most of these..." | Most of which items, tools, providers, or examples? | Most proxy providers in this comparison... |
| "The good ones..." | What makes them good? Which ones are being discussed? | Providers with residential IP pools across multiple countries... |
| "It is the right one..." | Which option is being recommended? | This provider is the better fit for high-volume scraping... |
| "Whatever runs..." | What exactly is running? A script, application, process, or service? | Whichever application sends the requests... |

**Recognition cues:**

* Pronouns or demonstratives without a clear antecedent: *this, that, these, those, it*.  
* Broad references such as *the workflow, the process, the outcome, the approach*.  
* Expressions such as *most of these, the good ones, the right one* without a clearly established reference.

### **2\. Vague evaluation**

Vague evaluation occurs when AI uses subjective or broad evaluative terms without specifying the criteria behind the assessment.

Words such as *better, meaningful, valuable, effective, worthwhile,* and *significant* can make a statement sound conclusive without explaining what is being evaluated or why.

| Expression | What's unclear? | More specific alternative |
| ----- | ----- | ----- |
| "Is the workflow worth it?" | Worth it in terms of cost, time, effort, or results? | Does the workflow reduce manual effort enough to justify its implementation cost? |
| "A better solution" | Better in terms of performance, cost, reliability, or usability? | A solution with lower latency and fewer failed requests |
| "A more effective approach" | Effective at achieving which objective? | An approach that reduces IP blocks during large-scale scraping |

**Recognition cues:**

* Subjective evaluations without supporting criteria.  
* Comparative terms without a clear basis for comparison.  
* Words such as *better, meaningful, valuable, significant,* and *effective* used without explaining what they mean in context.

**Note:** Vagueness isn't the same as contextual incongruence. Contextual incongruence is about choosing a word that doesn't fit its context. Vagueness is about wording that doesn't provide enough information in the first place. 

## **Pattern 7: Conjunction-led Sentence Openers**

This pattern involves repeatedly starting sentences with conjunctions, pronouns, demonstratives, and transition words such as *and, but, because, that, this,* and *that's why*.

These openings aren't inherently incorrect. Starting a sentence with *and, but,* or *because* is perfectly acceptable in many contexts. The issue is their repetitive or formulaic use, particularly when they become a predictable way to connect ideas or introduce explanations.

### **Common forms**

| Opening | Example |
| ----- | ----- |
| And | "And that's where proxy rotation becomes useful." |
| But | "But there's another factor to consider." |
| Because | "Because not every provider offers the same level of coverage." |
| That | "That makes it easier to manage multiple sessions." |
| That's why | "That's why choosing the right provider matters." |
| This | "This gives businesses greater control over their requests." |
| Unlike | "Unlike residential proxies, datacenter proxies use server-hosted IPs." |
| Together | "Together, these features provide a more reliable solution." |
| Most | "Most providers offer multiple pricing plans." |
| Many | "Many businesses rely on rotating proxies for scraping." |

## **Pattern 8: Repetitive Sentence Openings**

This pattern occurs when multiple sentences begin with the same word, phrase, or grammatical construction. AI-generated content often repeats familiar sentence openings such as *Most, This, By,* and *For*. Even when the sentences communicate different ideas, repeating the same opening structure creates a predictable rhythm.

### **Formulas**

| Formula | Structure | Examples |
| ----- | ----- | ----- |
| **Repeated first word** | This… This… This… | "This reduces errors. This saves time. This helps teams scale." |
| **Repeated quantifier** | Most \+ \[plural noun\] \+ \[verb\] | "Most employees want flexibility. Most managers want accountability." |
| **Repeated prepositional opening** | By/With/For \+ \[phrase\], \[main clause\] | "By automating approvals, teams save time. By centralising data, managers gain visibility." |
| **Repeated audience framing** | For \[audience\], X. For \[another audience\], Y. | "For sales teams, it means shorter sales cycles. For marketers, it means better campaign attribution." |
| **Repeated conditional opening** | If/When \+ \[condition\], \[result\]. | "If demand increases, the system scales. If traffic drops, resources are adjusted." |
| **Anaphora** | Same word or phrase opens consecutive sentences or clauses. | "It saves time. It cuts costs. It scales." |
| **Subject-verb monotony** | \[Subject\] \+ \[verb\] \+ \[object\]. Repeated across sentences. | "The tool syncs data. The team reviews it. The manager approves it." |
| **Length monotony** | \[Sentence of X words\]. \[Sentence of X words\]. \[Sentence of X words\]. | A paragraph where consecutive sentences have nearly identical lengths and structures. |

### **Editorial guidelines**

* No more than one sentence beginning with *Most, This, By,* or *For* under a single H2.  
* No more than two sentences in the entire draft should begin with the same word or phrase.  
* Avoid repeating the same grammatical construction across consecutive sentences.

## **Pattern 9 : Repetitive Vocabulary**

Repetitive vocabulary refers to the disproportionate use of certain words, expressions, and word families across AI-generated content.

The issue isn't that these words are incorrect or should never appear in writing. It's their frequency, concentration, and predictable use across otherwise unrelated subjects.

As models are updated, their preferred vocabulary can change. This list of AI-preferred vocabulary will keep growing and existing favourites may become less prominent, and some persist across multiple generations.

### **Commonly observed words and expressions**

**Words:**

Quietly, actually, delve, landscape, leverage, foster, fits, sits, gap, layer, tell, real, unlock, unveil, uncover, unravel, unleash, demystify, decode, elevate, explore, discover, embrace, imagine, navigate, traverse, venture, timeless, dynamic, evolving, ever-evolving, rapid, rapidly, breakthrough, trailblazing, cutting-edge, state-of-the-art, transformative, supercharge, harness, transform, reshape, reimagine, catalyze, remember.

**Metaphorical vocabulary:**

Journey, tapestry, symphony, weave, interwoven, intertwined, inextricably linked, harmony, fabric, terrain, climate, canvas, pitfalls.

**Recurring expressions and phrases:** 

\[Topic\] explained, Delve into, Dive into, Embark on, In the realm of, In today's, At its core, The advent of, Note that, Is certain to, Is sure to, In summary, In conclusion, In essence, Got you covered, What are you waiting for?, Why wait?, Whether you… or…, Take your `[noun]` to the next level, Set the stage, A `[adjective]` blend of, `[Noun]` is all about, Look no further, Imagine this, Picture this

## **Pattern 10: Punctuation and Sentence-Length Monotony**

### **1\. Overreliance on colons and semicolons**

LLMs frequently use colons and semicolons to connect ideas, introduce explanations, and extend sentences. These punctuation marks are grammatically valid and humans have always used them in their writing. However, their repetitive use in AI-generated prose can make the writing feel mechanical.

A colon often introduces an explanation, clarification, or elaboration that could have been written as a separate sentence. Semicolons can similarly connect closely related ideas that would read more naturally as separate sentences.

**Common constructions:**

* \[Statement\]: \[Explanation or elaboration\].  
* \[General claim\]: \[Specific example or clarification\].  
* \[Idea A\]; \[Related idea B\].  
* \[Statement\]: \[List of supporting points\].

**Examples:**

* "The platform offers several benefits: it saves time, reduces costs, and improves collaboration."  
* "There is one problem: the system cannot process large files."  
* "The process looks simple; however, it requires several manual steps."

This is not a blanket ban on colons. They remain useful in headings, bullet introductions, labels, tables, and places where they improve clarity.

Semicolons should also have a clear purpose. Don't use them simply to join two sentences that would work better independently or use other punctuation like a comma. 

### **2\. Overextended sentences**

AI-generated content often packs several related ideas, explanations, qualifications, and examples into one sentence.

The result can be a sentence that runs beyond 20 words, sometimes reaching 30 or 40 words. It may remain grammatically correct, but readers have to process too much information before reaching the main point.

**Example:**

"Businesses can use automation to streamline their internal processes, reduce the amount of manual work required across departments, improve collaboration between teams, and ensure that employees have more time to focus on strategic priorities."

This sentence contains several separate ideas. Breaking it up makes each one easier to understand.

"Businesses can automate routine internal processes and reduce manual work. This gives employees more time to focus on strategic priorities."

### **Editorial guidance**

* Aim for sentences under 20 words as a general readability guideline.  
* Break sentences exceeding 25–30 words into smaller units when they contain multiple ideas.  
* Give each sentence one primary thought or idea. 

## **Pattern 11: Filler Transitions** 

AI-generated content uses generic transition phrases to connect sentences or introduce new ideas without establishing a meaningful relationship between them.

A well-written paragraph develops an idea. Each sentence builds on something already introduced, adds relevant information, explains a consequence, introduces a contrast, or takes the discussion forward.

AI-generated content can struggle with this continuity. Instead of developing the relationship between two ideas, it often inserts a transition that announces the next point without explaining why it follows.

Expressions such as *Here's the interesting part, the timing matters, the result matters,* and *the distinction matters* can create the impression of progression. They don't necessarily advance the discussion.

### **Examples** 

* Here's the interesting part.  
* The important thing to remember is...  
* The distinction matters.  
* The timing matters.  
* The result matters.  
* This is where things get interesting.  
* Here's where it gets complicated.  
* That's what makes this important.  
* But there's another side to this.  
* Here's where things change.  
* Now, let's look at the other side.  
* This brings us to another important point.  
* The story doesn’t end there  
* This is important because...  
* And that's exactly why...  
* This matters because...  
* That's where the real value lies.  
* This makes all the difference.  
* The takeaway is simple.  
* The lesson here is clear.  
* The bottom line?  
* The result? 

## **Pattern 12: Participial Phrase Overuse (-ing Constructions)**

This pattern involves using present participle phrases ending in *\-ing* to extend sentences, introduce additional actions, or describe the supposed benefits of an action.

A particularly common construction places an *\-ing* phrase after the main clause, often separated by a comma.

**Formula:**

\[Main action\], while \+ \[verb-ing\] \+ \[additional action or benefit\].

Examples:

* "The platform automates routine tasks while ensuring consistent performance."

Other variations include:

* ..., enabling...  
* ..., allowing...  
* ..., providing...  
* ..., creating...  
* ..., delivering...  
* ..., supporting...  
* ..., resulting in...  
* ..., contributing to...

## **Pattern 13: Roundabout Framing**

AI uses indirect, roundabout, or unnecessarily elaborate constructions to express an idea that could be communicated more directly.

Instead of stating a relationship, action, cause, consequence, or distinction plainly, the generated text wraps it in additional wording. The underlying meaning may remain the same, but the sentence takes a less direct route to communicate it. This often happens through constructions such as *where the real work starts, that's why it happens, this is what makes it different,* or *the reason behind this is*.

### **Common formulas and variations**

| Formula | Structure | Example |
| ----- | ----- | ----- |
| Where framing | X is where Y happens. | "The production environment is where the real testing begins." |
| Causal framing | X is why Y happens. | "Poor planning is why projects miss their deadlines." |
| Reason framing | The reason behind X is Y. | "The reason behind the delay is a lack of resources." |
| Significance framing | This is what makes X Y. | "This is what makes the approach effective." |
| Mechanism framing | This is how X happens. | "This is how the system processes incoming requests." |
| Purpose framing | X serves as a way to Y. | "The checklist serves as a way to reduce errors." |
| Explanatory framing | What this means is X. | "What this means is that teams need more time." |
| Difference framing | That's what sets X apart. | "That's what sets this approach apart from traditional methods." |

* **Constant drama:** Every point arrives as a reveal, so none of them feel important.  
* **Longer sentences for the same idea:** "Data quality is why forecasts fail" takes more effort to read than "Bad data breaks forecasts."  
* **The claim is often vague:** Strip the frame and there's frequently very little underneath.  
* **It repeats:** "That's where," "This is why" and "What matters is" pile up across a piece.

## **Pattern 14: Overgeneralization**

AI presents a limited finding, individual opinion, or small number of sources as though it represents a widely accepted view or established consensus. A model might cite one study, one expert, or one publication and then use language that implies broader agreement. This makes the claim sound more authoritative than the available evidence supports.

### **Common forms and variations**

* "Widely regarded as..."  
* "Commonly considered..."  
* "Generally accepted as..."  
* "It is widely believed that..."  
* "Experts agree that..."  
* "Researchers have consistently found..."  
* "Studies have shown that..."  
* "The industry recognises..."  
* "There is broad consensus that..."  
* "It is universally acknowledged that..."  
* "Many consider it to be..."  
* "It has long been recognised as..."

## **Pattern 15: Formulaic Hooks and Openers**

This pattern involves starting articles, sections, social posts, or other pieces of content with predictable hooks and introductory constructions.

AI-generated content often reaches for familiar opening formulas to create curiosity, establish relevance, introduce a problem, or make the reader feel included.

These openings can sound engaging at first but when they rely on generic scenarios, manufactured urgency, empty questions, or exaggerated promises, they delay the actual subject instead of giving readers a reason to continue.

### **Common hook and opener formulas**

**Strongly recognisable patterns**

These are particularly formulaic and often signal generic AI-generated openings.

| Pattern | Formula or example |
| ----- | ----- |
| Community frame | "Whether you're a founder, a marketer, or..." |
| Reveal setup | "Here's the thing..." |
| Temporal-landscape opener | "In today's landscape..." |
| World-state opener | "In a world where..." |

| Pattern | Formula or example |
| ----- | ----- |
| Formulaic essay opener | "In the rapidly evolving landscape of X..." |
| Emergence claim | "X has emerged as a key..." |
| Candor opener | "Let's be honest..." |
| Confession opener | "I used to think X. I was wrong." |
| Contrarian opener | "Most people believe X. They're wrong." |
| Curiosity hook | "Have you ever wondered..." |
| Direct-imperative opener | "Stop doing X." |
| Empathy opener | "If you've ever struggled with..." |
| Unsourced statistic opener | "Studies show that X% of..." |
| Urgency frame | "The window for X is closing." |
| Kicker setup | "Here's the kicker..." |
| Hypothetical reveal | "What if I told you..." |
| Obvious-truth opener | "It's no secret that..." |
| Information announcement | "Here's what you need to know..." |
| Truth announcement | "Here's the truth..." |

**Context-dependent patterns**

These depend heavily on execution. They aren't inherently AI-associated, but can become lazy opening devices.

| Pattern | Formula or example |
| ----- | ----- |
| Bare rhetorical question | "Ever wondered why X happens?" |
| Dramatic invitation | "Buckle up." |

### **Other variations worth tracking**

The same tendency can appear through additional opening constructions:

* "Let's dive into..."  
* "Before we get started..."  
* "First things first..."  
* "Imagine waking up to..."  
* "Picture a world where..."  
* "Think about it..."  
* "You might be wondering..."  
* "The answer might surprise you."  
* "There's a reason why..."  
* "What makes X so important?"  
* "X is changing the way we..."  
* "From X to Y, everything is changing."  
* "If there's one thing you should know..."  
* "In an increasingly competitive world..."  
* "Now more than ever..."  
* "Welcome to the ultimate guide to..."  
* "In this article, we'll explore..."  
* "Let's break it down."  
* "The truth is..."  
* "Here's why that matters."

## **Pattern 16: Conditional Negation**

AI begins a statement by describing what something isn't, what someone shouldn't do, or what conditions aren't met, before communicating the actual point. Instead of stating the recommendation, observation, or action directly, the sentence takes a negative route to establish it.

This can make ordinary advice sound more prescriptive or deliberately constructed. The pattern becomes particularly noticeable when multiple sentences use negative framing throughout the same piece.

**Common formulas and variations:**

| Formula | Example |
| ----- | ----- |
| Do not \+ \[action\] | "Do not jump straight to autonomy." |
| Not every \+ \[noun\] \+ \[verb\] | "Not every workflow needs an agent." |
| We don't \+ \[action\] | "We don't sell a platform." |
| X isn't \+ \[description\] | "The solution isn't suitable for every business." |
| No \+ \[noun\] \+ \[verb\] | "No single tool solves every problem." |
| Without \+ \[condition\], \+ \[consequence\] | "Without proper planning, projects can fail." |
| Never \+ \[action\] | "Never deploy without testing." |
| X doesn't mean Y | "Automation doesn't mean removing human oversight." |

### **Conditional negative framing**

This uses a negative condition to introduce a recommendation, rule, or conclusion.

**Variations:**

* If X isn't Y, then Z.  
* If X does not meet Y, do Z.  
* If X isn't ready, don't do Y.  
* Unless X happens, don't do Y.  
* Without X, Y cannot happen.

### **Editorial guidance**

* State the actual recommendation when possible.  
* Avoid turning context-dependent decisions into universal rules.  
* Use negative framing when correcting a genuine misconception or preventing a specific mistake.  
* Watch for repeated negative openings across paragraphs and sections.  
* Check whether the negation adds useful emphasis or simply delays the point.

## **Pattern 17: Incomplete Sentence Constructions**

This pattern involves sentences or clauses that don't provide all the information needed to communicate a complete thought.

AI-generated writing can sometimes omit or under-specify essential sentence elements. This may include the subject performing an action, the action itself, the object receiving it, or the information needed to understand what a sentence refers to.

The result can be a sentence that sounds grammatically plausible but feels incomplete when read in context. The reader has to infer who is doing something, what is happening, or what the action relates to.

| Type | What's missing | Examples |
| ----- | ----- | ----- |
| **1\. Missing subject** | Who or what does the action | Requires additional configuration before deployment Can improve efficiency across departments Helps reduce manual intervention Making it easier to manage multiple projects |
| **2\. Missing object or complement** | What the action applies to | The system helps teams manage The company decided to improve The platform enables users to access This allows businesses to integrate |
| **3\. Missing or incomplete verb** | A main verb, so there's no complete clause | The platform designed for enterprise teams The implementation process, including several additional requirements The new system capable of processing large volumes of data |
| **4\. Dependent clause standing alone** | The main clause it depends on | Because the existing infrastructure cannot support it While maintaining compatibility with existing systems Although the implementation process is relatively straightforward If the requirements change |
| **5\. Missing context** | What "this," "that," "it" or "the same" refers to (the grammar is complete, the meaning isn't) | This makes it easier That creates another problem It also affects the process The same applies here |

## **Pattern 18: Passive Voice and Third-Person Detachment**

### **1\. Overuse of passive voice**

Passive voice places the person or thing receiving an action at the centre of the sentence, rather than the person or thing performing it.

**Test:** Can the reader answer *who* does *what* to *what*? If any part is missing and can't be found in the sentence before, the sentence is incomplete. 

### **2\. Third-person detachment**

This involves consistently describing the subject, product, company, or audience in the third person instead of addressing the reader directly or establishing a clear authorial perspective.

In content intended to speak directly to a reader, this can create unnecessary distance.

**Common formulas and variations:**

| Formula | Example |
| ----- | ----- |
| \[Audience\] \+ can \+ verb | "Businesses can use the platform to manage their workflows." |
| \[Users\] \+ should \+ verb | "Users should review their settings regularly." |
| \[Company\] \+ helps \+ audience | "The platform helps businesses improve productivity." |
| \[Subject\] \+ enables \+ audience | "The solution enables teams to collaborate more effectively." |
| \[Audience\] \+ needs to \+ verb | "Organisations need to evaluate their requirements." |
| \[Product/company\] \+ provides \+ benefit | "The software provides businesses with greater visibility." |

The individual constructions are perfectly valid. The pattern becomes noticeable when an entire article repeatedly describes what businesses, users, organisations, and companies do, without ever establishing a direct relationship with the reader.

For example:

**Third-person framing:**

"Businesses can use automation to reduce manual work. Teams can also use reporting tools to monitor performance."

**Direct reader address:**

"You can automate repetitive tasks and spend less time on manual work. Reporting tools also help you monitor performance."

The second version establishes a direct relationship with the reader. However, direct address isn't always appropriate. The intended audience, publication format, and brand voice should determine the perspective.

## **Important notes**

### **Examples are Illustrative and Not Exhaustive**

The examples throughout this document are provided for reference. They illustrate how a particular AI writing pattern can appear in generated text. They are not hard-coded rules, exhaustive lists, or definitive templates.

LLMs can produce countless variations of the same underlying pattern. They can change the wording, sentence structure, vocabulary, or placement while retaining the same linguistic tendency. They can also combine multiple patterns or introduce entirely new variations that aren't documented here.

Filtering out the exact phrases or sentences listed in this document will not eliminate the underlying patterns. Models can simply generate different expressions that follow the same construction.

Use this library to recognise patterns instead of match phrases. Focus on the underlying linguistic behaviour, understand how it manifests in different contexts, and remain open to identifying new variations and patterns as AI-generated writing evolves.

### **Editorial guidance is intentionally selective**

You'll notice that some patterns include editorial guidance, while others only describe the behaviour, its variations, and examples. This is intentional.

The objective of this library is to identify, document, and explain AI writing patterns. It isn't intended to prescribe how every sentence should be rewritten or provide a fixed alternative for every expression.

Providing standardised fixes for every pattern creates another problem. Writers may start replacing identified AI patterns with the same set of recommended alternatives. Over time, this can make their writing just as predictable, repetitive, and formulaic as the patterns they're trying to avoid.

Writing shouldn't become an exercise in following another set of rules. There should be room for individual voice, creativity, experimentation, and different ways of expressing the same idea.

