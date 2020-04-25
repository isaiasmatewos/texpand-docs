# Configure Text Expansion

Learn how to configure text expansion to match your specific needs.

There are two ways to configure text expansion, **global settings** and **phrase settings**.

## Global Settings

Global text expansion settings change the text expansion behavior of all your phrases, except those that have their own [settings](#phrase-settings). 

To find global text expansion settings go to: 

*O pen Texpand → Menu (⠇) → Settings → Text Expansion* 

### Backspace to undo

If this is turned on tapping the backspace key (⌫) will change the expanded text back to the typed shortcut, helpful if you have mistakenly expanded a shortcut.

Turning it off will disable this behavior.

### Smart case

When turned on, smart case changes the expanded text case based on the case of the typed shortcut, example:

```
ty → thank you
Ty → Thank you
TY → THANK YOU
```

If smart case is disabled Texpand will expand the phrase as it is, without modifying it's case.

### Append space

If enabled Texpand will add a space at the end of the expanded text.


### Expand with space/punctuation

When enabled, this allows you to expand a shortcut by tapping space key or punctuation characters such as: `.,;:?`

If a punctuation character is used to expand a shortcut, it will be added to the end of the expanded text, example:

```
Hwr? → How are you?
Ty,  → Thank you, 
```

If this is disabled, you will have to tap the phrase preview window to expand text:

![Tap the preview window to expand](img/expand_by_tap.png)

If both [phrase preview](#phrase-preview) and "Expand with space/punctuation" are disabled, shortcuts will expand immediately without any user interaction.


## Phrase Settings

Phrase settings allow you to change expansion behavior of specific phrases, regardless of [global settings](#global-settings).

To open phrase settings:

![How to open phrase settings](img/phrase_settings_steps.png)


### Disable backspace to undo

Disables [backspace to undo](#backspace-to-undo) for a specific phrase.

### Disable smart case

Disables [smart case](#smart-case) for a phrase.

### Don't append space

Space won't be [appended](#append-space) when this phrase expands.

### Don't expand by space/punctuation

[Tapping the space key or typing a punctuation character](#expand-with-spacepunctuation) won't trigger expansion for a phrase.

### Expands within words

This makes it possible to expand a shortcut in between characters, for example, assume you have a shortcut 'tn' that expands to 'tion', if this is enabled you can do this:

```
Fixatn   →   Fixation
Correctn →   Correction
```

## Overlay UI settings

Texpand displays small overlay windows to assist you with inserting your phrases, you can configure many aspects of these windows by going to:

*Open Texpand → Menu (⠇) → Settings → Appearance & Overlay UI* 

You can also change application theme and language in this screen.


### Phrase preview

Phrase preview shows a small part of the phrase that's about to be inserted when you type a shortcut, you can also [open a phrase](/getting-started?id=opening-your-phrases-with-other-applications ':target=_self') with other applications by tapping the the icon that appears besides the phrase.

If you don't want to to see phrase previews, you can uncheck this setting.

>💡 You can open the phrase editor by long pressing the phrase window to quickly make changes to your phrase


### Configure shortcut suggestions window

Texpand displays [shortcut suggestions](/README?id=shortcut-suggestions) to help you easily find your shortcuts. You can configure how shortcut suggestions work by going to: 

*Menu (⠇) → Settings → Appearance & Overlay UI → Suggestions* 

#### Show shortcut suggestions

Enable/disable shortcut suggestions.

#### Suggestion indicator threshold

Texpand lets you know that there are shortcuts similar to the word you're typing by displaying a small search icon (🔍).

By default Texpand starts searching for similar shortcuts when you type at least 2 characters of a word, this setting allows you change the amount of characters that need to be typed before Texpand starts searching for similar shortcuts.

### Max shortcut suggestions to show

This setting determines how many shortcuts are displayed at once in the shortcut suggestion window. 

You can configure Texpand to display up to 6 shortcut suggestions.

## Configure phrase list window

Customize the [phrase list](/getting-started?id=creating-a-phrase-list ':target=_self') window.

### Tap space to show phrase list window

When this is enabled, you can tap space after typing a shortcut associated with a phrase list to see the phrase list items. 

If this is disabled you will have to tap the small list icon (<i class="bx bx-list-ul"></i>) to show a phrase list window.

### Max phrase list items to show

Use this setting to specify how many phrase list items are displayed at once in the phrase list window. 

You can configure Texpand to display up to 6 phrase list items.


## Extras

Additional overlay windows settings.

### Overlay UI timeout

Specifies how long (in seconds) overlay windows will be displayed before they are automatically closed. 

This only applies to: phrase previews, shortcuts suggestion indicator (🔍) and phrase list indicator (<i class="bx bx-list-ul"></i>)

> <i class='bx bx-info-circle' ></i> All overlay windows will be closed when 
		you navigate to another screen or tap another UI element.


### Overlay UI opacity

This settings allows you to change the transparency of overlay windows, by default they are opaque. This settings ranges from very transparent (5) to opaque (10).



