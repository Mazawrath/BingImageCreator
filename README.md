# BingImageCreator

High quality image generation by Microsoft. Reverse engineered API.
Fork from https://github.com/acheong08/BingImageCreator

`pip3 install .`

```
 $ python3 -m BingImageCreator -h
usage: BingImageCreator.py [-h] -U U --prompt PROMPT [--output-dir OUTPUT_DIR]

options:
  -h, --help            show this help message and exit
  -U U                  Auth cookie from browser
  --prompt PROMPT       Prompt to generate images for
  --asyncio             Use async to sync png
  --output-dir OUTPUT_DIR
                        Output directory
```

[Developer Documentation](https://github.com/acheong08/BingImageCreator/blob/main/DOCUMENTATION.md)

## Getting authentication

### Browsers (Edge, Opera, Vivaldi, Brave, Firefox)

- Go to https://bing.com/.
- F12 to open XHR call some api to get the `cookie`
- call some api to copy the `cookie`and use this
- Copy the output. This is used in `--U` or `auth_cookie`.
