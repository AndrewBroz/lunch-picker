# [Lunch Picker][docs]

[![Run in Postman][button]][run]

[Lunch Picker][docs] is a [Postman collection][collections] that acts as a restaurant discovery service, powered by the [Yelp Fusion API][yelp]. It suggests places for you or a team to have lunch and posts them to Slack, and can be run locally with the [Postman collection runner][runner] or with [Newman][newman], or as a scheduled remote job with [Postman Monitors][monitors].

You can [customize Lunch Picker's restaurant selection criteria][options] such as location, distance, and price range with environment variables. The collection automatically saves its choice history to a [Postman environment][environments] after each run, using that history to make sure the choices stay interesting each time it's run.

Start by [reading the docs][docs] or go straight to [running Lunch Picker in Postman][run]. Bon appétit!

_MIT License, Copyright (c) 2017 Andrew Broz_


[button]: https://run.pstmn.io/button.svg
[collections]: https://www.getpostman.com/docs/postman/collections/creating_collections "About Collections"
[docs]: https://documenter.getpostman.com/view/218543/lunch-picker/6fWy4Ao "Lunch Picker Documentation"
[environments]: https://www.getpostman.com/docs/postman/environments_and_globals/manage_environments "About Environments"
[monitors]: https://www.getpostman.com/docs/postman/monitors/intro_monitors "Postman Monitors"
[newman]: https://www.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman "Newman CLI"
[options]: https://documenter.getpostman.com/view/218543/lunch-picker/6fWy4Ao#cc479560-f6cf-f199-1757-65d9f051a324 "Lunch Picker Options"
[run]: https://app.getpostman.com/run-collection/18f56d0892e624da67b7#?env%5BLunch%20Picker%20(Beta).template%5D=W3siZW5hYmxlZCI6dHJ1ZSwia2V5IjoieWVscENsaWVudElEIiwidmFsdWUiOiI8WWVscCBDbGllbnQgSUQ+IiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6InllbHBDbGllbnRTZWNyZXQiLCJ2YWx1ZSI6IjxZZWxwIENsaWVudCBTZWNyZXQ+IiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImxvY2F0aW9uIiwidmFsdWUiOiI8QSBTdHJlZXQgQWRkcmVzcz4iLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5Ijoid2ViaG9vayIsInZhbHVlIjoiPFNsYWNrIFdlYmhvb2s+IiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6InBvc3RtYW5BcGlLZXkiLCJ2YWx1ZSI6IjxQb3N0bWFuIEFQSSBLZXk+IiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImVudmlyb25tZW50SUQiLCJ2YWx1ZSI6IjxFbnZpcm9ubWVudCBJRD4iLCJ0eXBlIjoidGV4dCJ9XQ== "Run the Lunch Picker Collection in Postman"
[runner]: https://www.getpostman.com/docs/postman/collection_runs/starting_a_collection_run "About Collection Runs"
[yelp]: https://www.yelp.com/developers/documentation/v3 "The Yelp Fusion API"
