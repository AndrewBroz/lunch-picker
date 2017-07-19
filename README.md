# [Lunch Picker][docs]

[![Run in Postman][button]][run]

[Lunch Picker][docs] is a [Postman collection][collections] that acts as a restaurant discovery service, powered by the [Yelp Fusion API][yelp]. It suggests places for you or a team to have lunch and posts them to Slack, and can be run locally with the [Postman collection runner][runner] or with [Newman][newman], or as a scheduled remote job with [Postman Monitors][monitors].

You can [customize Lunch Picker's restaurant selection criteria][options] such as location, distance, and price range with [environment variables][environments]. The collection automatically saves its choice history to a [Postman environment][environments] and uses that history to make sure the selections stay interesting each time it's run.

Start by [reading the docs][docs], then try [running Lunch Picker in Postman][run]. _Bon appétit!_

![An Example Slack Post][post]

_MIT License, Copyright (c) 2017 Andrew Broz_


[button]: https://run.pstmn.io/button.svg
[collections]: https://www.getpostman.com/docs/postman/collections/creating_collections "About Collections"
[docs]: https://documenter.getpostman.com/view/218543/lunch-picker/6fWy4Ao "Lunch Picker Documentation"
[environments]: https://www.getpostman.com/docs/postman/environments_and_globals/manage_environments "About Environments"
[monitors]: https://www.getpostman.com/docs/postman/monitors/intro_monitors "Postman Monitors"
[newman]: https://www.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman "Newman CLI"
[options]: https://documenter.getpostman.com/view/218543/lunch-picker/6fWy4Ao#cc479560-f6cf-f199-1757-65d9f051a324 "Lunch Picker Options"
[post]: https://i.imgur.com/2YJeB28.png "An example Slack post with restaurant picks from Lunch Picker running as an 8am monitor."
[run]: https://app.getpostman.com/run-collection/b3b712104cbac4d1a152#?env%5BLunch%20Picker.template%5D=W3siZW5hYmxlZCI6dHJ1ZSwia2V5IjoieWVscENsaWVudElEIiwidmFsdWUiOiIiLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoieWVscENsaWVudFNlY3JldCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6InllbHBBY2Nlc3NUb2tlbiIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImxvY2F0aW9uIiwidmFsdWUiOiI0OSBHZWFyeSBTdCwgU2FuIEZyYW5jaXNjbywgQ0EgOTQxMDgiLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoicHJpY2UiLCJ2YWx1ZSI6IjEsMiIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJ3ZWJob29rIiwidmFsdWUiOiIiLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoicG9zdG1hbkFwaUtleSIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImVudmlyb25tZW50SUQiLCJ2YWx1ZSI6IiIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJoaXN0b3J5TGVuZ3RoIiwidmFsdWUiOiIxMiIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJjaG9pY2VDb3VudCIsInZhbHVlIjoiMyIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJtYXhSZXN1bHRzIiwidmFsdWUiOiIzMDAiLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5Ijoid2Fsa2luZyIsInZhbHVlIjoidHJ1ZSIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJyYWRpdXMiLCJ2YWx1ZSI6IjgwMCIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJvcGVuSW4iLCJ2YWx1ZSI6IjEiLCJ0eXBlIjoidGV4dCJ9XQ== "Run the Lunch Picker Collection in Postman"
[runner]: https://www.getpostman.com/docs/postman/collection_runs/starting_a_collection_run "About Collection Runs"
[yelp]: https://www.yelp.com/developers/documentation/v3 "The Yelp Fusion API"
