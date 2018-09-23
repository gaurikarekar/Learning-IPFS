# Learning-IPFS

## Day 1
* ### What is IPFS?

> **"A peer-to-peer hypermedia protocol to make the web faster, safer, and more open."**

[Official IPFS Website](https://ipfs.io/)


***

* ### Installation:
[Download and Installation](https://docs.ipfs.io/introduction/install/)


***
### Basic Usage :

Demo of the workflow: [Demo video](https://www.youtube.com/watch?v=8CMxDNuuAiQ)

[Basic Usage](https://docs.ipfs.io/introduction/usage/)



`ipfs init`

returns a command that includes a hash value. This is to get you started with IPFS and access it's guide.



`ipfs cat /ipfs/QmYwAPJzv5CZsnA625s3Xf2nemtYgPpHdWEz79ojWnPbdG/readme`

successful execution will display the IPFS logo.



The Quick-Start guide.

`ipfs cat /ipfs/QmYwAPJzv5CZsnA625s3Xf2nemtYgPpHdWEz79ojWnPbdG/quick-start`


***


**Starting the IPFS deamon(going online):**

`ipfs daemon`

Played around adding files to IPFS and displaying them using their hash values.


#### Display the files locally

`ipfs cat ipfs/<hashvalue>`


#### Display the files on the browser

for images and videos :- `localhost:8080/ipfs/<the-hash-value-of-the-image-or-video>` in the browser.

for text files :-  `localhost:5001/ipfs/<the-hash-value-of-the-textfile>`


***

For the Web UI refer their  [Fancy Web Console](http://localhost:5001/webui)

***
## Day 2

Links

[pinning](https://flyingzumwalt.gitbooks.io/decentralized-web-primer/content/files-on-ipfs/lessons/pin-files.html)

[example](https://ipfs.io/ipfs/QmNZiPk974vDsPmQii3YbrMKfi12KTSNM7XMiYyiea4VYZ/example#/ipfs/QmRFTtbyEp3UaT67ByYW299Suw7HKKnWK6NJMdNFzDjYdX/pinning/readme.md)

[code your own blockchain](https://medium.com/@mycoralhealth/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc)

[secure sharing of files over ipfs](https://medium.com/@mycoralhealth/learn-to-securely-share-files-on-the-blockchain-with-ipfs-219ee47df54c)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAwNjUyNTc1NSw2MDkyMTk3MTFdfQ==
-->

[GPG installation and how to use](http://blog.ghostinthemachines.com/2015/03/01/how-to-use-gpg-command-line/)
