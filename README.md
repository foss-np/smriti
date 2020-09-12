# Smriti
## Translation Memory (TM)

A translation momory (TM) is a data store /database to store "segments", which are sentences or paragraphs or sentence like units those are previously been translated. Each segments are called translation units (TU)  each TU has at least two parts of information : source segment and the target unit. 

Smaller units such as words or idioms are handled by Translation memory and handled by Glossaries/ Terminologies or a translation/Localization project.

## Translation Memory eXchange (**TMX**)

Out of numerous popular formats for sharing and exchangin Translation Memory TMX is one. It is a based on the XML specification. 

An example TMX file looks like this : 

``` xm
<tmx version="1.4">
  <header
    creationtool="XYZTool" creationtoolversion="1.01-023"
    datatype="PlainText" segtype="sentence"
    adminlang="en-us" srclang="en"
    o-tmf="ABCTransMem"/>
  <body>
    <tu>
      <tuv xml:lang="en">
        <seg>Hello world!</seg>
      </tuv>
      <tuv xml:lang="fr">
        <seg>Bonjour tout le monde!</seg>
      </tuv>
    </tu>
  </body>
</tmx>
```

## Why Translation Memory (TM)

- TM helpes in a localization or translation project by increasing contributor productivity.
- TM helps maintain consistency across localization or translations project if shared same set of TM.

## Open Translation Memory (TM)

Open Translation Memory that is reviewed by the community and can be used freely* is a must have thing. 



