# Additional XMage Tokens

There's a few tokens that never received official cards, mostly older stuff but also some newer cards from sets like Jumpstart. Because this artwork isn't on Scryfall, it's not available via the standard image import process. This archive is an attempt to provide art for those cards using some of the "un-official" tokens from MTGO/MTGA, along with some custom artwork.

## Sources

Cockatrice's [tokens.xml](https://github.com/Cockatrice/Magic-Token/blob/master/tokens.xml) was a primary resource for the artwork in this repository along with mtg.onl and card art from Scryfall.

## Notes

There's a few cases were I wasn't able to implement dedicated artwork for a particular class/card. This is because XMages fall back method when it can't find a defined token is to look for TOKENNAME.full.jpg. Some of these classes use the same token name but would otherwise have different statlines/colors/etc. I've added generic images for each so there's at least some artwork and XMage will still overlay the correct details/stats so this is really only an issue if you try and view the card art when the token is in play. Tokens are not an exact 1:1 for the following:

* 5/5 Green Beast from [One Dozen Eyes](https://scryfall.com/card/c13/159/one-dozen-eyes)
* 2/2 Green Beast from [Keeper of the Beasts](https://scryfall.com/card/exo/112/keeper-of-the-beasts)
* Either token from [Wand of the Elements](https://scryfall.com/card/dst/158/wand-of-the-elements)
* 3/1 Red Knight from [Court of Embereth](https://scryfall.com/card/woc/24/court-of-embereth)
* 1/1 White Knight from [Errand of Duty](https://scryfall.com/card/me2/12/errand-of-duty)
* 2/2 White Reflection from [Spirit Mirror](https://scryfall.com/card/tpr/35/spirit-mirror)

# How to use

1. Download `art.zip` from this repository.
2. Find and backup `TOK.zip` in your images directory for XMage (so you don't have to redownload everything if something goes wrong).
3. Open `TOK.zip`. I find 7Zip easiest for this but any archiver should work.
4. Open `art.zip` and copy all the directories and image files from it into the root of `TOK.zip`.