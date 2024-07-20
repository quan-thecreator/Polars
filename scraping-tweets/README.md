# Goal

Extract tweets from popular accounts, completed accoutns will be listed below. The tweets should be extracted to json files, to be later processed by Rust code that has two subcommands. One will place these tweets into the database while avoiding duplicates, and the other will run a single threaded process to query the Dolphin-Mixtral model on my system to then place in another table, ensure tweet surreal uniqueness.
