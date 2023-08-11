# text-annotator
Text annotator is a simple Javascript based web document that allows the user to create interactive 
annotations on arbitrary text. It was created for the Reed College Quest, and is intended primarily
for use by newspapers focused on digital coverage.

## Instructions on How to Use This Template
1. Make a copy of the document titled web-version.html with a new filename, never edit this original source.
2. Insert your text under row > page-main > content-block. Wrap each new paragraph in 
    the paragraph tag p, and wrap each phrase to be annotated in the anchor tag a with the class 'note'.
    This is demonstrated in the template. No other modifications to the text are necessary, as the actual
    annotation process is handled by Javascript at the bottom of the page.
3. Under the first script block, update the annotations dictionary with each desired annotation,
    using the following format: "'annotated text goes here': 'annotation goes here',"
    End the dictionary with a semicolon. The dictionary keys must exactly match the text content of the
    annotated text in the paragraph, and each anchor tag must have exactly one dictionary reference. 
    Do not create anchor tags without matching dictionary references, or attempt to assign multiple annotations
    to one annotated phrase.
4. Copy and paste the entire document into a custom HTML field in WordPress or the CMS of your choice.

## Demonstration
For a working example, see <a href="https://reedquest.org/annotations-test/">https://reedquest.org/annotations-test/</a>
 
