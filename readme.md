DefaultKeyBindings.dict file (`~/Library/KeyBindings/DefaultKeyBindings.dict`) for Mac OS X, created by [Brett Terpstra][] and based heavily on work done by [Lri][lrikeys].
Please note that these bindings won't work in all applications: TextWrangler and TextMate, for example, override these with their own settings.
See Lri's [website][lriweb] for more coding madness.

[lrikeys]: http://osxnotes.net/keybindings.html
[lriweb]: http://osxnotes.net/
[brett terpstra]: http://brettterpstra.com

**Installation:** Copy the DefaultKeyBindings.dict file to the `~/Library/KeyBindings/` directory (create `KeyBindings` if it doesn't already exist). 
Any open applications will need to be re-started before the key bindings will take effect -- or log out and log back in.

For more information, see my [blog post](http://brettterpstra.com/keybinding-madness/), check out [Macworld hints](http://hints.macworld.com/article.php?story=20060317045211408), an older but very relevant [article from Harvard](http://www.hcs.harvard.edu/~jrus/site/cocoa-text.html) and do [a search for more information](http://duckduckgo.com/?q=cocoa+defaultkeybindings.dict).

<b>Documentation</b> <i>(last updated 05/08/2012.)</i>

*Grouped items begin with the groups shortcut (if exists), followed by a subgroup (if exists) followed by the keys specified.*

<table>
<caption id="generalcommands"> General Commands </caption>
<colgroup>
<col style="text-align:center;"/>
<col style="text-align:left;"/>
</colgroup>

<thead>
<tr>
    <th style="text-align:center;" colspan="2">General Commands</th>
</tr>
<tr>
    <th style="text-align:center;">Key</th>
    <th style="text-align:left;">Function</th>
</tr>
</thead>

<tbody>
<tr>
    <td style="text-align:center;">^y</td>
    <td style="text-align:left;">replace yank: command with yankAndSelect for use with the kill ring ( defaults write -g NSTextKillRingSize -string 6)</td>
</tr>
<tr>
    <td style="text-align:center;">^⇧u</td>
    <td style="text-align:left;">uppercase word</td>
</tr>
<tr>
    <td style="text-align:center;">^⌥u</td>
    <td style="text-align:left;">lowercase word</td>
</tr>
<tr>
    <td style="text-align:center;">^⇧t</td>
    <td style="text-align:left;">titlecase word</td>
</tr>
<tr>
    <td style="text-align:center;">^⌥⇧u</td>
    <td style="text-align:left;">uppercase current paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">^⌥t</td>
    <td style="text-align:left;">titlecase paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">^w</td>
    <td style="text-align:left;">delete word before cursor</td>
</tr>
<tr>
    <td style="text-align:center;">⌥w</td>
    <td style="text-align:left;">select word</td>
</tr>
<tr>
    <td style="text-align:center;">⌥⇧s</td>
    <td style="text-align:left;">select entire line/paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">⌥s</td>
    <td style="text-align:left;">select from beginning of paragrah to last character</td>
</tr>
<tr>
    <td style="text-align:center;">^⌥⇧s</td>
    <td style="text-align:left;">select paragraph excluding leading/trailing whitespace (same as ^$@\UF701)</td>
</tr>
<tr>
    <td style="text-align:center;">⌥d</td>
    <td style="text-align:left;">delete line/paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">⌥y</td>
    <td style="text-align:left;">copy paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">⌥x</td>
    <td style="text-align:left;">cut paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">⌥p</td>
    <td style="text-align:left;">paste paragraph below</td>
</tr>
<tr>
    <td style="text-align:center;">⌥⇧p</td>
    <td style="text-align:left;">paste paragraph above</td>
</tr>
<tr>
    <td style="text-align:center;">^⇧a</td>
    <td style="text-align:left;">select to beginning of paragraph and copy</td>
</tr>
<tr>
    <td style="text-align:center;">^⇧e</td>
    <td style="text-align:left;">select to end of paragraph and copy</td>
</tr>
<tr>
    <td style="text-align:center;">⌥q</td>
    <td style="text-align:left;">cut to beginning of paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">⌥k</td>
    <td style="text-align:left;">cut to end of paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">⌥o</td>
    <td style="text-align:left;">blank line after current</td>
</tr>
<tr>
    <td style="text-align:center;">⌥⇧o</td>
    <td style="text-align:left;">blank line before current</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘k</td>
    <td style="text-align:left;">move line up</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘j</td>
    <td style="text-align:left;">move line down</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘l</td>
    <td style="text-align:left;">indent line</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘h</td>
    <td style="text-align:left;">outdent line (one tab or char)</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘↑</td>
    <td style="text-align:left;">move line up ( same commands but with arrow keys)</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘↓</td>
    <td style="text-align:left;">move line down</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘→</td>
    <td style="text-align:left;">indent line</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘←</td>
    <td style="text-align:left;">outdent line (one tab or char)</td>
</tr>
<tr>
    <td style="text-align:center;">^⇧⌘←</td>
    <td style="text-align:left;">Full outdent - Deletes all leading space of line/paragraph (updated) ( Control-shift-command-left arrow)</td>
</tr>
<tr>
    <td style="text-align:center;">^⇧⌘→</td>
    <td style="text-align:left;">Delete trailing space</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘⇧↑</td>
    <td style="text-align:left;">Delete leading and trailing whitespace for paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘⇧↓</td>
    <td style="text-align:left;">Select paragraph without leading or trailing whitespace (same as &#8220;^~s&#8221;)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥⇧↑</td>
    <td style="text-align:left;">modify selection up by paragraph (Command Option Shift Up)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥⇧↓</td>
    <td style="text-align:left;">modify selection down by paragraph (Command Option Shift Down)</td>
</tr>
<tr>
    <td style="text-align:center;">^⌥⇧←</td>
    <td style="text-align:left;">modify selection left by word</td>
</tr>
<tr>
    <td style="text-align:center;">^⌥⇧→</td>
    <td style="text-align:left;">modify selection right by word</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥^←</td>
    <td style="text-align:left;">Move to first Alphanumeric character of line (new)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥←</td>
    <td style="text-align:left;">Move to first non-whitespace character of line (new)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥⇧←</td>
    <td style="text-align:left;">Select to first character of line with leading space (new)</td>
</tr>
<tr>
    <td style="text-align:center;">⌥⌘→</td>
    <td style="text-align:left;">Move to last non-whitespace character of paragraph (new)</td>
</tr>
<tr>
    <td style="text-align:center;">^⌥→</td>
    <td style="text-align:left;">Move to end of paragraph and delete trailing whitespace (new)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘↩</td>
    <td style="text-align:left;">TextMate Command-Return (Command Enter)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⇧↩</td>
    <td style="text-align:left;">Insert blank line above paragraph (Command Shift Enter)</td>
</tr>
<tr>
    <td style="text-align:center;">⌥_</td>
    <td style="text-align:left;">hyphenate next space and move to next word ( this will kill non alphanumeric symbols and punctuation, use only on <em>words</em>)</td>
</tr>
<tr>
    <td style="text-align:center;">⌥1</td>
    <td style="text-align:left;">bookmark</td>
</tr>
<tr>
    <td style="text-align:center;">⌥2</td>
    <td style="text-align:left;">jump to bookmark</td>
</tr>
<tr>
    <td style="text-align:center;">⌥⌘↩</td>
    <td style="text-align:left;">Continue a list item with indentation and include the same delimiter ( Command Option Enter)</td>
</tr>
<tr>
    <td style="text-align:center;">⇧⇥</td>
    <td style="text-align:left;">remove one tab (or character) from start of line (outdent) ( Shift Tab)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥b</td>
    <td style="text-align:left;">bold selection (Markdown)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥i</td>
    <td style="text-align:left;">italicize selection (Markdown)</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥=</td>
    <td style="text-align:left;">increase markdown header level</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥-</td>
    <td style="text-align:left;">decrease markdown header level</td>
</tr>
<tr>
    <td style="text-align:center;">^⌥↩</td>
    <td style="text-align:left;">Add hard break for current line and insert newline below (new)</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘↩</td>
    <td style="text-align:left;">Break line at cursor and add Markdown hard line break (new)</td>
</tr>
<tr>
    <td style="text-align:center;">^&lt;</td>
    <td style="text-align:left;">Make selected text into paired HTML tag. Allows attributes, only dupes first word into closing tag (caveat: overwrites your pasteboard)</td>
</tr>
<tr>
    <td style="text-align:center;">⌥r</td>
    <td style="text-align:left;">repeat character before cursor</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⇧⌦</td>
    <td style="text-align:left;">Forward delete to end of paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⇧⌫</td>
    <td style="text-align:left;">Delete to beginning of paragraph</td>
</tr>
<tr>
    <td style="text-align:center;">⌘⌥7</td>
    <td style="text-align:left;">Right mouse click (useless, doesn&#8217;t maintain cursor position)</td>
</tr>
</tbody>
</table>


<table>
<caption id="commentingcommands"> Commenting commands </caption>
<colgroup>
<col style="text-align:center;"/>
<col style="text-align:center;"/>
<col style="text-align:center;"/>
<col style="text-align:left;"/>
</colgroup>

<thead>
<tr>
    <th style="text-align:center;" colspan="4">Commenting commands (^⌘c)</th>
</tr>
</thead>

<tbody>
<tr>
    <td style="text-align:center;">^⌘c</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">/</td>
    <td style="text-align:left;">comment with &#8220;//&#8221;</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘c</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">\</td>
    <td style="text-align:left;">comment with &#8220;#&#8221;</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘c</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">!</td>
    <td style="text-align:left;">HTML commenting</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘c</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">*</td>
    <td style="text-align:left;">Css Commenting</td>
</tr>
</tbody>
</table>


<table>
<caption id="multi-strokemarkdowncommands"> Multi-stroke Markdown commands </caption>
<colgroup>
<col style="text-align:center;"/>
<col style="text-align:center;"/>
<col style="text-align:center;"/>
<col style="text-align:left;"/>
</colgroup>

<thead>
<tr>
    <th style="text-align:center;" colspan="4">Multi-stroke Markdown commands (^⌘w)</th>
</tr>
</thead>

<tbody>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">␍</td>
    <td style="text-align:left;">force carriage return in text field</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">⇥</td>
    <td style="text-align:left;">force tab in text field</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">\</td>
    <td style="text-align:left;">insert reference link <code>[selection][[cursor]]</code></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">\</td>
    <td style="text-align:left;">insert reference <code>[selection]: [cursor]</code></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">+</td>
    <td style="text-align:left;">Unordered list item with</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">-</td>
    <td style="text-align:left;">Unordered list item with -</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">*</td>
    <td style="text-align:left;">Unordered list item with *</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">8</td>
    <td style="text-align:left;">convert current numbered list item to bullet, handles indentation</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">1</td>
    <td style="text-align:left;">convert current bullet list item to numbered</td>
</tr>
<tr>
    <td style="text-align:center;" colspan="3">Headlines (removes leading whitespace after inserting hashmarks) (h)</td>
    <td style="text-align:center;"></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">h</td>
    <td style="text-align:center;">1</td>
    <td style="text-align:left;">#</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">h</td>
    <td style="text-align:center;">2</td>
    <td style="text-align:left;">##</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">h</td>
    <td style="text-align:center;">3</td>
    <td style="text-align:left;">###</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">h</td>
    <td style="text-align:center;">4</td>
    <td style="text-align:left;">####</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">h</td>
    <td style="text-align:center;">5</td>
    <td style="text-align:left;">#####</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">h</td>
    <td style="text-align:center;">6</td>
    <td style="text-align:left;">######</td>
</tr>
<tr>
    <td style="text-align:center;" colspan="4"></td>
</tr>
<tr>
    <td style="text-align:center;" colspan="3">Markdown link (l)</td>
    <td style="text-align:center;"></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">l</td>
    <td style="text-align:center;">t</td>
    <td style="text-align:left;">create a link for selected text, cursor between () <code>[selected text]([cursor])</code> ( links without selected text first, these can produce a mess using multiple clipboards make a text selection before you run them)</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">l</td>
    <td style="text-align:center;">c</td>
    <td style="text-align:left;">create a link for selected text, inserting clipboard as url <code>[[cursor]selected text](clipboard contents)</code></td>
</tr>
<tr>
    <td style="text-align:center;" colspan="4"></td>
</tr>
<tr>
    <td style="text-align:center;" colspan="3">Link as image (i)</td>
    <td style="text-align:center;"></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">i</td>
    <td style="text-align:center;">t</td>
    <td style="text-align:left;">same as lt, but with image syntax <code>![selected text]([cursor])</code></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">i</td>
    <td style="text-align:center;">c</td>
    <td style="text-align:left;">same as lc, but with image syntax <code>![selected text](clipboard)</code></td>
</tr>
<tr>
    <td style="text-align:center;" colspan="4"></td>
</tr>
<tr>
    <td style="text-align:center;" colspan="3">Reference links (:)</td>
    <td style="text-align:center;"></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">:</td>
    <td style="text-align:center;">t</td>
    <td style="text-align:left;">create a reference from selected text</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘w</td>
    <td style="text-align:center;">:</td>
    <td style="text-align:center;">c</td>
    <td style="text-align:left;">create a reference from selected text, clipboard as url</td>
</tr>
<tr>
    <td style="text-align:center;" colspan="4"></td>
</tr>
</tbody>
</table>


<table>
<caption id="htmlcommands"> HTML commands </caption>
<colgroup>
<col style="text-align:center;"/>
<col style="text-align:center;"/>
<col style="text-align:center;"/>
<col style="text-align:left;"/>
</colgroup>

<thead>
<tr>
    <th style="text-align:center;" colspan="4">HTML commands (^⌘e)</th>
</tr>
</thead>

<tbody>
<tr>
    <td style="text-align:center;">^⌘e</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">=</td>
    <td style="text-align:left;">=&#8220;[cursor]&#8221;</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘e</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">e</td>
    <td style="text-align:left;">entity &amp;[cursor];</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘e</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">/</td>
    <td style="text-align:left;">http://</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘e</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">t</td>
    <td style="text-align:left;">Make previous word into paired HTML tag</td>
</tr>
<tr>
    <td style="text-align:center;" colspan="3">HTML Links (a)</td>
    <td style="text-align:center;"></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘e</td>
    <td style="text-align:center;">a</td>
    <td style="text-align:center;">t</td>
    <td style="text-align:left;">Insert HTML link for selected text, leave cursor in the href with &#8220;http://&#8221; selected</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘e</td>
    <td style="text-align:center;">a</td>
    <td style="text-align:center;">c</td>
    <td style="text-align:left;">Insert HTML link with clipboard as href</td>
</tr>
<tr>
    <td style="text-align:center;" colspan="4"></td>
</tr>
<tr>
    <td style="text-align:center;" colspan="3">HTML Image (i)</td>
    <td style="text-align:center;"></td>
</tr>
<tr>
    <td style="text-align:center;">^⌘e</td>
    <td style="text-align:center;">i</td>
    <td style="text-align:center;">t</td>
    <td style="text-align:left;">Insert image tag, any selected text is alt text, leave cursor in src attribute</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘e</td>
    <td style="text-align:center;">i</td>
    <td style="text-align:center;">c</td>
    <td style="text-align:left;">Insert image tag, clipboard as src, any selected text as alt, leave cursor at beginning of alt attribute</td>
</tr>
<tr>
    <td style="text-align:center;" colspan="4"></td>
</tr>
</tbody>
</table>


<table>
<caption id="surroundcommands"> Surround commands </caption>
<colgroup>
<col style="text-align:center;"/>
<col style="text-align:center;"/>
<col style="text-align:center;"/>
<col style="text-align:left;"/>
</colgroup>

<thead>
<tr>
    <th style="text-align:center;" colspan="4">Surround commands (^⌘s)</th>
</tr>
</thead>

<tbody>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">(</td>
    <td style="text-align:left;">wrap () with spaces</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">)</td>
    <td style="text-align:left;">wrap () no spaces</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">\</td>
    <td style="text-align:left;">wrap [] with spaces</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">\</td>
    <td style="text-align:left;">wrap [] no spaces</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">{</td>
    <td style="text-align:left;">wrap {} with spaces</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">}</td>
    <td style="text-align:left;">wrap {} no spaces</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">&lt;</td>
    <td style="text-align:left;">wrap &lt;&gt; with spaces</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">&gt;</td>
    <td style="text-align:left;">wrap &lt;&gt; no spaces</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">&#8217;</td>
    <td style="text-align:left;">wrap single quotes</td>
</tr>
<tr>
    <td style="text-align:center;">^⌘s</td>
    <td style="text-align:center;"></td>
    <td style="text-align:center;">`</td>
    <td style="text-align:left;">wrap backticks</td>
</tr>
</tbody>
</table>

This documentation is generated automatically from the comments and commands in the DefaultKeyBinding.dict file. The script `document_keybindings.rb` is free for use, but it's specifically designed for use with my formatting in the bindings plist (i.e. it's a little finicky).

