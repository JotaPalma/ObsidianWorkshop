# ObsidianWorkshop
Beginner Obsidian workshop

Hello and welcome to my beginner Obsidian workshop. Bear with me while I try to overcome my social anxiety by talking about something I'm passionate about.

[Here's the link to install obsidian](https://obsidian.md/download).
Join us on [/r/ObsidianMD](https://www.reddit.com/r/ObsidianMD/) or on [discord](https://discord.gg/obsidianmd)!


# Personal Knowledge Management

## What is it and why is it important
A personal knowledge management system, or PKM, is just that. A system that helps you manage your knowledge. It helps you collect, organize and access your knowledge. It should be something that's ingrained into your workflow.

## Your brain can't keep all the information
There's no nice way of putting this: Our brains aren't reliable. We forget things, we mix things up, we're forgetful beings who need all the help we can get.

## Niklas Luhmann's Zettelkasten
Without any technology, a German sociologist named Niklas Luhmann created a huge zettelkasten whom he called his writing partner. His belief was that, once you put enough information into the slip box, it reaches critical mass, and starts putting out ideas and connections for you to find. Luhmann wrote more than 70 books and almost 400 articles on subjects like law, economy, politics, art, religion, ecology, mass media, or love. All with the help of his zettelkasten. Of course, he's an overachiever in this area. All we can hope for is a system that helps you organize your thoughts and make connections.

# Why Obsidian and not another PKM tool?
I know this is a controversial topic, and it's not my place to tell you to drop Notion or any other PKM system you might be using. However, it's good to know your options. Obsidian is a good option because: 

## Markdown lasts forever
Markdown is an easy-to-read language that doesn't need a specialized program to be read. If Obsidian ever goes belly up, you're sure you can open your notes on many other programs, including the notebook app on any PC.

## You own your data
Your notes are literally just a folder on your computer. You can do what you want with them without fear of losing your precious data due to a server crash or because someone hacked the Obsidian staff. 

## Privacy
Since you own your own data, you're sure that it's as safe as you can keep it.

# Limitations
While I use Obsidian and am not likely to drop it any time soon, I recognize that there are limitations and that it's not a perfect tool.

## Lack of structure
There is no hierarchical structure in Obsidian. All the files are equal. Some people need a bit more structure in their lives, and that's okay.

## No collaboration (Yet)
This is a major one. While the staff has said that collaboration may be in their future, it hasn't landed yet. There are workarounds, but they're not the best. If you're looking for a free collaboration tool, Obsidian may not be for you.

# Obsidian basics
## Structure (or lack thereof)
There isn't much structure in Obsidian. For our convenience, there is a file system, but it's not hierarchical in the grand scheme of things. 
## Buttons
## Plugins
### Core
### Community

## One vault or more?
This is a controversial point within the community. Some swear by separating your notes into different vaults. I myself, with some exceptions, am a defender of having a single vault for everything. By having all your knowledge in one place, you can find unexpected connections. 

# Your first note
Let's get our hands dirty. Install Obsidian using the link on the [official website](https://obsidian.md/download)

## Creating your vault
Once you open the app, you'll be prompted to create your vault. This will simply be a folder on your computer where all your notes will be stored.

## Markdown basics
Headings: #

Highlighting: ==jsj==

Code block
```html
<html>
  <head>
  </head>
<h1>Hello</h1>
</html>
```

Bold **sksks**

Italics *jsjse*

Callouts

> [!NOTE] Note title
> Contents


## Linking your note - the magic of obsidian
The square brackets [[]] are the magic of Obsidian. You type in anything inside double square brackets and it instantly becomes a note. At first, it will be faded out, since it's not a created file yet, but once you click it, a new note is born! Let's create a few notes and mention them inside other notes.

## The graph view
Now that we've mentioned some notes inside other notes, let's take a look at the global graph view. You'll see that, whenever you mention a note, you create a link to it. Once you've reached a certain number of notes, you'll notice your global graph won't be so useful anymore. But it's still cool to look at! You can group notes, color them, take some out of the graph, etc.

The local graph view lets you see every note connected to your current note. It's far more useful, in my opinion. You can fiddle around with the settings to go deeper into the level of notes.

## YAML 
Every note can have a YAML header. To create it, use three dashes --- 
Here, you can input meta information about the note,like aliases, tags and dataview queries

## Templates
Let's install the templates plugin. It's one of the plugins I use the most. Create a Templates folder, then a template note for something of your interest, like a book note, or a series review note.

# Advanced
## Canvas
Canvas is basically a mind mapping tool on steroids, since you can link your notes, websites, media and even create notes directly from the canvas view.
It's not visible on mobile yet, but it's a feature the dev team is working on.

## Dataview and other community plugins
Let's install dataview and enable it from the community plugin tab.


With LIST you can create a simple list view of your notes
With TABLE, you create a table where you can have headers 
With TASK, you can create a list of all the tasks on your vault

FROM : gets files from a specific location (example, a tag)
Incoming links: finds all notes linked to note 
Outgoing links: just add "FROM outgoing ([[example dataview link]])"
You can add more Queries in the FROM with AND and OR. With a -, it will subtract the query.

WHERE: "WHERE file.name = "xxx" "

File.name
File.size
Contains "WHERE contains(author, "James Clear")"

SORT 

I'll show you my own simple dataview query to see which files I last created and edited, so I can stay on top of my notes.
I could give a whole other workshop on Dataview alone, but I'll just leave you with the link to the [official dataview guide](https://blacksmithgu.github.io/obsidian-dataview/)

# Use cases
## PKM / Zettelkasten
You can use your vault as a PKM system. Create notes, link them and watch your digital garden grow!

## Programming notes
I'm not an expert on this, but I'm sure you can find a use for Obsidian for your programming notes!

## Roleplaying games
You can have notes for characters, places, missions, objects, and so much more. Many people use Obsidian to plan out their DnD campaigns.

## Book writing
Using essentially the same notes as in the Roleplaying example, you can plan out your book on Obsidian. Never lose track of your plots. It might help you find possible plotpoints you didn't notice before!

## University note taking
Basically the same use case as a zettelkasten, but optimized for university! I have a master note (Map of Content, or MOC) for each subject and link all my class notes to it with a dataview query. There's even a flashcard plugin to help you study!

## Task management
There are so many great task-related community plugins, it's possible to replicate nearly every aspect of your standard task manager apps, right here in Obsidian! 

Join us on [/r/ObsidianMD](https://www.reddit.com/r/ObsidianMD/) or on [discord](https://discord.gg/obsidianmd)!
