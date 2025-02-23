# Summa Experientia

Flow: you create a dhall file with write-ups of some of your achievements (i.e. experience) as well as their descriptions (i.e. interpretation of your experience).
Why: someday you will want to get back to see what you've done so far that's where Summa Experientia will cover you! It catalogs all your achievements and lets you see them in some beautiful ways.

There would be a project the main artifacts of which are:
- dhall library of configuration generation functions
  - the whole thing should be a one big object with all your achievemnts
  - it should be queryable using dhall functions in order to make really nice dev UX
  - it ofcourse should be importable into other dhall configurations :D
- static site generator (actually SSG is just a component)
