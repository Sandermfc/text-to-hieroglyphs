# text-to-hieroglyphs
Take an audio input (speech), convert it to text, and return a hieroglyph for each relevant word.

## Initial thoughts:
### Speech recognition & NLP:
	* Google cloud speech-to-text api
	* Amazon equivalent?
### Image search:
	* GoogleScraper
	* Straight up scraping (BeautifulSoup?)
	* Build on top of something existing. There might be room for optimization as we only need the top result and it doesn't have to be accurate.
### UI:
	* Initially, a local instance of the project will do. Display images with opencv or something.
	* Later, maybe a website frontend / send all audio to a hosted server for parsing?

