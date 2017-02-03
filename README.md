# haskell-stack
A haskell-stack dockerfile setup

This is built `FROM Haskell` which has `RUN stack setup` to save having to go through the incredibly slow stack setup.
And `WORKDIR /usr/src/app` so there is a known space to work.
