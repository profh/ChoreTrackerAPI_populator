# ChoreTracker populate files

These are supplemental files to the [ChoreTracker API labs](https://67272.cmuis.net/labs/11) in 67-272 to help you add a few records to the system so you can play with the API and see what gets returned.  It is not essential that you do this to complete the lab, but for many students it may be helpful.

_After_ you have built the initial API and inserted a record via the curl command as instructed in the lab (we want you to see the empty array first), you can populate the rest of the database with some sample values to make the rest of the lab more interesting. There are just four quick steps:

1. Copy the contents of seeds.rb into the `db/seeds.rb` file in your project
2. Drop the factories.rb file into the `test/` directory of your project
3. Add `gem 'factory_bot_rails` to your Gemfile and run the `bundle` command
4. Run `rails db:seed` to add the records to your database
