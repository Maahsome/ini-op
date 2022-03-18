# Forked for Brew Setup

The only reason this repository was forked was to create a BREW installable location, with builds for Arm to support the new Macbook M1 machines

## Version

The current RELEASE at the parent of the fork is the v2.9.0 version, so I will make that the current version installable via brew as well.

```plaintext
╭─[  ][ ~/…/Maahsome/ini-op ]
╰─[:)] % git ls-remote --tags origin
3b4daa0ab978a03c24eec20b4b62e29e5063e915	refs/tags/0.2.1
7bf05fb6b7defcd26e60814046443b37f134ba6d	refs/tags/v0.2.3
1a6339fc3b320578ca5b5059ed6aa9b9706f98e5	refs/tags/v0.2.3-final
1a6339fc3b320578ca5b5059ed6aa9b9706f98e5	refs/tags/v0.2.3-rc
223636b0027d70c24a22dcacc1d2a205737cc498	refs/tags/v0.2.5
62450bbfdb9c2ab63aec97e2cf4eea535118cb5c	refs/tags/v0.2.7
e3dc4f1fb51341cf8bd464cee1f234bd10d76bb8	refs/tags/v0.2.9
9274fcf544b49430105e5a1a3d0d4b6ed5e6619e	refs/tags/v0.3.0
```

I will create a release/v0.2 branch and remove the v0.2.9 tag, 
add the github Actions to the branch, then tag the head of that
branch with v0.2.9 and the github action should run and publish
everything.


