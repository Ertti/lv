### Theme
1. Atrodi theme kas tevi interesē.
2. Atver termināli un ievadi kādu no šīm komandām atkarībā no situācijas:
![[Pasted image 20240513170000.png]]
    1) Izmanto šo komandu ja tavs theme ir no marketplace. (Protams AuthorName.ThemeName vietā rakstīt atrastā theme autoru.nosaukumu)![[Pasted image 20240513170100.png]]
	{php artisan theme:install AuthorName.ThemeName}

    2) Ja tavs theme atrodas citā vietnē izmanto komandu "--from" kā paraugā
    {php artisan theme:install AuthorName.ThemeName --from=git@github.com:authorname/themename-theme.git}

    3) Ja zini īpašu versiju ko vēlies ielādēt izmanto komandu "--want" kā paraugā
    {php artisan theme:install AuthorName.ThemeName --from=git@github.com:authorname/themename-theme.git --want=dev-develop}

    4) Failā ar "oc" izmanto "--oc" kā paraugā
    {php artisan theme:install AuthorName.ThemeName --from=git@github.com:authorname/oc-themename-theme.git --oc}

### Plugin
1. Tāpat kā theme atrodi plugin.
2. Atver termināli un ievadi kādu no šīm komandām atkarībā no situācijas:
![[Pasted image 20240513170015.png]]
    1) Izmanto šo komandu ja tavs plugin ir no marketplace. (Protams AuthorName.PluginName vietā rakstīt atrastā theme autoru.nosaukumu)![[Pasted image 20240513170046.png]]
    {php artisan plugin:install AuthorName.PluginName}

    2) Ja tavs plugin atrodas citā vietnē izmanto komandu "--from" kā paraugā
    {php artisan plugin:install AuthorName.PluginName --from=git@github.com:authorname/pluginname-plugin.git}

    3) Ja zini īpašu versiju ko vēlies ielādēt izmanto komandu "--want" kā paraugā
    {php artisan plugin:install AuthorName.PluginName --from=git@github.com:authorname/pluginname-plugin.git --want=dev-develop}

    4) Failā ar "oc" izmanto "--oc" kā paraugā
    {php artisan plugin:install AuthorName.PluginName --from=git@github.com:authorname/pluginname-plugin.git --oc}
    
### Pēc tam
4. Ieraksti komandu {php artisan project:sync}, lai lejupielādētu visus nepieciešamos themes un plugins.
5.  Ieraksti pēdējo komandu {php artisan october:update}, lai atjauninātu visu un veiktu datubāzes migrāciju.
