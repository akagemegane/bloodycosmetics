# How to use?

This was requested by some NukemNet users who had trouble getting this setup, so here we go.

First off, ***notblood.def*** needs to be present in the same directory as notblood.exe.
Open up notblood.def with a text editor of choice, and look at the comments to get some ideas.

Uncomment the include statements so NotBlood will load the specified .DEF files. It was setup that way to be more modular.

**Here's an example (Title Screen Replacement)**

Before :

// Custom Title Screen //
**// include custom/titles/filename.def**

After :

// Custom Title Screen //
**include custom/titles/blooda\_castle.def**
