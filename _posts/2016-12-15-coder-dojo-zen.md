---
layout: post
title:  Setting up CoderDojo's Zen environment
date:   2016-12-25 13:42:21 +0200
categories: gci
---
![Zen development environment](/blog/images/zen.jpg)

Hello again and Happy Holidays if you celebrate!

Just today I managed to set up the Zen development environment on my computer! Yay! My exams are finally over, and now I have enough time to contribute again! :blush:

I didn't find this task a hard one, even though I encountered some difficulties at the beginning. I followed the instructions given in the README.md file of the [GitHub repository](https://github.com/coderdojo/cp-local-development), and they were clear and helpful.

# Prerequisites:
1. NodeJS
2. PostgreSQL

**Note:** Make sure that you only use node `0.10.x` or `5.x`, as others are not supported. I didn't pay attention at first, and I lost some time trying to figure out what the errors meant.

I met some difficulties while installing PostgreSQL, but I found a [great tutorial](http://www.designmagick.com/article/2/Starting-Out/Installing-PostgreSQL) which helped me through it. Don't forget, there are some packages needed for building Postgres, and you can install them using this command:

    sudo apt-get install build-essential libreadline-dev zlib1g-dev flex bison libxml2-dev libxslt-dev libssl-dev


The Zen installation ran smoothly afterwards. I also added some test data (as you can see, the map isn't empty). Upon installation, you should see Zen up and running at `localhost:8000` in your browser.

Happy coding!
