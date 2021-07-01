# wildermyth-de
 
(Hab noch keine Ahnung wie das hier auf GITHub läuft, also Tipps gerne gesehen!)
kleiner Sammler um Wildermyth zu übersetzen. Mitarbeit gerne gesehen. Ich würde mich an die Anleitung auf https://wildermyth.com/wiki/index.php?title=Translating halten:

Workflow
We recommend starting with interface.properties. Get the interface showing up correctly. If your target language cannot be rendered in the game's font, please contact us and we'll work out a font set, and add it as an option for you to choose. You'll have to choose "Use Local Fonts" while translating.

After the interface bundle, tackle dynamic, presentation, scenarios, errors, and aspects.

"story" can largely be editing in the "History" tab of the editor and should be done there. "effects" including comics should be edited in the comic editor. The flow for non-comic events is not finished yet but might use the bundling/un-bundling option discussed above.

When translating comics, you'll need to understand how tags work, particularly gender splits, since you may have to write your own depending on your language. The Writer's Guide and Tag Reference goes over how they work. The comic editor is highly recommended because it will give you feedback that your tags are correct, let you see the stories in context, and reroll parties to make sure all variations work. It will also let you adjust individual text box positions and sizes. These adjustments are saved to the .properties file of the event as ~TWEAK lines, you will see them in there. ONLY text boxes can be adjusted this way, actors or other comic details can not.
