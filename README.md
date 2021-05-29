# UEFA Euro 2020 Fantasy Football Team Picker.
This is a (very) early draft code for a random team selector based around the Fantasy Football model for Euro 2020. It is subject to massive refactors and changing the way it works and really really really could do with a feed for the data since there is masses of it to enter, especially if players are extended to have rankings and stats around them like on https://www.uefa.com/uefaeuro-2020/performancezone/#/  

The rules for team selection are:
No Duplicates
2x Goalies
4x Defenders
3x Midfielders
2x Forwards
3x Substitutes selected from defenders, midfielders and forwards.

## Todo
### Players.
Extend players into objects that can contain more information like player ranking, country, etc

### API.
Ideally find a free API that will provide all the above information would be ideal. Failing that write a scraper in PHP / Python for the above linked site. Potentially switch to database usage instead of straight JSON or a combination of the two.

### Save/Load/Export/Import.
Ability to save current teams and load them in with updating stats and ability to export/import teams as JSON for use in other tools.

### Code.
Stop making the baby Jesus weep and write some non terrible code after all the refactors.
