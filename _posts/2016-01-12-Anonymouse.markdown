---
title:  "Anonymouse"
date:   2016-01-12 2:35PM
categories: [iOS, communication]
tags:   [iOS, communication]
description: >
    Anonymouse is a peer-to-peer microblogging app for the iPhone. It is designed
    to provide local and anonymous communication that is censorship-resistant. This project
    is sponsored by the University of Michigan.
---
![Anonymouse Icon](/images/anonymouseIcon.png){:style="float: right; margin-left: 10px ;margin-top: 7px;"}
Anonymouse is a peer-to-peer microblogging app for the iPhone. It is designed
to provide local and anonymous communication that is censorship and
network-blogging resistant – it does so by leveraging an ad-hoc network
implemented with the iOS `Multipeer Connectivity` framework.
Since it leverages peer-to-peer wifi, the app can communicate other, nearby phones
without cellular service or infrastructure wifi.

You can check out the
[Anonymouse homepage][anonymouse]
for more information
or the [Anonymouse repo][repo]
for the source code.

The app has two main purposes. Its first purpose is as a local social-media
app that works without network service. Its second purpose is to serve as a way to
spread delay-tolerant messages in places where networks are being blocked or censored,
or where natural disasters have wiped out infrastructure network towers.

When I was working on this project, I was the primary iOS developer. I designed
the app's interface and functionality, from the `persistent storgae` support to the `connection protocols`.

Although I am no longer a part of this project, it is ongoing; the app is still in development.
It is sponsored by the University of Michigan's [Multidisciplinary Design Program][mdp].
The faculty mentor is [Robert Dick][rob].


[anonymouse]: http://1am-networks.org/index.html
[repo]:       https://github.com/psturmfels/ios-team
[mdp]:        http://mdp.engin.umich.edu
[rob]:        http://robertdick.org
