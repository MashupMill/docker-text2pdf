# docker-text2pdf
Docker image for running [text2pdf](http://www.eprg.org/pdfcorner/text2pdf/). Built from sources from [philips/text2pdf](https://github.com/philips/text2pdf).

## Usage

```bash
docker run --rm -v /path/to/something.txt:/input.txt mashupmill/text2pdf /input.txt > output.pdf
```
