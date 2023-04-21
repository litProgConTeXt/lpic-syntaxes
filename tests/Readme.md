# Testing tmLanguage.json grammars

To test a tmLanguage.json grammar, you can run the `testGrammar` javascript
command line tool found in this directory.

This `testGrammar` tool *MUST* be run inside this `tests` directory.

The `testGrammar` tool expects a TeX file as the only command line argument.
This TeX file will be loaded and parsed with the appropriate grammar. The
*first* line of the TeX file specifies which grammar to test and must be one of
the following forms:

- `%% context`
- `%% lpic`

## Example 

For example to test the `context.tmLanguage.json` grammar type:

```
  cd tests
  ./testGrammar jsonEcho.tex
```
To test the `lpic.tmLanguage.json` grammar type:

```
  cd tests
  ./testGrammar jeMain.tex
```
