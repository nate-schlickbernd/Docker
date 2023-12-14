# Docker Build Steps

## Tips

***In VS Code, press Ctrl+Shift+V to view this markdown file.***

## Build

**Step 1**: docker build -t nate-schlickbernd/project1:1.0 . \
**Step 2**: docker run -p 4000:4000 nate-schlickbernd/project1:1.0

## Cleanup

See what images are sitting around taking up hard drive space \
***Command***: docker image ls -a

Remove the unused images \
***Command***: docker image prune

## Push

Push images to a repository \
***Command***: docker image push nate-schlickbernd/project1:1.0
