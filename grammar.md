# grammar
> ⚠️ work in progress!

## syntax (ebnf)
* `<utterance>` ::= `[<conjunction>] <sentence> [<conjunction> [<sentence>]]`
* `<sentence>` ::= `[[<fronted_argument>] <predicate>] <argmuent>*`
* `<predicate>` ::= `<force> <content>`
* `<fronted_argument>` ::= `<word> | <argument>*`
* `<argument>` ::= `<role> [<role_clause>] | "io" <content> <argument>* ["no"]`
* `<role_clause>` ::= `<content> | "io" <content> <argument>* ["no"]`
* `<content>` ::= `<word>+ <na_phrase>`
* `<na_phrase>` ::= `"na" <content> | "na" <argument>`
* `<conjunction>` ::= `"oi" | "pa"`
* `<force>` ::= `"ka" | "ko" | "si" | "ma"`
* `<role>` ::= `"ia" | "mi" | "lo" | "la" | "li" | "ni" | "mo" | "so" | "sa" | "pi" | "po" | "sao"`
* `<word>` is any content word in the lami lioa dictionary (i.e. excluding particles)