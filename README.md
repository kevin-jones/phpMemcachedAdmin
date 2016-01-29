# phpMemcachedAdmin
Fork of phpMemcachedAdmin with HTML5 charts enabling a live stream of memcached activity

## History

This repo contains the original phpMemcachedAdmin 1.2.2 (previously on Google Code and unmaintained) with some new additions.

## What does phpMemcachedAdmin do?

phpMemcachedAdmin is a tool that allows you to monitor a memcached server very easily. It shows automatically refreshing statistics about the server. However, I did not find it initially very useful because I wanted to see trends in the data to optimise how we were using memcached in our projects.

So we added live charts that stream memcached stats onto a everlasting, smooth HTML5-powered line graph.

## Example chart

Example chart showing some memcached stats:

[[https://raw.githubusercontent.com/kevin-jones/phpMemcachedAdmin/master/Public/Images/chart1.png]]

## Credits

For the charts we use the amazing Smoothie Charts https://github.com/joewalnes/smoothie/

