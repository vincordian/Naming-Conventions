# Naming conventions

It's annoying to read code that looks straight out of a garbage can
So I made this or whatever


# Functions

Have functions 2 blanks away from eachother (personal preference)

Such as:

```lua

  local function foo()

  end

  --Second function:
  local function foobar()

  end

```


# Casing

Private functions should have camelCase, constants should have SNAKE_CASE, and public functions should have lower_snake_case or PascalCase
PascalCase for everything else unless it has some weird name such as gtx_1090_ti


# Comments

Don't have redundant or contradictory comments. Use common sense


# Naming

Name variables exactly what it actually does

Such as:

```lua
  local DiscordLibrary = "foo"

  --Or:

  local function Double(Number)
    return Number * 2
  end
```
