### Welcome to the meon-translations repo! This is where you can find the translation files Meon uses and write your own translation.

### Currently supported Languages: Turkish, English, Polish and Spanish

# Writing a translation for Meon

1) First, go to the [`translations`](https://github.com/BoupsInc/meon-translations/blob/master/translations) folder and click "Add File".

2) Copy the entire content of [`en.json`](https://github.com/BoupsInc/meon-translations/blob/master/translations/en.json) and paste it to the file you just created.

### IMPORTANT: The file's name should be in [ISO 639-2](https://www.loc.gov/standards/iso639-2/php/code_list.php) format. For example, if you are writing a translation in Spanish, the files name would be `es.json`.

A small example of a Spanish translation:

```json
{
  "es": { 
    "INFO_TITLE": "Información de Meon"
  }
}
```

As you can see, the **properties** (`INFO_TITLE` in this case) stay the same in all of the files, but the **values** get translated to the language you are translating to.

If you want a translated example, you can check the [`tr.json`](https://github.com/BoupsInc/meon-translations/blob/master/translations/tr.json) file which is a Turkish translation of the [`en.json`](https://github.com/BoupsInc/meon-translations/blob/master/translations/en.json) file.

### If you have questions, you can always join the [support server](https://discord.gg/WZKGGmdCqX)!
