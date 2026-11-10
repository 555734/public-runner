# public-runner

Build runner for the VoiceClone apps. It only builds: the source code lives in a private repository, and this repository
fetches just the app source folders with a read-only token when you start the workflow manually
(Actions → "Build VoiceClone (source stays private)" → Run workflow). Results are published under Releases.
