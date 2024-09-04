# Destiny Weaves Guidebook

This is the guidebook for Destiny Weaves, a semi-literate play-by-post text roleplay game set in the Pern universe and operated through JCINK and Discord.
The guidebook itself is hosted through Github Pages at https://destinyweaves.github.io/Guidebook/; what you see here is the source repository that generates that site.

This guidebook is meant to introduce players to the concept of text roleplay, to set expectations about how players should participate, and provide details about the world of Pern specific to Destiny Weaves, especially regarding the time period it's set in (8th pass) and the areas where it deviates from Ann McCaffrey's original world.

This guidebook is managed through Github to facilitate collaboration.
Players are encouraged to discuss and propose changes to this guidebook, or to take advantage of our open-source license to fork this repository and modify it to use for their own RP.

To the extent that the text of this guidebook is a work of original authorship, it's released under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
Technical components related to the just-the-docs Github Pages theme are released under the [MIT License](https://opensource.org/license/MIT).

## Local Editing / Previews

Markdown is easy enough to read, but if you want to preview the site with changes before you submit, you can do so by running a local development copy. You software devs out there will almost certainly have your own ideas and opinions about how you'll want to do that, but for everyone else:

1. Open CMD or PowerShell, and run:
   
   ```
   winget install Microsoft.VisualStudioCode Git.Git RubyInstallerTeam.RubyWithDevKit.3.2
   ```
   
   If prompted with a license agreement, type <kbd>Y</kbd> then press <kbd>Enter</kbd> to accept.

   This will install:
   - VSCode, the recommended editor.
   - Git, the program for interacting with a git repository like this one.
   - Ruby, the framework the guidebook's code needs to run.

2. Open VSCode (aka Visual Studio Code), which should have been installed in the previos step.

3. Clone the guidebook repository. See [this guide](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#_clone-a-repository-locally) for more detail on working with git, but for the short version:
   1. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
   2. Type/select "Git: Clone" from the menu.
   3. Select "Clone from URL" from the menu.
   4. Copy and paste `https://github.com/DestinyWeaves/Guidebook.git`

4. Open the terminal inside VSCode.
   Either, press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>`</kbd>, or select from the top taskbar, Terminal > New Terminal.

5. Install the Ruby packages the guidebook needs by running the command:

   ```
   bundle
   ```

6. Start the local server for viewing the guidebook in your browser with:

   ```
   bundle exec jekyll serve
   ```
   
7. Open http://localhost:4000/ in your browser to view the guidebook including any changes you've made to your local copy. Once you make a change, all you need to do is save the file and refresh your browser to see the update.

8. To contribute your changes, submit them as a pull request. See [this guide](https://code.visualstudio.com/docs/sourcecontrol/github) for info on using the VSCode Github Pull Requests and Issues extension to do this.


