-citing orthographic system: not enough to say something is digital -they way a text is encoded should express the semantics of the text so that it can be tokenized -first token of Iliad: μηνιν, a leixcal token -funny fishtail: punctuation token, even if it looks like a comma plus semicolon, it just one token -tokens are not just charcters, but are always classified -for line of Iliad: 
create tokenized edition, add another level to citation hierarchy VA1.1.1: μηνιν analyze VA1.1.1 with orthographic system, it will tell you it is a lexical token TLG012-Homeric poetry 1-Iliad .msa -alt edition generated automatically: tlg12.tlgoo1.msadiplomatic, scribal for things like sic/corr -we have: orginal diplomatic edition, scribal version(acknowledigng scribes version, like with replaced words, or offering two readings(we take on on line as diplomatic, superscript as scirbal alternative)) modern editorial normalization(acknowleding unintellagible passages///misspellings, our own readings, connecting byzantine orthogrpahy with normal readings) -encoding multivalent (multiple possible readings) documents and generating univocal editions -strong feelings about using tei to get to something else -we use tei to encode the texts and get the univocal editions -can use univocal editoins reduce to text with no markup and cts urn

   we have two parellel vers of texts with same passage citations, but different version components
    urn:cts:greekLit:tlg0012: 3rd compoenent name space: 4th work, 5th passage(cna be empty, but can't leave out end colon
    urn:cts:greekLit:tlg5026:msAim.hmt:3- all intermarginal scholia in book 3 of HMT's Venetus a
    3.51r_1-book 3 51 recto scholia 1
    -3.209.comment (numbered scholia) 3 lexical tokens, 1 punction token
    orthographic system lets us tokenize our text
    urn:cts:greekLit:tlg5026.msAint.tokens:3.209.comment.1 -
    orthogrpyhy, og that tokenizes and class, once youve cl and tk you can apply a parsing system
    -we need the analytical corpus:citable corpus,w orthogrpahic system, and parsing system, must be coordinated
    if you have all 3, you can drop in one line EVERYTHING
    -the NICE tokenized edition
-citeable text -defines urn, aand a citeable resource, where we define cts urn
-urn: identifier for one specific thing with one specific syntax
-citeable resource- a page of VA, the Iliad, and image of   page, has idenitfier and human readable label, and for our scholarship, identifier must be urn
--must be able to be serielize din delimited text string, independent of any techonology
-coteableibjectLwe we define object/Cite2 urn
-top level components, speaprted by colons,have two siemaltaenous, overlapping hierarchies: work hierarchy (group, text, versionn, exemplar) ex: tlg0012.tlg001.villoison.jefferson each manuscript is unique, so they don't need exemplars and passage hierarchy (for Iliad two levels, book and line)
-for scholia, three levels (
--tlg5026: scholia to the ilad          tlg5026.msAim.: Venetus A intermaginal another tier:     .hmt, hmt version .hmt:3.51R_2.comment we can scite emma or comment seperately, no comment means take the whole scholia
msA:1.1-1.10 1 through 10 
-base what is a citeable object and text
-exchange:utility library, does delimited text reading and writing
citeable text: dse validation
-purple: core concepts of cite architecture
-orthograpy legitimate charcters and classes, how to break up at ext
-manuscript orthography: allows us to recongize fishtail as a punction mark
-light blue text stuff: kanones -morpholigcal parser
-orthography: recognizes our specific language tokens, ex: Dutch use characters like apostophes differently
-edition builder: generating systems of pairs: urns and readings for the corpus, normalize the edition in whichever way you chose
-xml infrastrucutre, and code that takes us to cleaner abstraction
-TEI reader reduces completion of xml (ex: 3.51R_2.comment), mapping text reader to citation scheme
-edition bulilder reduces complexity of different markup to make univocal text. , able to make multiple versions (ex: from hmtversion to diplomatic version, .hmt : archival xml document   .dipl : scribally normalized text with no xml markup
-could throw both in same courpus, and have multple versions of same text-with knaones, apply corpus analysis to text
