# HTML Notes

## Headings
- headings are used for titles and sections
- h1 to h6 → titles and subtitles
- h1 is the most important heading(Main title)
- h2 for Subtitle
- h3 for Section 
- h6 is the least important

## Title tag
- title → sets the page title
- shown in the browser tab
- written inside the head element


## Document Structure & Meta Tags
- <!DOCTYPE html> → defines HTML5 document
- lang attribute → page language
- head → metadata container
- body → page content

###  Meta Tags
- meta charset → character encoding (UTF-8)
- meta description → page description
- meta keywords → page keywords
- meta author → page author
- meta viewport → responsive design
- meta http-equiv refresh → auto refresh page

### Other Tags
- br → line break
- hr → horizontal line


## Text content and code tags 
- p → paragraph text
- pre → preformatted text (keeps spaces and line breaks)
- code → displays code snippets



## Comments and inline elements
- <!-- comment --> → HTML comment (not shown in browser)
- span → inline container for text styling

## Text formatting tags
- b → bold text (visual only)
- strong → important text (semantic)
- i → italic text (visual only)
- em → emphasized text (semantic)
- small → smaller text
- mark → highlighted text
- u → underlined text
- ins → inserted text (semantic underline)
- s → incorrect text
- del → deleted text (semantic)
- sub → subscript text
- sup → superscript text

###  Differences and usage
- strong vs b → use strong for importance, b for style
- em vs i → use em for emphasis, i for style
- del vs s → del has semantic meaning
- ins vs u → ins has semantic meaning


## Images
- img → displays an image
- src → image URL/path
- alt → alternative text (important for accessibility)
- title → tooltip text on hover
- width / height → image size
- border → adds a border (better to do with CSS later)


## Audio
- audio → plays audio on the page
- source → provides the audio file
- type → file MIME type (e.g. audio/mpeg)
- controls → show play/pause controls
- loop → repeat audio
- muted → start muted


## Video
- video → plays video on the page
- width / height → video size
- controls → show player controls
- loop → repeat video
- muted → start muted
- autoplay → start automatically (often requires muted)
- poster → image shown before video plays
- preload → how the browser loads video (none / metadata / auto)

###  Subtitles (track)
- track → subtitles/captions file
- kind → type (subtitles / captions)
- label → name shown in player
- default → enabled by default



## Tables
- table → creates a table
- thead → header section
- tbody → body rows
- tfoot → footer section
- th → header cell
- td → normal cell
- caption → table title
- colspan → merge columns
- rowspan → merge rows




## Lists

### Unordered list
- ul → unordered list
- li → list item

### Ordered list
- ol → ordered list
- li → list item
- type → numbering style (1, A, a, I)
- start → starting number
- reversed → reverse order

### Description list
- dl → description list
- dt → term/name
- dd → description/details


## Containers and Semantic Elements

### Container elements (generic)
- div → generic block container (no meaning)
- span → generic inline container (no meaning)
Use them mainly for grouping + CSS styling.

### Semantic elements (have meaning)
- header → top area (logo/title)
- nav → navigation links
- main → main content of the page (once)
- section → a section of content
- article → independent content (post/news)
- aside → side content (sidebar/ads/notes)
- footer → bottom area (copyright/links)

### Why semantic?
- clearer code
- better accessibility (screen readers)
- better SEO

