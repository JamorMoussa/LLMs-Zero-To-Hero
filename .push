#!/usr/bin/env bash

if [ "$1" == "-m" ] && [ -n "$2" ]; then
    git status
    git add .
    git commit -m "$2"
    git push
else
    echo "Usage: ./script.sh -m 'commit message'"
fi