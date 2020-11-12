### devlopr-jekyll - A Beautiful Jekyll Theme Built for Developers

[![Gem Version](https://badge.fury.io/rb/devlopr.svg)](https://badge.fury.io/rb/devlopr)![workflow-badge](https://github.com/sujaykundu777/devlopr-jekyll/workflows/deploy/badge.svg)
[![Netlify Status](https://api.netlify.com/api/v1/badges/4232ac2b-63e0-4c78-92e0-e95aad5ab8c3/deploy-status)](https://app.netlify.com/sites/devlopr/deploys)
![](https://ruby-gem-downloads-badge.herokuapp.com/devlopr?type=total&color=brightgreen&style=plastic)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![Bakers](https://opencollective.com/devlopr-jekyll/tiers/badge.svg)](https://opencollective.com/devlopr-jekyll/)

Just a little something I'm using to jump start a site refresh. I like to think of it as a starter for building your own Jekyll site. I purposely keep the styling minimal and bare to make it easier to add your own flare and markup. (Under Active Development) !

Highly Customizable and No Hosting or Maintainence Cost is required !

### [Installation Guide](https://devlopr.netlify.app/get-started)

![devlopr jekyll](https://github.com/sujaykundu777/devlopr-jekyll/blob/master/assets/img/screenshot.PNG?raw=true)

devlopr uses Markdown Files to generate data like Blog Posts, Gallery, Shop Products etc. No external database is required.

### Deploy your devlopr-jekyll blog - One Click Deploy

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/new/project?template=https://github.com/sujaykundu777/devlopr-jekyll)
[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/sujaykundu777/devlopr-jekyll)
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/sujaykundu777/devlopr-jekyll)

### Demo (Hosted Apps)

- Github Pages Demo - [here](https://sanketkundu.github.io/)
- Firebase Demo - [here](https://devlopr.web.app)
- Netlify Demo - [here](https://devlopr.netlify.com)
- Zeit Now Demo - [here](https://devlopr-jekyll.now.sh)
- Heroku Demo - [here](https://devlopr-jekyll.herokuapp.com)
- AWS Amplify Demo - [here](https://master.d3t30wwddt6jju.amplifyapp.com/)

#### Features :

- Local CMS Admin Support using [Jekyll Admin](https://jekyll.github.io/jekyll-admin/)
- Onine CMS Admin Support using [Netlify CMS](https://sujaykundu.com/blog/how-to-setup-netlify-cms-with-github-pages-hosted-jekyll-blog/), Forestry, Siteleaf, CloudCannon.
- Supports Latest [Jekyll 4.x](https://jekyllrb.com) and [Bundler](https://bundler.io)
- Stylesheet built using Sass
- Comments using [Hyvor](https://talk.hyvor.com/) and [Disqus](https://disqus.com/)
- SEO-optimized
- Real Time Search
- Sell Stuff (Ecommerce) in your Blog using [Snipcart](https://snipcart.com/)
- Send Newsletters using [Mailchimp](https://mailchimp.com/)
- Contact Forms using [Formspree](https://formspree.io/)
- Coding Activity using [Wakatime](https://wakatime.com/)
- Hosting Support for [Github Pages](https://pages.github.com), [Netlify](https://netlify.com), [Zeit](https://zeit.co), [Heroku](https://heroku.com), [AWS Amplify](aws.amplify.com), [Firebase](https://firebase.com)
- CI/CD Support using [Travis CI](https://sujaykundu.com/blog/deploy-jekyll-blog-using-github-pages-and-travis-ci/), Buddy , Circle CI

#### Jekyll Admin
You can easily manage the site locally using the Jekyll admin : [http://localhost:4000/admin](http://localhost:4000/admin)

![Jekyll Admin](https://github.com/sujaykundu777/devlopr-jekyll/blob/master/assets/img/jekyll-admin.PNG?raw=true)

## Recent Release Changes (v 0.4.7):

- Minor Bug fixes and optimizations
- [Added Support for Multi Authors](https://devlopr.netlify.app/blog/added-multi-author-support/#/)
- [Added Support for Math Symbols](https://devlopr.netlify.app/blog/added-latex-equations-support/#/)

You can check out for all changelogs [here](https://www.buymeacoffee.com/sujaykundu/release-v-0-4-7)

## Pull the latest changes

```s
git remote -v
git remote add upstream https://github.com/sujaykundu777/devlopr-jekyll.git
git fetch upstream
git checkout master
git merge upstream/master
git push
```

## Using Docker :

Building the Image :

`docker build -t my-devlopr-jekyll-blog .`

Running the container :

`docker run -d -p 4000:4000 -it --volume="$PWD:/srv/jekyll" --name "my_blog" my-devlopr-jekyll-blog:latest jekyll serve --watch`

## Using Docker Compose :

### Development :

You can run the app in development mode : (your changes will be reflected --watch moded)

Serve the site at http://localhost:4000 :

`docker-compose -f docker-compose-dev.yml up --build --remove-orphans`

### Production :

You can run the app in production mode : (your changes will be reflected --watch moded)

Serve the site at http://localhost:4000 :

`docker-compose -f docker-compose-prod.yml up --build --remove-orphans`

Stop the app :
`docker-compose -f docker-compose-prod.yml down`
Once everything is good and ready to go live -

`docker-compose -f docker-compose-prod.yml up --build --detach`

## Contributors:

This project exists thanks to all the people who contribute.

Contributions are more than just welcome. Fork this repo and create a new branch, then submit a pull request

- 1.Fork it [http://github.com/sujaykundu777/devlopr-jekyll/fork](http://github.com/sujaykundu777/devlopr-jekyll/fork )

- 2.Create your feature branch
`git checkout -b my-new-feature`

- 3.Commit your changes
`git commit -am 'Add some feature'`

- 4.Push to the branch
`git push origin my-new-feature`

- 5.Create new Pull Request

### Remove Credits

You can remove credits/footer attribution links, by Donating $5 to our [Open Collective](https://opencollective.com/devlopr-jekyll/donate) or [Buymeacoffee](https://buymeacoffee.com/sujaykundu).

Thanks to all our Backers ! 🙏 [Become a Backer](https://opencollective.com/devlopr-jekyll#backer)

<a href="https://opencollective.com/devlopr-jekyll#backers" target="_blank"><img src="https://opencollective.com/devlopr-jekyll/backers.svg?width=890" /></a>

### For Help :

You can contact me, if you need any help via [Email](mailto:sujaykundu777@gmail.com). If you like the project. Don't forget to :star: !

## Licence

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT). You can do anything you want, including projects for your clients, as long as you mention an attribution back (credit links in footer). See the [Licence](https://github.com/sujaykundu777/devlopr-jekyll/blob/master/LICENSE) file

# Linux Features, Tipps and Tricks for Non-Beginners
Linux is awesome for several reasons, and one of them is that it is full of nice features. Some of them are character device files (like /dev/random and /dev/urandom), while some other features are just really cool little packages that come with almost every linux distribution. Here, I list some of the cool stuff that you can find on almost any fresh linux install.

## 1 /dev/(u)random
/dev/random and /dev/urandom are both random-number generators, or perhaps more accurately: random-byte generators. Here are two example commands on how to use it:

$ cat /dev/(u)random > ~/testfile

This will fill the file "testfile" in your home-folder with random bytes until you hit Ctrl+C. Be cautious, the file gets large FAST.

$ touch /home/testfile
$ dd if=/dev/(u)random of=/home/testfile count=2 bs=1024

This will fill a file "testfile" in your home folder with 2KB ($count times $bs bytes) of random bytes and then stop. Of course open that file with a simple text editor will not do much good, because the bytes will be interpreted as ASCII (or Unicode, or UTF-8, or ...) and will therfore look like gibberish. This leads me to the next cool built-in command:

## 2 hexdump
This command takes as input a file and outputs the file's contents in bytes. For example, when I run it on the testfile I just created with /dev/random, it returns:

00000000  45 3c e7 91 b4 bc f7 9c  77 51 ac f3 57 9d 4f 06  |E<......wQ..W.O.|
00000010  b3 61 ee 6b da b6 29 21  4a cc f0 3a 1b 62 9c f5  |.a.k..)!J..:.b..|
00000020  81 12 93 fa 9e 37 35 ca  0e fc bc 85 7f 61 3f d6  |.....75......a?.|
00000030  a3 c9 ec d4 75 02 e9 16  94 f4 68 f5 af 3a 0b 84  |....u.....h..:..|
00000040  e7 f2 4d 3e 39 4f 56 d0  c4 c6 c6 00 07 91 f3 dc  |..M>9OV.........|
00000050  0a 9a 2b 7b 4d 5b c7 a5  c9 b0 c3 bd 63 4b 8c ec  |..+{M[......cK..|
00000060  a8 60 3a b3 18 88 82 bd  ce 0f 1d 4e 4c 9b 6a 0e  |.`:........NL.j.|
00000070  be 6e 4c e4 b6 ea 54 ee  8e d0 00 65 aa 8c 14 0b  |.nL...T....e....|
00000080  52 22 81 62 10 6e 7d ba  ce 3c 70 4e 05 4d c3 87  |R".b.n}..<pN.M..|
00000090  79 90 3f ba 86 40 8e 8f  29 98 c0 52 50 e5 5b 12  |y.?..@..)..RP.[.|
000000a0  ea 16 a8 62 ca 6f 7a 7c  e4 30 fc 2a cf ed 24 61  |...b.oz|.0.*..$a|
000000b0  c0 9a 28 00 8f ce db 35  c4 b0 b0 a8 6a 6e 56 b2  |..(....5....jnV.|
000000c0  e3 cf d6 cd 03 43 ba 74  68 0c 80 ed 21 b9 e0 e1  |.....C.th...!...|
000000d0  a7 0d 7b ec 18 f0 b4 f2  fc 7a 26 4e 83 17 37 4b  |..{......z&N..7K|
000000e0  97 fc 47 a0 0a d1 4d 04  cb 70 0c 62 21 86 ee cc  |..G...M..p.b!...|
000000f0  f3 c3 18 b4 e8 59 f6 35  6a e0 49 0d 49 be 2d 9a  |.....Y.5j.I.I.-.|
00000100  e8 23 d4 df 07 93 d5 3a  3f 73 8f 89 40 b0 2f 5a  |.#.....:?s..@./Z|
00000110  c8 78 4c a7 0c 44 d7 33  9d af ce 8d 86 27 09 28  |.xL..D.3.....'.(|
00000120  88 93 1a b4 c5 f9 f0 6e  e6 44 d5 1c 81 cb 93 84  |.......n.D......|
00000130  98 ce fc 2c c0 51 7d dc  0b 2e 61 4a 85 bd dc a4  |...,.Q}...aJ....|
00000140  7f da 8a 95 ec 2d b3 06  da b2 99 da 60 22 4f 98  |.....-......`"O.|
00000150  97 27 14 24 41 d5 73 47  98 c3 de fb bd cb 5e     |.'.$A.sG......^|
0000015f

The first column describes the position of the line in the file in bytes, in hexadecimals. So, the second line starts at the 00000010_{hex} = 16th_{dec} byte in the file. 

The large middle column is the 16 bytes starting from the position given by the first column. Each byte is represented in hexadecimals and can therefore be represented by two digits.

The thirf, rightmost column is a representation of the bytes, interpreted as ASCII characters.

## 3 yes
This command outputs an endless string of "y\n", until you hit Ctrl+C. And the command

$ yes yourword

will output an endless string of "yourword\n". This might seem weird, but it enables you to do some really cool stuff. Imagine you want to update your system. You know it will take forever, and you know you will have to hit ENTER (or press y) a couple times in places where the package manager wants your approval. In this case, you could do

$ yes | sudo apt upgrade

or, as an Arch-based user:

$ yes | sudo pacman -Syu

Such a use is of course ONLY advised if you ABSOLUTELY know what you are doing.

## 4 /usr/share/cracklib/
Cracklib is a library with ~470,000 common passwords. It's cool for obvious reasons, but also simply as a collection of random words.

## 2>&1 and how to search the whole system
This is a rather cool trick that I use fairly often. What does it mean? ">" redirects whatever is on its left-hand-side to whatever is on the right-hand-side. When putting "2" at the end of a command. it represents whatever is written to stderr, that is: any error message. "1" stands for stdout, so the classical command output which is to be printed in the terminal. So, 2>&1 redirects any error message to stdout. Why can this be useful?

I'm sure you've had this problem before: You want to search the whole system for a file, so what you would like to do is something like this:

$ find / -name "filename"

However, this command will usually spit out a bunch of lines containing directories the find command was not allowed to enter, each line containing the phrase "Permission denied" at the end. This will even often happen when running the command with sudo, and it makes the find command's output useless. You might think about doing this:

$ find / -name "filename" | grep -v "Permission denied"

but this would not change anything, as | only pipes stdout, not error messages. So this command's output would look just like the previous one. Instead, when you pipe find's error messages to stdout, using | you can pass them along as the input of the grep-command, like so:

$ find / -name "filename" 2>&1 | grep -v "Permission denied"

And voilà! You'll get a nice and clean output only containing the directory of the file you're looking for. 

## 7 Use Symbolic Links
This is not inherently Linux, but I realized that many top-level Linux users don't really bother about symbolic links, although they are super handy for a lot of things! For example, imagine you have a huge folder with scientific literature, and you also have another folder which contains all of your lectures and related material, like so for example:

Desktop/Lectures/SpaceshipDesign/SpaceshipToilets
Desktop/Lectures/PhilosophyOfMind/TheoryOfConsciousness
Desktop/Literature/SpaceshipDesign/SpaceshipToilets
Desktop/Literature/PhilosophyOfMind/TheoryOfConsciousness

This is obviously redundant, but I don't want to delete one of the redundancies, because I like to have my lectures and their associated content neatly in one place, as well as all of my scientific literature in general. In order to remove that redundancy, I simply remove one redundant directory (e.g. the lecture directory), and create a symbolic link to the directory I kept instead:

$ sudo rm -rf Desktop/Lectures/SpaceshipDesign/SpaceshipToilets
$ ln -s Desktop/Literature/SpaceshipDesign/SpaceshipToilets Desktop/Lectures/SpaceshipDesign/SpaceshipToilets

And now we still have both directories, without having to store the same stuff twice. 
N.B.: For scientific literature there are of course cool tools out there (zotero etc.), but you know, symbolic links are much cooler! Furthermore they are obviously generalisable to everything else.

## 6 cal
Just a nice little gimmick if you quickly want to know the day of the week of a specific day. The 15th of July 1990, for example, was a Sunday, see:

$ cal 1990

## 7 !$ and !!
In bash, !$ stands for the last argument in the previous command, while !! stands for the whole last command. For example:

$ ca file
zsh: command not found: ca
$ cat !$

The above command will perform cat on file $file.


## Other Cool Stuff
Stuff I'll cover later:
Fortune, cowsay, neofetch, sudo insults