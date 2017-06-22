IPFessay
========

IPFessay is an application that runs on [IPFS](https://ipfs.io/) and allows you
to publish uncensorable essays to it. It supports Markdown for composition and
lets you write and publish essays right from your browser, with no extra
software or servers.

As long as IPFS is up, you'll be able to use IPFessay to publish texts to IPFS.

To use IPFessay, you can just access it on a publicly writable gateway such as
hardbin.com:

[https://hardbin.com/ipfs/QmQUrYJ6sCSDV6duC4Db7U8NXZG3DpNrVF77XtcrbWYiJY](https://hardbin.com/ipfs/QmQUrYJ6sCSDV6duC4Db7U8NXZG3DpNrVF77XtcrbWYiJY)

To use IPFessay on your personal node, you need to do a few things, unfortunately:

* [Install IPFS](https://ipfs.io/docs/install/) (just copy the binary somewhere
  and run it).
* Launch the daemon in writable mode (`ipfs daemon --writable`).
* Add the [CORS headers](https://github.com/ipfs/js-ipfs-api#cors) (an
  unfortunate necessity).
* Visit the following link:

[/ipfs/QmQUrYJ6sCSDV6duC4Db7U8NXZG3DpNrVF77XtcrbWYiJY](http://localhost:8080/ipfs/QmQUrYJ6sCSDV6duC4Db7U8NXZG3DpNrVF77XtcrbWYiJY)

This is a sample essay just so you can see what they look like:

[/ipfs/QmWFSuFDaApxK6DaBzEXdSXhb325fQY1hHn7Jc32DS77UK](https://ipfs.io/ipfs/QmWFSuFDaApxK6DaBzEXdSXhb325fQY1hHn7Jc32DS77UK)

The above links are immutable, ie they will always point to the same version of
IPFessay, even if there is a later version available.

For a link to the latest version of IPFessay, use this:

[/ipns/QmSWnBwMKZ28tcgMFdihD8XS7p6QzdRSGf71cCybaETSsU](/ipns/QmSWnBwMKZ28tcgMFdihD8XS7p6QzdRSGf71cCybaETSsU)


Contributing
------------

### Pinning

If you have a local IPFS daemon, please feel free to help out by pinning
a version of IPFessay. You can very easily do this by running:

~~~
ipfs pin add QmQUrYJ6sCSDV6duC4Db7U8NXZG3DpNrVF77XtcrbWYiJY
~~~

Which will make you a host of IPFessay and help make it faster and more
resilient.


### Code contributions

Please feel free to open an issue or a merge request if you find something that
can be improved or have any suggestions.

Thanks!

-- Stavros
