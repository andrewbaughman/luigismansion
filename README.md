
An h1 header
============

Paragraphs are separated by a blank line.

[comment]: <>2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
[comment]: <>look like:
[comment]: <>
[comment]: <>  * this one
[comment]: <>  * that one
[comment]: <>  * the other one
[comment]: <>
[comment]: <>Note that --- not considering the asterisk --- the actual text
[comment]: <>content starts at 4-columns in.
[comment]: <>
[comment]: <>> Block quotes are
[comment]: <>> written like so.
[comment]: <>>
[comment]: <>> They can span multiple paragraphs,
[comment]: <>> if you like.
[comment]: <>
[comment]: <>Use 3 dashes for an em-dash. Use 2 dashes for ranges (ex., "it's all
[comment]: <>in chapters 12--14"). Three dots ... will be converted to an ellipsis.
[comment]: <>Unicode is supported. ☺
[comment]: <>
[comment]: <>
[comment]: <>
[comment]: <>An h2 header
[comment]: <>------------
[comment]: <>
[comment]: <>Here's a numbered list:
[comment]: <>
[comment]: <> 1. first item
[comment]: <> 2. second item
[comment]: <> 3. third item
[comment]: <>
[comment]: <>Note again how the actual text starts at 4 columns in (4 characters
[comment]: <>from the left side). Here's a code sample:
[comment]: <>
[comment]: <>    # Let me re-iterate ...
[comment]: <>    for i in 1 .. 10 { do-something(i) }
[comment]: <>
[comment]: <>As you probably guessed, indented 4 spaces. By the way, instead of
[comment]: <>indenting the block, you can use delimited blocks, if you like:
[comment]: <>
[comment]: <>~~~
[comment]: <>define foobar() {
[comment]: <>    print "Welcome to flavor country!";
[comment]: <>}
[comment]: <>~~~
[comment]: <>
[comment]: <>(which makes copying & pasting easier). You can optionally mark the
[comment]: <>delimited block for Pandoc to syntax highlight it:
[comment]: <>
[comment]: <>~~~python
[comment]: <>import time
[comment]: <># Quick, count to ten!
[comment]: <>for i in range(10):
[comment]: <>    # (but not *too* quick)
[comment]: <>    time.sleep(0.5)
[comment]: <>    print(i)
[comment]: <>~~~
[comment]: <>
[comment]: <>
[comment]: <>
[comment]: <>### An h3 header ###
[comment]: <>
[comment]: <>Now a nested list:
[comment]: <>
[comment]: <> 1. First, get these ingredients:
[comment]: <>
[comment]: <>      * carrots
[comment]: <>      * celery
[comment]: <>      * lentils
[comment]: <>
[comment]: <> 2. Boil some water.
[comment]: <>
[comment]: <> 3. Dump everything in the pot and follow
[comment]: <>    this algorithm:
[comment]: <>
[comment]: <>        find wooden spoon
[comment]: <>        uncover pot
[comment]: <>        stir
[comment]: <>        cover pot
[comment]: <>        balance wooden spoon precariously on pot handle
[comment]: <>        wait 10 minutes
[comment]: <>        goto first step (or shut off burner when done)
[comment]: <>
[comment]: <>    Do not bump wooden spoon or it will fall.
[comment]: <>
[comment]: <>Notice again how text always lines up on 4-space indents (including
[comment]: <>that last line which continues item 3 above).

[comment]: <>Here's a link to [a website](http://foo.bar), to a [local
[comment]: <>doc](local-doc.html), and to a [section heading in the current
[comment]: <>doc](#an-h2-header). Here's a footnote [^1].
[comment]: <>
[comment]: <>[^1]: Some footnote text.
[comment]: <>
[comment]: <>Tables can look like this:
[comment]: <>
[comment]: <>Name           Size  Material      Color
[comment]: <>------------- -----  ------------  ------------
[comment]: <>All Business      9  leather       brown
[comment]: <>Roundabout       10  hemp canvas   natural
[comment]: <>Cinderella       11  glass         transparent
[comment]: <>
[comment]: <>Table: Shoes sizes, materials, and colors.
[comment]: <>
[comment]: <>(The above is the caption for the table.) Pandoc also supports
[comment]: <>multi-line tables:
[comment]: <>
[comment]: <>--------  -----------------------
[comment]: <>Keyword   Text
[comment]: <>--------  -----------------------
[comment]: <>red       Sunsets, apples, and
[comment]: <>          other red or reddish
[comment]: <>          things.
[comment]: <>
[comment]: <>green     Leaves, grass, frogs
[comment]: <>          and other things it's
[comment]: <>          not easy being.
[comment]: <>--------  -----------------------
[comment]: <>
[comment]: <>A horizontal rule follows.
[comment]: <>
[comment]: <>***
[comment]: <>
[comment]: <>Here's a definition list:
[comment]: <>
[comment]: <>apples
[comment]: <>  : Good for making applesauce.
[comment]: <>
[comment]: <> oranges
[comment]: <>   : Citrus!
[comment]: <> 
[comment]: <> tomatoes
[comment]: <>   : There's no "e" in tomatoe.
[comment]: <> 
[comment]: <> Again, text is indented 4 spaces. (Put a blank line between each
[comment]: <> term and  its definition to spread things out more.)
[comment]: <> 
[comment]: <> Here's a "line block" (note how whitespace is honored):
[comment]: <> 
[comment]: <> | Line one
[comment]: <> |   Line too
[comment]: <> | Line tree
[comment]: <> 
[comment]: <> and images can be specified like so:
[comment]: <> 
[comment]: <> ![example image](example-image.jpg "An exemplary image")
[comment]: <> 
[comment]: <> Inline math equation: $\omega = d\phi / dt$. Display
[comment]: <> math should get its own line like so:
[comment]: <> 
[comment]: <> $$I = \int \rho R^{2} dV$$
[comment]: <> 
[comment]: <> And note that you can backslash-escape any punctuation characters
[comment]: <> which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.
