# mp3_csv_tagger
read mp3-files to csv, then edit, then use the csv to add tags to those mp3s

## worksflow
### list
read untagged mp3 files into a csv, then manually add album, artist and title.
### edit csv
i manually filled the artist, album and title columns using excel because it was faster to copy paste and fill rows
### tag
then rerun the script in tag mode and it will add ID3 tags from the csv to the respective files
