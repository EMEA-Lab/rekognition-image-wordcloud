# rekognition-image-search-engine
Reference implementation on building a local image search engine that uses Amazon Rekognition image labels to create an inverted index.

# Architecture

![alt text](https://s3.amazonaws.com/smallya-test/localserachengine-architecture.png "Local Image
Search Engine with Rekognition")

# Instructions
(Tested on Mac OSX)
* pip install -r requirements.txt
* Create a directory called 'photos' and add some images in it.
* Run the indexer:

   ```
   $ python3 indexer.py
   ```
* A new file called web/photo_tags.png is created with the wordcloud of the tags of the photos.

## License

This code sample is licensed under the MIT-0 License.
