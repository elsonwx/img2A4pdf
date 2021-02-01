# img2A4pdf
convert a long screenshot image to A4 size pdf



##### how to screen full size page on google chrome

1. Open Chrome DevTools
2. `Ctrl + Shift + P` if you're on a PC, or `Command + Shift + P` on a Mac
3. type `capture full size screenshot` then `enter`



### Prerequisites

 [imagemagick](https://imagemagick.org/script/download.php) && [img2pdf](https://pypi.org/project/img2pdf/)

- macOS

   ```
   brew install imagemagick
   pip3 install img2pdf
   ```
   
- Ubuntu

  ```
  apt install imagemagick
  pip3 install img2pdf
  ```

### Usage

```shell
wget https://git.io/img2A4pdf && chmod +x img2A4pdf
./img2A4pdf input_screenshot.png
```
