# innovu-public

Repository for public Innovu resources

## Uploading public resources

1. Go to [https://github.com/Innovu/innovu-public/upload/master](https://github.com/Innovu/innovu-public/upload/master)
2. Click "Choose your files", select the file(s) you want to upload, then click "Open"
3. Scroll down and click "Commit changes"

Your file(s) should now be in the repository. You can verify by going back to [https://github.com/Innovu/innovu-public](https://github.com/Innovu/innovu-public) and making sure they are in the file listing.

You can also overwrite existing files in the repository using the same method if the filename you upload is the same as one already in the repository. This is useful for images that need to be updated on a regaulr basis.

## Getting resource links

To get the link you'll use in markdown, you need to use the "raw" link to a file, not the one that will send you back to github. For example, take the `example.png` image located at [https://github.com/Innovu/innovu-public/blob/master/example.png](https://github.com/Innovu/innovu-public/blob/master/example.png). To get its "raw" link we just need to:

1. Click the link for the resource for which you need a "raw" link
2. On the new page, click "Download" just above the resource
3. Once your resource loads in a new page, copy the URL from the browser, that's your "raw" link

For example, for the `example.png` image in this repository, the github link is:

```
https://github.com/Innovu/innovu-public/blob/master/example.png
```

but the "raw" link I'd need to add it to markdown is:

```
https://raw.githubusercontent.com/Innovu/innovu-public/master/example.png
```

## Adding images to markdown in widgets

```
![text](link)
```

Where `text` is the text to be shown if the image cannot load for some reason, and `link` is the link to the image you want to show. For example, to show the example.png image in this repository, you would use:

```
![innovu logo](https://raw.githubusercontent.com/Innovu/innovu-public/master/example.png)
```

and here's the output:

![innovu logo](https://raw.githubusercontent.com/Innovu/innovu-public/master/example.png)
