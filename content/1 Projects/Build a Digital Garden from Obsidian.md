---
Created On: 2024-05-03 06:25:08
Last Edited: 2024-05-12 13:51:57
publish: true
---

# Build 
### NEW INFO 
Quartz is back in front after getting annoyed with how clunky the DG plugin felt. When I got worried about dataview compatibility, I came across this link from the open issue on it:

https://github.com/saberzero1/quartz-syncer

So I could get a native to Obsidian experience and a prettier setup 🤩

Got it running 2024-05-11 and very pleased so far. 

### STOPPED: Plugin-based 

The config: 
- https://dg-docs.ole.dev/getting-started/03-note-settings/
- https://vercel.com/mbbrobergs-projects/mentalmoss
- https://mossymentalmodel.vercel.app

#### If I go this route... I'll need more functionality

- I asked one guy who has a prettier version how he did it: 
	- https://github.com/uroybd/topobon/issues/29#issuecomment-2100359955
	- https://github.com/uroybd/topobon/blob/main/src%2Fsite%2F_includes%2Fcomponents%2Fuser%2Fcommon%2Ffooter%2F001-floatingControls.njk

# Explore 
## Layout
### Structure 
#### Mine 

PARA > I could straight up share that as is — Projects / Areas (maintained) / Resources (snippets of thought) / Archive (no longer relevant to me)

Why avoid the structure I’ve put around my own thoughts? 
- I feel it’s *too complicated* — no, I am worried to be judged and reflection reminds me not to care 

#### Reuse some of Jacky’s?
From https://github.com/jackyzha0

His only folders 
- thoughts 
- writing 


title: "Seed"
description: "I tend to generally bookmark things for later then revisit them when I have time. These are collections of notes on articles, books, and readings. They are the seeds that form the basis of my ideas and thoughts."

title: "Sapling"
description: "Saplings are single nodes or thoughts. These are generally topics I've spent a decent number of hours thinking about and contain substantial original thought."

title: "Pattern"
description: "A pattern in my own pattern language. These represent atomic concepts and observations that appear and reappear within my thinking and work. See the note on 'A Pattern Language' for more information"

title: "Personal"
description: "Personal reflections and musings about my life. I really like to write feelings down as a way to process them and sometimes they take the form of blogposts like these."

For me it’s 
- seed
- sprout 
- verdant 

## Options
### Researching Quartz 
https://jzhao.xyz, building off of the [[Philosophy of Quartz]]
- Clearly into Deleuze! Writes about [[03 Resources/Notes/Rhizomes]] 

Pros
- Beautiful out of the box 
- Philosophically congruent with me 
Cons
- Not native — gotta figure out a workflow to go from Obsidian to Quartz repo
- Not obvious — an hour of tinkering got something going, but I have questions
### Researching Mkdocs
https://www.mkdocs.org/user-guide/configuration/#markdown_extensions

Because my intro to this whole concept comes form https://lyz-code.github.io/blue-book/

Seems sysadmin-heavy and less stylish than the others… 

### Researching Digital Garden Obsidian Plugin 
Got it up and running 2024-05-04 

Pros
- Great integration into Obsidian proper
- Simple enough hosting configuration with GitHub and Vercel 
- Will render dataview results, which is nice for my heavy use of them
Cons
- Don't love the templates, so I risk spending all my time tweaking instead of gardening
- Specifically: 
	- No dark/light toggle button 
	- Layout online and mobile is wonky
	- No navigation bar option?

Conclusion — I’m too into form as function to accept this solution as is... continue to explore themes via the community