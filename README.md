# Sairo-Publisher

Sairo-Publisher is a private, internal tool used by the owner of the YouTube
channel **sairo ch.** to upload that channel's own videos (short-form videos of
the VTuber Sairo). It is not offered to anyone else, and no other person signs
in to it.

## What it does

When the channel owner has approved a finished video, the tool uses the
YouTube Data API to:

- upload the video to the owner's channel;
- set its title, description, tags, category, language, privacy status and
  scheduled publish time;
- declare that it is not made for kids, and whether it contains altered or
  synthetic content;
- set its thumbnail and add it to one of the channel's playlists.

It does nothing without the owner's approval of each individual video, and it
does not read, collect or change anything else on YouTube.

## How it runs

The tool runs only on the channel owner's own computer, from the command line.
The owner signs in once with Google OAuth; the resulting token is stored only on
that computer.

## YouTube API Services

Sairo-Publisher uses YouTube API Services. By using it, its user agrees to the
[YouTube Terms of Service](https://www.youtube.com/t/terms); Google's handling
of data is described in the [Google Privacy Policy](https://policies.google.com/privacy).

## Privacy and terms

- [Privacy policy](PRIVACY.md)
- [Terms of service](TERMS.md)

## Contact

xmslchannel@gmail.com
