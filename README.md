# DraftsAppendNoteObsidian
A Drafts action to append a draft to a pre-selected Obsidian note. Available [here](https://directory.getdrafts.com/a/2Uo) in the Drafts Directory.

## Background
- This is a very simple action that I use to put terms into Anki decks. I have one Obsidian note setup for each Anki deck, and whenever I think of a new term to put into an Anki deck, I write it down in Drafts. With this action, I don't have to copy and paste anything. 

## Requirements
- [Advanced URI Plugin](https://github.com/Vinzent03/obsidian-advanced-uri) enabled in Obsidian 

## Configuration
- Fill in the `vault` Template Tag with your vault name, e.g., `Personal`. 
- Do the same with the relative path of the note for the `NoteToAppend` Template Tag. This should be the relative path to the file in your vault. In my case, I use notes in my Anki folder, so appending to the `English` note would be done as such: `Anki/English`. 

Drafts handles all of the URL encoding for the vault name, file path, and draft contents. For doing the same thing to multiple notes, simply duplicate the action and specify the desired file path in each one. I do this and have separate actions for separate notes in order to avoid having to navigate menus within actions.