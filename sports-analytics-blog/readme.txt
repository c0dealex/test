Adding content

   to add content to the site make a new file in the _posts folder with
   the following syntax:

   YYYY-MM-DD-a-fitting-name.md

   Make sure the file ending is ".md"


Changing the link of a post

   To change the link of a post change the permalink variable in the front
   matter:

   ---
   permalink: /posts/a-fitting-link/
   ---

   Don't forget to put a " / " at the end of the link.

Meta tags

   Use the title, section and tags variable in the front matter

   ---
   title: Title
   description: Summary
   tags: tag1,tag2,tag3
   ---

   Make sure you don't put a space between the comma and the next tag when
   editing the tags variable

Embedding tweets

   To embed a tweet copy the code
   from twitter (more info in this guide: https://help.twitter.com/de/using-twitter/how-to-embed-a-tweet)
   and paste it into the var code1, code2, code3, code4 or code5 in your front
   matter.

   ---
   code1: <blockquote class="twitter-tweet" data-lang="de"><p lang="en" dir="ltr">JuJutouchdown reception from Big Ben  for 1 yards  And Here we go Steelers, Yoi! <a href="https://twitter.com/hashtag/Steelers?src=hash&amp;ref_src=twsrc%5Etfw">#Steelers</a></p>&mdash; Myron Cope Bot (@Myron_Cope_Bot) <a href="https://twitter.com/Myron_Cope_Bot/status/1071898314747117568?ref_src=twsrc%5Etfw">9. Dezember 2018</a></blockquote><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
   ---

   Make sure the whole code is only 1 line! Twitter will give you something
   like this:

   <blockquote class="twitter-tweet" data-lang="de"><p lang="en" dir="ltr">JuJutouchdown reception from Big Ben  for 1 yards  And Here we go Steelers, Yoi! <a href="https://twitter.com/hashtag/Steelers?src=hash&amp;ref_src=twsrc%5Etfw">#Steelers</a></p>&mdash; Myron Cope Bot (@Myron_Cope_Bot) <a href="https://twitter.com/Myron_Cope_Bot/status/1071898314747117568?ref_src=twsrc%5Etfw">9. Dezember 2018</a></blockquote>
   <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

   Change that to:

   <blockquote class="twitter-tweet" data-lang="de"><p lang="en" dir="ltr">JuJutouchdown reception from Big Ben  for 1 yards  And Here we go Steelers, Yoi! <a href="https://twitter.com/hashtag/Steelers?src=hash&amp;ref_src=twsrc%5Etfw">#Steelers</a></p>&mdash; Myron Cope Bot (@Myron_Cope_Bot) <a href="https://twitter.com/Myron_Cope_Bot/status/1071898314747117568?ref_src=twsrc%5Etfw">9. Dezember 2018</a></blockquote><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

   Also make sure you're using the var code1 when embedding one or multiple
   tweets.

Running and uploading the site

   To test your site on localhost:4000  make sure you have installed jekyll on
   your computer and enter the command "bundle exec jekyll serve"
   in the sports-analytics-blog folder

   Before uploading your site to a server run hit Ctrl + c (on MacOS, Linux
   distros and Windows) if the "bundle exec jekyll serve" command is still
   running and run "bundle exec jekyll build".

   Then upload the content from the _site folder to your server.

Still got questions or need help?

   Use the 2019-05-25-boxes-2.md, 2019-05-25-boxes-3.md, 2019-05-25-boxes-4.md,
   2019-05-25-blog-test.md files in the _posts folder for reference if you have
   any more questions. If you need help, dm me on Fiverr or on Discord:
   code_alex#6748. My email is alexscharkowski3@gmail.com
