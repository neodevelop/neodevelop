# Hi, I'm neodevelop!

## Software developer at [MakingDevs](http://makingdevs.com)

[![Twitter: neodevelop](https://img.shields.io/twitter/follow/neodevelop?style=social)](https://twitter.com/neodevelop)
[![GitHub neodevelop](https://img.shields.io/github/followers/neodevelop?label=follow&style=social)](https://github.com/neodevelop)

I wrote some memories at [The Software Apprentice](http://the-software-apprentice.makingdevs.com).     
I transform coffee :coffee: into code, [look at this](http://users.barist.coffee/#profile/neodevelop)!    
Time ago I recorded :camera: a podcast at [ViveCodigo.org](http://vivecodigo.org)

## More about me!

### I like a lot the Elixir lang.

```elixir
def programming(me) do
  me
  |> add_coffee()
  |> take(the: "computer")
  |> write_your_thoughs(in: "requirements")
  |> learn
  |> drink(:beer)
end
```

### I write Ruby for helping people to learn; but the best part are the tests.

```ruby
RSpec.describe AutoResponse do
  [
    ["some 111 some","Thank you for contacting SMS Care. Our team will contact you soon for a free care referral."],
    #["some some","Please write us and include some code: 111 for contact, 222 for meet you better, 333 for mor info"],
    ["another response with 222","Thank you for contacting SMS Care. What is the name and age of your child? end with 221 code"]
  ].each do | sms, response |
    it "SMS is #{sms} and response is #{response}" do
      current_response = AutoResponse.instance.respond_to(sms)
      expect(current_response).to eq(response)
    end
  end
end
```

### I do Java in a Groovy way

```groovy
Me.metaClass.code { -> }
```

### Haskell it's impressive

```haskell
qsort [] = []
qsort(x:xs) = qsort smaller ++ [x] ++ qsort larger
              where
                smaller = [ a | a <- xs, a <= x]
                larger = [ b | b <- xs, b > x]
```

### But I do Haskell for the Web

```elm
improveProgrammer : Model -> Me -> Model
improveProgrammer model programmer =
    let
        skillProgrammer =
            { programmer
                | username = user.username
                , currentSkill = "Functional programming"
            }
    in
        { model
            | programmer = skillProgrammer }
```

### I'm huge fan of John McCarty!

```clojure
(me 
  (as 
    (a coder)))
```

### Also I run boxes in others computers for living...

```docker
FROM alpine:3.7
RUN apk add --no-cache all-the-tools
ENTRYPOINT ["all-the-tools"]
```

### I use the command line everyday

```shell
tail -f application.log | awk '
  /info/ {print "\033[32m" $0 "\033[39m"}
  /debug/ {print "\033[34m" $0 "\033[39m"}
  /warn/ {print "\033[33m" $0 "\033[39m"}
  /error/ {print "\033[31m" $0 "\033[39m"}'
```

I'm not a robot :robot:

[![neodevelop's github stats](https://github-readme-stats.vercel.app/api?username=neodevelop)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=neodevelop&hide=css)](https://github.com/anuraghazra/github-readme-stats)
