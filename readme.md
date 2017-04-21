# Streaming Twitter data

This is a fork of [Chris Albon's](https://github.com/chrisalbon) code for [streaming tweets from the election](https://github.com/chrisalbon/election_day_2016_twitter).

## Get credentials

Create a [Twitter app](https://apps.twitter.com/) and put the credentials in a file called `credentials.json` like so:

```
{
    "consumer_key":"YOUR KEY HERE",
    "consumer_secret":"YOUR SECRET HERE",
    "access_token":"YOUR ACCESS TOKEN HERE",
    "access_secret":"YOUR ACCESS SECRET HERE"
}
```

## Run commands

For getting Science March tweets:

```
python miner.py 'data/sciencemarch' \#ScienceMarch \#MarchforScience \#ScienceMarchDC \#ScienceMarchLA \#ScienceMarchBoston \#ScienceMarchLDN \#ScienceMarchSF \#ScienceMarchIND \#ScienceMarchSTL \#scimarchsea \#MarchforSciencePDX ScienceMarchDC "science march"
```

This will put the data in a CSV within a folder called `data/`.


