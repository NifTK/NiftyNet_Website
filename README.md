# The NiftyNet Public Website

This (temporary) repository is for the public-facing website of the
NiftyNet Collaboration, as hosted on the CMICLab GitLab instance.

## Requesting content and features

Please raise an [issues](https://cmiclab.cs.ucl.ac.uk/twhyntie/niftynet-website/issues)
and we'll do our best to implement your suggestions!

## Updating the website with git-ftp

Once you have configured [git-ftp](https://github.com/git-ftp/git-ftp/)
with the [niftynet.io](http://niftynet.io) FTP details, you can
push committed changes to the website directly to the website with
the following commands:

```bash
git commit -m "[Usual commit message]"
git push origin master
git ftp push
```

## Useful links

* [The NiftyNet Repository](https://github.com/NifTK/NiftyNet) on
* The [NiftyNet website](http://niftynet.io).
