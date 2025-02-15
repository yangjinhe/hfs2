# Obsolete
This is the repository of the old HFS.

I'm working on HFS 3 on another repository. Check it out! 
https://github.com/rejetto/hfs

## Introduction
You can use HFS (HTTP File Server) to send and receive files.
It's different from classic file sharing because it uses web technology.
It also differs from classic web servers because it's very easy to use and runs "right out-of-the box".

The virtual file system will allow you to easily share even one single file.

## Dev notes
Initially developed in 2002 with Delphi 6, now with Delphi 10.3.3 (Community Edition).
Icons are generated at http://fontello.com/ . Use fontello.json for further modifications.

For the default template we are targeting compatibility with Chrome 49 as it's the latest version running on Windows XP.

Warning: Delphi Community Edition 10.4 removed support for command-line compilation, and is thus unable to compile JEDI Code Library, and is thus unable to compile HFS2, ref [Community Edition no longer includes the command-line compilers](https://blogs.embarcadero.com/delphi-cbuilder-community-editions-now-available-in-version-10-4-2/#comment-1339) - meaning the last version of Community Edition cabale of compiling HFS2 is Delphi 10.3.x

## Libs used
- [ICS v8.64](http://www.overbyte.be) by François PIETTE 
- [TRegExpr v0.952b](https://github.com/andgineer/TRegExpr/releases) by Andrey V. Sorokin
- [JEDI Code Library v2.7](https://github.com/project-jedi/jcl)
- [Kryvich's Delphi Localizer v4.1](http://sites.google.com/site/kryvich)
