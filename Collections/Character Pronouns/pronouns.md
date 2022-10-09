Displays or sets your active character's pronouns, with an example of how to use them in sentences.
​
__Arguments__
* *(no args)* - Just displays your character's pronouns, defaulting to they/them.
* `[they|she|he]` - Sets your character's pronouns to one of the presets: gender-neutral plural (they/them/their/theirs), female (she/her/her/hers), or male (he/him/his/his), respectively.
* `<they> <them> <their> <theirs> [they/them]` - Sets custom pronouns. You'll need to include all of the first four as arguments, in the order given. The fifth argument is optional and allows you to customize what should be shown in brackets after the character's name.
​
__Multiple Pronouns__
You can specify multiple options for the same argument by separating them with a forward slash. For example, `he/they`.
​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​
​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​
Alias developers can use the following module to easily support multiple pronouns, randomly selecting from the possible options each time.
```py
using(pronouns = '2c4012a3-accd-4fcf-a5e2-30bb51800c4e')
```
Any aliases still using the old method will just show all options every time.