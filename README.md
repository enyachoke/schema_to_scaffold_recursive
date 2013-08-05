# Schema to Scaffold

[![Code Climate](https://codeclimate.com/badge.png)](https://github.com/enyachoke/schema_to_scaffold_recursive)

This Gem shall generate rails scaffolds based on an existing schema.rb unlike the mother gem


Use your schema.rb file from `<rails_app>/db` or generated with `rake db:schema:dump`
You can rename schema.rb to schema_your_fav_name.rb that I will find it to. This will prevent schema.rb from being
overwritten when one run rake db:migrate.


## Usage

Just type:

    scaffold [options]
    
	[options]
    -h				Displays help.
	-p <path>		It specifies a search path or a path to a file 
					ex: -p /user/path  or  /path/to/your/schema.rb
	-c				Works only on linux. Will copy the script copied to your clipboard.
					You will need to have xclip installed(see below).


