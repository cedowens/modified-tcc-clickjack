# modified-tcc-clickjack
modified version of Ron Masas's TCC-Clickjack Swift project

made the following changes to the original POC:

- runs applescript commands inline (removes depdency on external applescript file)
- links to an icns file on disk by default (removes dependency on external icns file)
- programmatically closes the app (removes the command line execution dependency)
- added inline applescript to list contents of ~/Desktop, ~/Documents, and ~/Downloads by using Finder TCC permissions granted by this technique

THIS TECHNIQUE WORKS ON BIG SUR AND MONTEREY
NOTE: GET INTO TERMINAL'S CONTEXT BEFORE RUNNING!
