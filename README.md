# Gitmoji for rofi

Custom file to show a [rofi-emoji](https://github.com/Mange/rofi-emoji) panel with only [gitmoji.dev](https://gitmoji.dev/) emojis.

Pass the file to rofi-emoji with the `-emoji-file` param.

![rofi-gitmoji](https://github.com/manuhabitela/rofit-gitmoji/assets/221253/b558fb5d-bb4d-434f-960c-017ea9818611)

## How the file was built

Quick and dirty made by hand, based on https://gitmoji.dev/api/gitmojis and https://github.com/Mange/rofi-emoji/blob/master/all_emojis.txt to build the list.

Iterated on each emoji of the gitmoji api, then added additional matching keywords from the all_emojis list.

:warning: Note that some emojis listed in in gitmoji don't seem to be the exact same of the usual ones of rofi-emojis. For example, gitmoji lists "♿️" while rofi-emoji uses "♿" and they seem actually different.

That made gitmoji commit linters return errors when using some default rofi-emojis. So this list fixes that and the few "different" emojis correctly match the precise gitmojis. Bye bye errors!
