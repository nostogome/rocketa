# rocketa Conversations and Prompts
### - Versioning in Conversations and Prompts

<img src="site/www/img/protect.png" alt="image a futuristic egg statue protected by birds and robots" width="600">
<p>© 2025 nostogome All rights reserved.</p>

---
## A *base* repository for `topical repositories` that track *versioned* `chats`, `conversations` and `prompts`

> "It's 2025; Forums are so dead! With curation, and forkability - our customers are finding new life in their support and branding activities" 
---
~***Margaret Beechan***, *CEO* ***Faceoff Support Solutions*** *fake, but...

---
> "Still maintaining a `FAQ` in *2025*!?  Still on *old* web forums?  Still not letting your ecosystem document for itself? Still not letting customers help others?  We hadn't realized the overhead of curating our forums and documents - what to release, where, how - frustrating ourselves and our customers.  Now the customer is always right - they can fork and share, and we can curate our side.  With the introduction of AI, the *answers* to the questions can evolve. Also, our ecosystem can fork for itself, (which it does, both *public* and *private*).  We can better tune in and curate the **official** `conversations` and `chats`. We're weightlessly gaining insight ourselves - asking the latest AI service for the latest answers.  It's in our hands, its in our customers hands.  It's quite the party, for everyone! But seriously, **rocketa** is a bit further... make a **rocketa** repo today, you'll see!" 
--- 
~***Anne Bei***, *Support Specialist*, **AccentSuperCorp** *fake, but

---
>> State of things: currently, encourages Maven-style versioning, and markdown-based repositories and `topical` [template project](https://github.com/nostogome/rocketa-template) - albeit without much actual dependency resolving, or even a tree-crawling documentation assembler, yet.
 
> *Note* this is a very new and evolving space.  Anything may change.

# What's this repo, though?
> This is simply a base repo for a structure of `topical` repos (known as [`compliant`](#compilant-repos)), a group of conventions that *enable tools* by leveraging globally-namespaced versioning (which among other things, enables `dependency management`, including `automated gathering`)  


>> **Ready to create your own `topical repo`**? 
 - git clone [rocketa-template](https://github.com/nostogome/rocketa-template) and replace the TOPICAL_* placeholders

# What is the goal?
 - Be a base for a `topical repository` ecosystem - conventions and tools combined with a global versioning strategy allow tools to do the work

 - At a minimum, `topical` repositories create a runway for an evolving conversation
   - **Create a Runway of Understanding**
     - Whether the viewers are:
       - *starting out*
       - *seasoned*
       - *casual observers*
   - **Let your ecosystem thrive**
     - **Documentation-level**, and **Forum-level**   (`conversations`/`chats`) 
       - Allow others to drive the *adoption*, *evolution* and *support*
         - public and private forks, including *internal*!
       - Maintain trustable, curated, `conversations` releases
       - Go on a date with your viewers!
         - Follow the forks, *internal* and *external*
         - Curate informal or **forum-like** support in `chats`
     - Communicate new developments (Tools support RSS for releases* )
       - Automatically follow dependent `conversations` and ask AI to make sense of it in an instant 

  - `topical repos` are
    - Curated by you
      - *formal* releases in `conversations` 
      - *informal* updates in `chats`
    - Curated by others
      - public and private forks allow 
        - the conversation to evolve
        - easy merging

  - But why use **rocketa** convention?
    - Tools, tools, tools.  Imagine:
      - RSS-style updates when new releases occur
      - Browse public / private forks (internal and external)
      - Easiily merge forks (curate your own)
      - Automated documentation (tree diving)
      - Dependency automation
        - Base in external (or internal) releases
          - Get updates when the *premise* of the conversation changes (e.g. the `current` pointer changes)
      - Conventions allow the tools to do the work (i.e. ask different AI, automated)
      - Trustable transition flows due to *versioning* and *structure*
      - Still publishing FAQs? Why not *give away the questions* instead?
        - **In a format and structure** that *evolves* the conversation
        - The spirit of **rocketa**
          - **Constrained** answers: let your viewers choice of AI contribute (**as they evolve**)
          - Details, release convention format
            - `<` actual AI response (rare)
            - `<-` human summary
            - `<--` human reaction/opinion (i.e. usually regarding nominal answer (AI/misconception battling) )
        - See an [example chat](https://github.com/nostogome/rocketa/tree/main/chats/org.nobodyknew/tdd/1.0.0/AAA/chat.md) 
          - aka "host[ /dir ]/user/reponame/[chats/org.nobodyknew/tdd/1.0.0/AAA/chat.md](https://github.com/nostogome/rocketa/tree/main/chats/org.nobodyknew/tdd/1.0.0/AAA/chat.md)"

# Who are topical repositories for?
> Use it to *convince*, to *bootstrap*, to *guide*, to *commiserate*
 - Run a **brand**?
 - Run a **community**, or are part of one?
 - Run a development **project**?
 - Have a complex scientific **research** project that is hard to explain?

# Showcase 
> "Releasable, forkable conversations?  Groundwork for Prompt dependency resolution, of Prompts and Conversations?!  What a brave new world, Pete!  -- Jorge P."

## Conventions summary
- A *repo* of *versioned* `conversations`, `chats` and `prompts` that conforms to:
- A very simple [format](https://github.com/nostogome/rocketa/tree/main/format.md) for `chats`, `conversations` and other releases, like `prompts`, extendable.
Following the [`frontmatter`](https://github.com/nostogome/rocketa/tree/main/README.md#format-file) and a **summary** **markdown** sections` See [Format file](https://github.com/nostogome/rocketa/tree/main/README.md#format-file), the conversations are easily viewable in markdown readers, with the following `reservations`
```
  '>' to AI (the questions)
  '<' from AI (raw)
  '<-' human summary of AI response
  '<--' human reaction to nominal response (AI or common misconceptions)
  ```

- A *spec* for convention that supports multiple repositories (known as `topical` repositories) for *familiar* interaction including *easy merging*; *automated tools*
  - directory structure
  - versioning (Maven-compatible)
    - namespacing (globally unique, github-style <user>/<repo> base dir, though any `host` *and*/*or* subdir (e.g. *https://mydomain.com/blog/myuser/mytopicalrepo*))
- `nostogome/rocketa` as the default repo for tooling and structure (incase it breaks out into actually needing a dependency system!)
  - Pull requests
    - Maven central rules (e.g. no overwriting)

## Spirit of rocketa
  We're all evolving!
  - Strip LLM responses (strip: `$ 'sed '/^<[^-]/d' chat.md`)
    - caveat: ***critiques of AI output*** obviously require the AI response inclusion
    - Follow your `topical repo` guidelines, but the **rocketa** default ***spirit*** is "***stripped***" to enable fast-track automated PR flow with clean input.
      - Links added to README.md: again `topical`(precendence)/`default` ->  contributions to repo's `README.md` should be mimimal (i.e, only add 1 line - enables fasttracking/automation of PRs)
      - *Be upfront*:  often, a few *raw AI responses* using: `<`, are included in any conversation of substance/length. So,
        - If you are issuing PRs, explain the `<` lines ***upfront***, so the human-merger can quickly *triage*

## Repository Goals'
 - *"This repo is not a topical repo, but may contain sample `chats`, `conversations` and `prompts`, or with itself as the subject"*
    - See [repository.md](https://github.com/nostogome/rocketa/tree/main/repository.md) for more information
- The main goal of this project is *to support* `topical repos` having a main goal of the [`prompts`](https://github.com/nostogome/rocketa/tree/main/prompts) 'artifacts' directory

## Details
- ***Prompts*** = AI prompts ([`./prompts`](prompts/)) 
  - example: ([`prompts/org.nobodyknew`](prompts/org.nobodyknew/))
  - example:
    - group (all artifacts) ([`prompts/org.nobodyknew/`](prompts/org.nobodyknew))
    - artifact (all versions) ([`prompts/org.nobodyknew/tdd/`](prompts/org.nobodyknew/tdd/)) 
    - artifact+version ([`prompts/org.nobodyknew/tdd/1.0.0`](prompts/org.nobodyknew/tdd/1.0.0))
    - artifact+version+hash ([`prompts/org.nobodyknew/tdd/1.0.0/jih39`](prompts/org.nobodyknew/tdd/1.0.0/jih39))

- ***Conversations/Chats*** = **formal**/**informal** (aka **documentation**/**forum**)
  - example: ([`./conversations`](conversations/)) 
    - group (all artifacts) ([`conversations/org.nobodyknew/`](conversations/org.nobodyknew))
    - artifact (all versions) ([`conversations/org.nobodyknew/tdd/`](conversations/org.nobodyknew/tdd/)) 
    - artifact+version ([`conversations/org.nobodyknew/tdd/1.0.0`](conversations/org.nobodyknew/tdd/1.0.0))
    - artifact+version+hash ([`conversations/org.nobodyknew/tdd/1.0.0/394j5hSD`](conversations/org.nobodyknew/tdd/1.0.0/394j5hSD))

  - example: ([`./chats`](chats/))
    - etc, etc ... 

# Versioning

> `<major>.<minor>.<patch>[-qualifier]`

  - follows [Maven Versioning Rules](https://maven.apache.org/pom.xml#version-order-specification)
    - *optional* `-qualifier` to signal non-standard support requirements (e.g. `1.0.0-NewAgentAPI`).
  - Hash included? Really? (e.g. `com.it:thechat:10.0.0:39dh8h3h`)
    - Yes, for `conversations` (convo-forking). Less used for `chats`, and rarely used for `prompts`
    - *Note* for those familiar with `coordinate-based` *dependency systems*, note a mindset change.  Unlike traditional use of hashes in software development (usually used for SNAPSHOTs), conversation iteration is just better at an accute level, where almost every word matters, contrasted with compatibility concerns of more traditional software development.


The ***main goal*** of the [nostogome/rocketa project](https://github.com/nostogome/rocketa) is the [`prompts`](https://github.com/nostogome/rocketa/tree/main/prompts) ('artifacts') directory

## Quick example, chats
See [chats/org.nobodyknew/tdd/1.0.0/AAA/chat.md](chats/org.nobodyknew/tdd/1.0.0/AAA/chat.md) 

## Usage flow

General Usage by flow order, but not necessarily. All have `full coordinate ability` (i.e. dir structure)
- Chats
  - conversations starters, usually never leave versions 1.0.0
- Conversations
  - more formal, forkable conversation flows supported by `hash-versioning` (commonly used more like 'git commit hash' than a -SNAPSHOT, but no rules enforced).  Parent dir has a current pointer file, named `current`
- Prompts
  - output, generated or otherwise 

---

## *chats* (informal, with or w/o responses, messier than conversations)
`./chats` informal chats with optionally *included* responses.  Intended to be mind-forked, and includes some examples.  Please recontribute to this (organized), and to conversations (final products without the LLM responses).

## *conversations* (formal, hint of more longevity/fork value - with or without responses)
`./conversations` releasable conversations that may have optional *included* (partial) responses - which lead to creation of artifacts in `./prompts`  - they are generally intended for creative sharing and to foster iteration. A metadata file is included for citing sources in `metadata.md` which lives at the `artifact`, `version`, and/or `hash` level.  This is for automated doc tree building.  There is also a `summary.md` file that contains priority information (e.g. printed first in doc tree build).  If releasing, include the coordinate of the `chats`, if applicable, in the frontmatter.

## *prompts* (raw prompts - with or without responses)
`./prompts` contain releasable prompts for specifically versioned creations. group/artifact/version/hash/ (e.g. *com.bytesalot/superbeing/1.0.2/8ffjeu3ba/*).  If releasing, include the coordinate of the `conversations` and `chats`, if applicable, in the frontmatter.

## Per directory files:
see [Files](#files)



## About automated citation and documentation rendering
> Planned: The (**rocketa**) `artifact coordinate` in `metadata.md` is to allow for automated pulling or documentation rendering of `summary.md` and `metadata.md` documentation. Run at a specified level, it can document the underlying component (and potentially pull in referenced) (e.g. find all cites for 'artifact' would trigger a recursive compilations of citations in the version and hash directories (while potentially pulling 'dependencies' docs from the central [nostogome/rocketa](https://github.com/nostogome/rocketa) repo or external (depending on tool support, leveraging `repositories.md` or frontmatter).  

A basic documentation build tool outputs a tree structure (that orders by inclusion, then summary, then commit date).  Manual "overall" summary documentation exists in a separate file, `summary.md` which may exist also at each level - and is printed first in the automated tree of documentation, a respective levels


## tools
> *Note*: no tools exist yet
Examples:
 - tools/
  - doctree-generator/
   - `doctree` (TBD) generates automated documentation by collecting and out outputting contents from `summary.md` (unparsed/concatenated) and `metadata.md` (citations, mainly, parsed) files, recursively
   - `deptool` acts like maven dependency tools, except no central repo: pulling from github-like <user>/<topicalrepo>

## Compilant Repos

>  ✅ **Ecosystem **enabled!** 🚀

 - `repositories.md` must reference `nostogome/rocketa` in the top 2 entries of the repositories.md file.  
 - **format** of `structure files`
   - `structure files`'s *markdown-viewable* `section` must begin with the message `"This file is part of the nostogome/rocketa spec."` (i.e. after `frontmatter`) 
     - the following files have a *specific format* to enable tooling (i.e. only update tables; leave headers intact) 
       - `repository.md`
       - `repositories.md`
     - the following have `frontmatter` that have *specific keys* (with *optional ones* still *evolving*)
       - `repository.md`
       - `repositories.md`
       - **all** `summary.md`
       - **all** `metadata.md`
 - **format** of `release files`
   - **comply** with the *master* [format.md](https://github.com/nostogome/rocketa/tree/main/format.md)
     - if `schema-id` supplied, *optional* in frontmatter
       - `schema-id` format is: `"<host>/<user>/<repo>:tag"` (e.g. `"github.com/nostagome/rocketa:v1"`)
         - `tag` name must include (`v`+ *one number* ] or [Maven-style](#versioning) "`1.0.0[-qualifier]`" to enable tooling
         - `tag` is a `git mechanism`
 - In any other case, fall back to [nostogome/rocketa spec](https://github.com/nostogome/rocketa/tree/main/README.md)

# Topical Repos
  - for a curated list, see the table in the respective `repositories.md`
  - See [Files](#files) for more information

# Topical Examples

## Downstream
Links to projects that are > ~80% direct result of using existing (i.e. *committed*) prompts [nostogome/rocketa/prompts](https://github.com/nostogome/rocketa/tree/main/prompts).  Topical repositories may or may not choose have this policy.

| Name | URL | Description | Use | Replaces target | Results |
|------|-----|-------------|-----|-----------------|---------|
| example | github/mygen | prompt generates entire project | Maven archetypes | Works, sometimes.  Looking forward to new models or langchain integrations |


# Model namespaces
  - See `repository.md` for curated models/namespaces. See [Files](#files)
  - Note the *master* [repository.md](https://github.com/nostogome/rocketa) should be consulted during dependency resolution. 

## Content policy
- Refer to content policy in repository.md

## Acceptancing Pulls, Maintenence, Deletion (though in history)
- Entries may disappear at any time, including but not limited to 
  - Maintenence, including Pruning
  - Removing previously accepted content due to changes in the Content Policy, as defined in `repository.md` or other `nostogome/rocketa` statements or will

## Pruning
 - won't prune `current` or those with a newer commit timestamp than the `current` file pointer


# Files 
  - 
  | File               | Parsed by tooling | Found in  | Directory                                         | Description                                           | Thirdparty use                     | Master/Tool use                        |
  |--------------------|----------------------|-----------|---------------------------------------------------|-------------------------------------------------------|------------------------------------|----------------------------------------|
  | `repository.md`    | Y | **rocketa** & `topical`      | / | name of the repo, policies                            | extend model references (namespaces), policies  | maintain model references |
  | [`repositories.md`](#repositories-detail)  | Y | **rocketa** & `topical` | / | extended repo, for dependency system (incl doc tools) | extend known repositories          | same as thirdparty |
  | `tools.md`         | T | **rocketa** & `topical` | / | description of tools available | extend / override tool information | describe tools available in base `nostogome/rocketa` | 
  | `summary.md`       | T/C | **rocketa** & `topical` | *optional* Any/All level in `release dirs` | Manual summary, concatenated by doc tools, optional frontmatter | non-parse-tooling/concatenation | same as thirdparty |
  | [`metadata.md`](#metadata-detail)      | T | **rocketa** & `topical` | *optional* Any/All level in `release dirs` | compliant frontmatter key/values, citations oriented | parse/tooling | same as thirdparty |
  | [`format.md`](#format-file)        | Y | **rocketa** & `topical` | /, and `release dirs` | reservations made in [master format.md](https://github.com/nostogome/rocketa/tree/main/format.md), otherwise extendable base for `release files`' format | Tools (PR/auto pulls) |  none |
  | [`current`](#pointer-file)        | T | **rocketa** & `topical` | Release dirs |  | 1-line file; contains 1 entry to most-recent subdir | Y/tools| none |

`T` = `top` (aka `frontmatter`)
`C` = non-parsed (likely concatenation)

# Files Detail
## Repositories Detail
 
 [repositories.md](#repositories.md) - See also [Files](#files)

 - **static** structure, mutable **tables**
 - list by groupId only, unless unless `artifact-level` is necessary
   - **no order is specified**, as this is also a *human-readable* document. 
   - When in doubt, sort by hierarchy >  more-specific versions *below* their parent > alphabetically

```
org.nobodyknew
org.nobodyknew:artifactA
org.nobodyknew:artifactB

```

 - See also [Frontmatter for Structure Files](#frontmatter-keys)
 - See also the header and tables in [repositories.md](repositories.md) for more information


[submit **minimal** pull requests](https://docs.github.com/en/pull-requests)

You may be interested in [frontmatter keys](#frontmatter-keys)

## Format file
Basic reservations and recommendations for the `chats`, `conversations` and `prompts` release files, commonly named `chat.md`, `prompt.md`

 - [Compliant](#compilant-repos) `topical repositories` will waive (if not **stay updated with**) `reservations` made by the **master** `format.md`: [https://github.com/nostogome/rocketa/tree/main/format.md](https://github.com/nostogome/rocketa/tree/main/format.md). 
 - Topical repo *root* `/format.md` can be modified in `topical repositories`, and may exist at `group` and `artifact` *levels*

 - Common layout: markdown sections (i.e. "---")
   - frontmatter section
     - see [frontmatter keys](#frontmatter-keys)
     - extendable by version-tagged schema (*schema-id*)
     - machine processable (i.e. models-tested: com.openai.gpt-4o )
   - summary section
     - human readable introduction/commentary/summary/conclusions
   - content section
     - Usually prefaced with a top-level markdown header (e.g. "# Conversation" )
     - a stream of `>`, `<`, `<-`, `<--` 
     ```
     `>` to AI (questions)
     `<` from AI (raw)
     `<-` summary
     `<--` reaction
     ```

      

## Pointer file
At any level in the `coordinate` may exist a file named `current` whose the contents (1 line) is the name of a subdirectory

A structure of:
```
| groupId
|   |-- artifactId
|   |   |-- version
|   |   |   |-- hash
```
like:

```
| org.nobodyknew
|   |-- tdd
|   |-- current # points to 1.0.1
|   |   |-- 1.0.0
|   |   |-- current #points to Df3iseS3ge
|   |   |   |-- 8j4df84w9w
|   |   |   |-- Df3iseS3ge
|   |   |-- 1.0.1
|   |   |-- current #points to udg48dg39g
|   |   |   |-- udg48dg39g
|   |   |   |-- 03dgDGEEjg
```

## Full Structure example


```
|-- `README.md`
|-- `repository.md`
|-- `repositories.md`
|-- `tools.md`
|-- conversations
|   |-- org.nobodyknew
|   |   |   |-- tdd
|   |   |   |-- current
|   |   |   |-- summary.md
|   |   |   |-- metadata.md
|   |   |   |   |-- 1.0.0
|   |   |   |   |-- current
|   |   |   |   |   |-- 8j4df84w9w
|   |   |   |   |   |-- Df3iseS3ge
|   |   |   |   |-- 1.0.1
|   |   |   |-- |-- summary.md
|   |   |   |-- |-- metadata.md
|   |   |   |   |-- current
|   |   |   |   |   |-- udg48dg39g
|   |   |   |   |   |-- 03dgDGEEjg
```

* If no pointer file, `*default*` is the latest by git commit time


## Metadata Detail

aside from frontmatter, `metadata.md` contents are for `citiations`
 - keys
   - `model` *optional*
   - `source` *optional* [an artifact coordinate]
   - lines that do not start with `'alphanum ='` are treated as commentary (optional)

 ```
 model = com.openai.gpt-4o

 source = com.pengit:sloppy:1.4.2:38dfhsdfuh3husdfhud

 source = uno.barkday:primemaster:1.0.2:9sdf8sfhsfuhf
 included their ideas about agents

 source = it.gerardo:react:3.5.3:73nsdufhdsfuh
 used some react generator ideas

 ```
You may be interested in [frontmatter keys](#frontmatter-keys)

# Frontmatter keys
 
 - Files
   - `schema-id` format is: `"<host>/<user>/<repo>:tag"` (e.g. `"github.com/nostagome/rocketa:v1"`)
     - `structure files` must include 
       - `schema-id` *required*
       - `created-ts`: *optional* [ISO8601]
       - `last-updated`: *optional* *recommended* [ISO8601]
     - `release files` frontmatter is *optional*
       - *recommended* keys
         - timestamps use keys `created-ts` and `last-updated` in ISO8601 format (e.g. "2025-02-15T12:03:37Z" or "2025-02-15")
         - author
         - copyright
         - source
         - name
         - goal
         - summary
         - chats-base [coordinate]
         - conversations-base [coordinate]
         - results
         - version-strategy
         - tested-models [ `comma-delimited` ], `namespace` prefix *optional* (e.g. gpt-4o,`com.openai.`o1-mini) ] See [Model namespaces](#model_namespaces)
         - expected-model-class: SYSTEM_PROMPT_1,FIM_1,
 - Keys
   - if `schema-id` is supplied (*optional* in some non-structure files)
     - `tag` name must include (`v`+ *one number* ] or [Maven-style](#versioning) "`1.0.0[-qualifier]`" to enable tooling
     - `tag` is a `git mechanism`


# License

Most content released under MIT license with exception of the /site directory, and other branding-related content and images specific to [github.com/nostogome/rocketa](https://github.com/nostogome/rocketa)

See [NOTICE](NOTICE), [LICENSE](LICENSE) for details
