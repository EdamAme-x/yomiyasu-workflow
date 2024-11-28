# Yomiyasu-workflow
`.ys` file parser in TypeScript

Parser for `yomiyasu` file that can be used in any environment (Web, Node, Deno, Bun, etc...)

```ruby
getData env:apiKey
  then result
     postData result
        then log
          print log
        catch error
          print log
  catch error
    print error
```
