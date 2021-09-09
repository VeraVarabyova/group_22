#!/bin/bash
cd First_script
mkdir shop1 shop2 shop3
cd shop2
touch 1f.txt 2f.txt 3f.txt 4f.json 5f.json
mkdir fruits vegetables berries
ls -la
mv ./{1f.txt,4f.json} fruits
