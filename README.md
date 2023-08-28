# clean_dl_folder
A Bash script to organize files based on their extensions into designated folders within the "Downloads" directory.

## Description

This script is designed to help you organize your downloaded files by sorting them into different folders based on their file extensions. It categorizes files into folders such as Documents, Pictures, Videos, and Music, all within the "Downloads" directory.

## Features

- Supports various file extensions for documents, pictures, videos, and music.
- Creates dedicated folders within the "Downloads" directory for each category to keep your files organized.
- Recursively searches through directories to sort files.
- Provides a summary of the total number of files sorted and the time taken.

## Usage
Install the script by cloning the repo
```
git clone git@github.com:maxencelupion/clean_dl_folder.git
```
Grant owner permissions
```
cd clean_dl_folder; chmod +x clean_dl
```
Execute the script
```
./clean_dl
```

## Configuration

You can customize the file extensions and corresponding folders by editing the arrays in the script. Adjust the `documents_extension`, `pictures_extension`, `video_extension`, and `music_extension` arrays to include your desired file extensions.

## Caution

- Double-check the script and ensure the file extensions and folder names match your preferences.
- Use this script responsibly and keep backups of your important files before sorting.
