# TARUMT INTRANET BEAUTIFIER

This is a chrome browser extension that tweak the user interface of TARUMT Intranet to make it look more modern and pleasing.

## Local Development

1. Clone this repository into your machine:

    ```bash
    git clone https://github.com/AlstonChan/TARUMT-Intranet-Beautifier
    ```

2. Change directory into the folder with `cd`, and run the following command to compile the `scss` file.

    ```bash
    sass --watch styles/main.scss:dist/style.css --style compressed
    ```

3. In any chromium based browser, heads to the extension page and enable developer mode. Select **Load unpacked** and select this folder.

4. Go to [TAR UMT Intranet](https://web.tarc.edu.my/portal/login.jsp) and you should see the extension has modified the page css.
