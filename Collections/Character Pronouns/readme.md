Now you can specify your character's pronouns!
​
My hope is that by publishing this collection, it will enable other alias developers to easily and consistently have their aliases refer to characters by their specific pronouns rather than always using gender-neutral terms regardless of the character.
​
Pronoun settings are saved to the cvars `ungendered`, `they`, `them`, `their`, `theirs`, `pronouns_summary` and `plural_pronouns`.
​
Note that `plural_pronouns` will need to be manually set if applicable. It is a YAML list of any subject pronouns other than `they` which should likewise be treated as plural for the purposes of verbs that come after them.
​
__Alias Devs: How to Support Pronouns V2__
As of 9th Oct 2022, characters having multiple pronouns is supported! You can use the following module to have your alias randomly select pronouns from the possibilities the user has chosen.
```py
using(pronouns = '2c4012a3-accd-4fcf-a5e2-30bb51800c4e')
```
This module is really simple to use! Example:
```py
f"""{name} {pronouns.summary()} can now be referred to using {pronouns.their()} correct pronouns!
{pronouns.They()} {pronouns.verb('is', 'are')} great!
Victory is {pronouns.theirs()}!"""
```
​
__Old Method: How to Support Pronouns V1__
You can effectively load the character's pronouns even outside of Draconic. See below for an example:
​
`!test <name> (<they>/<them>) can now be referred to using <their> correct pronouns! Victory is <theirs>!`
​
__Contacting the Author__
If you find any issues or would like to request additional variables or features, please feel free to ping me on the Avrae Development Discord server.
​
Source code available on my [GitHub](https://github.com/Lathaon/Avrae-Aliases).
I don't like coffee, but feel free to support me on [Ko-Fi](https://ko-fi.com/lathaon).