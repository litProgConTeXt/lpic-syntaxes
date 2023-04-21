# Ruby Grammars

We use the Jeff Hykin's
[ruby_grammar_builder](https://github.com/jeff-hykin/ruby_grammar_builder) to
build all of the VSCode/TextMate grammars we *maintain*.

To re-build these grammars yourself, you will need to install both
[Ruby](https://www.ruby-lang.org/en/) and then the [ruby_grammar_builder
gem](https://rubygems.org/gems/ruby_grammar_builder). See these two links for
details on how to install these tools.

## Converting existing grammars to Ruby Grammar format...

The very crude tool `plist2rbGrammar` in the `OriginalGrammars` directory can be
used to translate an existing grammar (in PList format) into a *rough*
approximation of a Ruby Grammar. Unfortunately any Ruby Grammar created using
the `plist2rbGrammar` tool WILL need editing!

At the moment the only existing grammars we have converted are:

  - `context.tmLanguage` (from the `OriginalGrammars` directory)
