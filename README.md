# Tethys Deep

## Development

This is built with [Middleman], using [the Amicus template][Amicus].

After you install this, run `bundle install` to get all the gems. Your version of Ruby _might_ matter. I'm using 2.2.2.

To run the development server, run `middleman`. 

## Deployment

You'll need to have the AWS credentials in a `~/.aws/tethysdeep.yml` file.

Then run `rake mm:publish`. This uses [middleman-aws].

  [Middleman]: http://middlemanapp.com/
  [Amicus]: https://github.com/nathos/amicus
  [middleman-aws]: https://github.com/alienfast/middleman-aws
