Gerrit plugin for fungit
=======================
Adds a [gerrit](https://code.google.com/p/gerrit/) integration panel to fungit.

Installation
------------
1. Go to your fungit plugin dir (defaults to ~/.fungit/plugins, create it if it doesn't exsist).
2. `git clone https://github.com/ungtb10d/fungit-gerrit.git`
3. `npm install` in the fungit-gerrit folder
4. Restart fungit

Configuration
-------------
In your `.fungitrc`:

    {
      "pluginConfigs": {
        "gerrit": {

          // Ssh username. Defaults to what the repository is configured with, or the currently logged in user.
          "sshUsername": undefined,

          // Ssh agent. Defaults to pageant on Windows and SSH_AUTH_SOCK on Unix.
          sshAgent: undefined,

        }
      }
    }
