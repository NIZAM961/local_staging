#!/usr/bin/env bash
git fetch origin
git checkout main
git pull origin main
git checkout -b staging
git add .
git commit -m "staging: <short message>"
git push -u origin staging

