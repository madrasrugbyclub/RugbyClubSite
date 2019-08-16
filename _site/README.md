# Madras Rugby Club webiste
This is the Github Repository used to store, edit and distribute the website. We've made a tutorial in order to ensure modifying the website can all be done as easily as possible: this could be done by a web developer or a layperson whose willing to take a fair learning curve. Setting up will probably be harder than editing the site so don't be to fazed by the start. Nevertheless if you need help feel free to contact me at: maxwill.kelly@gmail.com

## Programs you'll need
To modify the site, you will need the following programs:
* Atom - Used to edit the fundamental code - https://atom.io/
* Github Desktop - Used to upload changes to the site - https://desktop.github.com/
* Jekyll - Used for atomic design in which elements such as a menu bar are shared across webpages
* Ruby - Used by Jekyll
All of these programs are avaliable on Windows, Mac and Linux so there should be no issues with compatibilaty. 

## Installing Programs
To install Atom and Github Desktop the procedure should be fairly familiar: Go to their website, download the appropriate files, install them and be done with it. To go to their websites use the links provided above or just google them, either works. This doesn't apply to Ruby nor Jekyll.

For Ruby you'll install something different depending on your OS:
* Windows - https://rubyinstaller.org/downloads/ - Download the Ruby+DevKit (x64) Version via the links on the left sidebar
* macOS - macOS actually comes pre-installed with ruby but the version is often too old. To check: launch the program Terminal which can be found by searching for it in the Top-right corner or you can find it under Utilies in LaunchPad. Type `ruby -v`. If the version given is at or above 2.6 skip to installing Jekyll.

If your ruby version is less than 2.6 run the following commands:
* `xcode-select --install` - Installs tools to download an App Store for Ruby
* `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` - Installs an App Store for Ruby
* `brew install ruby` - Installs Ruby
* `export PATH=/usr/local/opt/ruby/bin:$PATH` - Basically tells macOS where to find ruby
* `ruby -v` - To check the version once more

For Jekyll:
* Windows - Go to your start menu and search for Start Command Prompt with Ruby and type: `gem install jekyll bundler`
* macOS - Launch terminal and type: `gem install --user-install bundler jekyll` then get your version of ruby once more via `ruby -v` and run `export PATH=$HOME/.gem/ruby/X.X.0/bin:$PATH` however replace both Xs with the version number of ruby make sure to **ignore the last number**

## Downloading the code
Go to Github Desktop which we downloaded earlier

## Editing the code

## Adding a story

## Submitting changes
